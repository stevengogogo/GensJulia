# Biology in Julia

> Bioinformatics, genomics, agriculture, food science, medicine, genetic engineering, etc...

- [BioJulia](https://biojulia.net/) organization
- [Julia Health](https://juliahealth.org) organizations

## Accessing databases

- [BioFetch.jl](https://github.com/BioJulia/BioFetch.jl) : Easily fetch biological sequences from online sources. Currently supports Entrez (NCBI) Nucleotide and Protein databases, as well as UniProt and Ensembl.
- [BioMedQuery.jl](https://github.com/JuliaHealth/BioMedQuery.jl) : Julia utilities to process and save results from BioMedical databases/APIs.
- [BioServices.jl](https://github.com/BioJulia/BioServices.jl) : Julia interface to APIs for various bio-related web services.
- [DailyMed.jl](https://github.com/wherrera10/DailyMed.jl) : Interface to the REST functions of the National Library of Medicine's DailyMed database.
- [PubChemCrawler.jl](https://github.com/JuliaHealth/PubChemCrawler.jl) : Utilities to programmatically query the PubChem database.
- [PubMedMiner.jl](https://github.com/JuliaHealth/PubMedMiner.jl) : Julia package for studying co-occurrences in PubMed articles.
- [RxNav.jl](https://github.com/wherrera10/RxNav.jl) : Julia interface to the National Library of Medicine's online pharmaceutical RxNav API.

## File I/O

- [BED.jl](https://github.com/BioJulia/BED.jl) : I/O and utilities for the BED file format.
- [DICOM.jl](https://github.com/JuliaHealth/DICOM.jl) : Julia package for reading and writing DICOM (Digital Imaging and Communications in Medicine) files.
- [FastaIO.jl](https://github.com/carlobaldassi/FastaIO.jl) : Utilities to read/write FASTA format files in Julia.
- [FASTX.jl](https://github.com/BioJulia/FASTX.jl) : Parse and process FASTA and FASTQ formatted files of biological sequences.
- [XAM.jl](https://github.com/BioJulia/XAM.jl) : Parse and process SAM and BAM formatted alignment map files.


## Bioinformatics and genomics

- [Ensemble.jl](https://github.com/farr/Ensemble.jl) : Stochastic samplers based on the "stretch move" for ensembles of walkers.
- [MIToS.jl](https://github.com/diegozea/MIToS.jl) : Mutual Information Tools for protein Sequence analysis in Julia.
- [MMTF.jl](https://github.com/BioJulia/MMTF.jl) : The Macromolecular Transmission Format (MMTF) is a new compact binary format to transmit and store biomolecular structures for fast 3D visualization and analysis.
- [NormalizeQuantiles.jl](https://github.com/oheil/NormalizeQuantiles.jl) : implements quantile normalization
- [PlmDCA](https://github.com/pagnani/PlmDCA) : Pseudo Likelihood Maximization for direct-coupling analysis of protein structure from many homologous amino-acid sequences.
- [SpeedDate.jl](https://github.com/vanOosterhoutLab/SpeedDate.jl) : A utility for rapidly estimating coalescence times between sequences.
- [XSim.jl](https://github.com/reworkhow/XSim.jl) : A fast and user-friendly tool to simulate sequence data and complicated pedigree structures.

---

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [BioArgParse.jl](https://github.com/Ward9250/BioArgParse.jl) : Extension to 'ArgParse.jl', enabling parsing of command line parameters to types in 'Bio.jl'.
- 🏚️ [BioFeatures.jl](https://github.com/nw11/BioFeatures.jl).
- 🏚️ [BismarkSummary.jl](https://github.com/nw11/BismarkSummary.jl) : Basic summary of multiple Bismark runs.
- 🏚️ [Circuitscape.jl](https://github.com/tanmaykm/Circuitscape.jl) : The Julia implementation of the [Circuitscape lib in Python](http://www.circuitscape.org/) that uses electronic circuit theory to solve problems in landscape ecology.
- 🏚️ [COSMIC.jl](https://github.com/haploxer/COSMIC.jl) : Data analysis engine for [COSMIC](http://cancer.sanger.ac.uk/cosmic) written in Julia.
- 🏚️ [Crispulator.jl](https://github.com/tlnagy/Crispulator.jl) : A discrete simulation tool for designing pooled genetic screens.
- 🏚️ [DynamicTimeWarp.jl](https://github.com/joefowler/DynamicTimeWarp.jl) : Implement Dynamic Time Warping for sequence alignment in Julia.
- 🏚️ [EMIRT.jl](https://github.com/seung-lab/EMIRT.jl) : Electron Microscopy Image Reconstruction Toolbox using julia language.
- 🏚️ [FusionDirect.jl](https://github.com/OpenGene/FusionDirect.jl) : Detect gene fusion directly from raw fastq files.
- 🏚️ [GenomeAnnotations.jl](https://github.com/nw11/GenomeAnnotations.jl) : Manage Local Genome Annotation files.
- 🏚️ [GenomicTiles.jl](https://github.com/nw11/GenomicTiles.jl)
- 🏚️ [gtf-parse-off](https://github.com/dcjones/gtf-parse-off) : Experiments with parsing gene transfer format (GTF).
- 🏚️ [HyperNEAT.jl](https://github.com/kzahedi/HyperNEAT.jl) : A generative encoding for evolving ANN based on the NeuroEvolution of Augmented Topologies (NEAT) algorithm for evolutionary computation.
- 🏚️ [MethylUtils.jl](https://github.com/nw11/MethylUtils.jl) : Tools for WGBS Methylation analysis.
- 🏚️ [OBC.jl](https://github.com/binarybana/OBC.jl) : Optimal Bayesian classification for RNA-Seq data.
- 🏚️ [OpenGene.jl](https://github.com/OpenGene/OpenGene.jl) : OpenGene core library in Julia.
- 🏚️ [Pagel.jl](https://github.com/porterjamesj/Pagel.jl) : Detect correlated evolution on phylogenies.
- 🏚️ [ProgressiveAligner.jl](https://github.com/latticetower/ProgressiveAligner.jl) : Progressive alignment scripts for protein sequences.
- 🏚️ [PseudoGenomes.jl](https://github.com/nw11/PseudoGenomes.jl) : Read alleles without a VCF parser.
- 🏚️ [PureSeq.jl](https://github.com/slundberg/PureSeq.jl) : Code for the Pure-seq project.
- 🏚️ [Rosalind.jl](https://github.com/PilgrimShadow/Rosalind.jl) : A bioinformatics library for solving problems from rosalind.info.
- 🏚️ [seqhax.jl](https://github.com/kdmurray91/seqhax.jl) : yet another NGS command.
- 🏚️ [smoothlife-jl](https://github.com/jamak/smoothlife-jl) : an implementation of the SmoothLife algorithm in Julia.
- 🏚️ [Subsequences.jl](https://github.com/WestleyArgentum/Subsequences.jl) : A package for finding longest common and longest contiguous subsequences.
- 🏚️ [taxize.jl](https://github.com/sckott/taxize.jl) : A taxonomic toolbelt for Julia.
- 🏚️ [TimeTrees.jl](https://github.com/tgvaughan/TimeTrees.jl) : Phylogenetic tree type for julia.
- 🏚️ [VariantCall.jl](https://github.com/mgvel/VariantCall.jl).
- 🏚️ [YARS.jl](https://github.com/kzahedi/YARS.jl) : YARS communication for RNA/proteins.

</details>

### BioJulia ecosystem

> Packages in the [BioJulia](https://biojulia.net/) organization.

- [BioAlignments.jl](https://github.com/BioJulia/BioAlignments.jl) :  Sequence alignment tools in BioJulia
- [BioSequences.jl](https://github.com/BioJulia/BioSequences.jl) : Biological sequences for the julia language.
- [BioStructures.jl](https://github.com/BioJulia/BioStructures.jl) : A Julia package to read, write and manipulate macromolecular structures (particularly proteins).
- [BioSymbols.jl](https://github.com/BioJulia/BioSymbols.jl) : Nucleic and amino acid primitive types.
- [BioTools.jl](https://github.com/BioJulia/BioTools.jl) : Interfaces to common external biological tools from julia scripts and programs (e.g. BLAST).
- [GeneticVariation.jl](https://github.com/BioJulia/GeneticVariation.jl) : types and methods for working with genetic variation.
- [GenomeGraphs.jl](https://github.com/BioJulia/GenomeGraphs.jl) :  A modern genomics framework for julia
- [GenomicFeatures.jl](https://github.com/BioJulia/GenomicFeatures.jl) : utilities for working with interval based genomic annotations.
- [IntervalTrees.jl](https://github.com/BioJulia/IntervalTrees.jl) : A data structure for efficient manipulation of sets of intervals.
- [KmerAnalysis.jl](https://github.com/BioJulia/KmerAnalysis.jl) :  Kmer counting algorithms and count-data utilities for the BioJulia framework.
- [Microbiome.jl](https://github.com/BioJulia/Microbiome.jl) : manipulating and analyzing microbiome and microbial community data.

### Phylogeny

Evolution trees deduced from biosequences. [Wikiedia: Phylogenetics](https://en.wikipedia.org/wiki/Phylogenetics).

- [Phylogenies.jl](https://github.com/BioJulia/Phylogenies.jl) : Phylogenetic trees and geneologies. (No `Project.toml`)
- [PhyloNetworks.jl](https://github.com/crsl4/PhyloNetworks.jl) : A Julia package for statistical inference, data manipulation and visualization of phylogenetic networks. The companion package for plotting is [PhyloPlots.jl](https://github.com/cecileane/PhyloPlots.jl)
- [PhyloTrees.jl](https://github.com/jangevaare/PhyloTrees.jl) : Phylogenetic tree simulation.

### Genomics

[Wikipedia: GWAS](https://en.wikipedia.org/wiki/Genome-wide_association_study)

- [JWAS.jl](https://github.com/reworkhow/JWAS.jl) : An open-source software tool written in Julia for Bayesian multiple regression methods applied to genome-wide association studies and genomic prediction.
- [MendelBase.jl](https://github.com/OpenMendel/MendelBase.jl) : contains the base functions of OpenMendel.
- [PopGen.jl](https://github.com/BioJulia/PopGen.jl) : Population Genetics in Julia.
- [SnpArrays.jl](https://github.com/OpenMendel/SnpArrays.jl) : provides utilities for handling compressed storage of biallelic SNP (Single-Nucleotide Polymorphism) data.

---

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [AlignmentStatistics.jl](https://github.com/DanielHoffmann32/AlignmentStatistics.jl) : A package for statistical analyses of sequence alignments.
- 🏚️ [StatGenData.jl](https://github.com/dmbates/StatGenData.jl) : Statistical analysis of genomic data.
- 🏚️ [VarianceComponentTest.jl](https://github.com/Tao-Hu/VarianceComponentTest.jl) : A Julia package for performing exact variance component tests in genome-wide association study (GWAS).

</details>

**Resources**

- [Wikipedia: list of RNA-Seq bioinformatics tools](http://en.wikipedia.org/wiki/List_of_RNA-Seq_bioinformatics_tools), not many of which are in Julia but depending on the language, they may have an API.
- [Data Analysis for Genomics](https://genomicsclass.github.io/book/) : using R but FYI.

## Metabolic networks

- [COBRA.jl](https://github.com/opencobra/COBRA.jl) : COnstraint-Based Reconstruction and Analysis, used to perform COBRA analyses such as Flux Balance Anlysis (FBA), Flux Variability Anlysis (FVA), or any of its associated variants such as `distributedFBA`.
- [COBREXA.jl](https://github.com/LCSB-BioCore/COBREXA.jl) : constraint-based reconstruction and analysis tools for exa-scale metabolic models in Julia. It uses [JuMP.jl](https://github.com/jump-dev/JuMP.jl) to formulate optimization problems.


## Healthcare

[Wikipedia: Biomedicine](https://en.wikipedia.org/wiki/Category:Biomedicine)

- [openBF](https://github.com/INSIGNEO/openBF) : A finite-volume solver for elastic arterial blood flow networks.

## BioStatistics

- [ROC.jl](https://github.com/diegozea/ROC.jl) : Receiver Operating Characteristic (ROC) Curve for Julia Language.

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [pedigree.jl](https://github.com/Rpedigree/pedigree.jl) : Pedigree extractors and representation as a Julia type with two integer members, sire and dam. A parent not in the pedigree is coded as 0.

</details>

## Molecular Biology

- [CellFishing.jl](https://github.com/bicycle1885/CellFishing.jl) : (cell finder via hashing) is a tool to find similar cells of query cells based on their transcriptome expression profiles, a.k.a. single-cell sequencing.

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [EvoDuplexes.jl](https://github.com/timbitz/EvoDuplexes.jl) : A Julia package to fold all local and long-range RNA duplexes.

</details>

## Microscopy and bioimages

[Wikipedia: Microscopy](https://en.wikipedia.org/wiki/Microscopy)

- [BioformatsLoader.jl](https://github.com/ahnlabb/BioformatsLoader.jl) : load images using bioformats  based on `JavaCall.jl`.
- [DeconvOptim.jl](https://github.com/roflmaostc/DeconvOptim.jl) : A multi-dimensional, high performance deconvolution framework written in Julia Lang for CPUs and GPUs. [JuliaCon 2021 video](https://youtu.be/FodpnOhccis)
- [FourierTools.jl](https://github.com/bionanoimaging/FourierTools.jl) : Tools for working with Fourier (Frequency ) space. [JuliaCon 2021 video](https://youtu.be/qYgJDb_Ko2E)
- [ImagineFormat.jl](https://github.com/timholy/ImagineFormat.jl) : Read [.imagine](http://dotwhat.net/file/extension/imagine/7604) light sheet microscopy file formats in Julia.
- [MicroscopyLabels.jl](https://github.com/tlnagy/MicroscopyLabels.jl) : Embed annotations in your microscopy images.
- [PSFs.jl](https://github.com/RainerHeintzmann/PSFs.jl) : Toolbox for calculating optical [PSFs](https://en.wikipedia.org/wiki/Point_spread_function).
- [View5D.jl](https://github.com/RainerHeintzmann/View5D.jl) : a Java-based viewer for up to 5-dimensional data.

## Neuroscience

[CodeNeuro](http://codeneuro.org/) : Bringing neuroscience and data science together.

- [BrainWave.jl](https://github.com/sam81/BrainWave.jl) : Julia functions to process electroencephalographic (EEG) recordings.
- [DCEMRI.jl](https://github.com/davidssmith/DCEMRI.jl) : A Fast, Validated Toolkit for Dynamic Contrast Enhanced MRI Analysis. A paper on the code is in press at [PeerJ](https://peerj.com/preprints/670/).
- [EEG.jl](https://github.com/codles/EEG.jl) : Process EEG files in Julia.
- [NeuroAnalysis.jl](https://github.com/babaq/NeuroAnalysis.jl) : Julia package for neural signal analysis.
- [NeuronBuilder](https://github.com/Dhruva2/NeuronBuilder) : Builds conductance based neural networks iteratively, from ion channels and synapses.
- [OpenEphysLoader.jl](https://github.com/galenlynch/OpenEphysLoader.jl) : A set of tools to load data written by the Open Ephys GUI.

---

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [NEAT.jl](https://github.com/Andy-P/NEAT.jl) : Julia implemention of NEAT (NeuroEvolution of Augmenting Topologies) algorithm.
- 🏚️ [SkullSegment.jl](https://github.com/simonster/SkullSegment.jl) : Macaque brain and skull extraction tools.
- 🏚️ [SpikeSorter.jl](https://github.com/grero/SpikeSorter.jl) : Spike sorting tool for experimental neuroscientists.

</details>

## Pharmacology

[Wikipedia: Pharmacology](https://en.wikipedia.org/wiki/Pharmacology)

See also [Pumas AI](https://github.com/PumasAI), the framework for Pharmaceutical Modeling and Simulation in Julia.

- [DataInterpolations.jl](https://github.com/PumasAI/DataInterpolations.jl) : A library of data interpolation and smoothing functions.
- [PumasTutorials.jl](https://github.com/PumasAI/PumasTutorials.jl) : Tutorials for pharmaceutical modeling and simulation with Pumas.jl. http://tutorials.pumas.ai

## Resources and Teaching

- [Python for biologists resources](https://docs.google.com/spreadsheets/d/1BjKsN0B1hqd4dJW5slZ5KPuToCjSMRyA7Bl8MwWrbS4/edit#gid=0) google document by Lenny Teytelman.
- [Software Carpentry](https://software-carpentry.org/lessons.html) teaching material.
- [Train online @ EMBL-EBI](https://www.ebi.ac.uk/training/on-demand) provides free courses on Europe's most widely used data resources, created by experts at EMBL-EBI and collaborating institutes.
- [TrainingPhyloIntro](https://github.com/aidanbudd/trainingPhyloIntro) : Practical exercises and slides for teaching computational molecular evolution.
- [capetown2014](https://github.com/aidanbudd/capetown2014) : Teaching material for EMBO Practical Course on Computational analysis of protein-protein interactions - From sequences to networks run in Cape Town 2014.
- [course_EMBO_at_TGAC_PPI_Sep2015](https://github.com/aidanbudd/course_EMBO_at_TGAC_PPI_Sep2015) : Program and some material for EMBO Practical Course on computational analysis of protein-protein interactions: From sequences to networks, taking place at TGAC, Norwich, UK, Sep-Oct 2015.
- Ian Quigley's (@mucociliary on twitter) notes on teaching [applied bioinformatics / compbio](http://daudin.icmb.utexas.edu/wiki/index.php/List_of_sessions).
- [Ubiquitous Genomics](http://ubiquitousgenomics.teamerlich.org) : COMSE6998/ Class 2015 by Prof. Yaniv Erlich. The [source is available on github](https://github.com/erlichya/ubiquitousgenomics).

