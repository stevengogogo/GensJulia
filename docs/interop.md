# Julia interop

> Julia interoperativity with other programming languages.

- [JuliaInterop Organization](https://github.com/JuliaInterop)

## Mathematica

- [MathLink.jl][] : Julia language interface for Mathematica/Wolfram Engine.

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [Mathematica.jl](https://github.com/MikeInnes/Mathematica.jl) : is a package that provides an interface for using Wolfram Mathematica™ from the Julia language. Use [MathLink.jl][] instead.

</details>

[MathLink.jl]: https://github.com/JuliaInterop/MathLink.jl

## Git

- [Git.jl](https://github.com/JuliaVersionControl/Git.jl) : Julia wrapper for command line Git.
- [GitHub.jl](https://github.com/JuliaWeb/GitHub.jl) : A Julia package for interfacing with the GitHub API.

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [MechaJulia](https://github.com/MechaJulia/MechaJulia) : A little GitHub bot that will assist with anything and everything Julia-related that is needed of it.
- 🏚️ [Octokit.jl](https://github.com/Keno/Octokit.jl) : Julia package to access the GitHub API.

</details>

## C

A built-in [native c interface](https://docs.julialang.org/en/v1/manual/calling-c-and-fortran-code/) is available.

- [Clang.jl](https://github.com/JuliaInterop/Clang.jl) : A Julia language wrapper for libclang: the stable, C-exported interface to the LLVM Clang compiler.

## Cpp

- [CxxWrap.jl][] : A package to provide a Boost.Python-like wrapping for C+- types and functions to Julia.

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [Cpp.jl](https://github.com/timholy/Cpp.jl) : Utilities for calling C+- from Julia. Use [CxxWrap.jl][] instead.
- 🏚️ [Cxx.jl](https://github.com/Keno/Cxx.jl) : The Julia C+- Foreign Function Interface (FFI) with `@cxx` macro. Only works (out of the box) currently with Julia 1.1.x to 1.3.x.
- 🏚️ [CxxROOT.jl](https://github.com/Keno/CxxROOT.jl) : A Cxx.jl based interface to CERN's ROOT.

</details>

[CxxWrap.jl]: https://github.com/barche/CxxWrap.jl

## Erlang

- [ErlPort.jl](https://github.com/thorgisl/ErlPort.jl) : A Julia-Erlang module for use in the [erlport](http://erlport.org) project.

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [FsBert](https://github.com/et4te/FsBert) : A Julia library for encoding / decoding binary Erlang terms.

</details>

## Fortran

Julia has [native Fortran interface](https://docs.julialang.org/en/v1/manual/calling-c-and-fortran-code/). Projects like 🏚️ [FortranIO.jl](https://github.com/rephorm/FortranIO.jl) are obsolete.

## Go

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [GoTMSupport.jl](https://github.com/ordovician/GoTMSupport.jl) : Support for writing bundle commands for the Go programming language in Julia.

</details>

## Java

### Running Java from Julia

- [JavaCall.jl](https://github.com/JuliaInterop/JavaCall.jl) : call Java programs from Julia.
- [JDBC.jl](https://github.com/aviks/JDBC.jl) : Julia interface to Java database drivers.
- [TeaSeis.jl](https://github.com/ChevronETC/TeaSeis.jl) : JavaSeis IO implementation for the Julia language.

### Running Julia from Java

[Discourse thread: Embedding Julia in the Java Virtual Machine](https://discourse.julialang.org/t/embedding-julia-in-the-java-virtual-machine/51444).

- [julia4j](https://github.com/rssdev10/julia4j) : Julia4J uses SWIG to build a Java Native Interface (JNI) integration with Julia.
- [libjulia-clj](https://github.com/cnuernber/libjulia-clj) : Julia bindings for Clojure JVM.

## JavaScript

- [JSExpr.jl](https://github.com/JuliaGizmos/JSExpr.jl) : Translate Julia to JavaScript.
- [Mustache.jl](https://github.com/jverzani/Mustache.jl) : Port of mustache.js to julia.
- [TableView.jl](https://github.com/JuliaComputing/TableView.jl) : an ag-grid based table viewer built on [WebIO.jl](https://github.com/JuliaGizmos/WebIO.jl).

---

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [DThree.jl](https://github.com/jverzani/DThree.jl) : Simple interface to d3.js from Julia. And its fork 🏚️ [d3.jl](https://github.com/EricForgy/d3.jl)
- 🏚️ [GoogleCharts.jl](https://github.com/jverzani/GoogleCharts.jl) : Julia interface to Google Chart Tools.
- 🏚️ [jlbox](https://github.com/compressed/jlbox) : Use node.js to provide a mechanism for automatically reloading julia source and test files via gulp.js and a ZMQ socket.
- 🏚️ [JSTypes.jl](https://github.com/johnmyleswhite/JSTypes.jl) : Mimic Javascript objects using Julian types.
- 🏚️ [node-julia](https://github.com/waTeim/node-julia) :  Fast and simple access to `Julia` embedded in `node.js`.
- 🏚️ [PlotlyJS.jl](https://github.com/EricForgy/PlotlyJS.jl) : A Julia wrapper API for `plotly.js`by @EricForgy. Merged with the package above?
- 🏚️ [Vue.jl](https://github.com/JuliaGizmos/Vue.jl) : A Julia wrapper for `Vue.js`.

</details>

## MATLAB

**See also**

[matlab-to-julia](https://lakras.github.io/matlab-to-julia/) online translator.

**Packages**

- [JuliaFromMATLAB.jl](https://github.com/jondeuce/JuliaFromMATLAB.jl) : Call Julia from MATLAB.
- [MAT.jl](https://github.com/JuliaIO/MAT.jl) : A Julia module for reading MATLAB files.
- [MATLAB.jl](https://github.com/JuliaInterop/MATLAB.jl) : an interface for using MATLAB® from Julia using the MATLAB C api.

---

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [MatlabCompat.jl](https://github.com/MatlabCompat/MatlabCompat.jl) : Julia library aimed at simplifying conversion of legacy MATLAB/Octave code into Julia by providing functions similar to MATLAB/Octave.
- 🏚️ [Mex.jl](https://github.com/juliamatlab/mexjulia) : Call Julia from matlab. Call Julia from MATLAB. This project is effectively in hibernation as its author no longer has access to matlab.
- 🏚️ [Moonwalk.jl](https://github.com/diogo149/Moonwalk.jl) : A partial MATLAB to Julia compiler, just to ease the transition of libraries.

</details>

## ObjectiveC

- [ObjectiveC.jl](https://github.com/JuliaInterop/ObjectiveC.jl) : A Julia library that allows you to call Objective-C methods using native syntax.

## Perl

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [FileFind.jl](https://github.com/johnmyleswhite/FileFind.jl) : Minimal Implementation of Perl's `File:Find` in Julia.

</details>

## Python

- [FStrings.jl](https://github.com/magonser/FStrings.jl) : Implementation of Python style [fsrings](https://www.python.org/dev/peps/pep-0498/) literal string interpolation based on `Printf.@sprintf`.
- [PyCall.jl](https://github.com/JuliaPy/PyCall.jl) : Call Python functions from Julia.
- [PyJulia](https://github.com/JuliaPy/pyjulia) : Python interface to Julia. (Call Julia functions from Python)

---

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [Polyglot.jl](https://github.com/wavexx/Polyglot.jl) : Transparent remote/recursive evaluation between languages - it also supports Perl, PHP and Javascript.
- 🏚️ [PySyntax.jl](https://github.com/kdheepak/PySyntax.jl) : Allows Python-like syntax in Julia by providing a light wrapper on top of PyCall.jl in the form of a macro.

</details>

## R

> - [Julia in Rmarkdown](https://cran.r-project.org/web/packages/JuliaCall/vignettes/Julia_in_RMarkdown.html) using [JuliaCall](https://rpubs.com/Consistency/310507).

- [RCall.jl](https://github.com/JuliaStats/RCall.jl) : Embedded R within Julia - ports all the `R` API functions from C into Julia.
- [RData.jl](https://github.com/JuliaData/RData.jl) : CodeIssues 5Pull requests 0Projects 0WikiSecurityInsightsRead R data files from Julia.
- [ReadStat.jl](https://github.com/WizardMac/ReadStat.jl) : Read files from Stata, SAS, and SPSS.

---

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [jl4R](https://github.com/rcqls/jl4R) : `Julia for R` will embed the julia language in R, with very basic julia types getting converted into R objects.
- 🏚️ [ProjectTemplate.jl](https://github.com/johnmyleswhite/ProjectTemplate.jl) : is a draft port of the ProjectTemplate package for R to Julia.
- 🏚️ [RCalling.jl](https://github.com/randy3k/RCalling.jl) : An R interface of Julia - uses the Julia API (in C) and `R` API (also in C) intensively to call R library packages.
- 🏚️ [Rif.jl](https://github.com/lgautier/Rif.jl) : An interface to the R language and its fork, 🏚️ [Julio](https://github.com/tshort/julio).
- 🏚️ [RJulia](https://github.com/armgong/RJulia) : R package to call Julia - Use Julia embedded API to write a packege for R.
- 🏚️ [utils.jl](https://github.com/johnmyleswhite/utils.jl) : Utility functions for Julia -R compatibility wrapper.
- 🏚️ Run Julia code chunk in [knitr](http://rpubs.com/yihui/julia-knitr) : Allows you to run Julia from R using [julia_socket.jl](https://github.com/yihui/runr/blob/master/inst/lang/julia_socket.jl)

</details>

## REDUCE

- [Reduce.jl][] : Symbolic parser generator for Julia language expressions using REDUCE algebra term rewriter.
- [ReduceAlgebra.jl][] : Meta-package for [Reduce.jl][] and External Packages (e.g. [ReduceLinAlg.jl][])
- [ReduceLinAlg.jl][] : A selection of functions that are useful in the world of linear algebra.

[ReduceAlgebra.jl]: https://github.com/JuliaReducePkg/ReduceAlgebra.jl
[Reduce.jl]: https://github.com/chakravala/Reduce.jl
[ReduceLinAlg.jl]: https://github.com/JuliaReducePkg/ReduceLinAlg.jl

## Ruby

[Ruby interoperability](https://github.com/arbox/ruby-interoperability)

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [guard-julia](https://github.com/svs14/guard-julia) : Guard plugin for Julia development. Julia guard automatically launches respective tests when Julia files are modified.
- 🏗️ [jl4rb](https://github.com/rcqls/jl4rb) : Julia for Ruby embeds the julia language in ruby, with very basic julia types being converted to ruby objects.
- 🏗️🏚️ [ruby-julia](https://github.com/mrkn/ruby-julia) : Julia on Ruby (frequently updated, but supports Julia 1.1 only)

</details>
