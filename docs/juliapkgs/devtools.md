# Development tools for Julia

> Developement tools, compilers, debuggers, [DevOps](https://en.wikipedia.org/wiki/DevOps)

- [awesome devops](https://github.com/wmariuss/awesome-devops)
- [cache.julialang.org](https://github.com/staticfloat/cache.julialang.org) : JuliaLang binary caching infrastructure.
- [Devops Weekly](http://www.devopsweekly.com/) by email subscription.
- [Julia Server Status](http://status.julialang.org/) : Status page for services hosted by JuliaLang.
- [julia-buildbot](https://github.com/staticfloat/julia-buildbot) : Buildbot configuration for [build.julialang.org](https://build.julialang.org/).
- [JuliaHub](https://juliahub.com/ui/Home)
- [General registry](https://github.com/JuliaRegistries/General) : The official registry of general Julia packages.

**Organizations**

- [Julia debug](https://github.com/JuliaDebug)
- [Julia editor suport](https://github.com/JuliaEditorSupport)
- [Julia packaging](https://github.com/JuliaPackaging)

## Developing Julia packages

- [Compat.jl](https://github.com/JuliaLang/Compat.jl) : A package for cross-version compatibility between old Julia and the new - takes care of syntax breakage and provides compatibility constructs that will work in both versions without warnings.
- [Kip.jl](https://github.com/jkroso/Kip.jl) : An Python-like, alternative module system for Julia.
- [PkgCite.jl](https://github.com/SebastianM-C/PkgCite.jl) : prints a sentence with the citations for all the packages used in the current environment and will automatically copy it to the clipboard.
- [PkgSkeleton.jl][] : Generate Julia package skeletons using a simple template system.
- [PkgTemplates.jl][] : Create new Julia packages, the easy way. Include templaye files for GitHub / GitLab CI.
- [PkgUtils.jl](https://github.com/arnavs/PkgUtils.jl) by @arnavs : Some small utilities to help with Julia packages
- [Registrator.jl](https://github.com/JuliaComputing/Registrator.jl) : Julia [package](https://pkg.julialang.org/) registration bot.
- [Requires.jl](https://github.com/MikeInnes/Requires.jl) : Lazy code loading for Julia.
- [VersionParsing.jl](https://github.com/stevengj/VersionParsing.jl) : flexible VersionNumber parsing in Julia.

[PkgTemplates.jl]: https://github.com/invenia/PkgTemplates.jl
[PkgSkeleton.jl]: https://github.com/tpapp/PkgSkeleton.jl

---

- 🏗️ [PkgDev.jl](https://github.com/JuliaLang/PkgDev.jl) : Julia Package Development Kit.
- 🏚️ [attobot](https://github.com/attobot/attobot) : Julia package release bot. Use `Registrator.jl` now.
- 🏚️ [DeclarativePackages.jl](https://github.com/rened/DeclarativePackages.jl) : (jdp for short), allows the project to declaratively specify which Julia packages are being used, with exact version or commit details.
- 🏚️ [EasyPkg.jl](https://github.com/oschulz/EasyPkg.jl) : A Julia package to simplify package development.
- 🏚️ [Help.jl](https://github.com/nkottary/Help.jl) : Reverse documentation for Julia.
- 🏚️ [julia-require](https://github.com/MetalNinjas/julia-require) : Macros to make loading (and reloading) files in Julia easier.
- 🏚️ [JuliaPackageMirrors](https://github.com/JuliaPackageMirrors) : An organization that archives of all registered Julia packages.
- 🏚️ [Julz.jl](https://github.com/djsegal/Julz.jl) : Opinionated Framework for Developing Packages.
- 🏚️ [METADATA.jl](https://github.com/JuliaLang/METADATA.jl) : The official set of Julia packages. Replaced by `General` registry.
- 🏚️ [MetadataTools.jl](https://github.com/JuliaPackaging/MetadataTools.jl) : Functionality to analyze the structure of Julia's METADATA repository.
- 🏚️ [mirror-updater](https://github.com/JuliaPackageMirrors/mirror-updater) : Update script for JuliaPackageMirrors.
- 🏚️ [NettleBuilder](https://github.com/staticfloat/NettleBuilder/) : BinaryBuilder repo for `libnettle`.
- 🏚️ [PackageEvaluator.jl](https://github.com/IainNZ/PackageEvaluator.jl) : The Julia package evaluator.
- 🏚️ [PkgUtils.jl](https://github.com/johnmyleswhite/PkgUtils.jl) @johnmyleswhite : Tools for analyzing Julia packages.
- 🏚️ [PrivateModules.jl](https://github.com/JuliaPackageMirrors/PrivateModules.jl) : Julia package mirror.

### Prebuilt Binaries

See [Julia Packaging](https://github.com/JuliaPackaging) team. The binary repository is called [Yggdrasil][].

- [BinaryBuilder.jl](https://github.com/JuliaPackaging/BinaryBuilder.jl) : Binary Dependency Builder for Julia.
- [BinaryProvider.jl](https://github.com/JuliaPackaging/BinaryProvider.jl) : A reliable binary provider for Julia.
- [BinDeps.jl](https://github.com/JuliaLang/BinDeps.jl) : Tool for building binary dependencies for Julia modules.
- [Conda.jl](https://github.com/Luthaf/Conda.jl) : Conda managing Julia binary dependencies. e.g. for `IJulia.jl` and `PyPlot.jl`.
- [RunBinary.jl](https://gitlab.com/aplavin/RunBinary.jl) : running binaries from the [Yggdrasil][] repo.


[Yggdrasil]: https://github.com/JuliaPackaging/Yggdrasil

### Compilers

- [PackageCompiler.jl](https://github.com/JuliaLang/PackageCompiler.jl) : Compile your Julia enviironment into a system image or a standalone binary.
- [SnappyBuilder](https://github.com/davidanthoff/SnappyBuilder) : BinaryBuilder for `libsnappy` to build [julia snap](https://snapcraft.io/julia).
- 🏚️ [BuildExecutable.jl](https://github.com/dhoegh/BuildExecutable.jl) : Build standalone executables from a Julia script.
- [Clang.jl](https://github.com/ihnorton/Clang.jl) : Julia interface to libclang and C wrapper generator.
- [llvm-cbe](https://github.com/JuliaComputing/llvm-cbe) : A resurrected LLVM C Backend, with improvements for Julia.

---

- 🏚️ [CompilerOptions.jl](https://github.com/sjkelly/CompilerOptions.jl) : A Julia package for reading compiler options.
- 🏚️ [CompilerTools.jl](https://github.com/IntelLabs/CompilerTools.jl) : The CompilerTools package, part of the High Performance Scripting project at Intel Labs.
- 🏚️ [Eglib.jl](https://github.com/ihnorton/Eglib.jl) : Clang.jl wrapping example, C code from @kindlmann.
- 🏚️ [JITTools.jl](https://github.com/Keno/JITTools.jl) : Tools for working with in-memory object.
- 🏚️ [julia-icc-travis](https://github.com/sunoru/julia-icc-travis) : Build Julia using icc on the Travis CI.
- 🏚️ [LLVM.jl](https://github.com/jakebolewski/LLVM.jl) : A Julia package for LLVM.
- 🏚️ [ParallelAccelerator.jl](https://github.com/IntelLabs/ParallelAccelerator.jl) : The ParallelAccelerator package, part of the High Performance Scripting project at Intel Labs.

### Julia developement helpers

Bridging pre-1.0 Julia code to 1.0+.

- 🏚️ [FemtoCleaner.jl](https://github.com/JuliaComputing/FemtoCleaner.jl) : The [FemtoCleaner](https://github.com/apps/femtocleaner) app cleans your julia projects by upgrading deprecated syntax, removing version compatibility workarounds and anything else that has a unique upgrade path. This app exist to smooth the transition from Julia version 0.6 to 0.7(1.0+).
- 🏚️ [HackThatBase.jl](https://github.com/ihnorton/HackThatBase.jl) : A helper tool to reload and test modifications to base without recompiling the full system image.
- 🏚️ [PkgSearch.jl](https://github.com/essenciary/PkgSearch.jl) : A Julia REPL utility for package discovery.
- 🏚️ [PkgVerifierPrototype](https://github.com/LachlanGunn/PkgVerifierPrototype) : Julia package verifier prototype.


## Test-driven develpment (TDD)

- [Unittest in Julia](https://docs.julialang.org/en/v1/stdlib/Test/)
- [Test driven development (TDD)](https://blog.staffjoy.com/test-driven-development-in-juliajk-8b66d3664852) in Julia.

**Packages**

- [Coverage.jl](https://github.com/JuliaCI/Coverage.jl) : tracking code testing coverage and memory usage and optionally upload them to online services like Coveralls or Codecov. Its base library is [CoverageBase.jl](https://github.com/JuliaCI/CoverageBase.jl).
- [Jive.jl](https://github.com/wookay/Jive.jl) : running test in parallel. It also supports watch folder function.
- [MockAWS.jl](https://github.com/JuliaCloud/MockAWS.jl) : patch functions for testing all AWS services.
- [Mocking.jl](https://github.com/invenia/Mocking.jl) : allowing temporary overwriting of Julia methods for testing purposes.
- [Watcher.jl](https://github.com/rened/Watcher.jl) : auto-run unit tests every time a file gets saved.
- [UnitTestDesign.jl](https://github.com/adolgert/UnitTestDesign.jl) : chooses effiennt combinations functional arguments to maximize test coverage.


---

- 🏚️ [BaseTestDeprecated.jl](https://github.com/IainNZ/BaseTestDeprecated.jl) : Provides the `Base.Test` functionality removed in `Julia v0.5`.
- 🏚️ [FactCheck.jl](https://github.com/zachallaun/FactCheck.jl) : Midje-like testing framework written for Julia.
- 🏚️ [Fixtures.jl](https://github.com/burrowsa/Fixtures.jl) : provides fixtures, mocks, matchers and patching to improve your tests with Julia.
- 🏚️ [Jig.jl](https://github.com/milktrader/Jig.jl) : Testing framework for Julia.
- 🏚️ [JLTest](https://github.com/smangano/JLTest) : A unittest framework for Julia (inspired by Python's unittest).
- 🏚️ [JulieTest.jl](https://github.com/arypurnomoz/JulieTest.jl) : A Julia testing framework inspired by javascript's Mocha. See the [Wiki](https://github.com/arypurnomoz/JulieTest.jl/wiki)
- 🏚️ [microcoverage](https://github.com/StephenVavasis/microcoverage) : This module computes code coverage for a Julia program at a more fine-grained level than the built-in coverage feature. Specifically, it provides coverage counts for each branch of the `||, && and ?:` operators where they occur. It also counts the number of invocations to statement-functions.
- 🏚️ [PackageTesting.jl](https://github.com/johnmyleswhite/PackageTesting.jl) : A standard for testing Julia packages.
- 🏚️ [RunTests.jl](https://github.com/burrowsa/RunTests.jl) : A test running framework for Julia that extends Base.Test
- 🏚️ [Saute.jl](https://github.com/milktrader/Saute.jl) : is another testing framework for Julia.
- 🏚️ [testfast.jl](https://github.com/Veraticus/testfast.jl) : Automatically finds test files and runs them.
- 🏚️ [Fuzz.jl](https://github.com/danluu/Fuzz.jl) : A naive fuzzer that can generate bugs.

### Logging

Use the built-in [logging](https://docs.julialang.org/en/v1/stdlib/Logging/) facilities instead.

- 🏚️ [Log4jl.jl](https://github.com/wildart/Log4jl.jl) : A comprehensive and flexible logging framework for Julia programs.
- 🏚️ [Logging.jl](https://github.com/kmsquire/Logging.jl) : The Logging module.
- 🏚️ [LogMover.jl](https://github.com/nkottary/LogMover.jl)
- 🏚️ [Lumberjack.jl](https://github.com/forio/Lumberjack.jl) : A logging library by Westley Hennigh.
- 🏚️ [Stage.jl](https://github.com/saltpork/Stage.jl) : has stage macros, checkpoints and loggers for Julia.

### Regression Testing

- [PkgBenchmark.jl](https://github.com/JuliaCI/PkgBenchmark.jl) : Easy benchmark tracking for packages
- [PkgEval.jl](https://github.com/JuliaCI/PkgEval.jl) : Evaluate Julia packages for a range of Julia versions.
- [VisualRegressionTests.jl](https://github.com/JuliaPlots/VisualRegressionTests.jl) : Automated integrated regression tests for graphics libraries.

## Debugger

- [Debugger.jl](https://github.com/JuliaDebug/Debugger.jl) : Julia debugger using the `@enter` macro.
- [Ghost.jl](https://github.com/dfdx/Ghost.jl) : a code tracer for the Julia programming language. It lets you trace the function execution, recording all primitive operations onto a linearized tape.
- [Infiltrator.jl](https://github.com/JuliaDebug/Infiltrator.jl) : `@infiltrate` macro sets a "breakpoint" in a local context. All code is completely compiled.
- [Rebugger.jl](https://github.com/timholy/Rebugger.jl) : An expression-level debugger for Julia, sans the ability to interact with or manipulate call stacks (see [Gallium](https://github.com/Keno/Gallium.jl)), but it can trace execution via the manipulation of Julia expressions.
- [Suppressor.jl](https://github.com/Ismael-VC/Suppressor.jl) :  Julia macros for suppressing output (STDOUT), warnings (STDERR) or both streams at the same time.
- [ToggleableAsserts.jl](https://github.com/MasonProtter/ToggleableAsserts.jl) : Assertions that can be turned on or off with a switch, without runtime penalty when they're off.
- [Traceur.jl](https://github.com/MikeInnes/Traceur.jl) : codified version of the [Julia performance tips](https://docs.julialang.org/en/v1/manual/performance-tips/). You run your code, it tells you about any obvious performance traps.

---

- 🏚️ [Debug.jl](https://github.com/toivoh/Debug.jl) : Prototype interactive debugger for Julia.
- 🏗️ [DebuggingUtilities.jl](https://github.com/timholy/DebuggingUtilities.jl) : Simple utilities for debugging julia code.
- 🏚️ [ASTInterpreter2.jl](https://github.com/Keno/ASTInterpreter2.jl) : Re-write of ASTInterpreter for julia v0.6+.
- 🏚️ [Gallium.jl](https://github.com/Keno/Gallium.jl) : The Julia debugger for CPP.
- 🏚️ [RR.jl](https://github.com/Keno/RR.jl) : Julia interface to mozilla's `rr`.

## Documentation

[Julia docstrings](https://docs.julialang.org/en/v1/manual/documentation/)

- [CommonMark.jl](https://github.com/MichaelHatherly/CommonMark.jl) : A CommonMark-compliant parser for Julia.
- [DocStringExtensions.jl](https://github.com/JuliaDocs/DocStringExtensions.jl) : Extensions for Julia's docsystem.
- [Documenter.jl](https://github.com/JuliaDocs/Documenter.jl) : Official documentation generator for Julia.
- [Literate.jl](https://github.com/fredrikekre/Literate.jl) : literate programming in Julia.
- [Remark.jl](https://github.com/piever/Remark.jl) : A Julia package to create presentations from markdown using Remark.
- [sphinx-julia](https://github.com/bastikr/sphinx-julia) : Documenting Julia projects with Sphinx.
- [Weave.jl](https://github.com/JunoLab/Weave.jl) : A scientific report generator/literate programming tool for Julia based on Pweave and resembles Knitr and Sweave.

---

- 🏚️ [Docile.jl](https://github.com/MichaelHatherly/Docile.jl) : Experimental Julia package documentation system.
- 🏚️ [Doxygen](https://github.com/jiahao/julia/tree/cjh/doxygen) : A branch providing support for documenting in Julia using Doxygen and doxyfilter.jl tools.
- 🏚️ [HelpTestbed.jl](https://github.com/tshort/HelpTestbed.jl) : package is for exploring options for help when you add a Julia package - when used from the REPL, the @help macro fetches, say, the signature of a function call, which can be used to find the package.
- 🏚️ [Judo.jl](https://github.com/dcjones/Judo.jl) : is a Julia document generator, which takes documents written in pandoc markdown and converts them into html, but differs from general purpose markdown tools in a few ways.
- 🏚️ [Lexicon.jl](https://github.com/MichaelHatherly/Lexicon.jl) : Julia package documentation generator that provides access to the documentation created by the @doc macro from Docile.jl. It allows querying of package documentation from the Julia REPL and building HTML documentation.
- 🏚️ [Publish.jl](https://github.com/dressel/Publish.jl) : A package for publishing code - uses Latex to create a pdf with your code and output.
- 🏚️ [Report.jl](https://github.com/sveme/Report.jl) : A Markdown report writer for Julia.
- 🏚️ [Roxygen.jl](https://github.com/johnmyleswhite/Roxygen.jl) : A Roxygen-like documentation package for automatically generating documentation from Julia source files.
- 🏚️ [Tuxedo.jl](https://github.com/milktrader/Tuxedo.jl) : Dressing up your algorithms with documentation-driven development.

## IDE

Integrated development environment.

See [Julia editor suport](https://github.com/JuliaEditorSupport) team.

- [jEdit-julia](https://github.com/tuckerkevin/jedit-julia) : A [jEdit](http://jedit.org/) mode for Julia.
- [Julia VSCode](https://www.julia-vscode.org/) : A powerful, free IDE for the Julia language.
- [Julia.tmbundle](https://github.com/JuliaLang/Julia.tmbundle) : Julia language support for TextMate 2 (and Sublime Text).
- [Liclipse](https://www.liclipse.com/) : LiClipse, Eclipse plus some customizations, supports Julia.
- [OhMyREPL.jl](https://github.com/KristofferC/OhMyREPL.jl) : Syntax highlighting and other enhancements for the Julia REPL.
- [Reminisce](https://github.com/JuliaIDE/Reminisce) : Sublime-style saving of tabs and content for Light Table.
- [JuliaMono](https://github.com/cormullion/juliamono) : a monospaced font for Julia (and of course other languages).


---

- 🏚️ [Acorn.jl](https://github.com/nick-paul/Acorn.jl) : A pure julia text editor.
- 🏚️ [BlinkEditor.jl](https://github.com/EricForgy/BlinkEditor.jl) : A simple Blink editor based on Mike Innes' JuliaCon 2015 presentation.
- 🏚️ [InteractNext.jl](https://github.com/JuliaGizmos/InteractNext.jl) : is a lot like Interact.jl, except that as well as running in IJulia, it also works in the Atom/Juno IDE, in a desktop window with `Blink.jl`, and served in a webpage via `Mux.jl`.
- 🏚️ [Jewel.jl](https://github.com/JuliaIDE/Jewel.jl) : IDE backend for Julia.
- 🏚️ [julia-ide](https://github.com/malmaud/julia-ide) : YAJI.
- 🏚️ [Julia-LT](https://github.com/JuliaIDE/Julia-LT) : Julia plugin for Light Table based on the Jewel.jl editor backend.
- 🏚️ [JuliaDT.jl](https://github.com/JuliaComputing/JuliaDT) : Julia Development Toolkit for Eclipse.
- 🏚️ [Julietta.jl](https://github.com/tknopp/Julietta.jl) : An integrated developement environment (IDE) for the programming language Julia.
- 🏚️ [June-LT](https://github.com/JuliaIDE/June-LT) : The June themes for Light Table.
- 🏚️ [Juno-LT](https://github.com/JuliaIDE/Juno-LT) : A Julia environment built on Light Table. [JunoLab](http://junolab.org).
- 🏚️ [JunoLTDistro](https://github.com/JuliaIDE/JunoLTDistro) : Juno-LT Distribution & Installer.
- 🏚️ [Sublime-Julia](https://github.com/quinnj/Sublime-Julia) : Sublime Syntax, Build, Snippets, and REPL for the Julia language. 🏚️ [JuliaCompletions](https://github.com/jakeconnor/JuliaCompletions)

### Atom

> The development is shifted to Julia VSCode. Juno (Julia in Atom) is currently in maintenance mode.

- [Atom.jl](https://github.com/JunoLab/Atom.jl) : Julia Client for Atom. Maintenance-only mode.
- [atom-language-julia](https://github.com/JuliaLang/atom-language-julia) : A Julia language support package for the Atom editor.
- [atom-julia-client](https://github.com/JunoLab/atom-julia-client) : Julia Eval in Atom.
- 🏚️ [Electron.jl](https://github.com/jkroso/Electron.jl) : Provides easy access to atom/electron from Julia.
- 🏚️ [Jude](https://github.com/jamesdanged/Jude) : A set of [development extensions](https://atom.io/packages/jude) for Julia in the Atom editor to improve developer productivity. Currently, it provides `autocomplete` and `jump to definition`.

### Emacs

- [emacs-ess-julia.el](https://github.com/emacs-ess/ESS/blob/master/lisp/ess-julia.el) : ESS support for julia language, includes font-lock, indentation, sending code to sub-process, interactive documentation, imenu, completion and eldoc. Also see its [Installation instructions for Julia](https://github.com/emacs-ess/ESS/wiki/Julia)
- [julia-emacs](https://github.com/JuliaEditorSupport/julia-emacs) : Julia support in Emacs.
- [julia-repl](https://github.com/tpapp/julia-repl) : Run an interior Julia REPL in a terminal inside Emacs.

### Vim

- [Julia-Vim](https://github.com/JuliaLang/julia-vim).
- [Neovim.jl](https://github.com/bfredl/Neovim.jl) by @bfredl : Neovim client for Julia.
- [vim-notebook](https://github.com/baruchel/vim-notebook) : Vim users can use Julia from the `vim-notebook` plugin.

### Jupyter

[Jupyter](https://github.com/jupyter)


- [IJulia.jl](https://github.com/JuliaLang/IJulia.jl) : Julia kernel for Jupyter. How to create a [Custom IJulia Widget](http://nbviewer.ipython.org/urls/gist.githubusercontent.com/avrahamruderman/116845471f0d79942aff/raw/fb1f659e635f4585ebb449aa2519deffd15aba31/writing-custom-ijulia-widgets.ipynb)
- [Interact.jl](https://github.com/JuliaLang/Interact.jl) : Library for interactive widgets in IJulia.
- [IPython.jl](https://github.com/tkf/IPython.jl) : Launch IPython in Julia.
- [jupyterhub](https://github.com/jupyterhub/jupyterhub) : Multi-user server for Jupyter notebooks.
- [NBInclude.jl](https://github.com/stevengj/NBInclude.jl) : Import code from IJulia Jupyter notebooks into Julia programs.
- [Sublime-IJulia](https://github.com/quinnj/Sublime-IJulia) : is an IJulia Frontend to run julia from within Sublime Text-3 through the IJulia backend.

---

- 🏗️ [WeavePynb.jl](https://github.com/jverzani/WeavePynb.jl) : Simple package to convert markdown files to IJulia notebooks.
- 🏚️ [Autoreload.jl](https://github.com/malmaud/Autoreload.jl) : A package for autoreloading files for interactive work in IJulia.
- 🏚️ [Colaboratory](https://github.com/jupyter/colaboratory) : Create and store notebooks in Google Drive and allow for collaborative editing of notebooks.
- 🏚️ [ErrorLineNumber.jl](https://github.com/StephenVavasis/ErrorLineNumber.jl) : Address line number bug in Julia 0.4 error reporting.
- 🏚️ [Hydra.jl](https://github.com/Keno/Hydra.jl) : Hosted Multi-user IJulia distribution.
- 🏚️ [IJuliaWidgets.jl](https://github.com/shashi/IJuliaWidgets.jl) : Interactive widgets for IJulia.
- 🏚️ [jlbox](https://github.com/compressed/jlbox) : uses node.js to provide a mechanism for automatically reloading julia source and test files via gulp.js and a ZMQ socket.

### Web IDE

[📖 web IDE](https://en.wikipedia.org/wiki/Web_integrated_development_environment)

- [Google colab Julia notebook](https://colab.research.google.com/github/ageron/julia_notebooks/blob/master/Julia_for_Pythonistas.ipynb)
- [Julia Hub](https://juliahub.com/ui/index.html)
- [Julia on the SageMath cloud server](https://cloud.sagemath.com)
- [Repl.it](https://replit.com/)
- [Nextjournal](https://nextjournal.com/)
- [CodeBunk](http://codebunk.com) supports Julia for collaborative screen-sharing on the cloud.

**Packages**

- [CodeTools.jl](https://github.com/JunoLab/CodeTools.jl) : A collection of tools for handling Julia code (evaluation, autocompletion etc.), designed to be used as a backend library for IDE support.
- [DevTools.jl](https://github.com/JunoLab/DevTools.jl) : provides a couple of useful graphical tools for working with Julia, built on top of Blink.jl.
- [Hiccup.jl](https://github.com/JunoLab/Hiccup.jl) : A super-simple library designed to make making HTML easy in Julia. It's heavily inspired by Clojure's Hiccup DSL.
- [LanguageServer.jl](https://github.com/julia-vscode/LanguageServer.jl) : An implementation of the Microsoft Language Server Protocol for the julia language.
- [LNR.jl](https://github.com/JunoLab/LNR.jl) : Line numbering reader.

---

- 🏚️ [Media.jl](https://github.com/JunoLab/Media.jl) : A display system which enables the user handle multiple input/output devices and decide what media types get displayed where. (No `Project.toml`)
- 🏚️ [JuliaWebRepl.jl](https://github.com/vtjnash/JuliaWebRepl.jl)
- 🏚️ [OpenStack.jl](https://github.com/Keno/OpenStack.jl) : Access the OpenStack API using Julia.

## Shell scripting

[Shell scripting](https://en.wikipedia.org/wiki/Shell_script)

[Administrative scripting with Julia](https://github.com/ninjaaron/administrative-scripting-with-julia) : A guide for writing shell scripts in Julia.

- [Homebrew.jl](https://github.com/JuliaLang/Homebrew.jl/) : OSX Binary dependency provider for Julia.
- [LibALPM.jl](https://github.com/yuyichao/LibALPM.jl) : Wrapper for libalpm, the ArchLinux package manager.
- [WinRPM.jl](https://github.com/JuliaLang/WinRPM.jl) : RPM-md processing library to crosscompile code for Windows.
- 🏚️ [APT.jl](https://github.com/bbshortcut/APT.jl) : A module to manipulate Debian Advanced Package Tool (APT). It comes with `pnlt`, an executable that allows to manage package name lists.
- 🏚️ [DebbyPacker.jl](https://github.com/UCL/DebbyPacker.jl) : Set of scripts to easily create debian packages.
- 🏚️ [Nix.jl](https://github.com/JuliaPackaging/Nix.jl) : Nix package manager for Julia.

### Build automation

- 🏚️ [Jake.jl](https://github.com/nolta/Jake.jl) : Rake for Julia.
- 🏚️ [jlbuild](https://github.com/jlbuild) : A bot that controls the julia buildbots to build releases and perform some additional continous integration on secondary platforms. Ping (`@jlbuild`) in a comment, PR, issue, etc... and this GitHub comment-based interface to testing buildbots will build the relevant Julia version on all platforms, post download links and even execute small chunks of code across those platforms.
- 🏚️ [Juke.jl](https://github.com/kshramt/Juke.jl) : `make` in Julia.
- 🏚️ [julia-ansible-scripts](https://github.com/staticfloat/julia-ansible-scripts) : Various julia ansible scripts for provisioning servers, buildbots etc...

## GUI

- [Blink.jl](https://github.com/JuliaGizmos/Blink.jl) : Julia wrapper around [Electron](https://electronjs.org/).
- [Electron.jl](https://github.com/davidanthoff/Electron.jl) : Julia wrapper for [Electron](https://electronjs.org/) with a more minimalistic feature set than `Blink.jl`.
- [Tk.jl](https://github.com/JuliaGraphics/Tk.jl) : The Julia interface for the Tk windowing toolkit.

---

- 🏚️ [Canvas.jl](https://github.com/shashi/Canvas.jl) : Composable UIs in Julia.
- 🏚️ [JGUI.jl](https://github.com/jverzani/JGUI.jl) : Simplified interface for making GUI's in Julia.
- 🏚️ [Julietta.jl](https://github.com/tknopp/Julietta.jl) : A toolkit for viewing Julia packages, modules, etc....
- 🏚️ [Table.jl](https://github.com/cpritcha/Table.jl) : Display Tables in plain text, HTML, LaTex.
- 🏚️ [XClipboard.jl](https://github.com/kmsquire/XClipboard.jl) : Xlib clipboard bindings to drag and drop in X11(X-Window System for bitmap displays).

### Qt

- [QML.jl](https://github.com/barche/QML.jl) : Small example for starting an interface to Qt5 QML.
- 🏚️ [PySide.jl](https://github.com/jverzani/PySide.jl) : A julia interface for accessing Qt via PyCall and PySide.
- 🏚️ [Qt5.jl](https://github.com/tbreloff/Qt5.jl) : A wrapper around C+- library `Qt5`.

### GTK

- [Gtk.jl](https://github.com/JuliaLang/Gtk.jl) : Julia interface to the GTK windowing toolkit.
- [GtkApps.jl](https://github.com/tknopp/GtkApps.jl) : GTK Apps by @tknopp.
- 🏚️ [GI.jl](https://github.com/bfredl/GI.jl) : Julia bindings using libgobject-introspection.
- 🏚️ [GtkInteract.jl](https://github.com/jverzani/GtkInteract.jl) : Part of Interact.jl functionality with Gtk.

## Continuous integration (CI) providers

[PkgTemplates.jl][] or [PkgSkeleton.jl][] can create the following CI/CD config files.

### Travis

Unfortunately, [Travis does not love opensource anymore](https://www.theregister.com/2020/11/02/travis_ci_pricng/).

- 🏚️ [Travis-CI build server](https://travis-ci.org/JuliaLang/) for Julia.
- 🏚️ [TestDocs.jl](https://github.com/simonbyrne/TestDocs.jl) : A test package to try to automatically build docs on travis.
- 🏚️ [TravisTest.jl](https://github.com/JuliaCI/TravisTest.jl) : Repository for testing Julia support at the Travis Continuous Integration (CI) service.
- 🏚️ [julia-helper](https://github.com/jiahao/julia-helper) : Git hook scripts to help Julia developers with optional Travis CI support.

### Gitlab-CI

- [GitlabJuliaDemo.jl](https://gitlab.com/tkpapp/GitlabJuliaDemo.jl) : A minimal example for setting up CI with Julia on Gitlab. The [blog post](https://tpapp.github.io/post/julia-ci-gitlab/) describing how a Julia package repo in Gitlab can be setup with continuous integration and coverage summary. A sample CI file `.gitlab-ci.yml` is [here](https://gitlab.com/tkpapp/GitlabJuliaDemo.jl/-/blob/master/.gitlab-ci.yml).

### GitHub

[GitHub actions for Julia](https://github.com/julia-actions). A sample CI file can be accessed [here](https://github.com/tpapp/PkgSkeleton.jl/blob/master/.github/workflows/CI.yml).

- [setup-julia](https://github.com/julia-actions/setup-julia) : downloading a specified version of Julia and adding it to PATH.
- [julia-buildpkg](https://github.com/julia-actions/julia-buildpkg)
- [julia-runtest](https://github.com/julia-actions/julia-runtest)
- [julia-processcoverage](https://github.com/julia-actions/julia-processcoverage)
- [CompatHelper workflow](https://github.com/JuliaRegistries/CompatHelper.jl/blob/master/.github/workflows/CompatHelper.yml)

## Containers-Virtualization

[Virtualization](http://en.wikipedia.org/wiki/Category:Virtualization_software)

- [Julia docker image](https://hub.docker.com/_/julia) and the packaging [`DOCKERFILE`](https://github.com/docker-library/julia).
- [Kuber.jl](https://github.com/JuliaComputing/Kuber.jl) : A Julia Kubernetes Client.
- 🏚️ [julia-vagrant](https://github.com/staticfloat/julia-vagrant) : Packer/Vagrant script recipes for making virtual machines (VM's) - create Vagrant boxes and Openstack images for performing builds and tests of Julia.
- 🏚️ [RudeOil.jl](https://github.com/UCL/RudeOil.jl) : A package to easily interact with docker and docker-machine.

## Sandbox

- [Playground.jl](https://github.com/Rory-Finnegan/Playground.jl) : A Julia-lang environment builder (like python's virtualenv) package to create Julia sandboxes, similar to python virtual environments.
- 🏚️ [JDock](https://github.com/amitmurthy/JDock) : An IJulia sandbox using Docker containers.