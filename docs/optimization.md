---
title: "Optimization"
weight: 190
---

# (Mathematical) Optimization

> [Mathematical Optimization](https://en.wikipedia.org/wiki/Category:Mathematical_optimization) packages in Julia

**Organizations**

- [JuMP-dev](https://github.com/jump-dev)
- [Julia Opt](https://github.com/JuliaOpt)
- [Julia Smooth Optimizers](https://github.com/JuliaSmoothOptimizers)

## Frameworks

- [JuMP.jl](https://github.com/jump-dev/JuMP.jl) : A modeling language for Mathematical Optimization (linear, mixed-integer, conic, semidefinite, nonlinear).
- [GalacticOptim.jl](https://github.com/SciML/GalacticOptim.jl) : `GalacticOptim.jl` seeks to bring together all of the optimization packages it can find, local and global, into one unified Julia interface.

## Bindings for external solvers

> Some of them require paid license to work.

- [AmplNLReader.jl](https://github.com/JuliaSmoothOptimizers/AmplNLReader.jl) : A Julia Interface to AMPL.
- [AmplNLWriter.jl](https://github.com/jump-dev/AmplNLWriter.jl) : an interface between `MathOptInterface.jl` and [AMPL-enabled solvers](http://ampl.com/products/solvers/all-solvers-for-ampl/).
- [AmplNLWriter.jl](https://github.com/jump-dev/AmplNLWriter.jl) : Julia interface to AMPL-enabled solvers.
- [Cbc.jl](https://github.com/jump-dev/Cbc.jl) : Interface to the Coin-OR Cbc solver for mixed-integer programming.
- [CPLEX.jl](https://github.com/jump-dev/CPLEX.jl) : An interface for using IBM's [CPLEX Optimizer](https://www.ibm.com/products/ilog-cplex-optimization-studio)™ from the Julia language.
- [CSDP.jl](https://github.com/jump-dev/CSDP.jl) : Julia wrapper to [CSDP](https://projects.coin-or.org/Csdp/) semidefinite programming solver.
- [CUTEst.jl](https://github.com/JuliaSmoothOptimizers/CUTEst.jl) : Julia interface for [CUTEst](https://github.com/ralna/CUTEst/wiki), a repository of constrained and unconstrained nonlinear programming problems for testing and comparing optimization algorithms.
- [ECOS.jl](https://github.com/jump-dev/ECOS.jl) : Julia wrapper for the ECOS conic optimization solver.
- [GLPK.jl](https://github.com/jump-dev/GLPK.jl) : GLPK wrapper module for Julia.
- [GLPKMathProgInterface.jl](https://github.com/JuliaOpt/GLPKMathProgInterface.jl) : Interface between the GLPK.jl wrapper and MathProgBase.jl.
- [Gurobi.jl](https://github.com/jump-dev/Gurobi.jl) : a Julia interface for the commercial [Gurobi](http://www.gurobi.com/) Optimizer.
- [HSL.jl](https://github.com/JuliaSmoothOptimizers/HSL.jl) : Julia interface to the HSL Mathematical Software Library.
- [Ipopt.jl](https://github.com/jump-dev/Ipopt.jl) : Julia interface to the [Ipopt](https://coin-or.github.io/Ipopt/) nonlinear solver.
- [KNITRO.jl](https://github.com/jump-dev/KNITRO.jl) : Julia interface for [KNITRO solver](https://www.artelys.com/knitro).
- [Mosek.jl](https://github.com/MOSEK/Mosek.jl) : Interface to the Mosek solver in Julia.
- [NLopt.jl](https://github.com/JuliaOpt/NLopt.jl) : Package to call the [NLopt](http://ab-initio.mit.edu/nlopt) nonlinear-optimization library from the Julia language.
- [Xpress.jl](https://github.com/jump-dev/Xpress.jl) : A Julia interface for the [FICO Xpress solver](https://github.com/jump-dev/Xpress.jl/blob/master/www.fico.com/products/fico-xpress-solver).

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [SCIP.jl](https://github.com/mlubin/SCIP.jl) by @mlubin : An optimization software for mixed-integer programs.
- 🏚️ [SCIP.jl](https://github.com/ryanjoneil/SCIP.jl) by @ryanjoneil : A Julia interface to the SCIP solver.
- 🏚️ [SCS.jl](https://github.com/JuliaOpt/SCS.jl) : Julia Wrapper for [SCS](https://github.com/cvxgrp/scs).

</details>

## Linear Programming-Optimization

[Wikipedia: Linear Programming-Optimization](https://en.wikipedia.org/wiki/Linear_programming)

- [Clp.jl](https://github.com/jump-dev/Clp.jl) : Interface to the Coin-OR Linear Programming solver (CLP)
- [NLPModels.jl](https://github.com/JuliaSmoothOptimizers/NLPModels.jl) : Data Structures for Optimization Models.
- [PiecewiseLinearOpt.jl](https://github.com/joehuchette/PiecewiseLinearOpt.jl) : Optimizing over piecewise linear functions.
- [Tulip.jl](https://github.com/ds4dm/Tulip.jl) : is an open-source interior-point solver for linear optimization, written in pure Julia. It implements the homogeneous primal-dual interior-point algorithm with multiple centrality corrections, and therefore handles unbounded and infeasible problems.

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [jlSimplex](https://github.com/mlubin/jlSimplex) : Proof-of-concept implementation of the (dual) simplex algorithm for linear programming in Julia.
- 🏚️ [NLTester](https://github.com/IainNZ/NLTester) : Code for benchmarks comparing AMPL, Julia, and YALMIP (MATLAB) for nonlinear modeling.

</details>

## Nonlinear Programming

[Wikipedia: Nonlinear Programming](https://en.wikipedia.org/wiki/Nonlinear_programming)

- [BARON.jl](https://github.com/joehuchette/BARON.jl) : A wrapper for the BARON mixed-integer nonlinear programming solver.
- [ConicNonlinearBridge.jl](https://github.com/mlubin/ConicNonlinearBridge.jl) : Wrapper to solve [conic](http://mathprogbasejl.readthedocs.org/en/latest/conic.html) optimization problems with derivative-based nonlinear solvers.
- [Convex.jl](https://github.com/jump-dev/Convex.jl) : A Julia library for mathematical programming that makes it easy to formulate and fast to solve nonlinear convex optimization problems.
- [EAGO.jl](https://github.com/PSORLab/EAGO.jl) : A development environment for robust and global optimization. EAGO stands for Easy-Advanced Global Optimization.

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [DReal.jl](https://github.com/zenna/DReal.jl) : A Julia wrapper for Nonlinear SMT solving using  the dReal SMT solver.
- 🏚️ [OptimizationServices.jl](https://github.com/tkelman/OptimizationServices.jl) : Julia interface to [COIN-OR Optimization Services](https://projects.coin-or.org/OS).
- 🏚️ [Quadprog.jl](https://github.com/harmeling/Quadprog.jl) : A wrapper around Ipopt.jl to solve quadratic programming problems.

</details>

## Misc

- [AutomotiveDrivingModels.jl](https://github.com/tawheeler/AutomotiveDrivingModels.jl) : For car encounter models.
- [BlackBoxOptim.jl](https://github.com/robertfeldt/BlackBoxOptim.jl) : An experimental, work-in-progress global optimization framework for Julia, supporting both multi- and single-objective optimization problems, focused on (meta-)heuristic/stochastic algorithms (DE, PSO, CMA-ES etc).
- [CharibdeOptim.jl](https://github.com/JuliaIntervals/CharibdeOptim.jl) : A Julia implementation of the cooperative solver Charibde in which it uses two parallel running algorithms *Differential Evolution* and *Interval Branch & Contract algorithm* to achieve solution of any difficult problem.
- [ConstraintProgramming.jl](https://github.com/JuliaIntervals/IntervalConstraintProgramming.jl) :  Calculates the feasible region for a set of real-valued inequalities with Julia.
- [CutPools.jl](https://github.com/joehuchette/CutPools.jl) : Pools of cutting planes for JuMP models.
- [Hyperopt.jl](https://github.com/baggepinnen/Hyperopt.jl) : A package to perform hyperparameter optimization. Currently supports random search, latin hypercube sampling and Bayesian optimization.
- [InfiniteOpt.jl](https://github.com/pulsipher/InfiniteOpt.jl) : An interface for infinite-dimensional optimization problems. e.g. stochastic programming, dynamic programming, space-time optimization. See also the [YouTube video](https://www.youtube.com/watch?v=q5ETFLZbxiU).
- [LinearOperators.jl](https://github.com/JuliaSmoothOptimizers/LinearOperators.jl) : Linear Operators for Julia. Operators behave like matrices but are defined by their effect when applied to a vector.
- [LsqFit.jl](https://github.com/JuliaNLSolvers/LsqFit.jl) : Simple curve fitting functionality from [Optim.jl][] has been moved into its own package.
- [MathProgBase.jl](https://github.com/JuliaOpt/MathProgBase.jl) : Solver-independent functions (incl. linprog and mixintprog) and low-level interface for Mathematical Programming.
- [Mayday.jl](https://github.com/rdeits/Mayday.jl) : Sums-of-Squares optimization through semidefinite programming (SDP) in Julia, powered by JuMP.
- [Optim.jl][] : A basic optimization algorithms implementation.
- [OSQP.jl](https://github.com/oxfordcontrol/OSQP.jl) : A Julia wrapper for the Operator Splitting Quadratic Program (OSQP) solver is a numerical optimization package.
- [PolyJuMP.jl](https://github.com/JuliaOpt/PolyJuMP.jl) : A JuMP extension for Polynomial Optimization.
- [QuadDIRECT.jl](https://github.com/timholy/QuadDIRECT.jl) : Global optimization without derivatives.
- [SemidefiniteModels](https://github.com/JuliaOpt/SemidefiniteModels.jl) : A MathProgBase extension for Semidefinite Modelling.
- [SMM.jl](https://github.com/floswald/SMM.jl) : Simulated Method of Moments for Julia.
- [StructDualDynProg.jl](https://github.com/JuliaStochOpt/StructDualDynProg.jl) : Implementation of SDDP (Stochastic Dual Dynamic Programming) using the StructJuMP modeling interface.
- [StructJuMP.jl](https://github.com/joehuchette/StructJuMP.jl) : A block-structured optimization framework for JuMP.
- [SumOfSquares.jl](https://github.com/jump-dev/SumOfSquares.jl) : Sum of Squares Programming for Julia.
- [Surrogates.jl](https://github.com/SciML/Surrogates.jl) : Surrogate modeling and optimization.
- [TrafficAssignment.jl](https://github.com/chkwon/TrafficAssignment.jl) : A package for traffic assignment that loads the network data and finds the user equilibrium traffic pattern.

---

[Optim.jl]: https://github.com/JuliaNLSolvers/Optim.jl

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [BLOM.jl](https://github.com/tkelman/BLOM.jl) : A Julia port of the Berkeley Library for Optimization Modeling (Work-In-Progress).
- 🏚️ [Caching.jl](https://github.com/zgornel/Caching.jl) : Memoization mechanism.
- 🏚️ [CGP.jl](https://github.com/glesica/CGP.jl) : Cartesian Genetic Programming (CGP) implemented in Julia.
- 🏚️ [CGRASP.jl](https://github.com/tautologico/CGRASP.jl) : Continuous Greedy Randomized Adaptive Search Procedure (CGRASP), in Julia.
- 🏚️ [DDUS.jl](https://github.com/vgupta1/DDUS.jl) : Data-driven Uncertainty Sets for the JuMPeR framework.
- 🏚️ [EAGODomainReduction.jl](https://github.com/MatthewStuber/EAGODomainReduction.jl) : Domain Reduction Procedures in Global Optimization.
- 🏚️ [GeneticAlgorithms.jl](https://github.com/forio/GeneticAlgorithms.jl) : is a lightweight framework that simplifies the process of creating genetic algorithms and running them in parallel.
- 🏚️ [InformedDifferentialEvolution.jl](https://github.com/rened/InformedDifferentialEvolution.jl) : Implementation of Differential Evolution with optional custom predictors. (No `Project.toml`)
- 🏚️ [jobshop](https://github.com/stefan-k/jobshop) : The Jobshop (Open Shop Scheduling Problem (OSSP)) problem is solved with evolutionary strategies in Julia.
- 🏚️ [JuGP.jl](https://github.com/mlubin/JuGP.jl) : A prototype JuMP extension for geometric programming. (No `Project.toml`)
- 🏚️ [julia-nlopt](https://github.com/MetalNinjas/julia-nlopt) : NLopt bindings for julia.
- 🏚️ [JuliaCMAES](https://github.com/Staross/JuliaCMAES) : CMA-ES port - a mix of the original minimal MATLAB implementation (purecmaes.m) and the full one (cmaes.m).
- 🏚️ [JuMPeR.jl](https://github.com/IainNZ/JuMPeR.jl) : Julia for Mathematical Programming (JuMP) extension for Robust optimization. (No `Project.toml`)
- 🏚️ [LinearResponseVariationalBayes.jl](https://github.com/rgiordan/LinearResponseVariationalBayes.jl) : Julia tools for building simple variational Bayes models with JuMP.
- 🏚️ [LossFuns.jl](https://github.com/lindahua/LossFuns.jl) : An implementation of loss functions for empirical risk minimization.
- 🏚️ [LSQ.jl](https://github.com/davidlizeng/LSQ.jl) : is a library that makes it easy to formulate and solve least-squares optimization problems with linear equality constraints.
- 🏚️ [MinFinder.jl](https://github.com/Ken-B/MinFinder.jl) : The MinFinder algorithm to find all the minima for a differentiable function inside a bounded domain.
- 🏚️ [Munkres.jl](https://github.com/FugroRoames/Munkres.jl) : Munkres algorithm for the optimal assignment problem. (No `Project.toml`)
- 🏚️ [NEOS.jl](https://github.com/odow/NEOS.jl) : A Julia interface for the NEOS Optimisation Server.
- 🏚️ [NewOptimizer.jl](https://github.com/Keno/NewOptimizer.jl) : WIP for new optimizer for julia base.
- 🏚️ [NODAL.jl](https://github.com/phrb/NODAL.jl) : is an Open Distributed Autotuning Library in Julia. (No `Project.toml`)
- 🏚️ [ParallelGenocop.jl](https://github.com/display-none/ParallelGenocop.jl) : Parallel implementation of Genocop - a genetic algorithm for numerical optimization problems with linear constraints.
- 🏚️ [pikaia.jl](https://github.com/tmeits/pikaia.jl) : Genetic Algorithms (GA's).
- 🏚️ [Polyopt.jl](https://github.com/ahmadreza-marandi/Polyopt.jl) : Julia package for polynomial optimization using semidefinite programming, with some [presentation notebooks](https://github.com/MOSEK/Polyopt.jl/tree/master/notebooks) of an optimization package.
- 🏚️ [Proximal.jl](https://github.com/johnmyleswhite/Proximal.jl) : Translation of Parikh and Boyd code for proximal algorithms.
- 🏚️ [QuickCheck.jl](https://github.com/pao/QuickCheck.jl) : is listed in METADATA and based on QuickCheck specification-based randomized tester for Julia.
- 🏚️ [Ranking.jl](https://github.com/johnmyleswhite/Ranking.jl) : Tools for ranking in Julia. (No `Project.toml`)
- 🏚️ [RationalSimplex.jl](https://github.com/IainNZ/RationalSimplex.jl) : Pure Julia implementation of the simplex algorithm. (No `Project.toml`)
- 🏚️ [scheduleCrew.jl](https://github.com/hugdiniz/scheduleCrew.jl) : The project was developed for Topicos Especiais em Otimização.
- 🏚️ [SemidefiniteProgramming.jl](https://github.com/daviddelaat/SemidefiniteProgramming.jl) : This package provides a Julia interface for low-level modeling of semidefinite programming problems and for solving semidefinite programs with solvers such as SDPA and CSDP.
- 🏚️ [simplex.jl](https://github.com/davidagold/simplex.jl) : Practice project program that performs the simplex algorithm.
- 🏚️ [VinDsl.jl](https://github.com/jmxpearson/VinDsl.jl) : A fast and furious domain-specific language for variational inference in Julia.

</details>
