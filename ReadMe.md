# Privacy-Preserving-Machine-Learning-Resources

## Content
- [About](#about)
- [Secure Machine Learning](#secure-machine-learning)
- [Secure Federated Learning](#secure-federated-learning)
- [MPC](#MPC)
- [Federated Learning](#federated-learning)
- [Privacy Leakages of ML/FL](#privacy-leakages-of-ml/fl)
- [Blogs](#blogs)
- [Libraries and Frameworks](#libraries-and-frameworks)

# About

This is a current list of resources related to the research and development of privacy-preserving machine learning.

# Secure Machine Learning
* [Machine Learning Classification over Encrypted Data, NDSS'14](https://eprint.iacr.org/2014/331.pdf)
* [Oblivious Multi-Party Machine Learning on Trusted Processors, USENIX SECURITY'16](https://www.usenix.org/conference/usenixsecurity16/technical-sessions/presentation/ohrimenko)
* [Prio: Private, Robust, and Scalable Computation of Aggregate Statistics, NSDI'17](https://www.usenix.org/conference/nsdi17/technical-sessions/presentation/corrigan-gibbs)
* [SecureML: A System for Scalable Privacy-Preserving Machine Learning, S&P'17](https://eprint.iacr.org/2017/396)
* [MiniONN: Oblivious Neural Network Predictions via MiniONN Transformations, CCS'17](https://acmccs.github.io/papers/p619-liuA.pdf)
* [Chameleon: A Hybrid Secure Computation Framework for Machine Learning Applications, AsiaCCS'17](https://eprint.iacr.org/2017/1164)
* [DeepSecure: Scalable Provably-Secure Deep Learning, DAC'17](https://arxiv.org/abs/1705.08963)
* [Secure Computation for Machine Learning With SPDZ, NIPS'18](https://arxiv.org/abs/1901.00329)
* [ABY3:a Mixed protocol Framework for Machine Learning, CCS'18](https://eprint.iacr.org/2018/403.pdf)
* [SecureNN: Efficient and Private Neural Network Training, PETS'18](https://eprint.iacr.org/2018/442.pdf)
* [Gazelle: A Low Latency Framework for Secure Neural Network Inference, USENIX SECURITY'18](https://arxiv.org/abs/1801.05507)
* [CHET: an optimizing compiler for fully-homomorphic neural-network inferencing, PLDI'19](https://dl.acm.org/citation.cfm?id=3314628)
* [New Primitives for Actively-Secure MPC over Rings with Applications to Private Machine Learning, S&P'19](https://eprint.iacr.org/2019/599.pdf)
* [FLASH: Fast and Robust Framework for Privacy-preserving Machine Learning, PETS'19](https://eprint.iacr.org/2019/1365)
* [Helen: Maliciously Secure Coopetitive Learning for Linear Models, S&P'19](https://ieeexplore.ieee.org/abstract/document/8835215)
* [Efficient multi-key homomorphic encryption with packed ciphertexts with application to oblivious neural network inference. CCS'19](https://dl.acm.org/citation.cfm?id=3363207)
* [QUOTIENT: two-party secure neural network training and prediction, CCS'19](https://dl.acm.org/citation.cfm?id=3339819)
* [ASTRA: High Throughput 3PC over Rings with Application to Secure Prediction, CCSW'19](https://eprint.iacr.org/2019/429)
* [Trident: Efficient 4PC Framework for Privacy Preserving Machine Learning, NDSS'20](https://eprint.iacr.org/2019/1315)
* [BLAZE: Blazing Fast Privacy-Preserving Machine Learning, NDSS'20](https://eprint.iacr.org/2020/042)
* [Delphi: A Cryptographic Inference Service for Neural Networks, USENIX SECURITY'20](https://eprint.iacr.org/2020/050)
* [FALCON: Honest-Majority Maliciously Secure Framework for Private Deep Learning](https://arxiv.org/abs/2004.02229)
* [MP2ML: A Mixed-Protocol Machine Learning Framework for Private Inference, ARES'20](https://dl.acm.org/doi/abs/10.1145/3407023.3407045)
* [SANNS: Scaling Up Secure Approximate k-Nearest Neighbors Search, USENIX Security'20](https://www.usenix.org/conference/usenixsecurity20/presentation/chen-hao)
* [PySyft: A Generic Framework for Privacy Preserving Deep Learning](https://arxiv.org/abs/1811.04017)
* [Private Deep Learning in TensorFlow Using Secure Computation](https://arxiv.org/abs/1810.08130)
* [CryptoDL: Deep Neural Networks over Encrypted Data](https://arxiv.org/abs/1711.05189)
* [CryptoNets: Applying Neural Networks to Encrypted Data with High Throughput and Accuracy](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/04/CryptonetsTechReport.pdf)
* [CrypTFlow: Secure TensorFlow Inference](https://eprint.iacr.org/2019/1049.pdf)
* [CrypTFlow2: Practical 2-Party Secure Inference, CCS'20](https://arxiv.org/abs/2010.06457)
* [ARIANN: Low-Interaction Privacy-Preserving Deep Learning via Function Secret Sharing](https://arxiv.org/abs/2006.04593)
* [Practical Privacy-Preserving K-means Clustering, PETS'20](https://content.sciendo.com/view/journals/popets/2020/4/article-p414.xml)
* [ABY2.0: Improved Mixed-Protocol Secure Two-Party Computation (Full Version), USENIX Security'21](https://eprint.iacr.org/2020/1225.pdf)
* [Secure Evaluation of Quantized Neural Networks, PETS'20](https://content.sciendo.com/view/journals/popets/2020/4/article-p355.xml)
* [SWIFT: Super-fast and Robust Privacy-Preserving Machine Learning](https://arxiv.org/abs/2005.10296)
* [An Efficient 3-Party Framework for Privacy-Preserving Neural Network Inference, ESORICS'20](https://link.springer.com/chapter/10.1007/978-3-030-58951-6_21)

# Secure Federated Learning
* [Privacy-Preserving Deep Learning, CCS'15](https://dl.acm.org/citation.cfm?id=2813687)
* [Practical Secure Aggregation for Privacy Preserving Machine Learning, CCS'17](https://eprint.iacr.org/2017/281.pdf)
* [Privacy-Preserving Deep Learning via Additively Homomorphic Encryption, TIFS'17](https://ieeexplore.ieee.org/document/8241854)
* [NIKE-based Fast Privacy-preserving High-dimensional Data Aggregation for Mobile Devices, CACR'18](http://cacr.uwaterloo.ca/techreports/2018/cacr2018-10.pdf)
* [PrivFL: Practical Privacy-preserving Federated Regressions on High-dimensional Data over Mobile Networks, CCSW'19](https://eprint.iacr.org/2019/979.pdf)
* [VerifyNet: Secure and verifiable federated learning, TIFS'19](https://ieeexplore.ieee.org/abstract/document/8765347)
* [PrivColl: Practical Privacy-Preserving Collaborative Machine Learning](https://link.springer.com/chapter/10.1007/978-3-030-58951-6_20)
* [NPMML: A Framework for Non-interactive Privacy-preserving Multi-party Machine Learning, TDSC'20](https://ieeexplore.ieee.org/abstract/document/8981947)
* [SAFER: Sparse secure Aggregation for FEderated leaRning](https://arxiv.org/abs/2007.14861)
* [Secure Byzantine-Robust Machine Learning](https://arxiv.org/abs/2006.04747)
* [Secure Single-Server Aggregation with (Poly)Logarithmic Overhead, CCS'20](https://eprint.iacr.org/2020/704.pdf)
* [Batchcrypt: Efficient homomorphic encryption for cross-silo federated learning, USENIX ATC'21](https://www.usenix.org/conference/atc20/presentation/zhang-chengliang)
* [FedSel: Federated SGD under Local Differential Privacy with Top-k Dimension Selection, DASFAA'20](https://arxiv.org/abs/2003.10637)

# MPC
* [Multiparty computation from somewhat homomorphic encryption, Crypto'12](https://link.springer.com/chapter/10.1007/978-3-642-32009-5_38)
* [Practical covertly secure MPC for dishonest majority–or: breaking the SPDZ limits, ESORICS'13](https://link.springer.com/chapter/10.1007/978-3-642-40203-6_1)
* [MASCOT: faster malicious arithmetic secure computation with oblivious transfer, CCS'16](https://dl.acm.org/citation.cfm?id=2978357)
* [SPDZ^2k: Efficient MPC mod 2^k for Dishonest Majority, Crypto'18](https://link.springer.com/chapter/10.1007/978-3-319-96881-0_26)
* [Overdrive^2k: Making SPDZ Great Again](https://eprint.iacr.org/2017/1230)
* [High-Throughput Semi-Honest Secure Three-Party Computation with an Honest Majority, CCS'16](https://dl.acm.org/citation.cfm?id=2978331)
* [Sharemind: A framework for fast privacy-preserving computations, ESORICS'08](https://link.springer.com/chapter/10.1007/978-3-540-88313-5_13)
* [Efficiently Verifiable Computation on Encrypted Data, CCS'14](https://dl.acm.org/citation.cfm?id=2660366)
* [PrivPy: General and Scalable Privacy-Preserving Data Mining, KDD'19](https://dl.acm.org/doi/abs/10.1145/3292500.3330920)

# Federated Learning
## Communication Optimization
* [Terngrad: Ternary gradients to reduce communication in distributed deep learning, NIPS'17](http://papers.nips.cc/paper/6749-terngrad-ternary-gradients-to-reduce-communication-in-distributed-deep-learning)
* [The Convergence of Sparsified Gradient Methods, NIPS'18](https://papers.nips.cc/paper/2018/hash/314450613369e0ee72d0da7f6fee773c-Abstract.html)
## Byzantine-Tolerant
* [Machine Learning with Adversaries: Byzantine Tolerant Gradient Descent, NIPS'17](http://papers.nips.cc/paper/6617-machine-learning-with-adversaries-byzantine-tolerant-gradient-descent)
* [Byzantine stochastic gradient descent, NIPS'18](https://papers.nips.cc/paper/2018/file/a07c2f3b3b907aaf8436a26c6d77f0a2-Paper.pdf)
* [The Hidden Vulnerability of Distributed Learning in Byzantium, ICML'18](https://arxiv.org/abs/1802.07927)
* [Byzantine-Robust Distributed Learning: Towards Optimal Statistical Rates, ICML'18](https://arxiv.org/abs/1803.01498)

# Privacy Leakages of ML/FL
* [Membership inference attacks against machine learning models, S&P'17](https://ieeexplore.ieee.org/abstract/document/7958568)
* [Comprehensive privacy analysis of deep learning: Passive and active white-box inference attacks against centralized and federated learning, S&P'19](https://ieeexplore.ieee.org/abstract/document/8835245)
* [Data Poisoning Attacks Against Federated Learning Systems, ESORICS'20](https://link.springer.com/chapter/10.1007/978-3-030-58951-6_24)
* [A Framework for Evaluating Client Privacy Leakages in Federated Learning, ESORICS'20](https://link.springer.com/chapter/10.1007/978-3-030-58951-6_27)

# Blogs
* [Cryptography and Machine Learning: Mixing both for private data analysis](https://mortendahl.github.io/)
* [Building Safe A.I.: A Tutorial for Encrypted Deep Learning](https://iamtrask.github.io/2017/03/17/safe-ai/)
* [Awesome MPC: Curated List of resources for MPC](https://github.com/rdragos/awesome-mpc)
* [机器学习隐私保护](https://www.zhihu.com/column/c_1121838720017338368)

# Libraries and Frameworks
* [TinyGarble: Logic Synthesis and Sequential Descriptions for Yao's Garbled Circuits](https://github.com/esonghori/TinyGarble)
* [SPDZ-2: Multiparty computation with SPDZ, MASCOT, and Overdrive offline phases](https://github.com/bristolcrypto/SPDZ-2)
* [ABY: A Framework for Efficient Mixed-Protocol Secure Two-Party Computation](https://github.com/encryptogroup/aby)
* [Obliv - C: C compiler for embedding privacy preserving protocols:](http://oblivc.org/)
* [TFHE: Fast Fully Homomorphic Encryption Library over the Torus](https://github.com/tfhe/tfhe)
* [SEAL: Simple Encypted Arithmatic Library](https://www.microsoft.com/en-us/research/project/simple-encrypted-arithmetic-library/)
* [PySEAL: Python interface to SEAL](https://github.com/Lab41/PySEAL)
* [HElib: An Implementation of homomorphic encryption](https://github.com/shaih/HElib])
* [EzPC: programmable, efficient, and scalable secure two-party computation for machine learning](https://github.com/mpc-msri/EzPC)
* [CUDA-accelerated Fully Homomorphic Encryption Library](https://github.com/vernamlab/cuFHE)
* [CrypTen: A framework for Privacy Preserving Machine Learning](https://github.com/facebookresearch/CrypTen)
* [tf-encrypted: A Framework for Machine Learning on Encrypted Data](https://github.com/tf-encrypted/tf-encrypted)
* [Sharemind](https://sourceforge.net/projects/sharemind/)
* [PythonPaillier](https://github.com/data61/python-paillier)

