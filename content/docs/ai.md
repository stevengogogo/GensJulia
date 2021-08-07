# Artificial intelligence in Julia

> Artificial intelligence and machine learning

**Organization**

- [Julia ML](https://juliaml.github.io)
- [FluxML](https://github.com/FluxML/)

## Machine Learning and Neural Networks

> General machine learning frameworks and Neural Networks

- [BayesianNonparametrics.jl](https://github.com/OFAI/BayesianNonparametrics.jl) : Bayesian nonparametrics in Julia.
- [Boltzmann.jl](https://github.com/dfdx/Boltzmann.jl) : Restricted Boltzmann Machines and Deep Belief Networks in Julia
- [Clustering.jl](https://github.com/johnmyleswhite/Clustering.jl) : Basic functions for clustering data ==> k-means, dp-means, etc..
- [DecisionTree.jl](https://github.com/bensadeghi/DecisionTree.jl) : Julia implementation of Decision Tree (CART) and Random Forest algorithms.
- [Discretizers.jl](https://github.com/sisl/Discretizers.jl) : A package to support discretization methods and mapping functions for data discretization and label maps.
- [EasyML.jl](https://github.com/OML-NPA/EasyML.jl) : Using machine learning in Julia through a graphical user interface.
- [FastAI.jl][] : Repository of best practices for deep learning in Julia, inspired by [fastai](https://github.com/fastai/fastai). [Showcase](https://lorenzoh.github.io/posts/fastaijl_ecosystem.html)
- [Flux.jl](https://github.com/FluxML/Flux.jl) : A library for machine learning implemented in Julia. See also [Flux model-zoo](https://github.com/FluxML/model-zoo).
- [FluxTraining.jl](https://github.com/FluxML/FluxTraining.jl) : A powerful, extensible neural net training library. The training backend for [FastAI.jl][].
- [FunctionalDataUtils.jl](https://github.com/rened/FunctionalDataUtils.jl) : Utility functions for the FunctionalData package, mainly from the area of computer vision and machine learning.
- [GeometricFlux.jl](https://github.com/FluxML/GeometricFlux.jl) : Geometric Deep Learning for Flux.
- [KernelFunctions.jl](https://github.com/JuliaGaussianProcesses/KernelFunctions.jl) : Kernel functions for machine learning.
- [Knet.jl](https://github.com/denizyuret/Knet.jl) : Koç University deep learning framework - A machine learning module implemented in Julia. See also [KnetNLP](https://github.com/egeersu/KnetNLP) and [KnetOnnx.jl](https://github.com/egeersu/KnetOnnx.jl)
- [LearningStrategies.jl](https://github.com/JuliaML/LearningStrategies.jl) : A generic and modular framework for building custom iterative algorithms in Julia.
- [LossFunctions.jl](https://github.com/JuliaML/LossFunctions.jl) : Julia package of loss functions for machine learning. [Documentation](https://juliaml.github.io/LossFunctions.jl/stable)
- [Merlin.jl](https://github.com/hshindo/Merlin.jl) : Flexible Deep Learning Framework in Julia.
- [Mitosis.jl](https://github.com/mschauer/Mitosis.jl) : Automatic probabilistic programming for scientific machine learning and dynamical models.
- [MLDatasets.jl](https://github.com/JuliaML/MLDatasets.jl) : Utility package for accessing common Machine Learning datasets in Julia.
- [MLJ.jl](https://github.com/alan-turing-institute/MLJ.jl) : A Julia machine learning framework by The Alan Turing Institute
- [MLLabelUtils.jl](https://github.com/JuliaML/MLLabelUtils.jl) : Utility package for working with classification targets and label-encodings.
- [NetworkLearning.jl](https://github.com/zgornel/NetworkLearning.jl) : Baseline collective classification library.
- [NeuralVerification.jl](https://github.com/sisl/NeuralVerification.jl) : verifying whether a neural network satisfies certain input-output constraints. [JuliaCon 2021 ideo](https://youtu.be/jyC2fVmHcF8)
- [NMF.jl](https://github.com/JuliaStats/NMF.jl) : Non-negative matrix factorization (NMF).
- [ONNX.jl](https://github.com/FluxML/ONNX.jl) : Read ONNX graphs and load these models in Julia.
- [ParticleFilters.jl](https://github.com/JuliaPOMDP/ParticleFilters.jl) : Simple particle filter implementation in Julia - works with `POMDPs.jl` models or others.
- [PredictMD.jl](https://github.com/bcbi/PredictMD.jl) : Uniform interface for machine learning in Julia.
- [PrivateMultiplicativeWeights.jl](https://github.com/mrtzh/PrivateMultiplicativeWeights.jl) : Differentially private synthetic data.
- [SumProductNetworks.jl](https://github.com/trappmartin/SumProductNetworks.jl) : Sum-Product Networks (deep probabilistic networks) package in Julia.
- [TheDataMustFlow.jl](https://github.com/ExpandingMan/TheDataMustFlow.jl) : Julia tools for feeding tabular data into machine learning.
- [TopoChains.jl](https://github.com/irhum/TopoChains.jl) : A flexible data structure for multi-input multi-output models.
- [TSVD.jl](https://github.com/andreasnoack/TSVD.jl) : Truncated singular value decomposition with partial reorthogonalization.
- [ValueHistories.jl](https://github.com/JuliaML/ValueHistories.jl) : Utilities to efficiently track learning curves or other optimization information.

[FastAI.jl]: https://github.com/FluxML/FastAI.jl

---

<details>

<summary>🏚️ Might not work in the current version of Julia</summary>

- 🏗️ [SpectralClustering.jl](https://github.com/lucianolorenti/SpectralClustering.jl) : Spectral clustering algorithms written in Julia.
- 🏗️ [XLATools.jl](https://github.com/MikeInnes/XLATools.jl) : Provides access to XLA and the XRT runtime (in Tensorflow), including the ability to build and compile XLA computations using the IRTools format.
- 🏚️ [ANN.jl](https://github.com/EricChiang/ANN.jl) : Julia artificial neural networks
- 🏚️ [ayush1999 | Keras.jl](https://github.com/ayush1999/Keras.jl) : A package built atop Flux to directly load Keras(.py) models into `Flux.jl`.
- 🏚️ [BackpropNeuralNet.jl](https://github.com/compressed/BackpropNeuralNet.jl) : A neural network in Julia.
- 🏚️ [BNMF.jl](https://github.com/r9y9/BNMF.jl) : Gamma Process Non-negative Matrix Factorization (GaP-NMF).
- 🏚️ [ConfidenceWeighted.jl](https://github.com/chezou/ConfidenceWeighted.jl) : Confidence weighted, a machine learning algorithm.
- 🏚️ [Contingency.jl](https://github.com/svs14/Contingency.jl) : Assorted techniques for the purpose of enabling automated machine learning.
- 🏚️ [DAI.jl](https://github.com/binarybana/DAI.jl) : A julia binding to the C+- discrete approximate inference library for graphical models: libDAI.
- 🏚️ [DecisionTrees.jl](https://github.com/MikeInnes/DecisionTrees.jl) : {NotSupported}
- 🏚️ [EGR.jl](https://github.com/stefanks/EGR.jl) : The Stochastic Gradient (SG) algorithm for machine learning.
- 🏚️ [ELM.jl](https://github.com/lepisma/ELM.jl) : Extreme Learning Machines are a variant of Single-Hidden Layer Feedforward Networks (SLFNs) with a significant departure as their weights aren't iteratively tuned. This boosts the speed of neurals nets heavily.
- 🏚️ [EmpiricalRiskMinimization.jl](https://github.com/reesepathak/EmpiricalRiskMinimization.jl) : Empirical Risk Minimization (and modeling) in Julia.
- 🏚️ [KSVM.jl](https://github.com/Evizero/KSVM.jl) @ Evizero : Support Vector Machines in pure Julia.
- 🏚️ [FeatureSelection.jl](https://github.com/Evizero/FeatureSelection.jl) : Common measures and algorithms for feature selection.
- 🏚️ [Flimsy.jl](https://github.com/thomlake/Flimsy.jl) : Gradient based Machine Learning for Julia.
- 🏚️ [go.jl](https://github.com/dmrd/go.jl) : A deep learning based Go bot implemented in Julia.
- 🏚️ [GradientBoost.jl](https://github.com/svs14/GradientBoost.jl) : Gradient boosting framework for Julia.
- 🏚️ [hinton.jl](https://github.com/lepisma/hinton.jl) : Create hinton diagrams in Julia. Hinton diagrams are used to visualize weight matrices in neural networks.
- 🏚️ [HopfieldNets.jl](https://github.com/johnmyleswhite/HopfieldNets.jl) : Discrete and continuous Hopfield networks in Julia.
- 🏚️ [HSIC.jl](https://github.com/trappmartin/HSIC.jl) : Julia implementations of the Hilbert-Schmidt Independence Criterion (HSIC).
- 🏚️ [JuliaTakingFittingAPIsSeriously](https://github.com/JuliaTakingFittingAPIsSeriously) : proof of concept taking the APIs for statistics, machine learning and other infomatics.
- 🏚️ [JuML.jl](https://github.com/Statfactory/JuML.jl) : Machine Learning in Julia.
- 🏚️ [KaggleDigitRecognizer.jl](https://github.com/benhamner/KaggleDigitRecognizer.jl) : Kaggle's Digit Recognizer competition.
- 🏚️ [KDTrees.jl](https://github.com/KristofferC/KDTrees.jl) : KD Trees.
- 🏚️ [Kernels.jl](https://github.com/trthatcher/Kernels.jl) : Mercer kernels and Gramian matrix calculation/approximation functions used in kernel methods of machine learning.
- 🏚️ [kNN.jl](https://github.com/johnmyleswhite/kNN.jl) : The k-Nearest Neighbors algorithm in Julia.
- 🏚️ [Ladder.jl](https://github.com/mrtzh/Ladder.jl) : A reliable leaderboard algorithm for machine learning competitions.
- 🏚️ [Learn.jl](https://github.com/Rory-Finnegan/Learn.jl) : Base framework library for machine learning packages.
- 🏚️ [LearnBase.jl](https://github.com/Evizero/LearnBase.jl) : Abstractions for Julia Machine Learning Packages.
- 🏚️ [MachineLearning.jl](https://github.com/benhamner/MachineLearning.jl) : a Machine Learning library package that consolidates common machine learning algorithms written in pure Julia and presents a consistent API.
- 🏚️ [MLKernels.jl](https://github.com/trthatcher/MLKernels.jl) : Mercer kernels and Gramian matrix calculation/approximation.
- 🏚️ [Mocha.jl](https://github.com/pluskid/Mocha.jl) : A Deep Learning framework for Julia, inspired by the C+- Deep Learning framework Caffe.
- 🏚️ [MultiLabelNeuralNetwork.jl](https://github.com/jperla/MultiLabelNeuralNetwork.jl) : A simple feed-forward neural network for multi-label classification.
- 🏚️ [neural.jl](https://github.com/compressed/neural.jl) : is a Julia implementation of a neural network, based on Sergio Fierens Ruby version.
- 🏚️ [NeuralNets.jl](https://github.com/anj1/NeuralNets.jl) : Generic artificial neural networks in Julia.
- 🏚️ [neuralnetwork.jl](https://github.com/tomaskrehlik/neuralnetwork.jl) : an implementation of label neural network.
- 🏚️ [NeuralNetworks.jl](https://github.com/soumith/NeuralNetworks.jl) : Various functions for Neural Networks implemented in Julia.
- 🏚️ [Ollam.jl](https://github.com/mit-nlp/Ollam.jl) : OLLAM = Online Learning of Linear Adaptatable Models.
- 🏚️ [OnlineAI.jl](https://github.com/tbreloff/OnlineAI.jl) : Machine learning for sequential/streaming data.  {Usable: 3, Robust: 3, Active: 3}
- 🏚️ [Orchestra.jl](https://github.com/svs14/Orchestra.jl) : Heterogeneous ensemble learning package for the Julia programming language.
- 🏚️ [ProjectiveDictionaryPairLearning.jl](https://github.com/quxiaofeng/ProjectiveDictionaryPairLearning.jl) : Juia code for the paper S. Gu, L. Zhang, W. Zuo, and X. Feng, “Projective Dictionary Pair Learning for Pattern Classification,” In NIPS 2014.
- 🏚️ [QuickShiftClustering.jl](https://github.com/rened/QuickShiftClustering.jl) : Fast hierarchical medoid clustering
- 🏚️ [RecurrentNN.jl](https://github.com/Andy-P/RecurrentNN.jl) : Deep RNN and LSTM in Julia.
- 🏚️ [RegERMs.jl](https://github.com/BigCrunsh/RegERMs.jl) : A package implementing several machine learning algorithms in a regularised empirical risk minimisation framework (SVMs, LogReg, Linear Regression) in Julia.
- 🏚️ [remusao | KSVM.jl](https://github.com/remusao/KSVM.jl) : Kernel Support Vector Machine (SVM) written in Julia.
- 🏚️ [RNN.jl](https://github.com/kzahedi/RNN.jl) : Recurrent Neural Networks.
- 🏚️ [SALSA.jl](https://github.com/jumutc/SALSA.jl) : _S_oftware Lab for _A_dvanced Machine _L_earning and _S_tochastic _A_lgorithms is a native Julia implementation of the well known stochastic algorithms for linear and non-linear Support Vector Machines.
- 🏚️ [SFA.jl](https://github.com/makokal/SFA.jl) : Implementation of the standard SFA (Slow Feature Analysis) algorithm (both linear and non-linear signal expansion) in Julia.
- 🏚️ [SimpleML.jl](https://github.com/aviks/SimpleML.jl) : Textbook implementations of some Machine Learning Algorithms in Julia.
- 🏚️ [SimpleNets](https://github.com/rgehring/SimpleNets) : Simple neural nets implementions in Julia.
- 🏚️ [SoftConfidenceWeighted.jl](https://github.com/IshitaTakeshi/SoftConfidenceWeighted.jl) : Exact Soft Confidence-Weighted Learning.
- 🏚️ [StackedNets.jl](https://github.com/yarlett/StackedNets.jl) : A simple interface to _deep_ stacks of neural network units that can be trained using gradient descent over defined error measures.
- 🏚️ [Strada.jl](https://github.com/pcmoritz/Strada.jl) : A deep learning library for Julia based on Caffe.
- 🏚️ [SVMLightLoader.jl](https://github.com/IshitaTakeshi/SVMLightLoader.jl) : Loader of svmlight / liblinear format files.

</details>

### Julia interface for external libraries

- [Glmnet.jl](https://github.com/simonster/Glmnet.jl) : Julia wrapper for fitting Lasso/ElasticNet GLM models using a R package glmnet.
- [JuliaTorch](https://github.com/boathit/JuliaTorch) : Using PyTorch in Julia Language via PyCall.
- [LIBLINEAR.jl](https://github.com/innerlee/LIBLINEAR.jl) : Julia binding to [Liblinear](https://www.csie.ntu.edu.tw/~cjlin/liblinear/), a library for Large Linear Classification.
- [LIBSVM.jl](https://github.com/JuliaML/LIBSVM.jl) : Julia bindings for [LIBSVM](http://www.csie.ntu.edu.tw/~cjlin/libsvm/) C library.
- [MXNet.jl](https://github.com/dmlc/MXNet.jl) : Flexible and efficient deep learning in Julia. (*merged into [main MXNet repo](https://github.com/apache/incubator-mxnet)*)
- [ScikitLearn.jl](https://github.com/cstjean/ScikitLearn.jl) : Julia implementation of the scikit-learn API via `PyCall.jl`. [Cheatsheet](http://scikit-learn.org/stable/tutorial/machine_learning_map/).
- [XGBoost.jl](https://github.com/dmlc/XGBoost.jl) : a Julia interface of [XGBoost](https://github.com/dmlc/xgboost).

---

<details>

<summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [FANN.jl](https://github.com/gasagna/FANN.jl) : A Julia wrapper for the Fast Artificial Neural Network Library (FANN).
- 🏚️ [Keras.jl](https://github.com/invenia/Keras.jl) @ invenia: A julia wrapper for keras.io.
- 🏚️ [liblinear.jl](https://github.com/tuzzeg/liblinear.jl) @ tuzzeg : Liblinear binding to Julia.
- 🏚️ [TensorFlow.jl](https://github.com/malmaud/TensorFlow.jl) : A Julia wrapper for TensorFlow, the open source machine learning framework from Google.
- 🏚️ [MNIST.jl](https://github.com/johnmyleswhite/MNIST.jl) : Tools for working with the MNIST data set.

</details>

### Spiking neural network

[Wikipedia: Spiking neural network](https://en.wikipedia.org/wiki/Spiking_neural_network)

- [SpikeSynchrony.jl](https://github.com/Datseris/SpikeSynchrony.jl) : Measuring distances, synchrony and correlation between spike trains.
- [SpikingNeuralNetworks.jl](https://github.com/AStupidBear/SpikingNeuralNetworks.jl) : Julia Spiking Neural Network Simulator.
- [WaspNet.jl](https://github.com/leaflabs/WaspNet.jl) : fixed-time-step simulations of primarily spiking neural networks (SNNs).
- 🏚️ [SpikeNet.jl](https://github.com/damiendr/SpikeNet.jl) : A spiking neural network simulator written in Julia.

### Resources

- [CIML](https://github.com/hal3/ciml) : A Course in Machine Learning. This repository contains the source code for the CIML book (see http://ciml.info/) as well as any course materials that seem useful (slides, documents, labs, etc.).
- [deepframeworks](https://github.com/zer0n/deepframeworks) : An evaluation of Deep Learning Frameworks.
- [Examples from _Thoughtful Machine Learning_](https://github.com/thoughtfulml/examples).
- [Julia_Neural_Network](https://github.com/nwenzel/Julia_Neural_Network) : Basic Neural Network written in JuliaLang.
- [juliastreetview](https://github.com/evq/juliastreetview) : Updated sample code for the Kaggle Julia Street View Character Recognition Tutorial.
- [Machine Learning Algorithm Cheat Sheet](http://www.lauradhamilton.com/machine-learning-algorithm-cheat-sheet) by Laura D Hamilton.
- [machine-learning-cheat-sheet](https://github.com/soulmachine/machine-learning-cheat-sheet) : Classical equations and diagrams in machine learning by @soulmachine.
- [mlpnnets.jl](https://github.com/tautologico/learning/blob/master/nnets/mlp/julia/mlpnnets.jl) : Feed-forward MLP neural network implementation.
- [A Machine Learning](http://work.caltech.edu/telecourse.html#lectures) course by Prof. Yaser Abu-Mostafa with videos on Youtube.

## Reinforcement Learning (RL)

[Wikipedia: Reinforcement Learning](https://en.wikipedia.org/wiki/Reinforcement_learning)

- [ReinforcementLearning.jl](https://github.com/JuliaReinforcementLearning/ReinforcementLearning.jl) : A Reinforcement Learning package.

<details>

<summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [DeepQLearning.jl](https://github.com/Andy-P/DeepQLearning.jl) : An implementation of DeepMind's Deep Q Learning algorithm.
- 🏚️ [ReinforcementLearning.jl](https://github.com/benhamner/ReinforcementLearning.jl) by @benhamner : A Reinforcement Learning package.

</details>

## Natural language processing (NLP)

[Wikipedia: Natural language processing](https://en.wikipedia.org/wiki/Natural_language_processing)

**Organization**

- [JuliaText](https://github.com/JuliaText)

---

**Packages**

- [AdaGram.jl](https://github.com/sbos/AdaGram.jl) : Adaptive Skip-gram implementation in Julia.
- [BKTrees.jl](https://github.com/zgornel/BKTrees.jl) : Julia implementation of Burkhard-Keller trees.
- [ConceptnetNumberbatch.jl](https://github.com/zgornel/ConceptnetNumberbatch.jl) : Julia interface to [ConceptnetNumberbatch](https://github.com/commonsense/conceptnet-numberbatch).
- [CorpusLoaders.jl](https://github.com/JuliaText/CorpusLoaders.jl) : A variety of loaders for various NLP corpora.
- [DependencyTrees.jl](https://github.com/dellison/DependencyTrees.jl) : A package for dependency parsing.
- [GloVe.jl](https://github.com/domluna/GloVe.jl) : Implements Global Word Vectors.
- [Glowe.jl](https://github.com/zgornel/Glowe.jl) : Julia interface to Global Word Vectors.
- [Languages.jl](https://github.com/JuliaText/Languages.jl) : A package for working with human languages.
- [Levenshtein.jl](https://github.com/rawrgrr/Levenshtein.jl) : Levenshtein distance between two strings.
- [ParserCombinator.jl](https://github.com/andrewcooke/ParserCombinator.jl) : A parser combinator library.
- [StringAnalysis.jl](https://github.com/zgornel/StringAnalysis.jl) : A hard fork of the [TextAnalysis.jl][] package, designed to provide a richer, faster and orthogonal API.
- [TextAnalysis.jl][] : A Julia package for text analysis.
- [TopicModels.jl](https://github.com/slycoder/TopicModels.jl) : Topic models are Bayesian, hierarchical mixture models of discrete data.
- [Word2Vec.jl](https://github.com/JuliaText/Word2Vec.jl) : Julia interface to word2vec.
- [WordNet.jl](https://github.com/JuliaText/WordNet.jl) : A Julia package for Princeton's WordNet®.


---

<details>

<summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [Peter Norvig's spelling corrector ported to Julia](https://gist.github.com/kmsquire/7569843), is now a part of the [DataStructures.jl](https://github.com/JuliaLang/DataStructures.jl) package.
- 🏚️ [allen](https://github.com/ninjin/allen) : A syntacto-semantic natural language parser.
- 🏚️ [DPL.jl](https://github.com/quxiaofeng/DPL.jl) : Projective Dictionary Pair Learning - code for the paper S. Gu, L. Zhang, W. Zuo, and X. Feng, “Projective Dictionary Pair Learning for Pattern Classification,” In NIPS 20144. <https://sites.google.com/site/shuhanggu/home>
- 🏚️ [GoodTuring.jl](https://github.com/JoFrhwld/GoodTuring.jl) : A Julia implementation of Simple Good Turing smoothing, largely adapted from @maxbane.
- 🏚️ [KUparser.jl](https://github.com/denizyuret/KUparser.jl) : Dependency parsing with word vectors.
- 🏚️ [LTSV.jl](https://github.com/kshramt/LTSV.jl) : Labeled Tab Separated Values (LTSV) parser.
- 🏚️ [MeCab.jl](https://github.com/chezou/MeCab.jl) : Julia binding of Japanese morphological analyzer MeCab.
- 🏚️ [NGram.jl](https://github.com/remusao/NGram.jl) : Implement the NGram model.
- 🏚️ [Parsimonious.jl](https://github.com/gitfoxi/Parsimonious.jl) : A PEG parser generator.
- 🏚️ [PEGParser.jl](https://github.com/abeschneider/PEGParser.jl) : A PEG Parser for Julia with Packrat capabilties, inspired by pyparsing, parsimonious, boost:spirit, as well as several others.
- 🏚️ [PyLexYacc.jl](https://github.com/iamed2/PyLexYacc.jl) : An interface to Python Lex-Yacc package that uses reflection for most of its processing.
- 🏚️ [SimpleParser.jl](https://github.com/ordovician/SimpleParser.jl) : A very simple hackable parser and lexer for simple languages.
- 🏚️ [Stemmers.jl](https://github.com/tanmaykm/Stemmers.jl) : Interface for text stemmer implementations.
- 🏚️ [Sumup.jl](https://github.com/remusao/Sumup.jl) : Automatic multi-documents, multi-topics summarization based on topic extraction.
- 🏚️ [Text.jl](https://github.com/mit-nlp/Text.jl) : Numerous tools for text processing.
- 🏚️ [Treekenize.jl](https://github.com/o-jasper/Treekenize.jl) : Parser with beginners and enders and infix.

</details>

[TextAnalysis.jl]: https://github.com/JuliaText/TextAnalysis.jl

### English NLP

- [EnglishText.jl](https://github.com/TotalVerb/EnglishText.jl) : Utilities for English-language quirks in Julia.
- [Why.jl](https://github.com/TorkelE/Why.jl) : A simple function, `why()`, which gives randomly generated answers.

## Speech recognition

- [MFCC.jl](https://github.com/JuliaDSP/MFCC.jl) : Standard Mel Frequency Cepstral Coefficients feature extraction for speech analysis.
- [WORLD.jl](https://github.com/r9y9/WORLD.jl) : A Julia wrapper for WORLD - a high-quality speech analysis, modification and synthesis system.

---

<details>

<summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [MelGeneralizedCepstrums.jl](https://github.com/r9y9/MelGeneralizedCepstrums.jl) : It provides a `mel generalized cepstrum` analysis for spectrum envelope estimation, which includes linear predicition, mel-cepstrum, generalized cepstrum and mel-generalized cepstrum analysis for Julia.
- 🏚️ [SpeechBase.jl](https://github.com/r9y9/SpeechBase.jl).
- 🏚️ [SPTK.jl](https://github.com/r9y9/SPTK.jl) : A Julia wrapper for the Speech Signal Processing Toolkit (SPTK), based on the modified version of SPTK.
- 🏚️ [SynthesisFilters.jl](https://github.com/r9y9/SynthesisFilters.jl) : Speech Synthesis Filters.

</details>
