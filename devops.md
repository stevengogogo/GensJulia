# DevOps for Julia

> Build automation software, Infrastructure management, Packaging, Release engineering/ management tools, Software configuration management (SCM) software, _Software Quality_: Quality-Analysis (QA), continuous integration (CI), continuous delivery (CD), Test-Driven-Development (TDD), Behaviour-Driven-Development (BDD), Documentation Driven Development (DDD), Unit testing, et al.

- [awesome devops](https://github.com/wmariuss/awesome-devops)
- [Devops Weekly](http://www.devopsweekly.com/) by email subscription.
- [Test driven development (TDD)](https://blog.staffjoy.com/test-driven-development-in-juliajk-8b66d3664852) in Julia.
- [julia-buildbot](https://github.com/staticfloat/julia-buildbot) : Buildbot configuration for [build.julialang.org](https://build.julialang.org/).
- [Julia Server Status](http://status.julialang.org/) : Status page for services hosted by JuliaLang.
- [Julia Packaging](https://github.com/JuliaPackaging) organization.

## Installing Julia

Alternative to downloading an extracting [official Julia binaries](http://julialang.org/downloads/):

- [jill](https://github.com/abelsiqueira/jill) :  Command line installer of the Julia Language for Linux and MacOS.
- [jill.py](https://github.com/johnnychen94/jill.py) : Python port of the `jill` installer.
- [JuliaUp](https://github.com/JuliaLang/juliaup) : Julia installer and updater in Windows Store.
- [JuliaVM](https://github.com/pmargreff/juliavm) : Simple bash script to manage multiple Julia environments. Inspired by `nvm` and `npm`.
- [Repology](https://repology.org/metapackage/julia/versions) : versions of julia across more than 120 (Linux) package repositories.

## Developing Julia packages

> Package/Infrastructure management tools and Documentation
> - [cache.julialang.org](https://github.com/staticfloat/cache.julialang.org) : Super-simple bottle-caching infrastructure for the site.
> - [JuliaHub](https://juliahub.com/ui/Home)
> - [Julia Package list](https://juliapackages.com/)
> - [General registry](https://github.com/JuliaRegistries/General) : The official registry of general Julia packages.


- [Compat.jl](https://github.com/JuliaLang/Compat.jl) : A package for cross-version compatibility between old Julia and the new - takes care of syntax breakage and provides compatibility constructs that will work in both versions without warnings.
- [Kip.jl](https://github.com/jkroso/Kip.jl) : An Python-like, alternative module system for Julia.
- [Pkg.jl](https://github.com/JuliaLang/Pkg.jl) : Version 3 of package manager for Julia. [Documentation](https://pkgdocs.julialang.org/v1/).
- [PkgSkeleton.jl](https://github.com/tpapp/PkgSkeleton.jl) : Generate Julia package skeletons using a simple template system.
- [PkgTemplates.jl](https://github.com/invenia/PkgTemplates.jl) : Create new Julia packages, the easy way. Include templaye files for GitHub / GitLab CI.
- [PkgUtils.jl](https://github.com/arnavs/PkgUtils.jl) by @arnavs : Some small utilities to help with Julia packages
- [Registrator.jl](https://github.com/JuliaComputing/Registrator.jl) : Julia [package](https://pkg.julialang.org/) registration bot.
- [Requires.jl](https://github.com/MikeInnes/Requires.jl) : Lazy code loading for Julia.
- [VersionParsing.jl](https://github.com/stevengj/VersionParsing.jl) : flexible VersionNumber parsing in Julia.


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

See [Julia Packaging](https://github.com/JuliaPackaging) team. The binary repository is called [Yggdrasil](https://github.com/JuliaPackaging/Yggdrasil).

- [BinaryBuilder.jl](https://github.com/JuliaPackaging/BinaryBuilder.jl) : Binary Dependency Builder for Julia.
- [BinaryProvider.jl](https://github.com/JuliaPackaging/BinaryProvider.jl) : A reliable binary provider for Julia.
- [BinDeps.jl](https://github.com/JuliaLang/BinDeps.jl) : Tool for building binary dependencies for Julia modules.
- [Conda.jl](https://github.com/Luthaf/Conda.jl) : Conda managing Julia binary dependencies. e.g. for `IJulia.jl` and `PyPlot.jl`.

### Build Julia Executables

- [PackageCompiler.jl](https://github.com/JuliaLang/PackageCompiler.jl) : Compile your Julia enviironment into a system image or a standalone binary.
- [SnappyBuilder](https://github.com/davidanthoff/SnappyBuilder) : BinaryBuilder for `libsnappy` to build [julia snap](https://snapcraft.io/julia).
- 🏚️ [BuildExecutable.jl](https://github.com/dhoegh/BuildExecutable.jl) : Build standalone executables from a Julia script.

### Julia developement helpers

Bridging pre-1.0 Julia code to 1.0+.

- 🏚️ [FemtoCleaner.jl](https://github.com/JuliaComputing/FemtoCleaner.jl) : The [FemtoCleaner](https://github.com/apps/femtocleaner) app cleans your julia projects by upgrading deprecated syntax, removing version compatibility workarounds and anything else that has a unique upgrade path. This app exist to smooth the transition from Julia version 0.6 to 0.7(1.0+).
- 🏚️ [HackThatBase.jl](https://github.com/ihnorton/HackThatBase.jl) : A helper tool to reload and test modifications to base without recompiling the full system image.
- 🏚️ [PkgSearch.jl](https://github.com/essenciary/PkgSearch.jl) : A Julia REPL utility for package discovery.
- 🏚️ [PkgVerifierPrototype](https://github.com/LachlanGunn/PkgVerifierPrototype) : Julia package verifier prototype.

## Test-driven develpment

See also

- [Unittest in Julia](https://docs.julialang.org/en/v1/stdlib/Test/)
- [Black Box Testing](http://en.wikipedia.org/wiki/Black-box_testing)

Packages

- [Coverage.jl](https://github.com/JuliaCI/Coverage.jl) : Tracking code testing coverage and memory usage and optionally upload them to online services like Coveralls or Codecov. Its base library is [CoverageBase.jl](https://github.com/JuliaCI/CoverageBase.jl).
- [Jive.jl](https://github.com/wookay/Jive.jl) : run your test in parallel. Also supports watch folder function.
- [Mocking.jl](https://github.com/invenia/Mocking.jl) : Allows temporary overwriting of Julia methods for testing purposes.
- [Watcher.jl](https://github.com/rened/Watcher.jl): Auto-run unit tests every time a file gets saved


- 🏚️ [BaseTestDeprecated.jl](https://github.com/IainNZ/BaseTestDeprecated.jl) : Provides the `Base.Test` functionality removed in `Julia v0.5`.
- 🏚️ [Debug.jl](https://github.com/toivoh/Debug.jl) : Prototype interactive debugger for Julia.
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

Please use Julia's [logging](https://docs.julialang.org/en/v1/stdlib/Logging/) facilities.

- 🏚️ [Log4jl.jl](https://github.com/wildart/Log4jl.jl) : A comprehensive and flexible logging framework for Julia programs.
- 🏚️ [Logging.jl](https://github.com/kmsquire/Logging.jl) : The Logging module.
- 🏚️ [LogMover.jl](https://github.com/nkottary/LogMover.jl)
- 🏚️ [Lumberjack.jl](https://github.com/forio/Lumberjack.jl) : A logging library by Westley Hennigh.
- 🏚️ [Stage.jl](https://github.com/saltpork/Stage.jl) : has stage macros, checkpoints and loggers for Julia.

### Regression Testing

- [PkgBenchmark.jl](https://github.com/JuliaCI/PkgBenchmark.jl) : Easy benchmark tracking for packages
- [PkgEval.jl](https://github.com/JuliaCI/PkgEval.jl) : Evaluate Julia packages for a range of Julia versions.
- [VisualRegressionTests.jl](https://github.com/JuliaPlots/VisualRegressionTests.jl) : Automated integrated regression tests for graphics libraries.

## Continuous integration (CI) providers

### Travis

Sadly, [Travis does not love opensource anymore](https://www.theregister.com/2020/11/02/travis_ci_pricng/).

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


- 🏚️ [JDock](https://github.com/amitmurthy/JDock) : An IJulia sandboxed by Docker containers.

## Julia for shell scripting

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
