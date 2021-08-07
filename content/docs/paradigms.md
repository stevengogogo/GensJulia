# Julia programming paradigms

- [Wikipedia: Programming Paradigms](https://en.wikipedia.org/wiki/Programming_paradigm)
- [Basic Language Comparison](https://github.com/JulesKouatchou/basic_language_comparison) : Basic Comparison of Various Computing Languages, eg. Python, Julia, Matlab, IDL, R, Java, Scala, C, Fortran.
- [Programming Language Theory](https://github.com/steshaw/plt-study)

## Automata

- [Wikipedia: Automata](https://en.wikipedia.org/wiki/Category:Automata_(computation))
- [Wikipedia: Finite Automata](https://en.wikipedia.org/wiki/Category:Finite_automata)

**Packages**

- [Automa.jl](https://github.com/BioJulia/Automa.jl) : A julia code generator for regular expressions - this package can do text validation, parsing, and tokenizing based on state machine compiler.
- [CodeTracking.jl](https://github.com/timholy/CodeTracking.jl) : An extension of Julia's InteractiveUtils library that provides an interface for obtaining strings and expressions of method definitions, method signatures, etc.. designed to work with Revise.jl (for versions v1.1.0 and higher).
- [MacroTools.jl](https://github.com/FluxML/MacroTools.jl) : A library providing helpful tools for writing macros, notably a very simple templating system with some functions

---

<details>

<summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [CellularAutomata.jl](https://github.com/natj/CellularAutomata.jl) : Cellular Automata package.
- 🏚️ [FiniteStateMachine.jl](https://github.com/tinybike/FiniteStateMachine.jl) : A simple Julia implementation of finite state machines.
- 🏚️ [InterVal.jl](https://github.com/J-Sarnoff/InterVal.jl) : Intervals are inter-values, an interval is its values and their intra-values.
- 🏚️ [LilKanren.jl](https://github.com/lilinjn/LilKanren.jl) : A collection of Kanren implementations in Julia. _miniKanren_ is an embedded Domain Specific Language for logic programming.

</details>

## Control Flow

- [Wikipedia: Control Flow](https://en.wikipedia.org/wiki/Category:Control_flow)
- [Julia docs: control-flow](https://docs.julialang.org/en/v1/manual/control-flow/)

**Packages**

- [CommonSubexpressions.jl](https://github.com/rdeits/CommonSubexpressions.jl) : Naïve combined subexpression elimination in Julia.
- [ControlSystems.jl](https://github.com/JuliaControl/ControlSystems.jl) : A Control Systems Toolbox for Julia.
- [IterTools.jl](https://github.com/JuliaCollections/IterTools.jl) : Common functional iterator patterns.
- [LinearControl.jl](https://github.com/jemofthewest/LinearControl.jl) : Julia package for analysis and design of control strategies for linear systems.
- [ProtoBuf.jl](https://github.com/JuliaIO/ProtoBuf.jl) : A Julia implementation for protocol buffers, a language-neutral, platform-neutral, extensible way of serializing structured data for use in communications protocols, data storage, and more.

---

<details>

<summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [Hooking.jl](https://github.com/Keno/Hooking.jl) : Function entry hooking for julia and C functions.
- 🏚️ [Iterators.jl](https://github.com/JuliaLang/Iterators.jl) : Common functional iterator patterns.
- 🏚️ [Slicot.jl](https://github.com/jcrist/Slicot.jl) : Julia wrapper for SLICOT Routines.
- 🏚️ [StatefulIterators.jl](https://github.com/andrewcooke/StatefulIterators.jl) : A stream-like wrapper around [iterable objects](https://en.wikipedia.org/wiki/Category:Iteration_in_programming).

</details>

## Functional Programming

See [Wikipedia: Declarative Programming](https://en.wikipedia.org/wiki/Declarative_programming) and [Wikipedia: Functional Programming](https://en.wikipedia.org/wiki/Functional_programming).

- [Chain.jl](https://github.com/jkrumbiegel/Chain.jl) : A Julia package for piping a value through a series of transformation expressions using a convenient syntax.
- [Glob.jl](https://github.com/vtjnash/Glob.jl) : Posix-compliant file name pattern matching.
- [Lazy.jl](https://github.com/MikeInnes/Lazy.jl) : Functional programming for Julia with lazily-evaluated lists and a large library of functions for working with them.
- [LispREPL.jl](https://github.com/swadey/LispREPL.jl) : REPL for `Lisp.jl`.
- [LispSyntax.jl](https://github.com/swadey/LispSyntax.jl) : lisp-like language in julia.
- [Monads.jl](https://github.com/pao/Monads.jl) : Monadic expressions and sequences for Julia. [hSee the doc](https://monadsjl.readthedocs.org/).
- [Pipe.jl](https://github.com/oxinabox/Pipe.jl) : Improved function piping in Julia.
- [MLStyle.jl](https://github.com/thautwarm/MLStyle.jl) : providing multiple productivity tools from ML (Meta Language) like pattern matching `@match`.

---

<details>

<summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [diy-lisp-julia](https://github.com/qhfgva/diy-lisp-julia) : A julia version of [diy-lisp](https://github.com/kvalle/diy-lisp).
- 🏚️ [FunctionalUtils.jl](https://github.com/zachallaun/FunctionalUtils.jl) : Functional Julia – based on fogus/lemonad.
- 🏚️ [PatternDispatch.jl](https://github.com/toivoh/PatternDispatch.jl) : Method dispatch based on pattern matching for Julia.

</details>

## Reversible programming

- [Article about reversible programming](https://www.sciencedirect.com/science/article/pii/S1571066110000204/pdf?md5=7014596c8e6fce7e9d8eee32ada5e1b5&pid=1-s2.0-S1571066110000204-main.pdf)

---

- [NiLang.jl](https://github.com/GiggleLiu/NiLang.jl) : a reversible domain-specific language (DSL). Every state change can be undone.

## Reactive Programming

[Wikipedia: Reactive Programming](https://en.wikipedia.org/wiki/Reactive_programming)

- [Pluto.jl](https://github.com/fonsp/Pluto.jl) : Simple reactive notebooks for Julia.
- [Reactive.jl](https://github.com/JuliaGizmos/Reactive.jl) : A package for reactive programming in Julia.
- [Rocket.jl](https://github.com/biaslab/Rocket.jl) : A functional reactive programming extensions library for Julia.

## Grammatical Evolution

<details>

<summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [Evolution.jl](https://github.com/xenon-/Evolution.jl) : Evolutionary Computation in Julia.
- 🏚️ [GrammaticalEvolution](https://github.com/abeschneider/GrammaticalEvolution) : An evolutionary technique that is similar to Genetic Programming (GP).

</details>

## Interpreters

[Wikipedia: Interpreters](https://en.wikipedia.org/wiki/Category:Interpreters_(computing))

- [JuliaInterpreter.jl](https://github.com/JuliaDebug/JuliaInterpreter.jl) : Interpreter for Julia code.

<details>

<summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [ASTInterpreter.jl](https://github.com/Keno/ASTInterpreter.jl) : Gallium's AST interpreter as a separate package to simplify development.

</details>

## Macro and Metaprogramming

**Resources**

- [Wikipedia: Macro](https://en.wikipedia.org/wiki/Macro_(computer_science))
- [Wikipedia: Metaprogramming](https://en.wikipedia.org/wiki/Metaprogramming)
- [Julia docs: Metaprogramming](https://docs.julialang.org/en/v1/manual/metaprogramming/#Metaprogramming)

**Packages**

- [SyntaxTree.jl](https://github.com/chakravala/SyntaxTree.jl) : Toolset for modifying Julia AST and characteristic values.

---

<details>

<summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [ForceImport.jl](https://github.com/chakravala/ForceImport.jl) : Macro that force imports conflicting methods in Julia modules
- 🏚️ [ImportMacros.jl](https://github.com/fredrikekre/ImportMacros.jl) : Provides three macros: @import and @using which loads a module and binds it to an alias, and @from which loads an object from a module and binds it to an alias.
- 🏚️ [MetaMerge.jl](https://github.com/davidagold/MetaMerge.jl) : Merge functions with identical names from distinct modules.
- 🏚️ [NotInferenceDontLookHere.jl](https://github.com/Keno/NotInferenceDontLookHere.jl) : Package to help with Inference development. This is not inference. However, it does help you with developing inference by loading a separate copy of inference into this package and hooking up Revise. This allows you to easily test changes to inference in isolation.
- 🏚️ [RegexVar.jl](https://github.com/o-jasper/RegexVar.jl) : A macro to fill variables straight from the string.
- 🏚️ [TimeIt.jl](https://github.com/kbarbary/TimeIt.jl) : Timeit macro for Julia.
- 🏚️ [Unroll.jl](https://github.com/StephenVavasis/Unroll.jl) : A julia macro for unrolling conditional `for` loops.
- 🏚️ [UTime.jl](https://github.com/J-Sarnoff/UTime.jl) : Universal Time using local system timezone.

</details>

## Automatic Programming

[Wikipedia: Automatic Programming](https://en.wikipedia.org/wiki/Automatic_programming)

- [Cassette.jl](https://github.com/JuliaLabs/Cassette.jl) : a Julia package that provides a mechanism for dynamically injecting code transformation passes into Julia’s just-in-time (JIT) compilation cycle, enabling post hoc analysis, optimization, and modification of "Cassette-unaware" Julia programs.
- [IRTools.jl](https://github.com/FluxML/IRTools.jl) : Intermediate Representation toolkit to provide a simple and flexible IR format, expressive enough to work with both lowered and typed Julia code, as well as external IRs. It can be used with Julia metaprogramming tools such as Cassette.
- [Revise.jl](https://github.com/timholy/Revise.jl) : Automatically update function definitions in a running Julia session. It will help you keep your sessions running longer, reducing the need to restart Julia whenever you make changes to code.


## Program Analysis

- [Wikipedia: Program Analysis](https://en.wikipedia.org/wiki/Category:Program_analysis)\
- [Julia docs: profiling](https://docs.julialang.org/en/v1/manual/profile/).

**Packages**

- [CallGraphs.jl](https://github.com/timholy/CallGraphs.jl) : A package for analyzing source-code callgraphs, particularly of Julia's `src/` directory. The main motivation for this package was to aid in finding all functions that might trigger garbage collection by directly or indirectly calling `jl_gc_collect`; however, the package has broader uses.
- [Lens.jl](https://github.com/zenna/Lens.jl) : A simple Julia library to inspect the runtime behaviour of your programs, with minimal interference to the program itself.
- [LRUCache.jl](https://github.com/JuliaCollections/LRUCache.jl) : An implementation of a Least Recently Used (LRU) Cache.
- [ProfileSVG.jl](https://github.com/kimikage/ProfileSVG.jl) : Write flame graphs to SVG format and explore them interactively in Jupyter, Pluto, etc.
- [ProfileView.jl](https://github.com/timholy/ProfileView.jl) : Visualization of Julia profiling data
- [StatProfilerHTML.jl](https://github.com/tkluck/StatProfilerHTML.jl) : Show Julia profiling data in an explorable HTML page.

---

<details>

<summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [ASTInterpreter2.jl](https://github.com/Keno/ASTInterpreter2.jl) : Re-write of ASTInterpreter for `julia 0.6+`.
- 🏚️ [dataflow.jl](https://github.com/JeffBezanson/dataflow.jl) : Introduction to dataflow analysis using julia.
- 🏚️ [ExpressionPatterns.jl](https://github.com/fcard/ExpressionPatterns.jl) : Match, Destructure and Dispatch on expressions.
- 🏚️ [PAPI.jl](https://github.com/jakebolewski/PAPI.jl) : Julia bindings to the Performance Application Programming Interface (PAPI).

</details>

## Polymorphism amd multiple dispatch

**Resources**

- [Wikipedia: Polymorphism](https://en.wikipedia.org/wiki/Category:Polymorphism_(computer_science)) and [Holy Traits pattern](https://ahsmart.com/pub/holy-traits-design-patterns-and-best-practice-book.html).
- [The Design Impact of Multiple Dispatch](http://nbviewer.jupyter.org/gist/StefanKarpinski/b8fe9dbb36c1427b9f22) presented by StefanKarpinski at Strange Loop on 19-Sep-2013.
- [JuliaCon 2019: The Unreasonable Effectiveness of Multiple Dispatch by Stefan Karpinski](https://youtu.be/kc9HwsxE1OY)

**Packages**

- [BinaryTraits.jl](https://github.com/tk3369/BinaryTraits.jl) : easy-to-use trait library with formal interface specification support.
- [SimpleTraits.jl](https://github.com/mauro3/SimpleTraits.jl) : Simple Traits for Julia.
- [WhereTraits.jl](https://github.com/schlichtanders/WhereTraits.jl) : This package exports one powerful macro @traits with which you can extend Julia's where syntax.

---

<details>

<summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [julia-pattern-dispatch](https://github.com/toivoh/julia-pattern-dispatch) : Support for method dispatch in Julia based on pattern matching.

</details>

## Static analysis

- [Lint.jl](https://github.com/tonyhffong/Lint.jl) : A lint tool to hunt for imperfections and dodgy structures that could be improved for Julia code.
- [TimerOutputs.jl](https://github.com/KristofferC/TimerOutputs.jl) : Formatted output of timed sections in julia.

---

<details>

<summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [Quantity.jl](https://github.com/rephorm/Quantity.jl) : Numbers with units.
- 🏚️ [StackTraces.jl](https://github.com/invenia/StackTraces.jl) : Intuitive, useful stack traces for Julia. StackTraces functionality has been merged into the Julia standard library as of v0.5.

</details>

## Style Guidelines

- [Official Julia style guide](https://docs.julialang.org/en/v1/manual/style-guide/)
- [BlueStyle](https://github.com/invenia/BlueStyle) : A Julia style guide that lives in a blue world.
