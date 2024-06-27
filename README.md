# Awesome-information-theoretic-representation-learning
A curated paper list for information-theoretic representation learning.

All papers are selected and sorted by topic/year. Please send a pull request if you would like to add any paper.



## Theories and Analysis

### Maximum Entropy
- Information theory and statistical mechanics.
  *Edwin T. Jaynes.* `Physical review, 1957`  [[paper]](https://journals.aps.org/pr/abstract/10.1103/PhysRev.106.620)
- Axiomatic derivation of the principle of maximum entropy and the principle of minimum cross-entropy.
  *JE Shore, RW Johnson.* `IEEE Trans. Inf. Theory, 1980` [[paper]](https://ieeexplore.ieee.org/abstract/document/1056144/)
- On the rationale of maximum-entropy methods.
  *Edwin T. Jaynes.* `Proceedings of the IEEE, 1982` [[paper]](https://ieeexplore.ieee.org/abstract/document/1456693)
- Pac-bayes analysis of maximum entropy classification.
  *John Shawe-Taylor, David R. Hardoon.* `AISTATS, 2009` [[paper]](https://proceedings.mlr.press/v5/shawe-taylor09a.html)
- Maximum Entropy Discrimination Markov Networks.
  *Jun Zhu, Eric P. Xing.* `J. Mach. Learn. Res., 2009` [[paper]](https://dl.acm.org/doi/10.5555/1577069.1755871)
J Shawe-Taylor, D Hardoon - Artificial intelligence and statistics, 2009
- The role of entropy and reconstruction in multi-view self-supervised learning.
 *Borja Rodrı́guez Gálvez, Arno Blaas, Pau Rodriguez, Adam Golinski, Xavier Suau, Jason Ramapuram, Dan Busbridge, Luca Zappella*  `ICML, 2023` [[paper]](https://proceedings.mlr.press/v202/rodri-guez-galvez23a.html)

### Information Maximization
- Self-Organization in a Perceptual Network
 *Ralph Linsker.* `Computer, 1988` [[paper]](https://ieeexplore.ieee.org/document/36)
- On Mutual Information Maximization for Representation Learning
 *Michael Tschannen, Josip Djolonga, Paul K. Rubenstein, Sylvain Gelly, Mario Lucic.*  `ICLR, 2020` [[paper]](https://openreview.net/forum?id=rkxoh24FPH)
- A Mutual Information Maximization Perspective of Language Representation Learning. 
 *Lingpeng Kong, Cyprien de Masson d'Autume, Lei Yu, Wang Ling, Zihang Dai, Dani Yogatama.*  `ICLR, 2020` [[paper]](https://openreview.net/forum?id=Syx79eBKwr)
- Which Mutual-Information Representation Learning Objectives are Sufficient for Control?
 *Kate Rakelly, Abhishek Gupta, Carlos Florensa, Sergey Levine.* `NeurIPS, 2021` [[paper]](https://proceedings.neurips.cc/paper/2021/hash/dd45045f8c68db9f54e70c67048d32e8-Abstract.html)

### Information Bottleneck
- The information bottleneck method. 
 *Naftali Tishby, Fernando C Pereira, and William Bialek.*  `the 37th Allerton Conference on Communication and Computation, 1999` [[paper]](https://arxiv.org/abs/physics/0004057)
- Information bottleneck for Gaussian variables. 
 *Gal Chechik, Amir Globerson, Naftali Tishby, Yair Weiss.*  `NeurIPS, 2003` [[paper]](https://proceedings.neurips.cc/paper/2003/hash/7e05d6f828574fbc975a896b25bb011e-Abstract.html)
- Deep learning and the information bottleneck principle. 
 *Naftali Tishby and Noga Zaslavsky.*  `ITW, 2015` [[paper]](https://ieeexplore.ieee.org/document/7133169/)
- Opening the black box of deep neural networks via information. 
 *Ravid Shwartz-Ziv, Naftali Tishby.*  `CoRR, 2017` [[paper]](https://arxiv.org/abs/1703.00810)
- The role of the information bottleneck in representation learning. 
 *Matías Vera, Pablo Piantanida, Leonardo Rey Vega.*  `ISIT, 2018` [[paper]](https://ieeexplore.ieee.org/document/8437679/)
- On the information bottleneck theory of deep learning. 
 *Andrew M. Saxe, Yamini Bansal, Joel Dapello, Madhu Advani, Artemy Kolchinsky, Brendan D. Tracey, David D. Cox.*  `ICLR, 2018` [[paper]](https://openreview.net/forum?id=ry_WPG-A-)
- Learning representations for neural network-based classification using the information bottleneck principle. 
 *Rana Ali Amjad, Bernhard C. Geiger.*  ` IEEE Trans. Pattern Anal. Mach. Intell., 2020` [[paper]](https://ieeexplore.ieee.org/document/8680020)
- Learnability for the information bottleneck. 
 *Tailin Wu, Ian S. Fischer, Isaac L. Chuang, Max Tegmark.*  `UAI, 2020` [[paper]](https://proceedings.mlr.press/v115/wu20b.html)
- Perturbation theory for the information bottleneck. 
 *Vudtiwat Ngampruetikorn, David J. Schwab.*  `NeurIPS, 2021` [[paper]](https://proceedings.neurips.cc/paper/2021/hash/af8d9c4e238c63fb074b44eb6aed80ae-Abstract.html)
- How does information bottleneck help deep learning? 
 *Kenji Kawaguchi, Zhun Deng, Xu Ji, and Jiaoyang Huang.*  `ICML, 2023` [[paper]](https://proceedings.mlr.press/v202/kawaguchi23a.html)


### Others
- Information-theoretic analysis of generalization capability of learning algorithms.
 *Aolin Xu and Maxim Raginsky.*  `NeurIPS, 2017` [[paper]](https://proceedings.neurips.cc/paper/2017/hash/ad71c82b22f4f65b9398f76d8be4c615-Abstract.html)
- Emergence of invariance and disentanglement in deep representations. 
 *Alessandro Achille, Stefano Soatto.*  `ITA, 2018` [[paper]](https://ieeexplore.ieee.org/document/8503149/)
- Reasoning about generalization via conditional mutual information.
 *Thomas Steinke and Lydia Zakynthinou.*  `COLT, 2020` [[paper]](https://proceedings.mlr.press/v125/steinke20a.html)
- A Unifying Mutual Information View of Metric Learning: Cross-Entropy vs. Pairwise Losses.
 *Malik Boudiaf, Jérôme Rony, Imtiaz Masud Ziko, Eric Granger, Marco Pedersoli, Pablo Piantanida, Ismail Ben Aye.*  `ECCV, 2020` [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-58539-6_33)


## Learning Principle and Optimization

### Entropy-based Representation Learning
- Deterministic annealing for clustering, compression, classification, regression, and related optimization problems.
  *K Rose.* `Proceedings of the IEEE, 1998` [[paper]](https://ieeexplore.ieee.org/abstract/document/726788) 
- Unsupervised Learning of Finite Mixture Models.
  *Mário A. T. Figueiredo, Anil K. Jain.* `IEEE Trans. Pattern Anal. Mach. Intell., 2002` [[paper]](https://ieeexplore.ieee.org/document/990138/)  
- Semi-supervised learning by entropy minimization.
  *Yves Grandvalet, Yoshua Bengio.* `NeurIPS, 2004` [[paper]](https://proceedings.neurips.cc/paper/2004/hash/96f2b50b5d3613adf9c27049b2a888c7-Abstract.html)
- Nonparametric Supervised Learning by Linear Interpolation with Maximum Entropy.
  *Maya R. Gupta, Robert M. Gray, Richard A. Olshen.* `IEEE Trans. Pattern Anal. Mach. Intell., 2006` [[paper]](https://doi.org/10.1109/TPAMI.2006.101)
- Similarity-based Classification: Concepts and Algorithms.
  *Yihua Chen, Eric K. Garcia, Maya R. Gupta, Ali Rahimi, Luca Cazzanti.* `J. Mach. Learn. Res., 2009` [[paper]](https://dl.acm.org/doi/10.5555/1577069.1577096)
- Regularizing neural networks by penalizing confident output distributions.
  *Gabriel Pereyra, George Tucker, Jan Chorowski, Lukasz Kaiser, and Geoffrey E. Hinton.* `ICLR Workshop, 2017` [[paper]](https://openreview.net/forum?id=HyhbYrGYe)  
- Compressing images by encoding their latent representations with relative entropy coding.
  *Gergely Flamich, Marton Havasi, José Miguel Hernández-Lobato.* `NeurIPS, 2020` [[paper]](https://proceedings.neurips.cc/paper/2020/hash/ba053350fe56ed93e64b3e769062b680-Abstract.html)  
- Self-supervised learning via maximum entropy coding.
  *Xin Liu, Zhongdao Wang, Yali Li, Shengjin Wang.* `NeurIPS, 2022` [[paper]](https://papers.nips.cc/paper_files/paper/2022/hash/dc709714c52b35f2f34aca2a92b06bc8-Abstract-Conference.html)

### Infomax-based Representation Learning
- An information-maximization approach to blind separation and blind deconvolution.
  *Anthony J. Bell, Terrence J. Sejnowski.* `Neural Comput., 1995` [[paper]](https://doi.org/10.1162/neco.1995.7.6.1129)
- Alignment by maximization of mutual information.
  *Paul A. Viola, William M. Wells III* `ICCV, 1995` [[paper]](https://ieeexplore.ieee.org/document/466930/)
- Feature extraction by non-parametric mutual information maximization.
  *Kari Torkkola.* `J. Mach. Learn. Res., 2003` [[paper]](https://jmlr.org/papers/v3/torkkola03a.html)
- An information-theoretic framework for fast and robust unsupervised learning via neural population infomax.
  *Wentao Huang, Kechen Zhang:.* `ICLR, 2017` [[paper]](https://openreview.net/forum?id=SkYbF1slg)
- Representation learning with contrastive predictive coding.
  *Aäron van den Oord, Yazhe Li, Oriol Vinyals.* `CoRR, 2018` [[paper]](https://arxiv.org/abs/1807.03748)
- Learning deep representations by mutual information estimation and maximization.
  *R. Devon Hjelm, Alex Fedorov, Samuel Lavoie-Marchildon, Karan Grewal, Philip Bachman, Adam Trischler, Yoshua Bengio* ` ICLR, 2019` [[paper]](https://openreview.net/forum?id=Bklr3j0cKX)
- Learning representations by maximizing mutual information across views.
  *Philip Bachman, R. Devon Hjelm, William Buchwalter.* `NeurIPS, 2019` [[paper]](https://proceedings.neurips.cc/paper/2019/hash/ddf354219aac374f1d40b7e760ee5bb7-Abstract.html)
- On mutual information in contrastive learning for visual representations.
  *Mike Wu, Chengxu Zhuang, Milan Mosse, Daniel Yamins, Noah D. Goodman.* `CoRR, 2019` [[paper]](https://arxiv.org/abs/2005.13149)
- Learning adversarially robust representations via worst-case mutual information maximization.
  *Sicheng Zhu, Xiao Zhang, David Evans.* `ICML, 2020` [[paper]](https://proceedings.mlr.press/v119/zhu20e.html)
- Learning disentangled representations via mutual information estimation.
  *Sanchez, Eduardo Hugo, Mathieu Serrurier, and Mathias Ortner.* `ECCV, 2020` [[paper]](https://doi.org/10.1007/978-3-030-58542-6_13)
- Rethinking Minimal Sufficient Representation in Contrastive Learning.
  *Haoqing Wang, Xun Guo, Zhi-Hong Deng, Yan Lu.* `CVPR, 2022` [[paper]](https://doi.org/10.1109/CVPR52688.2022.01557)
- Representation Learning with Conditional Information Flow Maximization.
  *Dou Hu, Lingwei Wei, Wei Zhou, Songlin Hu.* `ACL, 2024` [[paper]](https://arxiv.org/abs/2406.05510)


### IB-based Representation Learning
- The deterministic information bottleneck.
  *DJ Strouse, David J. Schwab.* `UAI, 2016` [[paper]](http://auai.org/uai2016/proceedings/papers/319.pdf)
- Deep Variational Information Bottleneck.
  *Alexander A. Alemi, Ian Fischer, Joshua V. Dillon, Kevin Murphy.* `ICLR, 2017` [[paper]](https://openreview.net/forum?id=HyxQzBceg)
- Information dropout: Learning optimal representations through noisy computation.
  *Alessandro Achille, Stefano Soatto.* `IEEE Trans. Pattern Anal. Mach. Intell., 2018` [[paper]](https://ieeexplore.ieee.org/document/8253482/)
- Mutual information neural estimation.
  *Mohamed Ishmael Belghazi, Aristide Baratin, Sai Rajeswar, Sherjil Ozair, Yoshua Bengio, R. Devon Hjelm, and Aaron C. Courville.* `ICML, 2018` [[paper]](https://proceedings.mlr.press/v80/belghazi18a.html)
- Nonlinear Information Bottleneck.
  *Artemy Kolchinsky, Brendan D. Tracey, David H. Wolpert.* `Entropy, 2019` [[paper]](https://www.mdpi.com/1099-4300/21/12/1181)
- Variational discriminator bottleneck: Improving imitation learning, inverse rl, and gans by constraining information flow.
  *Xue Bin Peng, Angjoo Kanazawa, Sam Toyer, Pieter Abbeel, and Sergey Levine.* `ICLR, 2019` [[paper]](https://openreview.net/forum?id=HyxPx3R9tm)
- The conditional entropy bottleneck.
  *Ian S. Fischer.* `Entropy, 2020` [[paper]](https://www.mdpi.com/1099-4300/22/9/999)
- The HSIC bottleneck: Deep learning without back-propagation.
  *Kurt Wan-Duo Ma, J. P. Lewis, W. Bastiaan Kleijn.* `AAAI, 2020` [[paper]](https://doi.org/10.1609/aaai.v34i04.5950)
- Learning Robust Representations via Multi-View Information Bottleneck.
  *Marco Federici, Anjan Dutta, Patrick Forré, Nate Kushman, Zeynep Akata.* `ICLR, 2020` [[paper]](https://openreview.net/forum?id=B1xwcyHFDr)
- Learning Optimal Representations with the Decodable Information Bottleneck.
  *Yann Dubois, Douwe Kiela, David J. Schwab, Ramakrishna Vedantam.* `NeurIPS, 2020` [[paper]](https://proceedings.neurips.cc/paper/2020/hash/d8ea5f53c1b1eb087ac2e356253395d8-Abstract.html)
- The Dual Information Bottleneck.
  *Zoe Piran, Ravid Shwartz-Ziv, Naftali Tishby.* `CoRR, 2020` [[paper]](https://arxiv.org/abs/2006.04641)
- Revisiting Hilbert-Schmidt Information Bottleneck for Adversarial Robustness.
  *Zifeng Wang, Tong Jian, Aria Masoomi, Stratis Ioannidis, Jennifer G. Dy.* `NeurIPS, 2021` [[paper]](https://proceedings.neurips.cc/paper/2021/hash/055e31fa43e652cb4ab6c0ee845c8d36-Abstract.html)
- Multi-View Information-Bottleneck Representation Learning.
  *Zhibin Wan, Changqing Zhang, Pengfei Zhu, Qinghua Hu.* `AAAI, 2021` [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/17210)
- PAC-Bayes Information Bottleneck.
  *Zifeng Wang, Shao-Lun Huang, Ercan Engin Kuruoglu, Jimeng Sun, Xi Chen, Yefeng Zheng.* `ICLR, 2022` [[paper]](https://openreview.net/forum?id=iLHOIDsPv1P)
- Maximum Entropy Information Bottleneck for Uncertainty-aware Stochastic Embedding.
  *Sungtae An, Nataraj Jammalamadaka, Eunji Chong.* `CVPR Workshop, 2023` [[paper]](https://ieeexplore.ieee.org/document/10208631)
- Structured Probabilistic Coding.
  *Dou Hu, Lingwei Wei, Yaxin Liu, Wei Zhou, and Songlin Hu.* `AAAI, 2024` [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/29142)

### MI Estimation
- Estimation of the information by an adaptive partitioning of the observation space.
  *Georges A. Darbellay, Igor Vajda.* `IEEE Trans. Inf. Theory, 1999` [[paper]](https://doi.org/10.1109/18.761290)
- Estimation of entropy and mutual information.
  *Liam Paninski.* `Neural Comput., 2003` [[paper]](https://doi.org/10.1162/089976603321780272)
- Estimating mutual information.
  *Alexander Kraskov, Harald Stögbauer, and Peter Grassberger.* `Physical review, 2004` [[paper]](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.69.066138)
- Estimating divergence functionals and the likelihood ratio by penalized convex risk minimization.
  *XuanLong Nguyen, Martin J. Wainwright, Michael I. Jordan.* `NeurIPS, 2007` [[paper]](https://proceedings.neurips.cc/paper/2007/hash/72da7fd6d1302c0a159f6436d01e9eb0-Abstract.html)
- Density functional estimators with k-nearest neighbor bandwidths.
  *Weihao Gao, Sewoong Oh, Pramod Viswanath.* `ISIT, 2017` [[paper]](https://doi.org/10.1109/ISIT.2017.8006749)
- f-GAN: Training Generative Neural Samplers using Variational Divergence Minimization.
  *Sebastian Nowozin, Botond Cseke, Ryota Tomioka.* `NeurIPS, 2017` [[paper]](https://proceedings.neurips.cc/paper/2016/hash/cedebb6e872f539bef8c3f919874e9d7-Abstract.html)
- Estimating mutual information for discrete-continuous mixtures.
  *Weihao Gao, Sreeram Kannan, Sewoong Oh, Pramod Viswanath.* `NeurIPS, 2017` [[paper]](https://proceedings.neurips.cc/paper/2017/hash/ef72d53990bc4805684c9b61fa64a102-Abstract.html)
- Mutual information neural estimation.
  *Mohamed Ishmael Belghazi, Aristide Baratin, Sai Rajeswar, Sherjil Ozair, Yoshua Bengio, R. Devon Hjelm, and Aaron C. Courville.* `ICML, 2018` [[paper]](https://proceedings.mlr.press/v80/belghazi18a.html)
- Representation learning with contrastive predictive coding.
  *Aäron van den Oord, Yazhe Li, Oriol Vinyals.* `CoRR, 2018` [[paper]](https://arxiv.org/abs/1807.03748)
- On variational bounds of mutual information.
  *Ben Poole, Sherjil Ozair, Aäron van den Oord, Alexander A. Alemi, George Tucker.* `ICML, 2019` [[paper]](https://proceedings.mlr.press/v97/poole19a.html)
- Club: A contrastive log-ratio upper bound of mutual information.
  *Pengyu Cheng, Weituo Hao, Shuyang Dai, Jiachang Liu, Zhe Gan, Lawrence Carin.* `ICML, 2020` [[paper]](https://proceedings.mlr.press/v119/cheng20b.html)
- Conditional mutual information estimation for mixed, discrete and continuous data.
  *Octavio César Mesner, Cosma Rohilla Shalizi.* `IEEE Trans. Inf. Theory, 2021` [[paper]](https://ieeexplore.ieee.org/document/9201164/)
- Beyond normal: On the evaluation of mutual information estimators.
  *Pawel Czyz, Frederic Grabowski, Julia E. Vogt, Niko Beerenwinkel, Alexander Marx* `NeurIPS, 2023` [[paper]](https://proceedings.neurips.cc//paper_files/paper/2023/hash/36b80eae70ff629d667f210e13497edf-Abstract-Conference.html)


## Applications
### Entropy-based Methods
- Maximum-Entropy Fine Grained Classification.
  *Abhimanyu Dubey, Otkrist Gupta, Ramesh Raskar, Nikhil Naik.* `NeurIPS, 2018`
- Maximum Entropy-Regularized Multi-Goal Reinforcement Learning.
  *Rui Zhao, Xudong Sun, Volker Tresp.* `ICML, 2019` 
- Mitigating Information Leakage in Image Representations: A Maximum Entropy Approach.
  *Proteek Chandan Roy, Vishnu Naresh Boddeti.* `CVPR, 2019`
- Semi-Supervised Domain Adaptation via Minimax Entropy.
  *Kuniaki Saito, Donghyun Kim, Stan Sclaroff, Trevor Darrell, Kate Saenko.* `ICCV, 2019`
- Improving Neural Response Diversity with Frequency-Aware Cross-Entropy Loss.
  *Shaojie Jiang, Pengjie Ren, Christof Monz, Maarten de Rijke.* `WWW, 2019`
- Distributional Policy Evaluation: a Maximum Entropy approach to Representation Learning.
  *Riccardo Zamboni, Alberto Maria Metelli, Marcello Restelli.* `NeurIPS, 2023`
- MaxEnt Loss: Constrained Maximum Entropy for Calibration under Out-of-Distribution Shift.
  *Dexter Neo, Stefan Winkler, Tsuhan Chen.* `AAAI, 2024`

### Infomax-based Methods
- Infogan: Interpretable representation learning by information maximizing generative adversarial nets.
  *Xi Chen, Yan Duan, Rein Houthooft, John Schulman, Ilya Sutskever, and Pieter Abbeel.* `NeurIPS, 2016`
- Deep graph infomax.
  *Petar Velickovic, William Fedus, William L. Hamilton, Pietro Liò, Yoshua Bengio, R. Devon Hjelm.* `ICLR, 2019`
- InfoGraph: Unsupervised and Semi-supervised Graph-Level Representation Learning via Mutual Information Maximization.
  *Fan-Yun Sun, Jordan Hoffmann, Vikas Verma, Jian Tang.* `ICLR, 2020`
- An Unsupervised Sentence Embedding Method by Mutual Information Maximization.
  *Yan Zhang, Ruidan He, Zuozhu Liu, Kwan Hui Lim, Lidong Bing.* `EMNLP, 2020`
- Graph Representation Learning via Graphical Mutual Information Maximization.
  *Zhen Peng, Wenbing Huang, Minnan Luo, Qinghua Zheng, Yu Rong, Tingyang Xu, Junzhou Huang.* `WWW, 2020`
- Info3D: Representation Learning on 3D Objects Using Mutual Information Maximization and Contrastive Learning.
  *Aditya Sanghi.* `ECCV, 2020`
- Improving Multimodal Fusion with Hierarchical Mutual Information Maximization for Multimodal Sentiment Analysis.
  *Wei Han, Hui Chen, Soujanya Poria.* `EMNLP, 2021`
- Clustering by Maximizing Mutual Information Across Views.
  *Kien Do, Truyen Tran, Svetha Venkatesh.* `ICCV, 2021`
- Online Continual Learning through Mutual Information Maximization.
  *Yiduo Guo, Bing Liu, Dongyan Zhao.* `ICML, 2022`
- InfoDiffusion: Representation Learning Using Information Maximizing Diffusion Models.
  *Yingheng Wang, Yair Schiff, Aaron Gokaslan, Weishen Pan, Fei Wang, Christopher De Sa, Volodymyr Kuleshov.* `ICML, 2023`

### IB-based Methods
- Compressing Neural Networks using the Variational Information Bottleneck.
  *Bin Dai, Chen Zhu, Baining Guo, David P. Wipf.* `ICML, 2018`
- InfoBot: Transfer and Exploration via the Information Bottleneck.
  *Anirudh Goyal, Riashat Islam, Daniel Strouse, Zafarali Ahmed, Hugo Larochelle, Matthew M. Botvinick, Yoshua Bengio, Sergey Levine* `ICLR, 2019`
- Specializing Word Embeddings (for Parsing) by Information Bottleneck.
  *Xiang Lisa Li, Jason Eisner.* `EMNLP/IJCNLP, 2019`
- Restricting the Flow: Information Bottlenecks for Attribution.
  *Karl Schulz, Leon Sixt, Federico Tombari, Tim Landgraf.* `ICLR, 2020`
- Graph Information Bottleneck.
  *Tailin Wu, Hongyu Ren, Pan Li, Jure Leskovec.* `NeurIPS, 2020`
- Multi-Task Variational Information Bottleneck.
  *Weizhu Qian, Bowei Chen, Franck Gechter* `CoRR, 2020`
- DICE: Diversity in Deep Ensembles via Conditional Redundancy Adversarial Estimation.
  *Alexandre Ramé, Matthieu Cord.* `ICLR, 2021`
- Invariance Principle Meets Information Bottleneck for Out-of-Distribution Generalization.
  *Kartik Ahuja, Ethan Caballero, Dinghuai Zhang, Jean-Christophe Gagnon-Audet, Yoshua Bengio, Ioannis Mitliagkas, Irina Rish.* `NeurIPS, 2021`
- Variational information bottleneck for effective low-resource fine-tuning.
  *Rabeeh Karimi Mahabadi, Yonatan Belinkov, and James Henderson.* `ICLR, 2021`
- Infobert: Improving robustness of language models from an information theoretic perspective.
  *Boxin Wang, Shuohang Wang, Yu Cheng, Zhe Gan, Ruoxi Jia, Bo Li, Jingjing Liu.* `ICLR, 2021`
- Learning unbiased representations via mutual information backpropagation.
  *Ruggero Ragonesi, Riccardo Volpi, Jacopo Cavazza, and Vittorio Murino.* `CVPR Workshop, 2021`
- IB-GAN: Disentangled Representation Learning with Information Bottleneck Generative Adversarial Networks.
  *Insu Jeon, Wonkwang Lee, Myeongjang Pyeon, Gunhee Kim.* `AAAI, 2021`



