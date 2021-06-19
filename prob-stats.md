# Probability and Statistics in Julia

> Probabilistic programming, Stochastic process, Statistics

- [📖 Probability](https://en.wikipedia.org/wiki/Probability_theory) in Wikipedia.
- [Julia stats](https://github.com/JuliaStats) organization.


## Probabilistic programming

[📖 Probabilistic programming](https://en.wikipedia.org/wiki/Probabilistic_programming)

- [Gen.jl](https://github.com/probcomp/Gen.jl) : Probabilistic programming with programmable inference.
- [Omega.jl](https://github.com/zenna/Omega.jl) :  Causal, Higher-Order, Probabilistic Programming.
- [Soss.jl](https://github.com/cscherrer/Soss.jl) : Probabilistic programming via source rewriting.
- [Stan.jl](https://github.com/StanJulia/Stan.jl) : A Julia wrapper for the Stan language.
- [Stheno.jl](https://github.com/willtebbutt/Stheno.jl) : Probabilistic programming with Gaussian processes in Julia.
- [Turing.jl](https://github.com/TuringLang/Turing.jl) : A Turing complete probabilistic programming language.

## Stochastic process

[📖 Stochastic process](https://en.wikipedia.org/wiki/Stochastic_process)

### Markovian

[Markov Logic Network](https://en.wikipedia.org/wiki/Markov_logic_network)

- [POMDPs.jl](https://github.com/JuliaPOMDP/POMDPs.jl) : A Julia framework for solving Markov decision processes.
- [POMDPToolbox.jl](https://github.com/JuliaPOMDP/POMDPToolbox.jl) : Support tools for solving `POMDPs`.
- [HMMBase.jl](https://github.com/maxmouchet/HMMBase.jl) : A lightweight abstraction for hidden Markov models (HMM) in Julia.

### Gaussian

- [GaussianMixtures.jl](https://github.com/davidavdav/GaussianMixtures.jl) : Julia modules for Gaussian Mixture Models.
- [GaussianProcesses.jl](https://github.com/STOR-i/GaussianProcesses.jl) : A Julia package for Gaussian Processes.

### Bayesian

- [BayesNets.jl](https://github.com/sisl/BayesNets.jl) : Bayesian Networks for Julia.


- 🏚️ [BayesianNonparametrics.jl](https://github.com/OFAI/BayesianNonparametrics.jl) : Bayesian nonparametrics in Julia. (No `Project.toml`)
- 🏚️ [BayesianDataFusion.jl](https://github.com/jaak-s/BayesianDataFusion.jl) : Implementation of data fusion methods.
- 🏚️ [BayesEstDiffusion.jl](https://github.com/mschauer/BayesEstDiffusion.jl) : Bayesian estimation of diffusion processes.

## Statistic Regression analysis

[Regression analysis](https://en.wikipedia.org/wiki/Regression_analysis)

- [CurveFit.jl](https://github.com/pjabardo/CurveFit.jl) : Simple least squares and curve fitting functions.
- [FixedEffectModels.jl](https://github.com/FixedEffects/FixedEffectModels.jl) : Fast estimation of linear models with IV and high dimensional categorical variables.
- [GLM.jl](https://github.com/JuliaStats/GLM.jl) : Linear models (LM) and generalized linear models (GLM).
- [Isotonic.jl](https://github.com/ajtulloch/Isotonic.jl) : This implements several algorithms for isotonic regression in Julia. (No `Project.toml`)
- [LARS.jl](https://github.com/simonster/LARS.jl) : Least angle regression.
- [Lasso.jl](https://github.com/JuliaStats/Lasso.jl) : Lasso solvers for linear and generalized linear models.
- [MixedModels.jl](https://github.com/JuliaStats/MixedModels.jl) : A Julia package for fitting (statistical) mixed-effects models.
- [NonNegLeastSquares.jl](https://github.com/ahwillia/NonNegLeastSquares.jl) : Some nonnegative least squares solvers in Julia.
- [QuantileRegression.jl](https://github.com/pkofod/QuantileRegressions.jl) : Quantile regression in Julia.
- [SparseRegression.jl](https://github.com/joshday/SparseRegression.jl) : Statistical Models with Regularization in Pure Julia.


- 🏚️ [FLSA.jl](https://github.com/EQt/FLSA.jl) : Computing the Fused LASSO Signal Approximator to denoise data.
- 🏚️ [ParallelSparseRegression.jl](https://github.com/madeleineudell/ParallelSparseRegression.jl) : A Julia library for parallel sparse regression, that implements solvers for regression problems including least squares, ridge regression, LASSO, non-negative least squares, and elastic net; and proposes to add fast methods to obtain regularization paths.
- 🏚️ [Regression.jl](https://github.com/lindahua/Regression.jl) : Algorithms for regression analysis (e.g. linear regression and logistic regression).


## Density estimation

[Density_estimation](https://en.wikipedia.org/wiki/Density_estimation)

- [AverageShiftedHistograms.jl](https://github.com/joshday/AverageShiftedHistograms.jl) : David Scott's Average Shifted Histogram density estimation.
- [KernelDensity.jl](https://github.com/JuliaStats/KernelDensity.jl) : Kernel density estimators for continuous variables.
- [KernelEstimator.jl](https://github.com/panlanfeng/KernelEstimator.jl) : A Julia package for nonparametric density estimation. (No `Project.toml`)

## Multivariate

[Multivariate](https://en.wikipedia.org/wiki/Category:Multivariate_statistics)

- [LowRankModels.jl](https://github.com/madeleineudell/LowRankModels.jl) : modeling and fitting generalized low rank models.
- [ManifoldLearning.jl](https://github.com/wildart/ManifoldLearning.jl) : manifold learning and non-linear dimensionality reduction.
- [MultivariateStats.jl](https://github.com/JuliaStats/MultivariateStats.jl) : multivariate data analysis (e.g. dimension reduction).

## Geostatistics

[Geostatistics](https://en.wikipedia.org/wiki/Geostatistics)

- [GeoStats.jl](https://github.com/JuliaEarth/GeoStats.jl) : High-performance geostatistical algorithms in Julia.
- [GeoStatsImages.jl](https://github.com/JuliaEarth/GeoStatsImages.jl) : Training images for geostastical simulation.
- [GslibIO.jl](https://github.com/JuliaEarth/GslibIO.jl) : Utilities to read/write extended GSLIB files in Julia.

## Time series

[Time series](https://en.wikipedia.org/wiki/Time_series)

- [BasisFunctionExpansions.jl](https://github.com/baggepinnen/BasisFunctionExpansions.jl) : Basis Function Expansions for Julia.
- [ControlSystemIdentification.jl](https://github.com/baggepinnen/ControlSystemIdentification.jl) : System Identification for LTI systems, compatible with `ControlSystems.jl`.
- [DCCA.jl](https://github.com/johncwok/DCCA.jl) : Detrended cross-correlations coefficient analysis : an easy to use Julia implementation.
- [DependentBootstrap.jl](https://github.com/colintbowers/DependentBootstrap.jl) : A module that implements several varieties of the dependent statistical bootstrap as well as the corresponding block-length selection procedures.
- [LPVSpectral.jl](https://github.com/baggepinnen/LPVSpectral.jl) : Least-squares (sparse) spectral estimation and (sparse) LPV spectral decomposition.
- [PerronFrobenius.jl](https://github.com/kahaaga/PerronFrobenius.jl) : Estimating the transfer operator (Perron Frobenius operator) and invariant measures from time series.
- [Temporal.jl](https://github.com/dysonance/Temporal.jl) : Flexible and efficient time series class & methods for the Julia language.
- [TimeSeries.jl](https://github.com/JuliaStats/TimeSeries.jl) : Time-series toolkit for Julia.
- 🏚️ [SmoothingKernels.jl](https://github.com/johnmyleswhite/SmoothingKernels.jl) : Smoothing kernels for use in kernel regression and kernel density estimation.

## Online algorithm

- [OnlineStats.jl](https://github.com/joshday/OnlineStats.jl) : Online algorithms for statistics.

## Compositional Data Analysis

[Compositional Data Analysis](https://en.wikipedia.org/wiki/Compositional_data)

- [CoDa.jl](https://github.com/JuliaEarth/CoDa.jl) : Compositional Data Analysis in Julia

## Extreme value theory

[Extreme value theory](https://en.wikipedia.org/wiki/Extreme_value_theory)

- [ExtremeStats.jl](https://github.com/JuliaEarth/ExtremeStats.jl) : Extreme Value Statistics in Julia.

## Causal

- 🏚️ [CauseMap.jl](https://github.com/cyrusmaher/CauseMap.jl) : An implementation of Convergent Cross Mapping (CCM), a method for causal inference in non-linear dynamics systems, written in Julia.

## Sampling

- [Bootstrap.jl](https://github.com/julian-gehring/Bootstrap.jl) : Bootstrapping is a widely applicable technique for statistical estimation, especially in the absence of closed-form solutions.
- [GeneralizedSampling.jl](https://github.com/robertdj/GeneralizedSampling.jl) : Generalized Sampling in Julia.
- [Jackknife.jl](https://github.com/ararslan/Jackknife.jl) : Jackknife resampling and estimation in Julia.
- [Jags.jl](https://github.com/JagsJulia/Jags.jl) : Julia package for using Just another Gibbs sampler.
- [MonteCarloMeasurements.jl](https://github.com/baggepinnen/MonteCarloMeasurements.jl) : Uncertainty propagation by Monte-Carlo sampling: Real numbers with uncertainty represented by particle clouds.
- [RecombinatorKMeans.jl](https://github.com/carlobaldassi/RecombinatorKMeans.jl) : An implementation of the recombinator-k-means method.
- [StableDQMC.jl](https://github.com/crstnbr/StableDQMC.jl) : Numerical stabilization routines for determinant quantum Monte Carlo.
- 🏚️ [PSIS.jl](https://github.com/alvaro1101/PSIS.jl) : Pareto smoothed importance sampling (PSIS) and PSIS leave-one-out cross-validation for Julia.

## Tests

- [HypothesisTests.jl](https://github.com/JuliaStats/HypothesisTests.jl) : T-tests, Wilcoxon rank sum (Mann-Whitney U), signed rank, and circular statistics in Julia.
- 🏚️ [RobustStats.jl](https://github.com/mrxiaohe/RobustStats.jl) : A collection of robust statistical tests based on the R package WRS (R-Forge repository) by Rand Wilcox.

## Unclassified

- [AdaGram.jl](https://github.com/sbos/AdaGram.jl) : Adaptive Skip-gram implementation.
- [BloomFilters.jl](https://github.com/johnmyleswhite/BloomFilters.jl) : are a probabilistic data structur e that can be used to test the inclusion and exclusion of items in a list. (No `Project.toml`)
- [Civecm.jl](https://github.com/andreasnoack/Cointegration.jl) : Cointegration in Vector Error Correction Models in Julia.
- [ConjugatePriors.jl](https://github.com/JuliaStats/ConjugatePriors.jl) : A package to support conjugate prior distributions.
- [CovarianceMatrices.jl](https://github.com/gragusa/CovarianceMatrices.jl) : Covariance Matrix Estimation in Julia.
- [DiscriminantAnalysis.jl](https://github.com/trthatcher/DiscriminantAnalysis.jl) : A package for linear and quadratic regularized Discriminant Analysis.
- [Distances.jl](https://github.com/JuliaStats/Distances.jl) :  A Julia package for evaluating distances(metrics) between vectors.
- [Distributions.jl](https://github.com/JuliaStats/Distributions.jl) : Probability distributions in Julia.
- [Divergences.jl](https://github.com/gragusa/Divergences.jl) : A Julia package for evaluating divergences.
- [FeldtLib.jl](https://github.com/robertfeldt/FeldtLib.jl) : Misc julia code that have not yet found its home in a package...
- [FreqTables.jl](https://github.com/nalimilan/FreqTables.jl) : Frequency tables.
- [GaussDCA.jl](https://github.com/carlobaldassi/GaussDCA.jl) : Multivariate Gaussian Direct Coupling Analysis for residue contact prediction in protein families.
- [PortHamiltonian.jl](https://github.com/flavioluiz/PortHamiltonian.jl) : Port-Hamiltonian systems in Julia. (No `Project.toml`)
- [RankAggregation.jl](https://github.com/JuliaEarth/RankAggregation.jl) : Rank aggregation in Julia.
- [Rmath.jl](https://github.com/JuliaStats/Rmath.jl) : Archive of functions that emulate R's d-p-q-r functions for probability distributions.
- [StatsBase.jl](https://github.com/JuliaStats/StatsBase.jl) : Basic statistics.
- [TopicModels.jl](https://github.com/slycoder/TopicModels.jl) : TopicModels for Julia.
- [TSne.jl](https://github.com/lejon/TSne.jl) : Julia port of L.J.P. van der Maaten and G.E. Hinton's T-SNE visualisation technique.

- 🏚️ [CTDE.jl](https://github.com/adolgert/CTDE.jl) : Continuous time, discrete event system in Julia.
- 🏚️ [DirichletProcessMixtures.jl](https://github.com/sbos/DirichletProcessMixtures.jl) : This package implements Dirichlet Process Mixture Models in Julia using variational inference for truncated stick-breaking representation of Dirichlet Process.
- 🏚️ [FactorModels.jl](https://github.com/joidegn/FactorModels.jl) : Factor models or diffusion index models.
- 🏚️ [JointMoments.jl](https://github.com/tensorjack/JointMoments.jl) : Tensors and statistics for joint central moments.
- 🏚️ [KernSmooth.jl](https://github.com/lendle/KernSmooth.jl) : A direct port of the R package KernSmooth, (v2.23-10.), carrying an unlimited license.
- 🏚️ [PowerLaws.jl](https://github.com/johnybx/PowerLaws.jl) : A Julia package for power laws distributions.
- 🏚️ [PValueAdjust.jl](https://github.com/dirkschumacher/PValueAdjust.jl) : P-value adjustment methods for multiple testing correction.
