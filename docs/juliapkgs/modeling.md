# Modeling and simulation

> General packages for modeling and simulating kinetics

**Organizations**

- [ModiaSim](https://github.com/ModiaSim)
- [SciML](https://github.com/SciML)
- [Julia Dynamics](https://juliadynamics.github.io/JuliaDynamics/)

## Model File I/O


- [SBML.jl](https://github.com/LCSB-BioCore/SBML.jl) : Julia interface to the Systems Biology Markup Language (SBML) library.
- [SBMLToolkit.jl](https://github.com/SciML/SBMLToolkit.jl) : importing models specified in the Systems Biology Markup Language (SBML) into the Julia SciML ecosystem.
- [CellMLToolkit.jl](https://github.com/SciML/CellMLToolkit.jl) : a Julia library that connects `CellML` models to the Scientific Julia ecosystem.
- [ReactionNetworkImporters.jl](https://github.com/SciML/ReactionNetworkImporters.jl) : Loading BioNetGen `.net` file.


## Differential equations

[📖 Differential equations](https://en.wikipedia.org/wiki/Differential_equation)

- [Catalyst.jl](https://github.com/SciML/Catalyst.jl) : Domain-specific language (DSL) for chemical reaction networks.
- [DataDrivenDiffEq.jl](https://github.com/SciML/DataDrivenDiffEq.jl) : Data driven modeling and automated discovery of dynamical systems.
- [DiffEqSensitivity.jl](https://github.com/SciML/DiffEqSensitivity.jl) : A component of the DiffEq ecosystem for sensitivity analysis.
- [DifferentialEquations.jl][] : High-performance solvers of differential equations.
- [DiffModels.jl](https://github.com/jdrugo/DiffModels.jl) : Diffusion Model simulation and first-passage time densities in Julia.
- [DynamicalSystems.jl](https://github.com/JuliaDynamics/DynamicalSystems.jl) : Julia software library for the exploration of chaos and nonlinear dynamics.
- [ModelingToolkit.jl](https://github.com/SciML/ModelingToolkit.jl) : A modeling framework for automatically parallelized scientific machine learning (SciML) in Julia.
- [Modia.jl](https://github.com/ModiaSim/Modia.jl) : Modia is a Julia package for modeling and simulation of multidomain engineering systems described by differential equations, algebraic equations, and (space-discretized) partial differential equations.  
- [NeuralPDE.jl](https://github.com/SciML/NeuralPDE.jl) : Physics-Informed Neural Networks (PINN) and Deep BSDE Solvers of Differential Equations.
- [Pathogen.jl](https://github.com/jangevaa/Pathogen.jl) : Utilities to simulate and perform inference of disease dynamics.
- [RiemannHilbert.jl](https://github.com/JuliaHolomorphic/RiemannHilbert.jl) : A Julia package for solving Riemann–Hilbert problems.
- [SimJulia.jl](https://github.com/BenLauwens/SimJulia.jl) : A discrete event process oriented simulation framework written in Julia.
- [Sims.jl](https://github.com/tshort/Sims.jl) : Equation-based modeling and simulations in Julia.
- [SingularIntegralEquations.jl](https://github.com/JuliaApproximation/SingularIntegralEquations.jl) : An experimental Julia package for solving singular integral equations.
- [Sundials.jl](https://github.com/SciML/Sundials.jl) : A Julia package that interfaces to the Sundials library and includes a nonlinear solver (KINSOL), ODE's (CVODE), and DAE's (IDA).
- [WiltonInts84.jl](https://github.com/krcools/WiltonInts84.jl) : Integrals of arbitrary powers of R over flat triangles.

---

- 🏚️ [ChemicalKinetics.jl](https://github.com/papamarkou/ChemicalKinetics.jl) :  DiffEq related functionality for defining biological models.
- 🏚️ [DynamicalSystems.jl](https://github.com/timothyrenner/DynamicalSystems.jl) : A collection of Julia functions that produce the systems of ODEs for various dynamical systems.
- 🏚️ [MovcolN.jl](https://github.com/pwl/MovcolN.jl) : Moving collocation method to solve one dimensional partial differential equations.


## Stochastic algorithms

[📖 Stochastic simulation](https://en.wikipedia.org/wiki/Stochastic_simulation) algorithms (SSA) are also included in the `DifferentialEquations` ecosystem.

- [BioSimulator.jl](https://github.com/alanderos91/BioSimulator.jl) : A stochastic simulation framework in Julia.
- [Gillespie.jl](https://github.com/sdwfrost/Gillespie.jl) : Stochastic Gillespie-type simulations using Julia.

## Finite difference method

[📖 Finite difference method](https://en.wikipedia.org/wiki/Finite_difference_method)

- [DiffEqOperators.jl](https://github.com/SciML/DiffEqOperators.jl) : Linear operators for discretizations of differential equations.

## Finite element method

**See also**

- [📖 Finite element method](https://en.wikipedia.org/wiki/Finite_element_method)
- [Graphic | Geometry](/graphics?id=geometry) section.

**Packages**

- [FEMBasis.jl](https://github.com/JuliaFEM/FEMBasis.jl) : Package contains interpolation routines for standard finite element function spaces.
- [FinEtools.jl](https://github.com/PetrKryslUCSD/FinEtools.jl) : `FinEtools` is a package for basic operations on finite element meshes: Construction, modification, selection, and evaluation of quantities defined on a mesh.
- [JuliaFEM.jl](https://github.com/JuliaFEM/JuliaFEM.jl) : Finite Element method solver.
- [Krylov.jl](https://github.com/JuliaSmoothOptimizers/Krylov.jl) : A Julia Basket of Hand-Picked Krylov Methods.
- [LinearAlgebraicRepresentation.jl](https://github.com/cvdlab/LinearAlgebraicRepresentation.jl) : Official Julia implementation of [LAR](http://dx.doi.org/10.1016/j.cad.2013.08.044), the Linear Algebraic Representation for Solid Modeling. LAR is a general representation scheme for geometric and topological modeling.
- [PETSc.jl](https://github.com/JuliaParallel/PETSc.jl) : This package provides a high level interface for [PETSc](https://www.mcs.anl.gov/petsc/), enabling the use of PETSc as an AbstractArray.
- [PtFEM.jl](https://github.com/PtFEM/PtFEM.jl) : Investigate Julia version of __Programming the FEM__ by I M Smith, D V Griffiths.

---

- 🏚️ [HPFEM.jl](https://github.com/pjabardo/HPFEM.jl) : HP Finite elements in Julia.
- 🏚️ [Makhno.jl](https://github.com/pjabardo/Makhno.jl) : Spectral element code implemented in Julia.
- 🏚️ [FEM.jl](https://github.com/pjabardo/FEM.jl) : Simple finite elements in Julia.
- 🏚️ [SurfaceMesh.jl](https://github.com/michelk/SurfaceMesh.jl) : A Finite element surface mesh manipulation library to work with polygon-surface-meshes.
- 🏚️ [TrussPlotter.jl](https://github.com/sjkelly/TrussPlotter.jl) : This is a package to plot trusses for finite element results.

## Symbolic Computation

[📖 Symbolic Computation](https://en.wikipedia.org/wiki/Symbolic_computation)

- [Reduce.jl](https://github.com/chakravala/Reduce.jl) : Symbolic parser generator for Julia language expressions using REDUCE algebra term rewriter.
- [Symata.jl](https://github.com/jlapeyre/Symata.jl) : language for symbolic mathematics.
- [SymbolicRegression.jl](https://github.com/MilesCranmer/SymbolicRegression.jl) : Distributed High-Performance symbolic regression in Julia.
- [Symbolics.jl](https://github.com/JuliaSymbolics/Symbolics.jl) : A fast and modern CAS for a fast and modern language.
- [SymEngine.jl](https://github.com/symengine/SymEngine.jl) : Julia wrappers of SymEngine.
- [SymPy.jl](https://github.com/JuliaPy/SymPy.jl) : Julia interface to SymPy via PyCall.

## Agent-based models

[📖 Agent-based model](https://en.wikipedia.org/wiki/Agent-based_model)

- [Agents.jl](https://github.com/JuliaDynamics/Agents.jl) : Agent-based modeling framework in Julia.
- [DynamicalBilliards.jl](https://github.com/JuliaDynamics/DynamicalBilliards.jl) : An easy-to-use, modular and extendable Julia package for Dynamical Billiard systems in two dimensions.
- 🏚️ [NetLogo.jl](https://github.com/nicolaspayette/NetLogo.jl) : controlling [NetLogo](http://ccl.northwestern.edu/netlogo/) from Julia.


## Network modeling

- [Petri.jl](https://github.com/mehalter/Petri.jl) : Petri net modeling framework.
- [NetworkDynamics.jl](https://github.com/PIK-ICoNe/NetworkDynamics.jl) : A package for working with dynamical systems on complex networks. NetworkDynamics.jl provides an interface between [LightGraphs.jl][] and [DifferentialEquations.jl][].


## Integrated Assessment Modeling Framework

- [Mimi.jl](https://github.com/mimiframework/Mimi.jl) : [Integrated Assessment Modeling Framework](https://en.wikipedia.org/wiki/Integrated_assessment_modelling).
- [OptiMimi.jl](https://github.com/jrising/OptiMimi.jl) : Optimization for the `Mimi.jl` modeling framework.


## Utilities

- [DrWatson.jl](https://github.com/JuliaDynamics/DrWatson.jl) : a Julia package created to help people "deal" with their simulations, simulation parameters.
- [SimulationLogger.jl](https://github.com/JinraeKim/SimulationLogger.jl) : providing convenient logging tools for [DifferentialEquations.jl][].


[LightGraphs.jl]: https://github.com/JuliaGraphs/LightGraphs.jl
[DifferentialEquations.jl]: https://github.com/SciML/DifferentialEquations.jl