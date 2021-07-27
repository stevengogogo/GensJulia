# Data Structures and Algorithms in Julia

> General algorithms, data structures and data types for Julia

- [Awesome algorithms](https://github.com/tayllan/awesome-algorithms), a curated list of awesome places to learn and/or practice algorithms.
- [algo-book-julia](https://github.com/Alexander-N/algo-book-julia) : Snippets from Problem Solving with Algorithms and Data Structures in Julia.
- [study](https://github.com/codematician/study) : A study of interesting algorithms in Python.

## General Algorithms

- [CRC.jl](https://github.com/andrewcooke/CRC.jl) : a Julia module for calculating Cyclic Redundancy Checksums (CRCs).

---

- 🏚️ [ARules.jl](https://github.com/toddleo/ARules.jl) : Julia package for Association Rule Learning algorithms.
- 🏚️ [CRC32.jl](https://github.com/fhs/CRC32.jl) : 32-bit cyclic redundancy check (CRC-32) checksum implementation.
- 🏚️ [HClust.jl](https://github.com/davidavdav/HClust.jl) : Hierarchical Clustering for Julia, similar to R's hclust(), has now been merged into [Clustering.jl](https://github.com/JuliaStats/Clustering.jl)
- 🏚️ [LabelPropagation.jl](https://github.com/afternone/LabelPropagation.jl) : A fast, nearly linear time algorithm for detecting communtiy structure in networks.
- 🏚️ [RecSys.jl](https://github.com/abhijithch/RecSys.jl) : An implementation of the ALS-WR algorithm.
- 🏚️ [Codecs.jl](https://github.com/BioJulia/Codecs.jl) : Common data encoding algorithms.


## Pattern Matching

- [BlossomV.jl](https://github.com/mlewe/BlossomV.jl) : An interface for the Blossom V perfect matching algorithm.
- [Loess.jl](https://github.com/dcjones/Loess.jl) : is a loess implementation based on the fast kd-tree based approximation algorithm, a space-partitioning data structure for organizing points in a k-dimensional space.
- [Match.jl](https://github.com/kmsquire/Match.jl) : Advanced Pattern Matching for Julia.

---

- 🏚️ [AhoCorasick.jl](https://github.com/gilesc/AhoCorasick.jl) : Julia implementation of the Aho-Corasick algorithm for fast string searching.
- 🏚️ [JellyFish.jl](https://github.com/samuelcolvin/JellyFish.jl) : Port of the jellyfish string comparison library.
- 🏚️ [NearestNeighbors.jl](https://github.com/johnmyleswhite/NearestNeighbors.jl) : Data structures for nearest neighbor search.
- 🏚️ [PatternDispatch.jl](https://github.com/toivoh/PatternDispatch.jl) : Method dispatch based on pattern matching for Julia.
- 🏚️ [ReverseRegexes.jl](https://github.com/carlobaldassi/ReverseRegexes.jl) : Adds functionality to reverse-search strings with regexes

## Sorting

- [NaturalSort.jl](https://github.com/simonster/NaturalSort.jl) : Natural sort order.
- [SortingAlgorithms.jl](https://github.com/JuliaCollections/SortingAlgorithms.jl) : extra sorting algorithms extending Julia's sorting API.
- [SortingLab.jl](https://github.com/xiaodaigh/SortingLab.jl) : Experimental implementations of sorting algorithms.
- 🏚️ [SearchSortAlgos.jl](https://github.com/Dawny33/SearchSortAlgos.jl) : An API for common search and sort algorithms.

## NP-complete Problems

[📖 NP-complete](https://en.wikipedia.org/wiki/Category:NP-complete_problems) problems cannot be solved in polynomial time complexity and often have to be inexactly solved using heuristics.

- [TravelingSalesmanHeuristics.jl](https://github.com/evanfields/TravelingSalesmanHeuristics.jl) : Julia package for simple traveling salesman problem heuristics.

### Boolean satisfiability problem (SAT)

[📖 SAT](https://en.wikipedia.org/wiki/Satisfiability_modulo_theories) is a kind of NP-complete (NPC) problems.

- [PicoSAT.jl](https://github.com/jakebolewski/PicoSAT.jl) : Provides Julia bindings to the popular SAT solver [picosat](http://fmv.jku.at/picosat/) by Armin Biere. It is based off the Python pycosat and Go pigosat bindings written by Ilan Schnell and Willam Schwartz.
- 🏚️ [dReal.jl](https://github.com/zenna/dReal.jl) : Nonlinear SMT solving using dReal.
- 🏚️ [Z3.jl](https://github.com/zenna/Z3.jl) : This is a Julia interface to Z3 - a high performance theorem prover developed at Microsoft Research. Z3 can solve satisfiability modulo theory (SMT) problems.

## General Data structures and data types

- [DataStructures.jl](https://github.com/JuliaCollections/DataStructures.jl) : Julia implementation of Data structures.
- [FreeType.jl](https://github.com/JuliaGraphics/FreeType.jl) : Font FreeType 2 bindings API wrapper. See also [FreeTypeAbstraction.jl](https://github.com/JuliaGraphics/FreeTypeAbstraction.jl).
- [FunctionalCollections.jl](https://github.com/JuliaCollections/FunctionalCollections.jl) : Functional and and persistent data structures for Julia.
- [FunctionalData.jl](https://github.com/rened/FunctionalData.jl) : Functional, efficient data manipulation framework.
- [MUtils.jl](https://github.com/JuliaParallel/MessageUtils.jl) : A collection of utilities for messaging, `channels()`, `tspaces()`, `kvspaces()` etc.
- [ResultTypes.jl](https://github.com/iamed2/ResultTypes.jl) :  A Result type for Julia—it's like Nullables for Exceptions.
- [TypeSortedCollections.jl](https://github.com/tkoolen/TypeSortedCollections.jl) : It provides the TypeSortedCollection type, which can be used to store type-heterogeneous data in a way that allows operations on the data to be performed in a type-stable manner.

---

- 🏚️ [ASCIIByte.jl](https://github.com/Elin-/ASCIIByte.jl) : Julia package to deal with Characters of 8 bits.
- 🏚️ [DanaTypes.jl](https://github.com/DANA-Laboratory/DanaTypes.jl) : Types for continuous variables or parameters.
- 🏚️ [DictViews.jl](https://github.com/daviddelaat/DictViews.jl) : KeysView and ValuesView types for dynamic low-overhead views into the entries of dictionaries.
- 🏚️ [DotPlusInheritance.jl](https://github.com/DANA-Laboratory/DotPlusInheritance.jl) : Expression parser that simulates type inheritance.
- 🏚️ [jenks.jl](https://github.com/scw/jenks.jl)
- 🏚️ [julia-prettyshow](https://github.com/toivoh/julia-prettyshow) : A module to provide simple pretty printing facilities with base functionality for indentation etc, and a `pshow` (pretty show) implementation for julia ASTs.
- 🏚️ [MPFI.jl](https://github.com/andrioni/MPFI.jl) : A [MPFI](http://perso.ens-lyon.fr/nathalie.revol/software.html) wrapper for Julia.
- 🏚️ [RDF.jl](https://github.com/JuliaPackageMirrors/RDF.jl) : RDF package for working with RDF Graphs in Julia. Supports serialization as RDF N-Triples, RDF N-Quads and Turtle. [Julia package mirror](https://github.com/indiedotkim/RDF.jl)
- 🏚️ [ReTerms.jl](https://github.com/dmbates/ReTerms.jl) : Package providing abstract random-effects terms and specific types.
- 🏚️ [Sexpr.jl](https://github.com/vshesh/Sexpr.jl) : A program to port clojure-like [s-expression](https://en.wikipedia.org/wiki/S-expression) syntax to and from Julia.
- 🏚️ [TexExtensions.jl](https://github.com/Keno/TexExtensions.jl) : Tex Pretty printing of Julia Base types.


## Text / string data type

- [FixedSizeStrings.jl](https://github.com/JuliaComputing/FixedSizeStrings.jl) : A type for efficiently storing short strings of known size.
- [Format.jl](https://github.com/JuliaString/Format.jl) : This Julia package provides C and Python-style types and functions formatting support.
- [Formatting.jl](https://github.com/JuliaIO/Formatting.jl) : A Julia package to provide Python-like formatting support.
- [LaTeXStrings.jl](https://github.com/stevengj/LaTeXStrings.jl) : This is a small package to make it easier to type LaTeX equations in string literals in the Julia language.
- [ShortStrings.jl](https://github.com/JuliaString/ShortStrings.jl) : A fast and efficient string format implementation for storing strings of size less than 15 bytes.
- [StringDistances.jl](https://github.com/matthieugomez/StringDistances.jl) : String Distances in Julia.
- [StringLiterals.jl](https://github.com/JuliaString/StringLiterals.jl) : Implement improved string literals with Swift-style syntax for interpolation, hex, & unicode characters, plus C & Python style formatting and Unicode, HTML, LaTeX, and Emoji entities.
- [VersionParsing.jl](https://github.com/JuliaInterop/VersionParsing.jl) : flexible VersionNumber parsing in Julia.
- [WeakRefStrings.jl](https://github.com/JuliaData/WeakRefStrings.jl) : a minimal String type for Julia that allows for efficient string representation and transfer.

---

- 🏚️ [AutoFormat.jl](https://github.com/yulijia/AutoFormat.jl)
- 🏚️ [MonkeyString.jl](https://github.com/malmaud/MonkeyString.jl) : Fast string implementation inspired by SpiderMonkey.
- 🏚️ [MutableStrings.jl](https://github.com/tanmaykm/MutableStrings.jl) : Mutable string types for Julia.
- 🏚️ [StringInterpolation.jl](https://github.com/EricForgy/StringInterpolation.jl) : String interpolation for non-standard string literals.
- 🏚️ [Strings.jl](https://github.com/quinnj/Strings.jl) : Testing out a new String representation.
- 🏚️ [StringUtils.jl](https://github.com/ScottPJones/StringUtils.jl) : String utilities for Julia, Swift-like interpolation/quoting, better performing versions of string functions, etc.
- 🏚️ [TypeCheck.jl](https://github.com/astrieanna/TypeCheck.jl) : a type checker for Julia.
- 🏚️ [Typeclass.jl](https://github.com/jasonmorton/Typeclass.jl) : Prototype typeclasses for Julia.
- 🏚️ [TypeGraph.jl](https://github.com/johnmyleswhite/TypeGraph.jl) : Visualize the Julia type system.

## Graph data types

See [Graph Theory](graph.md#graph-data-types) section.

## Numeric data types

- [ArbFloats.jl](https://github.com/JuliaArbTypes/ArbFloats.jl) : extended precision *values* for arithmetic, elementary, and some special functions (25..500 digits).
- [ArbNumerics.jl](https://github.com/JeffreySarnoff/ArbNumerics.jl) : extended precision math, accurate and performant
- [BFloat16s.jl](https://github.com/JuliaMath/BFloat16s.jl) : This package defines the BFloat16 data type. The only currently available hardware implementation of this datatype are Google's Cloud TPUs. As such, this package is suitable to evaluate whether using TPUs would cause precision problems for any particular algorithm, even without access to TPU hardware. Note that this package is designed for functionality, not performance, so this package should be used for precision experiments only, not performance experiments.
- [BitIntegers.jl](https://github.com/rfourquet/BitIntegers.jl) : This package implements fixed-width integer types similar to standard builtin-ones like Int or UInt128.
- [ClosedIntervals.jl](https://github.com/scheinerman/ClosedIntervals.jl) : Closed intervals of the form [a,b].
- [CustomUnitRanges.jl](https://github.com/JuliaArrays/CustomUnitRanges.jl) : Package-specific AbstractUnitRange types for julia.
- [DecFP.jl](https://github.com/JuliaMath/DecFP.jl) : The package provides 32-bit, 64-bit, and 128-bit binary-encoded decimal floating-point types following the IEEE 754-2008, implemented as a wrapper around the (BSD-licensed) Intel Decimal Floating-Point Math Library.
- [Decimals.jl](https://github.com/JuliaMath/Decimals.jl) : Pure Julia decimal arithmetic library.
- [DoubleFloats.jl](https://github.com/JuliaMath/DoubleFloats.jl) : Math with 85- accurate bits.
- [FixedPointNumbers.jl](https://github.com/JuliaMath/FixedPointNumbers.jl) : This library exports fixed-point number types. A fixed-point number represents a fractional, or non-integral, number. In contrast with the more widely known floating-point numbers, fixed-point numbers have a fixed number of digits (bits) after the decimal (radix) point. They are effectively integers scaled by a constant factor.
- [Infinity.jl](https://github.com/cjdoris/Infinity.jl) : Representation of infinity in Julia.
- [Measurements.jl](https://github.com/JuliaPhysics/Measurements.jl) : Error propagation calculator and library. It supports real and complex numbers with uncertainty, arbitrary precision calculations, and operations with arrays.
- [MonteCarloMeasurements.jl](https://github.com/baggepinnen/MonteCarloMeasurements.jl) : Error propagation using Monte-Carlo simulation. Similar to Measurements.jl, but more accurate for highly nonlinear functions at the expense of longer execution time.
- [Measures.jl](https://github.com/JuliaGraphics/Measures.jl) : Unified measure and coordinates types.
- [Quaternions.jl](https://github.com/JuliaGeometry/Quaternions.jl) : Quaternions, octonions and dual-quaternions.
- [Quaternions.jl](https://github.com/peakbook/Quaternions.jl) : by @peakbook. Quaternion for Julia Language.
- [Ratios.jl](https://github.com/timholy/Ratios.jl) : Faster Rational-like types for Julia.
- [Unitful.jl](https://github.com/PainterQubits/Unitful.jl) : A Julia package for physical units.

---

- 🏚️ [ArbDecimals.jl](https://github.com/JuliaArbTypes/ArbDecimals.jl) : reliable and performant extended precision floating point math.
- 🏚️ [ArbFloats.jl](https://github.com/JuliaArbTypes/ArbFloats.jl) :  Arb available as an extended precision floating point context.
- 🏚️ [BigRationals.jl](https://github.com/andrioni/BigRationals.jl) : A BigRational package for Julia using GMP.
- 🏚️ [ChainedVectors.jl](https://github.com/tanmaykm/ChainedVectors.jl) : Few utility types over Julia Vector type.
- 🏚️ [DoubleDouble.jl](https://github.com/simonbyrne/DoubleDouble.jl) : A Julia package for performing extended-precision arithmetic using pairs of floating-point numbers.
- 🏚️ [FlexFloat.jl](https://github.com/J-Sarnoff/FlexFloat.jl) : Allows values to stretch in a way that preserves accuracy durring mathematical computations.
- 🏚️ [FloatFloats.jl](https://github.com/Jeffrey-Sarnoff/FloatFloats.jl).
- 🏚️ [FloatHigher.jl](https://github.com/J-Sarnoff/FloatHigher.jl) : accurate floating point math at extended precisions.
- 🏚️ [HigherPrecision.jl](https://github.com/saschatimme/HigherPrecision.jl) : HigherPrecision defines the subtypes of `AbstractFloat`, `DoubleFloat64`, a 128 bit number type with around 30 bits of precision, intended as a drop-in replacement for Float64 and BigFloat.
- 🏚️ [IEEEFloat16.jl](https://github.com/vchuravy/IEEEFloat16.jl)
- 🏚️ [Intervals.jl](https://github.com/andrioni/Intervals.jl) : A pure Julia reimplementation of MPFI, a multiple precision interval arithmetic library.
- 🏚️ [IntModN.jl](https://github.com/andrewcooke/IntModN.jl) : Ring(s) of Integers Modulo-N.
- 🏚️ [IntsWithInfinty.jl](https://github.com/Jeffrey-Sarnoff/IntsWithInfinty.jl) : Ints augmented with Infinity.
- 🏚️ [Scalar.jl](https://github.com/sabjohnso/Scalar.jl) : Scalar Types.
- 🏚️ [Units.jl](https://github.com/timholy/Units.jl) : Infrastructure for handling physical units for the Julia programming language. Use `Unitful.jl` instead.

### Array types

- [AbstractTensors.jl](https://github.com/chakravala/AbstractTensors.jl) : Tensor algebra abstract type interoperability with vector bundle parameter.
- [ArrayInterface.jl](https://github.com/JuliaArrays/ArrayInterface.jl) : Designs for new Base array interface primitives, used widely through scientific machine learning (SciML) and other organizations.
- [AxisArrays.jl](https://github.com/JuliaArrays/AxisArrays.jl) : Performant arrays where each dimension can have a named axis with values.
- [BandedMatrices.jl](https://github.com/JuliaMatrices/BandedMatrices.jl) : A Julia package for representing banded matrices.
- [BlockArrays.jl](https://github.com/JuliaArrays/BlockArrays.jl) : BlockArrays for Julia.
- [CategoricalArrays.jl](https://github.com/JuliaData/CategoricalArrays.jl) : Arrays for working with categorical data (both nominal and ordinal) in Julia.
- [ChunkedArrays.jl](https://github.com/ChrisRackauckas/ChunkedArrays.jl) : A package for increasing the performance of arrays generated iteratively.
- [ContinuumArrays.jl](https://github.com/JuliaApproximation/ContinuumArrays.jl) : A package for representing quasi arrays with continuous indices.
- [FastArrays.jl](https://github.com/eschnett/FastArrays.jl) : Multi-dimensional arrays with arbitrary upper and lower bounds that can be fixed at compile time.
- [IndirectArrays.jl](https://github.com/JuliaArrays/IndirectArrays.jl) : Julia implementation of indexed or "lookup" arrays.
- [InfiniteArrays.jl](https://github.com/JuliaArrays/InfiniteArrays.jl) : A Julia package for representing infinite-dimensional arrays.
- [LabelledArrays.jl](https://github.com/SciML/LabelledArrays.jl) : Arrays with a label for each element.
- [LazyArrays.jl](https://github.com/JuliaArrays/LazyArrays.jl) : Lazy arrays and linear algebra in Julia.
- [MappedArrays.jl](https://github.com/JuliaArrays/MappedArrays.jl) : Lazy in-place transformations of arrays.
- [MatrixDepot.jl](https://github.com/JuliaMatrices/MatrixDepot.jl) : An Extensible Test Matrix Collection for Julia. Documentation: http://matrixdepotjl.readthedocs.org/
- [NamedArrays.jl](https://github.com/davidavdav/NamedArrays.jl) : Julia type that implements a drop-in replacement of Array with named dimensions and Dict-type indexes.
- [NamedAxesArrays.jl](https://github.com/timholy/NamedAxesArrays.jl) : Performant arrays where each axis can be named.
- [OffsetArrays.jl](https://github.com/JuliaArrays/OffsetArrays.jl) : Fortran-like arrays with arbitrary, zero or negative starting indices for arrays in Julia. The main purpose of this package is to simplify translation from Fortran codes intensively using Fortran arrays with negative and zero starting indices, such as the codes accompanying the book Numerical Solution of Hyperbolic Partial Differential Equations by prof. John A. Trangenstein.
- [Pseudospectra.jl](https://github.com/RalphAS/Pseudospectra.jl) : a package for computing pseudospectra of non-symmetric matrices, and plotting them along with eigenvalues ("spectral portraits").
- [QuasiArrays.jl](https://github.com/JuliaApproximation/QuasiArrays.jl) : A package for representing quasi-arrays, viz. arrays with non-classical indexing, including possibly continuous indexing.
- [RandomMatrices.jl](https://github.com/JuliaMath/RandomMatrices.jl) : Random Matrices, extending the `Distributions` package to provide methods for working with matrix-valued random variables.
- [RangeArrays.jl](https://github.com/JuliaArrays/RangeArrays.jl) : Efficient and convenient array data structures where the columns of the arrays are generated (on the fly) by Ranges.
- [RecursiveArrayTools.jl](https://github.com/SciML/RecursiveArrayTools.jl) : Tools for easily handling nestings array objects like arrays of arrays.
- [ShiftedArrays.jl](https://github.com/JuliaArrays/ShiftedArrays.jl) : Lazy shifted arrays implementation for data analysis in Julia.
- [SpecialMatrices.jl](https://github.com/JuliaMatrices/SpecialMatrices.jl) : Julia package for working with special matrix types.
- [StaticArrays.jl](https://github.com/JuliaArrays/StaticArrays.jl) : Statically sized arrays for Julia.
- [StrideArrays.jl](https://github.com/chriselrod/StrideArrays.jl) : Library supporting the ArrayInterface.jl strided array interface.
- [StructArrays.jl](https://github.com/JuliaArrays/StructArrays.jl) : Efficient implementation of struct arrays.
- [SuffixArrays.jl](https://github.com/JuliaCollections/SuffixArrays.jl) : Native Julia suffix array implementation.
- [ToeplitzMatrices.jl](https://github.com/JuliaMatrices/ToeplitzMatrices.jl) : Fast matrix multiplication and division for Toeplitz matrices in Julia.
- [UniqueVectors.jl](https://github.com/garrison/UniqueVectors.jl) : Vectors of unique elements, with quick reverse lookups.
- [Vec.jl](https://github.com/sisl/Vec.jl) : Provides 2D and 3D vector types for vector operations. All types are immutable and are subtypes of `StaticArrays`.
- [WoodburyMatrices.jl](https://github.com/timholy/WoodburyMatrices.jl) : Library support for the [Woodbury matrix identity](http://en.wikipedia.org/wiki/Woodbury_matrix_identity).

---

- 🏚️ [FlexibleArrays.jl](https://github.com/eschnett/FlexibleArrays.jl) : Multi-dimensional arrays with arbitrary upper and lower bounds that can be fixed or flexible.
- 🏚️ [ImmutableArrays.jl](https://github.com/twadleigh/ImmutableArrays.jl) : Statically-sized immutable vectors and matrices.
- 🏚️ [JudyDicts.jl](https://github.com/tanmaykm/JudyDicts.jl) : Judy arrays are fast associative arrays with low memory usage.
- 🏚️ [NonuniformArray.jl](https://github.com/ReidAtcheson/NonuniformArray.jl) : This library handles the case of __array of arrays__ where each subarray may have different lengths - but enforces contiguity of data for ease of passing to outside linear algebra packages.
- 🏚️ [RandomBandedMatrices.jl](https://github.com/dlfivefifty/RandomBandedMatrices.jl).
- 🏚️ [Ranges.jl](https://github.com/JuliaArrays/Ranges.jl) : Array-like objects with compact storage for the Julia language. Merged in Julia `Base`.
- 🏚️ [RingArrays.jl](https://github.com/invenia/RingArrays.jl) : A sliding window over a huge array.
- 🏚️ [Series.jl](https://github.com/milktrader/Series.jl) : Series data structure in Julia.
- 🏚️ [SparseVectorMatrix.jl](https://github.com/pranavtbhat/SparseVectorMatrix.jl) : SparseMatrices as a vector of SparseVectors.
- 🏚️ [SparseVectors.jl](https://github.com/JuliaSparse/SparseVectors.jl) : A Julia package to support sparse vectors.
- 🏚️ [StructsOfArrays.jl](https://github.com/JuliaArrays/StructsOfArrays.jl) : Structures of Arrays that behave like Arrays of Structures.
- 🏚️ [TimeArrays.jl](https://github.com/milktrader/TimeArrays.jl) : A temporary repo exploring the union of SeriesPair arrays into multicolumn arrays with similar behavior.

## Composite Data Types

[📖 Composite Data Types](https://en.wikipedia.org/wiki/Category:Composite_data_types)

Also see `[Base.@kwdef](https://discourse.julialang.org/t/what-does-kwdef-do/51973)` for less boilerplate code in struct initialization.

- [Accessors.jl](https://github.com/JuliaObjects/Accessors.jl) : updating immutable data simple. It is the successor of `Setfield.jl`.
- [Bijections.jl](https://github.com/scheinerman/Bijections.jl) : Bijection datatype for Julia that blocks assigning the same value to two different keys.
- [DispatchedTuples.jl](https://github.com/charleskawczynski/DispatchedTuples.jl): `Dispatched Tuples` are like immutable dictionaries (so, they're technically more like NamedTuples) except that the keys are instances of types. Also, because DispatchedTuples are backed by tuples, they are GPU-friendly.
- [ExtractMacro.jl](https://github.com/carlobaldassi/ExtractMacro.jl) : Provides a convenience `@extract` macro to extract fields from composite types.
- [NamedTupleTools.jl](https://github.com/JeffreySarnoff/NamedTupleTools.jl) : utilities for working with NamedTuples.
- [Parameters.jl](https://github.com/mauro3/Parameters.jl) : Types with default field values, keyword constructors and (un-)pack macros.
- [Setfield.jl](https://github.com/jw3126/Setfield.jl) : Update deeply nested immutable structs.
- [SimpleTraits.jl](https://github.com/mauro3/SimpleTraits.jl) : Simple Traits for Julia
- [TypedDelegation.jl](https://github.com/JuliaArbTypes/TypedDelegation.jl) :  Use a Type's fields as operands for the type's operations and easily apply functions onto fields' values.
- [Unpack.jl](https://github.com/mauro3/UnPack.jl) : `@unpack` some or all of the fields of a type, and `@pack`, in the case of mutable datatypes.

---

- 🏚️ [AutoTypeParameters.jl](https://github.com/andrewcooke/AutoTypeParameters.jl) : A Julia library to reversibly encode any value so that it can be used as a type parameter.
- 🏚️ [DictWrappers.jl](https://github.com/iamed2/DictWrappers.jl) : Wrap any Julia composite type in an Associative interface.
- 🏚️ [EMLTranslator.jl](https://github.com/DANA-Laboratory/EMLTranslator.jl) : Adds Inheritance to julia composite type.
- 🏚️ [FixedSizeDictionaries.jl](https://github.com/SimonDanisch/FixedSizeDictionaries.jl) : Library which implements a fixed size variant of Dictionaries.
- 🏚️ [Modifyfield.jl](https://github.com/StephenVavasis/Modifyfield.jl) : It creates functions to modify immutable fields of a composite type inside a container.
- 🏚️ [Named.jl](https://github.com/HarlanH/Named.jl) : Julia named index and named vector types.
- 🏚️ [NamedTuples.jl](https://github.com/blackrock/NamedTuples.jl) : An implementation of named tuples to support both index and property based access, for example in the definition of a method or as the return value of a method. Merged into Base.
- 🏚️ [SimpleStructs.jl](https://github.com/pluskid/SimpleStructs.jl) : Easy to use struct definition with defaults and value constraints, as well as auto-defined user-friendly constructors.
- 🏚️ [Traits.jl](https://github.com/mauro3/Traits.jl) : Traits package contracts on a type or a tuple of types and allows dispatch to work with them.
- 🏚️ [TupleTypes.jl](https://github.com/mbauman/TupleTypes.jl) : A testbed for an API to access Tuple parameters.
- 🏚️ [TypeTree.jl](https://github.com/johnmyleswhite/TypeTree.jl) : source code and the interactive D3 visualization of a Julia type tree.
- OrderedCollections.jl(404) : OrderedDict and OrderedSet for Julia.
- 🏚️ [QuickStructs.jl](https://github.com/tbreloff/QuickStructs.jl) : Several data structures with goals of O(1) for important operations.
- 🏚️ [SymDict.jl](https://github.com/JuliaCloud/SymDict.jl) : Convenience functions for dictionaries with Symbol keys. (No `Project.toml`). You can use `Dict(pairs(nt))` instead.


## Resources

- [The State of the Type System | Jeff Bezanson](https://www.youtube.com/watch?v=Z2LtJUe1q8c) at JuliaCon 2017.
- [The Unreasonable Effectiveness of Multiple Dispatch | Stefan Karpinski](https://youtu.be/kc9HwsxE1OY)  at JuliaCon 2019.
- [A more thorough look at Julia's **double colon** syntax](http://nbviewer.ipython.org/github/tlycken/IJulia-Notebooks/blob/master/A%20more%20thorough%20look%20at%20Julia%27s%20%22double%20colon%22%20syntax.ipynb)
