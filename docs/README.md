# Gens Julia

![GitHub repo size](https://img.shields.io/github/repo-size/sosiristseng/GensJulia) ![GitHub commit activity](https://img.shields.io/github/commit-activity/m/sosiristseng/GensJulia)

## Disclaimer

This Julia resource list is largely based on [Julia.jl](https://github.com/svaksha/Julia.jl), which is under COPYRIGHT © 2012-Now SVAKSHA, dual-licensed for the data ([ODbL-v1.0+](https://opendatacommons.org/licenses/odbl/1-0/)) and the software ([AGPLv3+](http://www.gnu.org/licenses/agpl-3.0.en.html)), respectively.

## Install Julia

The canonical way is to download [official Julia binaries](http://julialang.org/downloads/). But you can try these installers.

<!-- tabs:start -->

#### **Linux and MacOS**

- [jill](https://github.com/abelsiqueira/jill) : Command line (bash) installer of the Julia Language for Linux and MacOS.
- [jill.py](https://github.com/johnnychen94/jill.py) : Python port of the `jill` installer. (Requires Python)
- [JuliaVM](https://github.com/pmargreff/juliavm) : Simple bash script to manage multiple Julia environments. Inspired by `nvm` and `npm`.

#### **Windows**

- [JuliaUp](https://github.com/JuliaLang/juliaup) : (An experimental) Julia installer and updater in Windows Store.
- [jill.py](https://github.com/johnnychen94/jill.py) : Python port of the `jill` installer. (Requires Python)
- [juliawin](https://github.com/heetbeet/juliawin) : A portable Julia for Windows, bundled with VSCode, Pluto, Conda & PyCall, and more.

<!-- tabs:end -->

## Find Julia packages

The Julia ecosystem includes a federation of packages. To find out what do the packages do at:

- [Julia.jl](https://github.com/svaksha/Julia.jl)
- [Julia Hub](https://juliahub.com/ui/index.html)
- [Julia packages](https://juliapackages.com/)
- [Package announcement](https://discourse.julialang.org/c/community/packages/47) in Julia discourse forums.
- Or my personal lists in this site (if you find them useful)

## Julia Communities

Get in touch with [the Julia community](http://julialang.org/community/) in various ways:

- [Julia discourse](https://discourse.julialang.org/) forums for all technical discussions. The *first choice* to find and ask questions there.
- [Julia on Slack](https://join.slack.com/t/julialang/shared_invite/zt-nmal0i0x-LcYEtdnTameGsXmBzMzgog)
- [Julia on Zulip](https://julialang.zulipchat.com/)
- [Julia GitHub Groups](https://julialang.org/community/organizations/) is a non-comprehensive list of Julia GitHub groups showing the extent of the Julia ecosystem.
- [Julia in Stackoverflow](http://stackoverflow.com/questions/tagged/julia-lang)

### Social media

- [Julia Reddit](http://www.reddit.com/r/Julia/)
- [Julialang news on Twitter](https://twitter.com/julialang_news)
- [Julia user groups](https://www.meetup.com/topics/julia/) in `meetup.com`.
- [Julia youtube channel](https://www.youtube.com/user/JuliaLanguage)

### Events

- [Julia events](https://julialang.org/community/#events)
- [JuliaCon](http://juliacon.org/) is an annual technical conference where community members from around the world come together to learn and share information about the latest trends and technologies in Julia development. The website is hoste at [juliacon.github.io](https://github.com/JuliaCon/juliacon.github.io). It is created using `Franklin.jl`, and is served by Github pages.

### Blogs about Julia

- [Official Julia language blog](http://julialang.org/blog/)
- [Julia Bloggers](https://www.juliabloggers.com) aggregates community blogs about Julia.
- Chris Rackauckas [blog posts](http://www.stochasticlifestyle.com/) mainly about modeling and simulation.
- [Blog by Bogumił Kamiński](https://bkamins.github.io/) focuses on `DataFrames.jl`.
- [OpenSourc.ES](https://opensourc.es)

#### Single blog posts or articles

- LWN article: An introduction to the Julia language - [Part 1](https://lwn.net/Articles/763626/).
- [Why 1-based indexing is OK](https://craftofcoding.wordpress.com/2017/03/12/why-1-based-indexing-is-ok/) by Michael Wirth.
- [Values vs. Bindings: The Map is Not the Territory](http://www.johnmyleswhite.com/notebook/2014/09/06/values-vs-bindings-the-map-is-not-the-territory/)
- [Cool things you can do in Julia](http://assoc.tumblr.com/post/71454527084/cool-things-you-can-do-in-julia)
- How to [call Python libraries](http://blog.leahhanson.us/julia-calling-python-calling-julia.html) in Julia.
- [Fun With Just-In-Time Compiling: Julia, Python, R and pqR](http://randyzwitch.com/python-pypy-julia-r-pqr-jit-just-in-time-compiler/) by Randy Zwitch.
- [Tabular Data I/O in Julia](http://www.r-bloggers.com/tabular-data-io-in-julia/) by Randy Zwitch.
- [What's bad about Julia](https://viralinstruction.com/posts/badjulia/) by Jakob.

## Research papers using Julia

[Julia Research](https://julialang.org/research/): a list of publications using Julia.

- [ReScience journal](https://github.com/ReScience/ReScience) for reproducible science.
- [Journal of Open source software](https://joss.theoj.org).

## Julia tutorials

- [Julia Official Documentation](https://docs.julialang.org/en/v1/index.html)

### Coming from other programming languages

- [Julia Cheatsheet](https://juliadocs.github.io/Julia-Cheat-Sheet/)
- [Learn Julia in Y minutes](https://learnxinyminutes.com/docs/julia/)
- [Julia-cheatsheet.pdf](http://math.mit.edu/~stevenj/Julia-cheatsheet.pdf) StevenJ's Julia cheatsheet.
- [Julia express](http://bogumilkaminski.pl/files/julia_express.pdf) by Bogumil Kaminski.

### General Julia tutorials

- [Learning Julia](https://julialang.org/learning/): official links to Julia tutorials.
- [Julia Academy](https://juliaacademy.com)
- [From zero to Julia](https://techytok.com/from-zero-to-julia/)
- [Think Julia](https://benlauwens.github.io/ThinkJulia.jl/latest/book.html)
- [QuantEcon](https://quantecon.org/quantecon-jl/) and the [code notebooks](https://github.com/QuantEcon/quantecon-notebooks-julia).
- [Julia concise tutorial](https://github.com/sylvaticus/juliatutorial)
- [Intro to Julia](https://ucidatascienceinitiative.github.io/IntroToJulia/) by Chris Rackauckas.
- [Introducing Julia wikibook](https://en.wikibooks.org/wiki/Introducing_Julia)
- [Julia Data Science](https://juliadatascience.io/), an open source and open access book on how to do Data Science using Julia.

### Coding practice

- [Exercism : Julia](https://exercism.io/tracks/julia)
- [Project Euler : Julia](https://github.com/heetbeet/project-euler-julia) : Project Euler puzzle notebooks for Julia.
- [Rosseta Code : Julia](http://rosettacode.org/wiki/Category:Julia)

### Learn Julia by examples

- [Fall in Love with Julia](https://github.com/schlichtanders/fall-in-love-with-julia): An introductory 101 series to get to know the power of Julialang.
- [Intermediate Julia workshop](https://github.com/dpsanders/intermediate_julia_2019), held at JuliaCon 2019, Baltimore, Maryland, USA
- [Introduction to Applied Linear Algebra in Julia](https://web.stanford.edu/~boyd/vmls/)
- [Julia by example](https://juliabyexample.helpmanual.io/)
- [Julia Project example](https://github.com/robbyriverside/ModulePlay) : ModulePlay is a simple example of using module tools.
- [julia-mit](https://github.com/stevengj/julia-mit) : Tutorials and information on the Julia language for MIT numerical-computation courses.

### Jupyter notebooks

- [A gallery of interesting Julia notebooks](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks#julia)
- [Introduction to Julia tutorials](https://github.com/xorJane/Introduction_to_Julia_tutorials) : Jupyter notebooks used for intro tutorials to teach Julia.
- [JuliaBoxTutorials](https://github.com/JuliaComputing/JuliaBoxTutorials) : Jupyter notebooks used to teach Julia in JuliaBox.

### Modeling and simulations

- [Differential Equations tutorials](https://tutorials.sciml.ai/)
- [Learn Julia via epidemic modelling](https://github.com/dpsanders/LearnJulia2020)
- [SIR pandemic modeling with Julia](https://github.com/epirecipes/sir-julia)

### Machine learning

- [Grokking Deep Learning with Julia](https://github.com/deepaksuresh/Grokking-Deep-Learning-with-Julia)
- [Machine Learning in Julia 2020](https://github.com/ablaom/MachineLearningInJulia2020)
- [Machine Learning Workshop 2019](https://github.com/mbauman/MachineLearningWorkshop2019)

### Visualization examples

- [Official docs](http://docs.juliaplots.org/latest/) of `Plots.jl`.
- [PlotsGallery.jl](https://github.com/goropikari/PlotsGallery.jl) : An unofficial `Plots.jl` Gallery inspired by MATLAB Plot Gallery.
- [Various PyPlot.jl examples](https://gist.github.com/gizmaa/7214002) : `PyPlot.jl` examples.
- [BeautifulMakie](https://lazarusa.github.io/BeautifulMakie/) : `Makie.jl` examples.
