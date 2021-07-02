# General mathematical tools in Julia

> [Mathematical](http://en.wikipedia.org/wiki/Lists_of_mathematics_topics) libraries/ packages, and related resources.

- [Julia Approximation](https://github.com/JuliaApproximation)
- [Julia Crypto](https://github.com/JuliaCrypto)
- [Julia Linear Algebra](https://github.com/JuliaLinearAlgebra)
- [Julia Math](https://github.com/JuliaMath)
- [Julia Matrices](https://github.com/JuliaMatrices/)
- [Julia Diff](https://github.com/JuliaDiff)
- [Julia sparse](https://github.com/JuliaSparse)
- [Julia DSP](https://github.com/JuliaDSP)

## General Mathematics packages

- [AppleAccelerate.jl](https://github.com/JuliaMath/AppleAccelerate.jl) : Julia interface to OS X's Accelerate framework.
- [EntropicCone.jl](https://github.com/blegat/EntropicCone.jl) : Entropic Cone approximation and optimization
- [FastPow.jl](https://github.com/JuliaMath/FastPow.jl) : `@fastpow` speeds up the computation of integer powers in any Julia expression by transforming them into optimal sequences of multiplications, with a slight sacrifice in accuracy.
- [GSL.jl](https://github.com/JuliaMath/GSL.jl) : Julia interface to the GNU Scientific Library - [GSL](https://www.gnu.org/software/gsl/doc/html/index.html).
- [Hecke.jl](https://github.com/thofma/Hecke.jl) : Computational algebraic number theory
- [Hexagons.jl](https://github.com/GiovineItalia/Hexagons.jl) : Useful tools for working with hexagonal grids.
- [MPFR.jl](https://github.com/andrioni/MPFR.jl) : A Julia package for the GNU MPFR library.
- [MTH229.jl](https://github.com/mth229/MTH229.jl) : Helper files for using Julia with MTH229.
- [NaNMath.jl](https://github.com/mlubin/NaNMath.jl) : Implementations of basic math functions which return NaN instead of throwing a `DomainError`.
- [NLreg.jl](https://github.com/dmbates/NLreg.jl) : Nonlinear regression in Julia.
- [Tau.jl](https://github.com/JuliaMath/Tau.jl) : A simple module providing definition of the Tau constant = 2pi.
- [Manifolds.jl](https://github.com/JuliaManifolds/Manifolds.jl) : a unified interface to define and use manifolds as well as a library of manifolds to use for your projects.


- 🏚️ [ApApproximation.jl](https://github.com/dprn/ApApproximation.jl) : Implementation of the almost-periodic approximation.
- 🏚️ [Cartesian.jl](https://github.com/timholy/Cartesian.jl) : Fast multidimensional algorithms. Now in Julia `Base`.
- 🏚️ [ContinuedFractions.jl](https://github.com/johnmyleswhite/ContinuedFractions.jl) : Types and functions for working with continued fractions in Julia. (No `Project.toml`)
- 🏚️ [CRF.jl](https://github.com/slyrz/CRF.jl) : Conditional Random Fields in Julia.
- 🏚️ [Devectorize.jl](https://github.com/lindahua/Devectorize.jl) : A Julia framework for delayed expression evaluation.
- 🏚️ [Entropy.jl](https://github.com/grero/Entropy.jl) : This package contains functionality for computing binless estimates of entropy from discrete and continuous samples for continuous distributions.
- 🏚️ [ExtremeValueDistributions.jl](https://github.com/sammorris81/ExtremeValueDistributions.jl) : A Julia package to fit extreme value distributions.
- 🏚️ [FloorLayout.jl](https://github.com/joehuchette/FloorLayout.jl) :  Framework and various drivers for floor layout formulation analysis.
- 🏚️ [MathToolkit.jl](https://github.com/baruchel/MathToolkit.jl) : A Julia package providing various functions mainly for the purpose of experimental mathematics.
- 🏚️ [Multicombinations.jl](https://github.com/jlep/Multicombinations.jl) : An iterator for k-combinations with repetitions, k-multicombinations, k-multisubsets.
- 🏚️ [Shannon.jl](https://github.com/kzahedi/Shannon.jl) : Entropy, Mutual Information, KL-Divergence related to Shannon's information theory and functions to binarize data.
- 🏚️ [SimilarityMetrics.jl](https://github.com/johnmyleswhite/SimilarityMetrics.jl) : Standard similarity metrics in Julia.
- 🏚️ [Smolyak](https://github.com/EconForge/Smolyak) : Efficient implementations of Smolyak's algorithm for function approxmation in Python and Julia.
- 🏚️ [TwoBasedIndexing.jl](https://github.com/simonster/TwoBasedIndexing.jl) : Two-based indexing.
- 🏚️ [Uncertain.jl](https://github.com/rephorm/Uncertain.jl) : Uncertain quantities and error propagation for the Julia language.
- 🏚️ [univariate__opt.jl](https://github.com/matthewclegg/univariate_opt.jl) : Univariate optimization and root-finding code for Julia.
- 🏚️ [Unums.jl](https://github.com/JuliaComputing/Unums.jl) : Unum (Universal Number) types and operations.
- 🏚️ [utils.jl](https://github.com/juho-lee/utils.jl) : basic utilities needed for scientific coding with julia.

## Cryptography

- [MbedTLS.jl](https://github.com/JuliaLang/MbedTLS.jl) : Wrapper around [mbedtls](https://tls.mbed.org/).
- [MD5.jl](https://github.com/JuliaCrypto/MD5.jl) : A pure julia MD5 implementation.
- [Nettle.jl](https://github.com/JuliaCrypto/Nettle.jl) : is a simple wrapper around libnettle, a cryptographic library, providing MD5, SHA1, SHA2 hashing and HMAC functionality, as well as AES encryption/decryption
- [RNGTest.jl](https://github.com/andreasnoackjensen/RNGTest.jl) : A package that is a Julia interface to the test suite TestU01 of Pierre l'Ecuyer to test random numbers.
- [SHA.jl](https://github.com/JuliaCrypto/SHA.jl) : a performant, 100% native-julia SHA-1, SHA-2 224, 256, 384 and 512, and SHA-3 224, 256, 384 and 512 functions.
- [SEAL.jl](https://github.com/JuliaCrypto/SEAL.jl) : wrapping the Microsoft SEAL library for homomorphic encryption


- 🏗️ [ToyFHE.jl](https://github.com/JuliaCrypto/ToyFHE.jl) : Toy implementation of [FHE algorithms](https://en.wikipedia.org/wiki/Homomorphic_encryption).
- 🏚️ [BlockCipherSelfStudy.jl](https://github.com/andrewcooke/BlockCipherSelfStudy.jl) : Blocks, and RC5.
- 🏚️ [Crypto.jl](https://github.com/danielsuo/Crypto.jl) : A library that wraps OpenSSL, but also has pure Julia implementations for reference.
- 🏚️ [FNVHash.jl](https://github.com/samoconnor/FNVHash.jl) : FNV (Fowler/Noll/Vo) is a fast, non-cryptographic hash algorithm with good dispersion.
- 🏚️ [OpenSSL.jl](https://github.com/dirk/OpenSSL.jl) : WIP OpenSSL bindings for Julia.
- 🏚️ [OpenSSLCrypto.jl](https://github.com/amitmurthy/OpenSSLCrypto.jl) : Julia interface to the crypto API of openssl.
- 🏚️ [RNGTesting](https://github.com/johnmyleswhite/RNGTesting) : Scripts for testing Julia's RNG's.
- 🏚️ [Sha256.jl](https://github.com/mad4alcohol/Sha256.jl) : sha25 hash algorithm for Julia.
- 🏚️ [Stupid.jl](https://github.com/andrewcooke/Stupid.jl) : Analysis of an 8 bit version of the cipher at http://news.quelsolaar.com/#comments101.

### Cryptocurrency

- 🏚️ Bit[Coin.jl](https://github.com/danielsuo/Coin.jl) : A library for working with Bitcoin written in Julia.
- 🏚️ [BitcoinBlockchain.jl](https://github.com/stejin/BitcoinBlockchain.jl) : Julia package for analyzing the Bitcoin blockchain via the API provided by https://blockchain.info/.

## Computer Arithmetic

[📖 Computer Arithmetic](https://en.wikipedia.org/wiki/Category:Computer_arithmetic)

- [Elementary Number Theory](https://github.com/williamstein/ent) : Primes, Congruences, and Secrets.
- [Calc.jl](https://github.com/tshort/Calc.jl) : An RPN calculator for the Julia REPL.
- [DeepConvert.jl](https://github.com/jlapeyre/DeepConvert.jl) : This package provides convenient literal construction of values of large data types.

### Floating Point

[Floating Point](https://en.wikipedia.org/wiki/Category:Floating_point)

For floating-point datatypes, see [Data Types](dsa.md#numeric-data-types) Section.

- [ErrorfreeArithmetic.jl](https://github.com/JeffreySarnoff/ErrorfreeArithmetic.jl) : Error-free transformations for arithmetic ops.
- [FastRounding.jl](https://github.com/JeffreySarnoff/FastRounding.jl) : Faster directed rounding for inline arithmetic.
- [ValidatedNumerics.jl](https://github.com/JuliaIntervals/ValidatedNumerics.jl) : Rigorous floating-point calculations via interval arithmetic.


- 🏚️ [ErrorFreeTransforms.jl](https://github.com/dsiem/ErrorFreeTransforms.jl) : Map the rounding errors in floating point arithmetic with error-free transformations (EFT).
- 🏚️ [Ryu.jl](https://github.com/quinnj/Ryu.jl) : Julia implementation of [ryu](https://github.com/ulfjack/ryu) that converts floating point numbers to decimal strings.
- 🏚️ [UnumX.jl](https://github.com/JuliaComputing/UnumX.jl) : Experimental Unums.

## Modelling and Simulations

See [modeling and simulations](modeling.md) section.

## Algebra

Resources: [Ideles adeles algebraic number theory](https://github.com/williamstein/adeles)

- [Equations.jl](https://github.com/jhlq/Equations.jl) : Derive mathematical relations.
- [Hecke.jl](https://github.com/thofma/Hecke.jl) : A package for algebraic number theory that works on top of `Nemo.jl` by Tommy Hofmann and Claus Fieker.
- [HemirealFactorization.jl](https://github.com/timholy/HemirealFactorization.jl) : Matrix factorizations over the hemireals.
- [HemirealNumbers.jl](https://github.com/timholy/HemirealNumbers.jl) : Implementation of hemireal arithmetic for Julia.
- [Mods.jl](https://github.com/scheinerman/Mods.jl) : Easy modular arithmetic for Julia.
- [Nemo.jl](https://github.com/Nemocas/Nemo.jl) : A computer algebra package for the Julia programming language.
- [OEIS.jl](https://github.com/MurrayT/OEIS.jl) : A basic wrapper to allow access to [OEIS](http://oeis.org/) integer sequences from within Julia.
- [SemiringAlgebra.jl](https://github.com/ViralBShah/SemiringAlgebra.jl) : [Semiring Algebra](https://dspace.mit.edu/openaccess-disseminate/1721.1/115964).


- 🏚️ [algebra](https://github.com/alrahimi/algebra/) : A hierarchy of abstract algebraic structures in Julia.
- 🏚️ [Clockwork.jl](https://github.com/malmaud/Clockwork.jl) : Represent modular arithmetic via clock symbols.
- 🏚️ [Cuhre.jl](https://github.com/tflovorn/Cuhre.jl) : Simplified Julia interface to Cuhre integration routine.
- 🏚️ [Digits.jl](https://github.com/greenflash1357/Digits.jl) : A module for integer digit manipulation.
- 🏚️ [FirstOrderLogic.jl](https://github.com/TotalVerb/FirstOrderLogic.jl) : This package aims to include functions that manipulate mathematical logic.
- 🏚️ [Juniper.jl](https://github.com/jcrist/Juniper.jl) : A simple computer algebra system.

### Boolean Algebra

[Boolean Algebra](http://en.wikipedia.org/wiki/Category:Boolean_algebra)

- [ShowSet.jl](https://github.com/scheinerman/ShowSet.jl) : Nicer output for Set and IntSet objects.
- 🏚️ [BitCircuits.jl](https://github.com/um-tech-evolution/BitCircuits.jl) : Boolean circuit evaluation using bitwise operations.

## Numerical Analysis

[Numerical Analysis](https://en.wikipedia.org/wiki/Category:Numerical_analysis)

- [AMD.jl](https://github.com/JuliaSmoothOptimizers/AMD.jl) : Approximate Minimum Degree (AMD) Ordering in Julia.
- [ApproXD.jl](https://github.com/floswald/ApproXD.jl) : B-splines and linear high-dimensional approximators in multiple dimensions for Julia.
- [Dierckx.jl](https://github.com/kbarbary/Dierckx.jl ): Julia package for 1-d and 2-d splines, a wrapper for the [dierckx](http://www.netlib.org/dierckx/index.html) Fortran library.
- [Dualization.jl](https://github.com/guilhermebodin/Dualization.jl) : Automatic dualization feature for MathOptInterface.jl conic optimization problems.
- [FastGaussQuadrature.jl](https://github.com/JuliaApproximation/FastGaussQuadrature.jl) : A Julia package to compute n-point Gauss quadrature nodes and weights to 16-digit accuracy and in O(n) time.
- [FastTransforms.jl](https://github.com/JuliaApproximation/FastTransforms.jl) : Julia package for fast orthogonal polynomial transforms.
- [GridInterpolations.jl](https://github.com/sisl/GridInterpolations.jl) : Multi-dimensional grid interpolation in arbitrary dimensions on a recti-linear grid.
- [Interpolations.jl](https://github.com/JuliaMath/Interpolations.jl) : Fast, continuous interpolation of discrete datasets in Julia.
- [Knitro.jl](https://github.com/jump-dev/KNITRO.jl) : Julia interface to the [Knitro](https://www.artelys.com/knitro) solver.
- [LinearExpressions.jl](https://github.com/cdsousa/LinearExpressions.jl) : Linear symbolic expressions for the Julia language.
- [NumericalAlgorithms.jl](https://github.com/mrtkp9993/NumericalAlgorithms.jl) : Statistics & Numerical algorithms implemented in Julia.
- [PiecewiseInterpolation.jl](https://github.com/gwater/PiecewiseInterpolation.jl) : A simple interface for interpolations on timeseries with first order discontinuities (using `Dierckx.jl`).
- [RollingFunctions.jl](https://github.com/JeffreySarnoff/RollingFunctions.jl) : Roll a function over data, run a statistic along a `weighted` data window.
- [Simplices.jl](https://github.com/JuliaDynamics/Simplices.jl) : Compute exact simplex intersections in N dimensions.
- [Sobol.jl](https://github.com/stevengj/Sobol.jl) : is a generation of Sobol low-discrepancy sequence (LDS) implementation, that generates **quasi-random** sequences of points in N dimensions which are equally distributed over an N-dimensional hypercube.


- 🏚️ [Dopri.jl](https://github.com/helgee/Dopri.jl) : A Julia wrapper for the DOPRI5 and DOP853 integrators.
- 🏚️ [EiSCor.jl](https://github.com/andreasnoack/EiSCor.jl) : A Julia wrapper of the Fortran library [eiscor](https://github.com/jaurentz/eiscor).
- 🏚️ [Grid.jl](https://github.com/timholy/Grid.jl) : Interpolation and related operations on grids.  Deprecated in favor of `Interpolations`.
- 🏚️ [OpenSpecFun.jl](https://github.com/ararslan/OpenSpecFun.jl) : A Julia wrapper for the OpenSpecFun library of special functions.
- 🏚️ [RK4.jl](https://github.com/ntezak/RK4.jl) : This package implements a fairly fast Runge-Kutta 4th order with fixed stepsize, also implements a stochastic solver that is not technically provably accurate, but works well for finite bandwidth SDE's.
- 🏚️ [RungeKuttaFehlberg.jl](https://github.com/gwater/RungeKuttaFehlberg.jl) : A Julia implementation of the RKF45 method for time integration.

## Linear Algebra

[Linear Algebra](https://en.wikipedia.org/wiki/Category:Linear_algebra)

- [DirectSum.jl](https://github.com/chakravala/DirectSum.jl) : Abstract tangent bundle vector space type operations.
- [Divergences.jl](https://github.com/gragusa/Divergences.jl) : A Julia package that makes it easy to evaluate divergence measures between two vectors. The package allows calculating the gradient and the diagonal of the Hessian of several divergences which can be used to good effect by the MomentBasedEstimators package.
- [Elemental.jl](https://github.com/JuliaParallel/Elemental.jl) : A Julia interface to the [Elemental linear algebra library](http://libelemental.org/) with third-party interfaces. [Source code](https://github.com/elemental/Elemental).
- [FGenerators.jl](https://github.com/JuliaFolds/FGenerators.jl) : A package for defining Transducers.jl-compatible extended foldl with a simple `@yield`-based syntax.
- [GenericLinearAlgebra.jl](https://github.com/JuliaLinearAlgebra/GenericLinearAlgebra.jl) : Partly to extend linear algebra functionality in base to cover generic element types, e.g. `BigFloat` and `Quaternion`, and partly to be a place to experiment with fast linear algebra routines.
- [IncrementalSVD.jl](https://github.com/aaw/IncrementalSVD.jl) : Simon Funk's approach to collaborative filtering using the singular value decomposition, implemented in Julia.
- [IntelVectorMath.jl](https://github.com/JuliaMath/IntelVectorMath.jl) : Julia bindings for the Intel Vector Math Library.
- [ITensors.jl](https://github.com/ITensor/ITensors.jl): A Julia library for efficient tensor calculations.
- [IterativeSolvers.jl](https://github.com/JuliaLinearAlgebra/IterativeSolvers.jl) : Iterative algorithms for solving linear systems, eigensystems, and singular value problems.
- [Leibniz.jl](https://github.com/chakravala/Leibniz.jl) : Operator algebras for mixed-symmetry multivariate differentiable tensor fields.
- [LinearMaps.jl](https://github.com/Jutho/LinearMaps.jl) : A Julia package for defining and working with linear maps, also known as linear transformations or linear operators acting on vectors. The only requirement for a LinearMap is that it can act on a vector (by multiplication) efficiently.
- [LLLplus.jl](https://github.com/christianpeel/LLLplus.jl) : LLL lattice reduction, sphere decoder, and related lattice tools.
- [LMCLUS.jl](https://github.com/wildart/LMCLUS.jl) : Julia's package for Linear Manifold Clustering.
- [MKL.jl](https://github.com/JuliaLinearAlgebra/MKL.jl) : Intel MKL linear algebra backend for Julia
- [MUMPS](https://github.com/lruthotto/MUMPS) : A wrapper for a MUltifrontal Massively Parallel sparse direct Solver of large linear systems in Julia.
- [MUMPSjInv.jl](https://github.com/JuliaInv/MUMPSjInv.jl) : An alternative implementation of a Julia interface to the sparse direct solver MUMPS. A MUMPS package for Julia is already registered but that package does not conform to the packaging standards for Julia.
- [SugarBLAS.jl](https://github.com/lopezm94/SugarBLAS.jl) : Syntactic sugar for BLAS polynomials.
- [TensorOperations.jl](https://github.com/Jutho/TensorOperations.jl) : Julia package for tensor contractions and related operations.
- [Transducers.jl](https://github.com/JuliaFolds/Transducers.jl) : provides composable algorithms on "sequence" of inputs. This feature, available in Clojure language, is a [transformation matrix](https://en.wikipedia.org/wiki/Transformation_matrix) for linear transformations that is now in Julia.
- [Tullio.jl](https://github.com/mcabbott/Tullio.jl) : A package for writing array operations in index notation.
- [VSL.jl](https://github.com/sunoru/VSL.jl) : Julia bindings for the Intel Vector Statistics Library.


- 🏚️ [Accelereval.jl](https://github.com/lindahua/Accelereval.jl) : A Julia framework for accelerated re-compiled evaluation of numerical functions that ensures faster computation.
- 🏚️ [BSplines.jl](https://github.com/gusl/BSplines.jl) : This package provides B-Splines for 1D signals, i.e. functions of type Real -> Real.
- 🏚️ [CLBLAS.jl](https://github.com/JuliaGPU/CLBLAS.jl) : CLBLAS integration for Julia. (No `Project.toml`)
- 🏚️ [CUSOLVER.jl](https://github.com/kshyatt/CUSOLVER.jl) : Julia bindings for the NVIDIA CUSOLVER library. CUSOLVER is a high-performance direct-solver matrix linear algebra library.
- 🏚️ [CUSPARSE.jl](https://github.com/kshyatt/CUSPARSE.jl) : Julia interface to NVIDIA's CUSPARSE library.
- 🏚️ [Hypre.jl](https://github.com/jgoldfar/Hypre.jl) : A wrapper for the Hypre library.
- 🏚️ [IDRsSolver.jl](https://github.com/mschauer/IDRsSolver.jl) : Induced Dimension Reduction method [IDR(s)] for solving general linear equations. Incorporated into `IterativeSolvers.jl`.
- 🏚️ [IterativeLinearSolvers.jl](https://github.com/andreasnoackjensen/IterativeLinearSolvers.jl).
- 🏚️ [JointMoments.jl](https://github.com/tinybike/JointMoments.jl) : Tensors and statistics for joint central moments.
- 🏚️ [LDA.jl](https://github.com/remusao/LDA.jl) : Linear Discriminant Analysis and Kernel Fisher Analysis.
- 🏚️ [LMesh.jl](https://bitbucket.org/maurow/lmesh.jl) : A Mesh package that implements the type of mesh sugessted by Logg (2012).
- 🏚️ [MiniBall.jl](https://github.com/JuliaFEM/MiniBall.jl) : Julia package for a smallest enclosing sphere for points in arbitrary dimensions.
- 🏚️ [NumericalShadow.jl](https://github.com/pgawron/NumericalShadow.jl) : Library to calculate numerical shadows in Julia language.
- 🏚️ [NumericExtensions.jl](https://github.com/lindahua/NumericExtensions.jl) : Julia extensions to provide high performance computational support for fast vectorized computation.
- 🏚️ [NumericFunctors.jl](https://github.com/lindahua/NumericFunctors.jl) : Typed functors for numerical computations.
- 🏚️ [NumericFuns.jl](https://github.com/lindahua/NumericFuns.jl) : Math functions and functors for numerical computations.
- 🏚️ [OpenCLBLAS.jl](https://github.com/mikhail-j/OpenCLBLAS.jl) : OpenCL BLAS library wrapper for Julia with samples.
- 🏚️ [ParallelLinalg.jl](https://github.com/intirb/ParallelLinalg.jl) : Distributed Dense Linear Algebra for Julia.
- 🏚️ [PNLA_Julia](https://github.com/kbatseli/PNLA_Julia) : Polynomial Multi-functional Numerical Linear Algebra package for solving all kinds of problems with multivariate polynomials in double precision in Julia.
- 🏚️ [SALT.jl](https://github.com/xdavidliu/SALT.jl) : SALT (steady-state ab-initio laser theory) solver package for Julia. (No `Project.toml`)
- 🏚️ [SuperLU.jl](https://github.com/dmbates/SuperLU.jl) : Julia interface to the SuperLU solver package for sparse systems.

### Matrices

[📖 Matrix Theory](https://en.wikipedia.org/wiki/Category:Matrix_theory)

> Special Array/Matrix Algorithms, for Array Types, see Data Types section.

- [AxisAlgorithms.jl](https://github.com/timholy/AxisAlgorithms.jl) : Efficient filtering and linear algebra routines for multidimensional arrays.
- [CatIndices.jl](https://github.com/JuliaArrays/CatIndices.jl) : Julia package for indices-aware array concatenation and growth.
- [ConvolutionTools.jl](https://github.com/gwater/ConvolutionTools.jl) : Tools for convolutions of multi-dimensional arrays in Julia.
- [Einsum.jl](https://github.com/ahwillia/Einsum.jl) : [Einstein summation notation](https://en.wikipedia.org/wiki/Einstein_notation) in julia.
- [EndpointRanges.jl](https://github.com/JuliaArrays/EndpointRanges.jl) : Julia package for doing arithmetic on endpoints in array indexing.
- [Kronecker.jl](https://github.com/MichielStock/Kronecker.jl) : A general-purpose toolbox for efficient Kronecker-based algebra that combines lazy evaluation and algebraic tricks such that it can implicitely work with huge matrices. It allows to work with large Kronecker systems both much faster and using much less memory than the naive implementation of the [Kronecker product](https://en.wikipedia.org/wiki/Kronecker_product).
- [KSVD.jl](https://github.com/IshitaTakeshi/KSVD.jl) : K-SVD is an algorithm for creating overcomplete dictionaries for sparse representations.
- [LowRankApprox.jl](https://github.com/JuliaMatrices/LowRankApprox.jl) : Fast low-rank matrix approximation in Julia.
- [PaddedViews.jl](https://github.com/JuliaArrays/PaddedViews.jl) : Add virtual padding to the edges of an array.
- [PDMats.jl](https://github.com/JuliaStats/PDMats.jl) : Uniform Interface for positive definite matrices of various structures.
- [PositiveFactorizations.jl](https://github.com/timholy/PositiveFactorizations.jl) : Positive-definite (approximations) to matrices.

- 🏗️ [ArrayIteration.jl](https://github.com/timholy/ArrayIteration.jl) : Testing new ideas for array iteration. Some of the features have already moved to Julia itself.
- 🏚️ [ArrayMeta.jl](https://github.com/shashi/ArrayMeta.jl) : metaprogramming for Julia arrays.
- 🏚️ [ArrayViews.jl](https://github.com/JuliaArrays/ArrayViews.jl) : A Julia package to explore a new system of array views. No longer necessary in Julia 0.4 or higher.
- 🏚️ [ArrayViewsAPL.jl](https://github.com/timholy/ArrayViewsAPL.jl) : Generic array-view type with APL indexing semantics.
- 🏚️ [Expokit.jl](https://github.com/acroy/Expokit.jl) : [EXPOKIT](http://www.maths.uq.edu.au/expokit) efficiently calculates the action of matrix exponentials on vectors for large sparse matrices.. (No `Project.toml`)
- 🏚️ [FArrayMod.jl](https://github.com/alsam/FArrayMod.jl) : provides the ability to use arbitrary starting indices for arrays in Julia programming language.
- 🏚️ [HMat.jl](https://github.com/YingzhouLi/HMat.jl) : Hierarchical Matrix.
- 🏚️ [InplaceOps.jl](https://github.com/simonbyrne/InplaceOps.jl) : Convenient macros for in-place matrix operations in Julia.
- 🏚️ [julia-delayed-matrix](https://github.com/kk49/julia-delayed-matrix) : Delayed processing of Vector / Matrix expression in Julia with various backends.
- 🏚️ [LargeColumns.jl](https://github.com/tpapp/LargeColumns.jl) : Handle large columns (vectors of equal length) with bits types in Julia using mmap.
- 🏚️ [Showoff.jl](https://github.com/dcjones/Showoff.jl) : Nicely format an array of n things for tables and plots.

#### Sparse Matrices

[📖 Sparse Matrices](https://en.wikipedia.org/wiki/Category:Sparse_matrices)

- [HarwellRutherfordBoeing.jl](https://github.com/JuliaSparse/HarwellRutherfordBoeing.jl) : A Julia Reader for the Harwell-Boeing and Rutherford-Boeing Formats.
- [InteractiveFixedEffectModels.jl](https://github.com/FixedEffects/InteractiveFixedEffectModels.jl) : Estimate factor models on sparse datasets.
- [MatrixMarket.jl](https://github.com/JuliaSparse/MatrixMarket.jl) : A package to read the [MatrixMarket file format](http://math.nist.gov/MatrixMarket/formats.html#MMformat).
- [Metis.jl](https://github.com/JuliaSparse/Metis.jl) : Julia interface to the [Metis](http://glaros.dtc.umn.edu/gkhome/metis/metis/overview) graph-partitioning algorithms.
- [MKLSparse.jl](https://github.com/JuliaSparse/MKLSparse.jl) : Override sparse-dense operations when MKL is available.
- [MUMPS.jl](https://github.com/JuliaInv/MUMPSjInv.jl) : An interface to [MUMPS](http://mumps.enseeiht.fr/) (a MUltifrontal Massively Parallel sparse direct Solver) to efficiently solve large and sparse linear systems in scientific computing.
- [Pardiso.jl](https://github.com/JuliaSparse/Pardiso.jl) : Calling the [PARDISO](https://www.pardiso-project.org) library from Julia.


- 🏚️ [CSparse.jl](https://github.com/dmbates/CSparse.jl) : A Julia implementation of functions in the CSparse and CXSparse libraries.
- 🏚️ [MultiFrontalCholesky.jl](https://github.com/JuliaSparse/MultiFrontalCholesky.jl) : The Cholesky decomposition of a Hermitian, positive-definite matrix into the product of a lower triangular matrix and its conjugate transpose, used for efficient numerical solutions and Monte Carlo simulations.
- 🏚️ [MUMPSseq.jl](https://github.com/JuliaSparse/MUMPSseq.jl) : Alternative Julia interface to MUMPS sparse system solver.
- 🏚️ [ParallelSparseMatMul.jl](https://github.com/madeleineudell/ParallelSparseMatMul.jl) : A Julia library for parallel sparse matrix multiplication using shared memory.
- 🏚️ [SparseData.jl](https://github.com/lindahua/SparseData.jl) : A Julia package to support working with sparse data sets (e.g. text corpus).
- 🏚️ [WSMP.jl](https://github.com/JuliaSparse/WSMP.jl) : Interface to the Watson Sparse Matrix Package.

### Matrix Resources

- Homer Reid's [Introduction to Numerical Analysis - Basic Numerical Programming in Julia](http://homerreid.dyndns.org/teaching/18.330/#ProblemSets) course.
- 2015Apr09 : [Video of Andreas Noack and Jiahao Chen](https://www.youtube.com/channel/UCizxnsw19qcTOdJdIJVtl0Q) speaking at the Linear Algebra and Optimization seminar at the Institute for Computational and Mathematical Engineering at Stanford.
- Learn the [theory of linear algebra](https://github.com/ULAFF/notebooks).
- [julia-paper-arrays](https://github.com/jiahao/julia-paper-arrays) : Julia position paper for [ARRAY '14](http://www.sable.mcgill.ca/array/).
- [Benchmarking Matrix Multiplication](http://nbviewer.ipython.org/url/math.mit.edu/~stevenj/18.335/Matrix-multiplication-experiments.ipynb)

## Digital signal processing (DSP)

[📖 DSP](https://en.wikipedia.org/wiki/Digital_signal_processing)

- [DSP.jl](https://github.com/JuliaDSP/DSP.jl) :Filter design, periodograms, window functions, and other digital signal processing functionality.
- [ImageMethodReverb.jl](https://github.com/nantonel/ImageMethodReverb.jl) : Julia implementation of a Room Acoustics Impulse Response Generator using the Randomized Image Method (RIM).
- [MDCT.jl](https://github.com/stevengj/MDCT.jl) : This module computes the modified discrete cosine transform (MDCT) in the Julia language and the inverse transform (IMDCT), using the fast type-IV discrete cosine tranform (DCT-IV) functions in Julia (via FFTW).
- [SortFilters.jl](https://github.com/sairus7/SortFilters.jl) : Fast moving quantile filters implemented as fast moving window sort algorithm. 


- 🏚️ [APES.jl](https://github.com/codles/APES.jl) : Amplitude and Phase Estimation of a Sinusoid.
- 🏚️ [ChaosCommunications.jl](https://github.com/papamarkou/ChaosCommunications.jl) : Simulation of chaos-based communication systems in Julia.
- 🏚️ [CompressedSensing](https://github.com/dahlend/CompressedSensing) : A basic compressed sensing algorithms available via the official package list with [documentation](http://compressedsensing.readthedocs.org/en/latest/).
- 🏚️ [Estimation.jl](https://github.com/JuliaDSP/Estimation.jl) : A julia package for DSP related estimation.
- 🏚️ [Fdtd.jl](https://github.com/nantonel/Fdtd.jl) : 3D Room Acoustics Finite Difference Time Domain (FDTD) Simulator.
- 🏚️ [KDSP.jl](https://github.com/kofron/KDSP.jl) : Yet another implementation of common DSP routines in Julia.
- 🏚️ [KernelRecursiveLeastSquares.jl](https://github.com/the-moliver/KernelRecursiveLeastSquares.jl) : Julia implementation of Kernel Recursive Least Squares algorithm.
- 🏚️ [Multirate.jl](https://github.com/JayKickliter/Multirate.jl) : Streaming polyphase DSP filters with sample rate conversion.
- 🏚️ [WDSP.jl](https://github.com/pjabardo/WDSP.jl) : Digital signal processing used in turbulence implemented in Julia.


### Fast Fourier transform (FFT)

[📖 FFT](https://en.wikipedia.org/wiki/Fast_Fourier_transform)

- [FFTViews.jl](https://github.com/JuliaArrays/FFTViews.jl) : Julia package for fast fourier transforms and periodic views.
- [FFTW.jl](https://github.com/JuliaMath/FFTW.jl) : Julia bindings to the FFTW library for fast Fourier transforms.
- [HexFFT.jl](https://github.com/gwater/HexFFT.jl) : Fast Fourier transform on hexagonal grids using Birdsong and Rummelt's [algorithm](http://ieeexplore.ieee.org/document/7532670/).
- [NFFT.jl](https://github.com/tknopp/NFFT.jl) : Julia implementation of the Non-equidistant Fast Fourier Transform (NFFT).


- 🏚️ [CLFFT.jl](https://github.com/JuliaGPU/CLFFT.jl) : Julia bindings for AMD's clFFT library.
- 🏚️ [CUFFT.jl](https://github.com/JuliaGPU/CUFFT.jl) : Wrapper for the CUDA FFT library.
- 🏚️ [SnFFT.jl](https://github.com/GDPlumb/SnFFT.jl) : A Julia package designed to facilitate harmonic analyis on the symmetric group of order n, denoted Sn.

## Symbolic Computation

See [Modeling | Symbolic Computation](modeling.md#symbolic-computation)

## Polynomials

[📖 Polynomials](https://en.wikipedia.org/wiki/Category:Polynomials)

- [ChebyshevApprox](https://github.com/RJDennis/ChebyshevApprox) : Julia code to approximate continuous functions using Chebyshev polynomials.
- [CoordinateSplittingPTrees.jl](https://github.com/timholy/CoordinateSplittingPTrees.jl) : Accurate and efficient full-degree multidimensional polynomial interpolation.
- [FastPolynomialRoots.jl](https://github.com/andreasnoack/FastPolynomialRoots.jl) : Fast and backward stable computation of roots of polynomials in Julia.
- [FixedPolynomials.jl](https://github.com/JuliaAlgebra/FixedPolynomials.jl) : A package for really fast evaluation of multivariate polynomials. (No `Porject.toml`)
- [Jacobi.jl](https://github.com/pjabardo/Jacobi.jl) : Jacobi polynomials and Gauss quadrature related functions.
- [MultiPoly.jl](https://github.com/daviddelaat/MultiPoly.jl) : Sparse multivariate polynomials in Julia. (No `Porject.toml`)
- [MultivariatePolynomials.jl](https://github.com/JuliaAlgebra/MultivariatePolynomials.jl) : Multivariate polynomials and multivariate moments.
- [Polynomial.jl](https://github.com/JuliaMath/Polynomials.jl) : Polynomial manipulations and [PolyExt.jl](https://gist.github.com/mathpup/8514578), an extension of Polynomial.jl to support polynomial division, with handy conversions and promotion rules.
- [PolynomialRoots.jl](https://github.com/giordano/PolynomialRoots.jl) : Fast complex polynomial root finder, with support for arbitrary precision calculations
- [Remez.jl](https://github.com/simonbyrne/Remez.jl) : [Remez algorithm](https://en.wikipedia.org/wiki/Remez_algorithm) for computing minimax polynomial approximations.
- [SemialgebraicSets.jl](https://github.com/JuliaAlgebra/SemialgebraicSets.jl) : Extension of MultivariatePolynomials to semialgebraic sets.
- [TaylorModels.jl](https://github.com/dpsanders/TaylorModels.jl) : A numerical mathematics package to treat the high-order scaling property of the remainder bound interval in a [Taylor polynomial](http://bt.pa.msu.edu/index_TaylorModels.htm).


- 🏚️ [InterPol.jl](https://github.com/pwl/InterPol.jl) : Interpolating polynomial for Julia.
- 🏚️ [Orthopolys.jl](https://github.com/daviddelaat/Orthopolys.jl) : Orthogonal Polynomials - Currently supports Jacobi polyonomials, Gegenbauer polynomials, Hermite polynomials.
- 🏚️ [TempInterp.jl](https://github.com/cc7768/TempInterp.jl) : Evaluation of Chebyshev polynomials and splines.

## Functions

[📖 Functions](http://en.wikipedia.org/wiki/Category:Types_of_functions)

> Evaluation and approximations of functions

- [ApproxFun.jl](https://github.com/JuliaApproximation/ApproxFun.jl) : Julia package for function approximation.
- [BasisFunctions.jl](https://github.com/daanhb/BasisFunctions.jl) : A collection of routines for working with a number of standard basis functions. For more complete software packages to manipulate numerical function approximations, please consider ApproxFun.
- [Elliptic.jl](https://github.com/nolta/Elliptic.jl) : Elliptic integral and Jacobi elliptic special functions.
- [FrameFun.jl](https://github.com/JuliaApproximation/FrameFun.jl) : Exploring practical possibilities of approximating functions with frames rather than with a basis.
- [LambertW.jl](https://github.com/jlapeyre/LambertW.jl) : A package implementing the Lambert_W function and associated omega constant.
- [SpecialFunctions.jl](https://github.com/JuliaMath/SpecialFunctions.jl) : Special mathematical functions in Julia.
- [Struve.jl](https://github.com/gwater/Struve.jl) : [Struve](https://dlmf.nist.gov/11) functions for Julia.
- 🏚️ [FastAnonymous.jl](https://github.com/timholy/FastAnonymous.jl) : Fast __anonymous functions__ for Julia. A native feature for Julia 0.5+.

## Calculus

**Packages**
- [Calculus.jl](https://github.com/JuliaMath/Calculus.jl) : Calculus package.
- [ChainRules.jl](https://github.com/JuliaDiff/ChainRules.jl) : forward and reverse mode automatic differentiation primitives.
- [Cuba.jl](https://github.com/giordano/Cuba.jl) : Library for multidimensional numerical integration with the [Cuba library](http://www.feynarts.de/cuba/).
- [Cubature.jl](https://github.com/JuliaMath/Cubature.jl) : One- and multi-dimensional adaptive integration routines for the Julia language.
- [DualNumbers.jl](https://github.com/JuliaDiff/DualNumbers.jl) : Julia package for representing dual numbers and for performing dual algebra.
- [FastGaussQuadrature.jl](https://github.com/JuliaApproximation/FastGaussQuadrature.jl) : Computes Gauss quadrature rules to 16-digit precision (so far Legendre, Jacobi, Lobatto, Radau).
- [FiniteDifferences.jl](https://github.com/JuliaDiff/FiniteDifferences.jl) : estimating derivatives with [finite differences](https://en.wikipedia.org/wiki/Finite_difference).
- [FiniteDiff.jl](https://github.com/JuliaDiff/FiniteDiff.jl) : Fast non-allocating calculations of gradients, Jacobians, and Hessians with sparsity support.
- [ForwardDiff.jl](https://github.com/JuliaDiff/ForwardDiff.jl) : Forward Mode Automatic Differentiation for Julia.
- [HCubature.jl](https://github.com/JuliaMath/HCubature.jl) : Pure-Julia multidimensional h-adaptive integration.
- [HyperDualNumbers.jl](https://github.com/JuliaDiff/HyperDualNumbers.jl) : Hyper-Dual Numbers for Exact Second-Derivative Calculations, is structured similar to the DualNumbers package, which aims for complete support for HyperDual types for numerical functions within Julia's Base. Currently, basic mathematical operations and trigonometric functions are supported.
- [ReverseDiff.jl](https://github.com/JuliaDiff/ReverseDiff.jl) : Reverse Mode Automatic Differentiation for Julia.
- [ReverseDiffSparse.jl](https://github.com/mlubin/ReverseDiffSparse.jl) : Hessian algorithmic differentiation to compute hessian sparsity pattern.
- [RiemannComplexNumbers.jl](https://github.com/scheinerman/RiemannComplexNumbers.jl) : The RiemannComplexNumbers module is an alternative Complex type for Julia (with a single complex infinity value).
- [Roots.jl](https://github.com/JuliaMath/Roots.jl) : Root finding functions for Julia.
- [TaylorSeries.jl](https://github.com/JuliaDiff/TaylorSeries.jl) : A julia package for Taylor expansions in one independent variable.
- [Yota.jl](https://github.com/dfdx/Yota.jl) : Reverse-mode automatic differentiation for static and dynamic graphs.



- 🏚️ [IFastSum.jl](https://github.com/J-Sarnoff/IFastSum.jl) : Accurate summation (Yuhang Zhao's iFastSum).
- 🏚️ [MINE.jl](https://github.com/zhmz90/MINE.jl) : Julia wrapper for Maximal Information-based Nonparametric Exploration (MIC and MINE family).
- 🏚️ [Options.jl](https://github.com/JuliaLang/Options.jl) : A framework for providing optional arguments to functions.
- 🏚️ [PowerSeries.jl](https://github.com/jwmerrill/PowerSeries.jl) : Truncated Power Series for Julia.
- 🏚️ [Quadrature.jl](https://github.com/kofron/Quadrature.jl) : Gauss quadrature in Base.
- 🏚️ [ReverseDiffOverload.jl](https://github.com/LaurenceA/ReverseDiffOverload.jl) : Reverse mode differentiation for pre-defined functions.
- 🏚️ [ReverseDiffSource.jl](https://github.com/JuliaDiff/ReverseDiffSource.jl) : Automated differentiation by reverse accumulation. [Documentation](http://reversediffsourcejl.readthedocs.org/en/master/index.html).
- 🏚️ [ReverseDiffTape.jl](https://github.com/fqiang/ReverseDiffTape.jl) : A Julia package for reverse mode differentiation on a tape.


**Resources**
- [Riemann Hypothesis book](http://wstein.org/rh/) with the [source code on github](https://github.com/williamstein/rh).
- [Calculus With Julia](https://github.com/CalculusWithJulia/CalculusWithJulia.github.io) : Introductory Calculus with the Julia Programming Language.
- An IJulia notebook showing [Taylor's method integration of the pendulum](http://nbviewer.ipython.org/gist/lbenet/616fa81f3c12c9cfcf97).

## Mathematical Analysis

[📖 Mathematical Analysis](https://en.wikipedia.org/wiki/Category:Mathematical_analysis)

- [Complementarity.jl](https://github.com/chkwon/Complementarity.jl) : This package provides a modeling and computational interface for solving Mixed Complementarity Problems (MCP), modeling by JuMP.jl and computing by PATHSolver.jl.
- [Fatou.jl](https://github.com/chakravala/Fatou.jl) : Fatou sets in Julia (Fractals, Newton basins, Mandelbrot).
- [PATHSolver.jl](https://github.com/chkwon/PATHSolver.jl) : Coverage StatusThis package provides a Julia wrapper of the PATH Solver for solving Mixed Complementarity Problems (MCP).
- [Wilkinson.jl](https://github.com/chakravala/Wilkinson.jl) : Toolkit for studying numerical analysis and floating point algebra round-off error in Julia.

## Discrete math

[📖 Discrete math](https://en.wikipedia.org/wiki/Category:Discrete_mathematics).
[📖 Combinatorics](https://en.wikipedia.org/wiki/Category:Combinatorics).

- [Collatz.jl](https://github.com/StefanKarpinski/Collatz.jl) : The [Collatz conjecture](https://en.wikipedia.org/wiki/Collatz_conjecture).
- [PermPlain.jl](https://github.com/jlapeyre/PermPlain.jl) : Permutations of integers.
- [Permutations.jl](https://github.com/scheinerman/Permutations.jl) : Permutations class for Julia.
- [SimplePosets.jl](https://github.com/scheinerman/SimplePosets.jl) : Simple partially ordered sets for Julia.
- [ZChop.jl](https://github.com/jlapeyre/ZChop.jl) : Replaces small numbers with zero.


- 🏚️ [Catalan.jl](https://github.com/andrioni/Catalan.jl) : a combinatorics library for Julia.
- 🏚️ [DiscreteInference.jl](https://github.com/lindahua/DiscreteInference.jl) : Viterbi algorithm.
- 🏚️ [IPPMath.jl](https://github.com/lindahua/IPPMath.jl) : A Julia package for vectorized math computation based on Intel IPP.
- 🏚️ [PrimeSieve.jl](https://github.com/jlapeyre/PrimeSieve.jl) : This package provides an interface to tables of primes and a sieve library.
- 🏚️ [RomanNumerals.jl](https://github.com/anthonyclays/RomanNumerals.jl) : Support for Roman numerals in Julia.
- 🏚️ [Shannon.jl](https://github.com/kzahedi/Shannon.jl) : Entropy, Mutual Information, KL-Divergence related to Shannon's information theory and functions to binarize data.
- 🏚️ [PermutationsA.jl](https://github.com/jlapeyre/PermutationsA.jl) by @jlapeyre : Permutation data types and methods.

### Graph Theory

See [Graph algorithms](graph.md#graph-algorithms) section.

## Puzzles

- [Chess.jl](https://github.com/romstad/Chess.jl) : Julia chess programming library.


- 🏚️ [PlayingCards.jl](https://github.com/DataWookie/PlayingCards.jl) : Package for simulating Playing Cards games in Julia.
- 🏚️ [Sudoku.jl](https://github.com/hayd/Sudoku.jl) by @hayd : A port of Peter Norvig's __Solving Every Sudoku Puzzle__ to Julia.
- 🏚️ [sudoku.jl](https://github.com/johnmyleswhite/sudoku.jl) by @johnmyleswhite : A simple Sudoku solver in Julia.
- 🏚️ [sudoku](https://github.com/Alexander-N/sudoku) by @Alexander-N : Reimplementing the Python version of Peter Norvig's Sudoku solver in Julia.
- 🏚️ [SudokuService](https://github.com/IainNZ/SudokuService) : Sudoku-as-a-service, powered by Julia, JuMP modelling, and CoinOR CBC integer programming solver.
- 🏚️ [Tetris.jl](https://github.com/djsegal/Tetris.jl) : Tetris.

### Resources

- [Project_Euler_Julia.ipynb](http://nbviewer.ipython.org/github/punkrockpolly/Playing-with-Julia/blob/master/Project_Euler_Julia.ipynb) : Solutions to [Project Euler](http://projecteuler.net) Problems, algorithm & math puzzles.
