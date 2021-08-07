---
title: "Physics"
weight: 210
---

# Physics in Julia

> Physics simulations, Quantum physics

**Organizations**

- [Julia Dynamics](https://github.com/JuliaDynamics)
- [Julia Energy](https://github.com/JuliaEnergy)
- [Julia Physics](https://github.com/JuliaPhysics)
- [QuantumBFS](https://github.com/QuantumBFS)

## Plasma Physics

[Wikipedia: Plasma](https://en.wikipedia.org/wiki/Plasma_(physics))

- [OrbitTomography.jl](https://github.com/lstagner/OrbitTomography.jl) : A Method for Determining the Population of Individual Fast-ion Orbits from Experimental Measurements.
- [VlaPy](https://github.com/joglekara/VlaPy) : **(Python package)** 1D-1V Vlasov-Poisson(-Fokker-Planck) Plasma Physics Simulation Tool.

## Electricity

- [ACME.jl](https://github.com/HSU-ANT/ACME.jl) : Analog Circuit Modeling and Emulation for Julia.
- [PowerDynamics.jl](https://github.com/JuliaEnergy/PowerDynamics.jl) : Package for dynamical modeling of power grids.
- [PowerSystems.jl](https://github.com/NREL-SIIP/PowerSystems.jl) : Data structures in Julia to enable power systems analysis.
- [PowerSimulations.jl](https://github.com/NREL-SIIP/PowerSimulations.jl) : Julia for optimization simulation and modeling of PowerSystems.


## Electromagnetism

**Resources**

- [Wikipedia: Electromagnetic spectrum](https://en.wikipedia.org/wiki/Electromagnetic_spectrum)
- [Wikipedia: Optics](https://en.wikipedia.org/wiki/Optics)


**Packages**

- [Peacock.jl](https://github.com/sp94/Peacock.jl) : Photonic crystals in Julia.
- [PhysicalOptics.jl](https://github.com/JuliaPhysics/PhysicalOptics.jl) : A package for simulation of physical optics.
- [RadiationSpectra.jl](https://github.com/JuliaPhysics/RadiationSpectra.jl) : Toolkit for analysis of radiation spectra in Julia.
- [SpikeSorting.jl](https://github.com/paulmthompson/SpikeSorting.jl) : Online spike sorting methods in Julia.

---

<details>

<summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [Dipole julia](https://github.com/manuamador/Dipole_julia) : A set of functions that computes the electromagnetic radiation of an Hertz dipole (E and B fields).
- 🏚️ [Reverb Julia](https://github.com/manuamador/Reverb_Julia) : A julia version of an electromagnetic reverberation chamber model based on image theory.
- 🏚️ [Stirrer](https://github.com/manuamador/Stirrer) : A Julia and Python set of tools to model stirrers in reverberation chambers.
- 🏚️ [Z](https://github.com/manuamador/Z) : Wave impedance in a reverberation chamber.

</details>

## Computational Fluid Dynamics (CFD)

**Resources**

- [Wikipedia: Fluid Dynamics](https://en.wikipedia.org/wiki/Fluid_dynamics)
- Blog post about [CFD tutorial in julia](https://www.juliabloggers.com/cfd-tutorial-in-julia/)

**Packages**

- [Oceananigans.jl](https://github.com/CliMA/Oceananigans.jl) : Fast and friendly fluid dynamics on CPUs and GPUs.

<details>

<summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [hydro](https://github.com/natj/hydro) : Fairly simple, relatively small & mildly interesting hydrodynamic code.
- 🏚️ [LatBo.jl](https://github.com/UCL/LatBo.jl) : [Lattice-Boltzmann](http://www.scholarpedia.org/article/Lattice_Boltzmann_Method) method in Julia.

</details>

## Quantum Mechanics

- [Cliffords.jl](https://github.com/BBN-Q/Cliffords.jl) : This library allows for efficient calculation of [Clifford](http://en.wikipedia.org/wiki/Clifford_algebra) circuits by tracking the evolution of X and Z generators.
- [Hadamard.jl](https://github.com/stevengj/Hadamard.jl) : Fast multidimensional Walsh-Hadamard transforms.
- [MERA.jl](https://github.com/mhauru/MERA.jl) : provides Julia implementations of some basic [Multiscale Entaglement Renormalization Ansatz algorithms](https://arxiv.org/abs/quant-ph/0610099).
- [Qlab.jl](https://github.com/blakejohnson/Qlab.jl) : Data manipulation and analysis tools tailored for quantum computing experiments.
- [QSimulator.jl](https://github.com/BBN-Q/QSimulator.jl) : Package for simulating time dynamics of quantum systems with a focus on superconducting qubits.
- [QuantumOptics.jl](https://github.com/bastikr/QuantumOptics.jl) : Quantum optics toolbox is a numerical framework written in Julia that makes it easy to simulate various kinds of quantum systems. It is similar to the [Quantum Optics Toolbox](http://qo.phy.auckland.ac.nz/toolbox) for MATLAB and its Python equivalent [QuTiP](http://qutip.org/).
- [WignerSymbols.jl](https://github.com/Jutho/WignerSymbols.jl) : A Julia package for computing Wigner symbols and related quantities.
- [Yao.jl](https://github.com/QuantumBFS/Yao.jl) : Extensible, Efficient Quantum Algorithm Design for Humans.

---

<details>

<summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [AdiaRoll.jl](https://github.com/Roger-luo/AdiaRoll.jl) : An Adiabatic Computation Simulator for quantum computation.
- 🏚️ [QuBase.jl](https://github.com/JuliaQuantum/QuBase.jl) : A foundational library for quantum mechanics in Julia, that provides a unifying type structure and set of basic functions for computational quantum mechanics.
- 🏚️ [QuDirac.jl](https://github.com/JuliaQuantum/QuDirac.jl) : A library for performing quantum mechanics using Dirac notation.
- 🏚️ [QuDOS.jl](https://github.com/acroy/QuDOS.jl) : Quantum Dynamics of Open Systems in Julia.
- 🏚️ [QuDynamics.jl](https://github.com/JuliaQuantum/QuDynamics.jl) : A library for solving dynamical equations in quantum mechanics.

</details>

## Statistical Mechanics

- 🏚️ [IsingModels.jl](https://github.com/johnmyleswhite/IsingModels.jl) : Drawing inexact samples from the Ising model using a Gibbs sampler.
- 🏚️ [MyIsing.jl](https://github.com/kaslusimoes/MyIsing.jl) : A naive and first try to implement a 2D Square Ising Model using Julia.

## Thermodynamics

[Wikipedia: Thermodynamics](http://en.wikipedia.org/wiki/Category:Thermodynamics)

- [Psychro.jl](https://github.com/pjabardo/Psychro.jl) : Thermodynamic properties of moist air (real gas mixture).

<details>

<summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [ThermodynamicsTable.jl](https://github.com/DANA-Laboratory/ThermodynamicsTable.jl) : Thermodynamics table for critical values, heat capacity, etc..
- 🏚️ [WaveToy.jl](https://github.com/eschnett/WaveToy.jl) : Julia WaveToy.

</details>

## Other physics packages

<details>

<summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [auditory.jl](https://github.com/jfsantos/auditory.jl) : Auditory filterbanks in Julia.
- 🏚️ [Chipmunk.jl](https://github.com/zyedidia/Chipmunk.jl) : A binding of the physics engine [Chipmunk](https://chipmunk-physics.net/) for Julia.
- 🏚️ [CMSSW.jl](https://github.com/jpata/CMSSW.jl) : A work-in-progress wrapper for ROOT.jl.
- 🏚️ [Codata.jl](https://github.com/kofron/Codata.jl)
- 🏚️ [HEP.jl](https://github.com/jpata/HEP.jl) : A collection of methods useful for HEP.
- 🏚️ [JLab.jl](https://github.com/amyascwk/JLab.jl) : Some scripts used in MIT 8.13 Experimental Physics (Fall 2014).
- 🏚️ [JuliaPower](https://github.com/prezaei85/JuliaPower) : A package of scripts in Julia to solve power flow and simulate cascading failures in power systems.
- 🏚️ [JuliBoots](https://github.com/mfpaulos/JuliBoots) : Conformal bootstrap calculations.
- 🏚️ [LHEF.jl](https://github.com/Keno/LHEF.jl) : Quick and dirty implementation of the Les Houches Event Format, for particle Physics, in terms of Fortran commonblocks where the information is embedded in a minimal XML-style structure.
- 🏚️ [Mass.jl](https://github.com/ggggggggg/Mass.jl) : An experimental frameworks for TES pulse analysis.
- 🏚️ [Physical.jl](https://github.com/ggggggggg/Physical.jl)
- 🏚️ [Quantities.jl](https://github.com/ElOceanografo/Quantities.jl) : Dimensions and Quantities.
- 🏚️ [ROOT.jl](https://github.com/jpata/ROOT.jl) : A toy experiment interfacing ROOT and Julia through FWLite. [ROOT](http://root.cern.ch) is a data analysis library widely used at experiments at CERN for HEP data analyses.
- 🏚️ [ROOTDataFrames.jl](https://github.com/jpata/ROOTDataFrames.jl) : A wrapper for ROOT Trees through the Abstract DataFrame interface.
- 🏚️ [Signals.jl](https://github.com/mbauman/Signals.jl) : A high level Signal type with a common timebase and groups of channels.
- 🏚️ [Xray.jl](https://github.com/ggggggggg/Xray.jl) : Julia interface for NIST x-ray database.
- 🏚️ [SALT.jl](https://github.com/xdavidliu/SALT.jl) : SALT (steady-state ab-initio laser theory) solver package for Julia. (No `Project.toml`)

</details>
