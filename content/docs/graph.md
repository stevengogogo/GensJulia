---
title: "Graph Theory"
weight: 120
---

# Graph Theory

> General graph data structures, algorithms [Wikipedia | Graph Theory](https://en.wikipedia.org/wiki/Graph_theory)

**Organizations**

- [Julia Graphs](https://github.com/JuliaGraphs)

## File I/O for Graphs

- [GraphIO.jl](https://github.com/JuliaGraphs/GraphIO.jl) : GraphIO provides support to [LightGraphs.jl][] for reading/writing graphs in various formats.
- [SNAPDatasets.jl](https://github.com/JuliaGraphs/SNAPDatasets.jl) : [LightGraphs.jl][]-formatted graph files taken from the [SNAP Datasets](https://snap.stanford.edu/data/index.html) collection.

## Graph data types

- [AbstractTrees.jl](https://github.com/JuliaCollections/AbstractTrees.jl) : Abstract julia interfaces for working with trees.
- [Arrowhead.jl](https://github.com/ivanslapnicar/Arrowhead.jl) : Arrowhead and Diagonal-plus-rank-one Eigenvalue Solvers.
- [LightGraphs.jl][] : An optimized simple graphs package designed for fast analysis using standard functions that seeks to mimic the functionality of established packages like NetworkX, but with better performance.
- [Seep.jl](https://github.com/mit-ll/Seep.jl) : It builds and evaluates computational flow graphs in julia.
- [SimpleGraphs.jl](https://github.com/scheinerman/SimpleGraphs.jl) : A module for working with simple graphs (no loops, no multiple edges, no directed edges).
- [LightGraphsExtras.jl](https://github.com/JuliaGraphs/LightGraphsExtras.jl) : Additional functionality for [LightGraphs.jl][].
- [MetaGraphs.jl](https://github.com/JuliaGraphs/MetaGraphs.jl) : [LightGraphs.jl][] graphs with arbitrary metadata.
- [Multigraphs.jl](https://github.com/QuantumBFS/Multigraphs.jl) : A multigraph extension of [LightGraphs.jl][].
- [SpecialGraphs.jl](https://github.com/JuliaGraphs/SpecialGraphs.jl) : Encoding special graph structures in types. ⚠️ Not registered.
- [SimpleWeightedGraphs.jl](https://github.com/JuliaGraphs/SimpleWeightedGraphs.jl) : Edge-Weighted Graphs for [LightGraphs.jl][].
- [SimpleValueGraphs.jl](https://github.com/simonschoelly/SimpleValueGraphs.jl) : A [LightGraphs.jl][] compatible package for graphs with multiple, homogeneous vertex, edge and graph metadata.
- [SimpleHypergraphs.jl](https://github.com/pszufe/SimpleHypergraphs.jl) : A simple hypergraphs package for the Julia programming language.

---

{{< details "🏚️ Might not work in the current version of Julia" >}}

- 🏚️ [BGraph.jl](https://github.com/adolgert/BGraph.jl) : An adjacency list that uses typed properties for vertices, edges, and graphs.
- 🏚️ [CompressedStacks.jl](https://github.com/Azzaare/CompressedStacks.jl)
- 🏚️ [DeepReshapes.jl](https://github.com/lmshk/DeepReshapes.jl) : Reshape arbitrarily nested structures of Tuples and Arrays in Julia.
- 🏚️ [EvolvingGraphs.jl](https://github.com/EtymoIO/EvolvingGraphs.jl) : Working with time-dependent networks in Julia.
- 🏚️ [FingerTrees.jl](https://github.com/mschauer/FingerTrees.jl) : A Finger Tree is a functional data structure that can give an amortized constant time access to the fingers (leaves) of the tree where the data is stored, while the internal nodes are labeled in some way as to provide the functionality of the particular data structure being implemented.
- 🏚️ [Graft.jl](https://github.com/pranavtbhat/Graft.jl) : Graft stores vertex and edge metadata in separate dataframes.
- 🏚️ [Lists.jl](https://github.com/adolgert/Lists.jl) : Singly linked list and doubly linked list for Julia.
- 🏚️ [PropertyGraph.jl](https://github.com/PhillP/PropertyGraph.jl) : A Julia package for constructing, creating and querying graph data structures.
- 🏚️ [PropertyGraphMongo.jl](https://github.com/PhillP/PropertyGraphMongo.jl) : A Mongo storage provider for the `PropertyGraph.jl` package.
- 🏚️ [RedBlackTrees.jl](https://github.com/pygy/RedBlackTrees.jl) : A red–black self-balancing binary search tree in Julia. REF: [http://en.wikipedia.org/wiki/Red_black_trees](http://en.wikipedia.org/wiki/Red_black_trees)
- 🏚️ [SpatialGraphs.jl](https://github.com/sawcordwell/SpatialGraphs.jl)
- 🏚️ [SumTrees.jl](https://github.com/iamed2/SumTrees.jl) : Binary tree where the nodes contain the sum of the left and right children.
- 🏚️ [Trie.jl](https://github.com/JuliaLang/Trie.jl) : Implementation of the trie data structure.

{{< /details >}}

[LightGraphs.jl]: https://github.com/JuliaGraphs/LightGraphs.jl

## Graph algorithms

- [CommunityDetection.jl](https://github.com/JuliaGraphs/CommunityDetection.jl) : Implements community detection for [LightGraphs.jl][].
- [Dendriform.jl](https://github.com/chakravala/Dendriform.jl) : Dendriform di-algebra algorithms to compute using Loday's arithmetic on groves of planar binary trees.
- [GraphDataFrameBridge.jl](https://github.com/JuliaGraphs/GraphDataFrameBridge.jl) : Tools for interoperability between DataFrame objects and LightGraphs and MetaGraphs objects.
- [LayeredLayouts.jl](https://github.com/oxinabox/LayeredLayouts.jl) : Layered Layout Algorithms for Directed Acyclic Graphs (DAGs).
- [MatrixNetworks.jl](https://github.com/nassarhuda/MatrixNetworks.jl) : Graph and Network algorithms.
- [NetworkLayout.jl](https://github.com/JuliaGraphs/NetworkLayout.jl) : Layout algorithms for graphs and trees in pure Julia.
- [RobustShortestPath.jl](https://github.com/chkwon/RobustShortestPath.jl) : Robust Shortest Path Finder.
- [LightGraphsFlows.jl](https://github.com/JuliaGraphs/LightGraphsFlows.jl) : [Flow algorithms](https://en.wikipedia.org/wiki/Maximum_flow_problem) on top of [LightGraphs.jl][]
- [LightGraphsMatching.jl](https://github.com/JuliaGraphs/LightGraphsMatching.jl) : Matching algorithms for [LightGraphs.jl][].
- [SuiteSparseGraphBLAS.jl](https://github.com/JuliaSparse/SuiteSparseGraphBLAS.jl) : Julia wrapper for SuiteSparse:GraphBLAS.

---

{{< details "🏚️ Might not work in the current version of Julia" >}}

- 🏚️ [bloom.jl](https://github.com/boydgreenfield/bloom.jl) : Bloom filter implementation in Julia.
- 🏚️ [Blox.jl](https://github.com/tbreloff/Blox.jl) : Views of concatenated AbstractArrays in Julia.
- 🏚️ [Brim.jl](https://github.com/PoisotLab/Brim.jl) : BRIM modularity - Various ways to optimize the modularity of bipartite networks using BRIM in Julia.
- 🏚️ [Flow.jl](https://github.com/MikeInnes/Flow.jl) : DataFlow programming for Julia.
- 🏚️ [GraphicalModels.jl](https://github.com/johnmyleswhite/GraphicalModels.jl) : Data structures and parsing tools for representing graphical models in Julia.
- 🏚️ [GraphLayout.jl](https://github.com/IainNZ/GraphLayout.jl) : Graph layout algorithms in pure Julia.
- 🏚️ [Graphs.jl](https://github.com/JuliaLang/Graphs.jl) : a package for working with graph types and algorithms in Julia.
- 🏚️ [InfoTheory.jl](https://github.com/robertfeldt/InfoTheory.jl) : Estimating information theoretic measures (entropy, mutual information etc) from data.
- 🏚️ [InvariantEnsembles.jl](https://github.com/dlfivefifty/InvariantEnsembles.jl) : Sample random unitary invariant ensembles.
- 🏚️ [L1DecisionTree.jl](https://github.com/neggert/L1DecisionTree.jl).
- 🏚️ [LiftedHierarchies.jl](https://github.com/joehuchette/LiftedHierarchies.jl) : Hierarchical relaxations for mixed-integer optimization (Lasserre, Sherali-Adams, etc.)
- 🏚️ [LightGraphsGraphBLAS.jl](https://github.com/abhinavmehndiratta/LightGraphsGraphBLAS.jl) : GraphBLAS backed graphs for [LightGraphs.jl][].
- 🏚️ [LSH.jl](https://github.com/Keno/LSH.jl) : Locality Sensitive Hashing functions.
- 🏚️ [MinimalPerfectHashes.jl](https://github.com/soundcloud/MinimalPerfectHashes.jl) : An implementation of minimal perfect hash function generation as described in Czech et. al. 1992. http://bit.ly/137iukS
- 🏚️ [Networks.jl](https://github.com/daviddelaat/Networks.jl) : A library for working with Graphs in Julia.
- 🏚️ [RandomForestBehaviors.jl](https://github.com/tawheeler/RandomForestBehaviors.jl) : Microscopic driving models based on random forests.
- 🏚️ [RepresentationTheory.jl](https://github.com/dlfivefifty/RepresentationTheory.jl) :  representation theory of the symmetric group.
- 🏚️ [rsk](https://github.com/JuliaX/rsk) : Code for exploring the Robinson–Schensted–Knuth correspondence.
- 🏚️ [SFrames.jl](https://github.com/malmaud/SFrames.jl) : Wrapper around the open-source components of Graphlab.
- 🏚️ [Sims.jl](https://github.com/tshort/Sims.jl) : Non-causal, equation-based modeling in Julia.
- 🏚️ [TSPSubgradient.jl](https://github.com/whilo/TSPSubgradient.jl) : A TSP approximation with the subgradient method.

{{< /details >}}

**Resources**

- [aleph_star](https://github.com/imagry/aleph_star) : Reinforcement learning with A* and a deep heuristic.
- [Wikipedia: Graphal gorithms](https://en.wikipedia.org/wiki/Category:Graph_algorithms)

## Visualizing Graphs

See also the [Visualizations](visualization.md) section.

- [GraphPlot.jl](https://github.com/afternone/GraphPlot.jl) : Graph visualization for Julia.
- [GraphRecipes.jl](https://github.com/JuliaPlots/GraphRecipes.jl) : Graph-related recipes to be used with Plots.jl.
- [VegaGraphs.jl](https://github.com/JuliaGraphs/VegaGraphs.jl) : Graph visualization with [Vega-Lite](https://github.com/queryverse/VegaLite.jl).

---

{{< details "🏚️ Might not work in the current version of Julia" >}}

- 🏚️ [GraphVisualize.jl](https://github.com/JuliaGraphs/GraphVisualize.jl) : Graph visualization with tight integration with `LightGraphs.jl` package.
- 🏚️ [GraphViz.jl](https://github.com/Keno/GraphViz.jl) : Julia bindings for the GraphViz library.

{{< /details >}}
