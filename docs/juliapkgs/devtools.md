# Development tools for Julia

> Developement tools, compilers, debuggers

- [Debugger](https://discourse.julialang.org/tags/debug) topic threads on discourse.
- [Julia debugger](https://github.com/JuliaDebug) organization
- [Julia official documentation](https://docs.julialang.org)
- [Julia editor suport](https://github.com/JuliaEditorSupport)

## Debugger

- [Debugger.jl](https://github.com/JuliaDebug/Debugger.jl) : Julia debugger using the `@enter` macro.
- [Ghost.jl](https://github.com/dfdx/Ghost.jl) : a code tracer for the Julia programming language. It lets you trace the function execution, recording all primitive operations onto a linearized tape.
- [Infiltrator.jl](https://github.com/JuliaDebug/Infiltrator.jl) : `@infiltrate` macro sets a "breakpoint" in a local context. All code is completely compiled.
- [Rebugger.jl](https://github.com/timholy/Rebugger.jl) : An expression-level debugger for Julia, sans the ability to interact with or manipulate call stacks (see Gallium), but it can trace execution via the manipulation of Julia expressions.
- [Suppressor.jl](https://github.com/Ismael-VC/Suppressor.jl) :  Julia macros for suppressing output (STDOUT), warnings (STDERR) or both streams at the same time.
- [ToggleableAsserts.jl](https://github.com/MasonProtter/ToggleableAsserts.jl) : Assertions that can be turned on or off with a switch, without runtime penalty when they're off.
- [Traceur.jl](https://github.com/MikeInnes/Traceur.jl) : codified version of the [Julia performance tips](https://docs.julialang.org/en/v1/manual/performance-tips/).

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

- [jEdit-julia](https://github.com/tuckerkevin/jedit-julia) : A jEdit mode for Julia.
- [Julia VSCode](https://www.julia-vscode.org/) : A powerful, free IDE for the Julia language.
- [Julia.tmbundle](https://github.com/JuliaLang/Julia.tmbundle) : Julia language support for TextMate 2 (and Sublime Text).
- [Liclipse](https://www.liclipse.com/) : LiClipse, Eclipse plus some customizations, supports Julia.
- [OhMyREPL.jl](https://github.com/KristofferC/OhMyREPL.jl) : Syntax highlighting and other enhancements for the Julia REPL.
- [Reminisce](https://github.com/JuliaIDE/Reminisce) : Sublime-style saving of tabs and content for Light Table.

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

**See also**

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
