---
title: "Design Pattern in Julia"
weight: 0
date: 2021-08-14T17:33:28+08:00
draft: false
author: ""
description: ""
tags: ["design pattern"]
categories: ["Tips"]
---

Some notes of Tom kwong's book [Hands on Design patterns in Julia](https://www.packtpub.com/product/hands-on-design-patterns-and-best-practices-with-julia/9781838648817). Please consider buying that book if you like it.

<!--more-->

## Sources

- [Julia docs](https://docs.julialang.org/en/v1/)
- [opensourc.es](https://opensourc.es/)
- [Hands on Design patterns in Julia](https://www.packtpub.com/product/hands-on-design-patterns-and-best-practices-with-julia/9781838648817), the book by Tom kwong.


## Separated Project environments

It is recommended to maintain a minimal root environment (with a few necessary packages like `Revise.jl`) and [customize the local Julia project environment](https://opensourc.es/blog/all-about-pkg/#environments) by the following steps:

1. Go to your project folder and run `julia --project=.`. This will run `pkg> activate .` for you.
2. Add you packages by `pkg> add Pkg1 Pkg2...`

## Packages and modules

Julia also encourages making your own packages, even temporarily, to utilize unit-testing, precompilation, and to separate namespaces.

- Creating Julia packages is light-weight: `pkg> generate PkgName` only creates two files (one julia and one TOML file). For a more complete configuration, consider using [PkgTemplates](https://github.com/invenia/PkgTemplates.jl) or [PkgSkeleton.jl](https://github.com/tpapp/PkgSkeleton.jl) for more functionalities like CI testing and code coverage.
- [Revise.jl](https://github.com/timholy/Revise.jl) watches file system changes and update the code in the loaded packages / modules automatically.

## Functional interfaces and multiple dispatch

In the Julia world, generic functions called [functions](https://docs.julialang.org/en/v1/manual/functions/), while those with type annotations / parameterizations are called [methods](https://docs.julialang.org/en/v1/manual/methods/). My impressions so far was that, Julia is a _functional interface-first_ programming language, by the power of [multiple dispatch paradigm](https://opensourc.es/blog/basics-multiple-dispatch/), to make Julia a much more flexible (in programming) and composable between packages: e.g. [DiffEq + Flux + GPU kernel](https://github.com/SciML/DiffEqFlux.jl)), and mathematically natural. However, it requires a vastly different mindset for users coming from the object-oriented worlds like Python / Java.

- Abstract types cannot have fields. They are only meant to be inherited with their functional interfaces. Concrete types (structs with fields), on the other hand, cannot not be inherited.
- Use parameteric [type (structs)](https://docs.julialang.org/en/v1/manual/types/#Parametric-Types) and [methods](https://docs.julialang.org/en/v1/manual/methods/#Parametric-Methods) rather than directly type-annotate the fields / arguments.
- Traits are functions that return True/False/Error based on the input type. See [holy traits](https://www.juliabloggers.com/the-emergent-features-of-julialang-part-ii-traits/) for more details.

## Delegation pattern

This is a form of polymorphism via composition[^1] to established packages to reuse their code at the cost of an additional layer of indirection.

[^1]: https://stackoverflow.com/questions/54789937/what-is-delegation-in-julia


## Holy traits

[Holy traits](https://www.juliabloggers.com/the-emergent-features-of-julialang-part-ii-traits/) are named after Tim Holy.

- Traits are empty structs.
- Data types are assigned catagorically to traits' interfaces, implementing different behavior for different kind of data type.
- Traits heirarchy could be separated from the type heirarchy they modeled.

[SimpleTraits.jl](https://github.com/mauro3/SimpleTraits.jl) automates some of the boilerplate code.

## Struct of arrays (SoA)

Struct of arrays (SoA) are superior to array of structs (AoS) in terms of performance in SIMD and GPU.

[StructArrays](https://github.com/JuliaArrays/StructArrays.jl) handles the mapping of AoS (on the surface) to SoA (in the memory).

## Memoization

Memoization saves duplicated work in repetitive or recursive calls.

[Memoize.jl](https://github.com/JuliaCollections/Memoize.jl) would do the boilerplate code.

## Barrier functions for type stability

Julia runs slower in type-unstable code. Use `@code_warntype` in front of an expression to spot type instability. (or use `@inferred` in unit tests to err on type instabilities) Use generic functions (aka barrier functions) to ensure type stability.

e.g.

- `zero(x)` instead of `0`.
- [Separate kernel functions](https://docs.julialang.org/en/v1/manual/performance-tips/#kernel-functions)

## Keyword definition for struct initialization

- [Parameters.jl](https://github.com/mauro3/Parameters.jl) package.
- Built-in `Base.@kwdef`.

## Accessor: getters and setters

Overload `Base.getproperty(x, :a)` for getters (`x.a`) and `Base.setproperty!(x, :a, val)` for setters (`x.a = val`).

## Let blocks

A `let` block defines its own local namespace. The variables defined inside a let block cannot be accessed outside and will not cause name conflicts.

## Functional pipes

Functional pipes `|>` are useful in data pipelines. Checkout [Chain.jl](https://github.com/jkrumbiegel/Chain.jl) for enhanced pipelines.

## Antipatterns

### Tpye instability

[*Type instability*](https://docs.julialang.org/en/v1/manual/faq/#man-type-stability) especially in tight loops yields poor performance.

### Global variables

The compiler will have a hard time inferring the type of the global (module-level) variable (it can be changed anytime) and could cause type instability in functions using it.  **However**, *global constants* are welcomed in Julia since the compiler can optimize global constants.

### Non-concrete field type

`struct A x::Real end` provides no benefit against `struct A x end`. Use parametric types instead alike the example below.

```julia
struct A{T<:Real}
    x::T
end
```

### Type piracy

Type piracy means redefining an existing function or twisting the behavior of a function. **Do not overload methods for types you do not own**.

### Narrow argument types

Narrow argument types means overspecialization. Write generic code first.

