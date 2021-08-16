# Concurrency and Parallel Computing in Julia

> HPC, Distributed Computing, Cloud computing, Cluster computing, Grid computing, Parallel computing, Hardware arch (ARM, CUDA, GPU, MIPS), Kernels

**Resources**

- [Julia manual for parallel computing](https://docs.julialang.org/en/v1/manual/parallel-computing/)
- [Org: Julia Parallel](https://github.com/JuliaParallel)
- [Org: Julia Folds](https://github.com/JuliaFolds)
- [Org: Julia Cloud](https://github.com/JuliaCloud)
- [Wikipedia: Concurrency](https://en.wikipedia.org/wiki/Concurrency_%28computer_science%29)
- [Wikipedia: Parallel Computing](https://en.wikipedia.org/wiki/Category:Parallel_computing)


## General Packages

- [Actors.jl](https://github.com/JuliaActors/Actors.jl) : [Actor Model](https://en.wikipedia.org/wiki/Actor_model).
- [FLoops.jl](https://github.com/JuliaFolds/FLoops.jl): provides a macro `@floop`. It can be used to generate a fast generic iteration over complex collections.
- [Folds.jl](https://github.com/JuliaFolds/Folds.jl) : A unified interface for sequential, threaded, and distributed fold.
- [TiledIteration.jl](https://github.com/JuliaArrays/TiledIteration.jl) : Julia package to facilitate writing mulithreaded, multidimensional, cache-efficient code.

---

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [Blocks.jl](https://github.com/JuliaParallel/Blocks.jl) : A framework to represent chunks of entities and parallel methods on them.
- 🏚️ [ScaLAPACK.jl](https://github.com/JuliaParallel/ScaLAPACK.jl) : Scalable Linear Algebra PACKage.

</details>

## APIs and bindings

- [ArrayFire.jl](https://github.com/JuliaComputing/ArrayFire.jl) : Julia Wrapper for the [ArrayFire](http://arrayfire.com/) library.
- [Elly.jl](https://github.com/JuliaParallel/Elly.jl) : [Hadoop](https://hadoop.apache.org/) HDFS and Yarn client.
- [Hwloc.jl](https://github.com/JuliaParallel/Hwloc.jl) : Wrapper to the [hwloc library](http://www.open-mpi.org/projects/hwloc/) to provide a portable abstraction (across OS, versions, architectures, ...) of the hierarchical topology of modern architectures, including NUMA memory nodes, sockets, shared caches, cores and simultaneous multithreading.
- [MPI.jl](https://github.com/JuliaParallel/MPI.jl) : [MPI](http://www.mpi-forum.org/) wrappers for Julia.
- [julia-slurm-example](https://github.com/magerton/julia-slurm-example) : Simple example scripts for running Julia on a SLURM.

---

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [HDFS.jl](https://github.com/JuliaParallel/HDFS.jl) : An interface wrapper over the Hadoop HDFS library that wraps the HDFS C library libhdfs and provides APIs similar to Julia Filesystem APIs which can be used for direct access to HDFS files.
- 🏚️ [OCCA.jl](https://github.com/ReidAtcheson/OCCA.jl) : Julia interface into [OCCA2](https://github.com/tcew/OCCA2) by @tcew, an extensible multi-threading programming API written in C++.
- 🏚️ [Slurm.jl](https://github.com/JuliaParallel/Slurm.jl) : Experimental Julia interface to `slurm.schedmd.com`.

</details>

## Cloud computing

- [AWS.jl](https://github.com/JuliaCloud/AWS.jl) : supports the EC2 and S3 API's, letting you start and stop EC2 instances dynamically.
- [AWSCore.jl](https://github.com/samoconnor/AWSCore.jl) : [Amazon Web Services](https://aws.amazon.com/) Core Functions and Types.
- [AWSS3.jl](https://github.com/samoconnor/AWSS3.jl) : AWS S3 Simple Storage Service interface for Julia.
- [GCloud.jl](https://github.com/spencerlyon2/GCloud.jl) : Tools for working with Google Compute engine via the cloud CLI.
- [GoogleCloud.jl](https://github.com/JuliaCloud/GoogleCloud.jl) : Google Cloud APIs for Julia.

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [CloudArray.jl](https://github.com/gsd-ufal/CloudArray.jl) : Easy big data programming in the cloud.

</details>

## Multi-Threading

- [KissThreading.jl](https://github.com/bkamins/KissThreading.jl) : Simple patterns supporting working with threads in Julia.
- [ThreadsX.jl](https://github.com/tkf/ThreadsX.jl) : Parallelized Base functions.

---

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [RawMutex.jl](https://github.com/vchuravy/RawMutex.jl) : A __MUT__ual __EX__clusion program object in Julia that allows multiple program threads to share the same resource, such as file access, but not simultaneously.
- 🏚️ [MT-Workloads](https://github.com/ranjanan/MT-Workloads) : Multi-threaded workloads in Julia.

</details>

## SIMD Computing

**Resources**

- [Wikipedia: SIMD Computing](https://en.wikipedia.org/wiki/Category:SIMD_computing).
- [Julia docs: `@simd`](https://docs.julialang.org/en/v1/base/base/#Base.SimdLoop.@simd) macro.

**Packages**

- [LoopVectorization.jl](https://github.com/JuliaSIMD/LoopVectorization.jl) : `@turbo` macro for vectorizing loops.
- [SIMD.jl](https://github.com/eschnett/SIMD.jl) : Explicit SIMD vector operations for Julia.

---

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [SIMDPirates.jl](https://github.com/chriselrod/SIMDPirates.jl) : A library for SIMD intrinsics. The code was stolen from SIMD.jl, whose authors and maintainers deserve credit for most of the good work here. Aside from pirating code, SIMDPirates also provides an @pirate macro that lets you imagine you're commiting type piracy
- 🏚️ [SIMDVectors.jl](https://github.com/KristofferC/SIMDVectors.jl) : An experimental package that uses the PR #15244 to create a stack allocated fixed size vector which supports SIMD operations and very similar in spirit to the SIMD.jl package.
- 🏚️ [Yeppp.jl](https://github.com/JuliaLang/Yeppp.jl) : A low level, high performance library for vectorized operations, elementwise operation on arrays.

</details>

## Multiprocessing and Distributed Computing

**Resources**

- [Wikipedia: Distributed Computing](https://en.wikipedia.org/wiki/Category:Distributed_computing) across multiple compute nodes.
- [Wikipedia: Job Scheduler](https://en.wikipedia.org/wiki/Job_scheduler)
- [Julia at scale](https://discourse.julialang.org/c/domain/parallel/34) topic on discourse.

**Packages**

- [ClusterManagers.jl](https://github.com/JuliaLang/ClusterManagers.jl) : Support for different clustering technologies.
- [Dagger.jl](https://github.com/JuliaParallel/Dagger.jl) : A framework for out-of-core and parallel computation and hierarchical Scheduling of DAG Structured Computations.
- [DistributedArrays.jl](https://github.com/JuliaParallel/DistributedArrays.jl) : A task persistency mechanism based on hash-graphs for Dispatcher.jl.
- [FunHPC.jl](https://github.com/eschnett/FunHPC.jl) : Functional High-Performance Computing - A high-level API for distributed computing, implemented on top of MPI. [Bitbucket](https://bitbucket.org/eschnett/funhpc.jl) mirror.
- [HPAT.jl](https://github.com/IntelLabs/HPAT.jl) : High Performance Analytics Toolkit (HPAT) is a Julia-based framework for big data analytics on clusters.
- [JuliaMPIMonteCarlo.jl](https://github.com/mcreel/JuliaMPIMonteCarlo.jl) : Illustrative examples using Julia and MPI to do Markov Chain Monte Carlo (MCMC) methods.
- [MessageUtils.jl](https://github.com/JuliaParallel/MessageUtils.jl) : A collection of utilities for messaging.
- [MPIArrays.jl](https://github.com/barche/MPIArrays.jl) : Distributed arrays based on MPI onesided communication.
- [Persist.jl](https://github.com/eschnett/Persist.jl) : The package Persist allows running jobs independent of the Julia shell.
- [Schedulers.jl](https://github.com/ChevronETC/Schedulers.jl) : It provides elastic and fault tolerant parallel map and parallel map reduce methods. The primary feature that distinguishes Schedulers parallel map method from Julia's `Distributed.pmap` is elasticity where the cluster is permitted to dynamically grow/shrink.
- [ParallelDataTransfer.jl](https://github.com/ChrisRackauckas/ParallelDataTransfer.jl) : A bunch of helper functions for transferring data between worker processes.

---

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [ChainedVectors.jl](https://github.com/tanmaykm/ChainedVectors.jl) : Few utility types over Julia Vector type.
- 🏚️ [ClusterDicts.jl](https://github.com/amitmurthy/ClusterDicts.jl) : Global and Distributed dictionaries for Julia.
- 🏚️ [Collectl.jl](https://github.com/ranjanan/Collectl.jl) : Plotting information from Collectl in julia.
- 🏚️ [Dispatcher.jl](https://github.com/invenia/Dispatcher.jl) : A framework for out-of-core and parallel computation and hierarchical Scheduling of DAG Structured Computations.
- 🏚️ [DispatcherCache.jl](https://github.com/zgornel/DispatcherCache.jl) : Tool for building and executing a computation graph given a series of dependent operations.
- 🏚️ [Dtree.jl](https://github.com/kpamnany/Dtree.jl) : Julia wrapper for a distributed dynamic scheduler for HPC applications.
- 🏚️ [Flume.jl](https://github.com/malmaud/Flume.jl) : A port of the Google Flume Data-Parallel Pipeline system.
- 🏚️ [HavenOnDemand.jl](https://github.com/richitmx/HavenOnDemand.jl) : Julia package to access HPE Haven OnDemand API.
- 🏚️ [hpcc.jl](https://github.com/jiahao/hpcc.jl) : Implementation of the HPC Challenge kernels in Julia.
- 🏚️ [IBFS.jl](https://github.com/eurika-kaiser/IBFS.jl) : Grid simulation solver.
- 🏚️ [LCJC.jl](https://github.com/amitmurthy/LCJC.jl) : Loosely Coupled Julia Clusters.
- 🏚️ [ParallelGLM.jl](https://github.com/dmbates/ParallelGLM.jl) : Parallel fitting of GLMs using SharedArrays.
- 🏚️ [PTools.jl](https://github.com/amitmurthy/PTools.jl) : A collection of utilities for parallel computing in Julia.
- 🏚️ [SGEArrays.jl](https://github.com/davidavdav/SGEArrays.jl) : SGEArray implements a simple iterator in Julia to efficiently handle Sun Grid Engine task arrays.

</details>

## GPU computing

[Wikipedia: GPGPU](https://en.wikipedia.org/wiki/General-purpose_computing_on_graphics_processing_units)

**Resources**

- Blog post on [Compiling Julia for NVIDIA GPUs](http://blog.maleadt.net/2015/01/15/julia-cuda/)
- Sample notebooks for: [GPU Julia](http://nbviewer.ipython.org/7436359), and [GPU Transpose](http://nbviewer.ipython.org/7436439).
- Blog post on [High-Performance GPU Computing](https://devblogs.nvidia.com/parallelforall/gpu-computing-julia-programming-language/#more-8555) in the Julia Programming Language.

**Packages**

- [CVortex.jl](https://github.com/hjabird/CVortex.jl) : Julia wrapper for [cvortex](https://github.com/hjabird/cvortex) GPU accelerated vortex filament and vortex particle methods.
- [CuCountMap.jl](https://github.com/xiaodaigh/CuCountMap.jl) : Fast `StatsBase.countmap` for small types on the GPU via `CUDA.jl`
- [CUDA.jl](https://github.com/JuliaGPU/CUDA.jl) : CUDA programming in Julia. [JuliaCon 2021 video](https://youtu.be/fw0R5G8pB0U)
- [FoldsCUDA.jl](https://github.com/JuliaFolds/FoldsCUDA.jl): provides Transducers.jl-compatible fold (reduce) implemented using `CUDA.jl`. This brings the transducers and reducing function combinators implemented in Transducers.jl to GPU. Furthermore, using FLoops.jl, you can write parallel for loops that run on GPU.

---

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [CLBLAS.jl](https://github.com/JuliaGPU/CLBLAS.jl) : CLBLAS integration for Julia.
- 🏚️ [CUBLAS.jl](https://github.com/JuliaGPU/CUBLAS.jl) : Julia interface to CUBLAS.
- 🏚️ [CUDAnative.jl](https://github.com/JuliaGPU/CUDAnative.jl) : Support for compiling and executing native Julia kernels on CUDA hardware.
- 🏚️ [CUDArt.jl](https://github.com/JuliaAttic/CUDArt.jl) : Wrapper for CUDA runtime API.
- 🏚️ [CUDNN.jl](https://github.com/JuliaAttic/CUDNN.jl) : Julia wrapper for the NVIDIA cuDNN GPU deep learning library.
- 🏚️ [CURAND.jl](https://github.com/JuliaAttic/CURAND.jl) : Wrapper for NVidia's cuRAND library.
- 🏚️ [GPU-benchmarking](https://github.com/ranjanan/GPU-benchmarking) : GPU benchmarking on Julia.
- 🏚️ [HSA.jl](https://github.com/JuliaGPU/HSA.jl) : Julia Bindings for the HSA Runtime.
- 🏚️ [julia-CuMatrix](https://github.com/stefan-k/julia-CuMatrix) : CUDA Matrix library.
- 🏚️ [julia-kernels](https://github.com/toivoh/julia-kernels) : A small suite of tools aimed at being able to write kernels in Julia, which could be executed on the CPU, or as GPU kernels.
- 🏚️ [MXNet.jl](https://github.com/dmlc/MXNet.jl) : The dmlc/mxnet Julia package that brings flexible and efficient GPU computing and state-of-art deep learning to Julia. `MXNet.jl` is a part of Apache [MXNet](https://github.com/apache/incubator-mxnet) project now.
- 🏚️ [OpenCL.jl](https://github.com/JuliaGPU/OpenCL.jl) : OpenCL 1.2 Julia bindings - a cross platform parallel computation API for programming parallel devices, with implementations from AMD, Nvidia, Intel, and others, similar in scope to PyOpenCL.
- 🏚️ [Titan.jl](https://github.com/malmaud/Titan.jl) : Write GPU kernels using pure Julia.
- 🏚️ [Transpiler.jl](https://github.com/SimonDanisch/Transpiler.jl) : Transpiling from Julia's typed AST to CUDA / OpenCL code.
- 🏚️ [UberSignals.jl](https://github.com/SimonDanisch/UberSignals.jl) : Concept for a fast event signal system, using JIT and GPU acceleration, loosely inspired by Reactive.jl.

</details>
