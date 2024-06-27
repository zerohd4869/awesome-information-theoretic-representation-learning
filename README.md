# Awesome-information-theoretic-representation-learning
A curated paper list for information-theoretic representation learning.

All papers are selected and sorted by topic/year/importance. Please send a pull request if you would like to add any paper.



## Theories and Analysis

### Maximum Entropy
- Information theory and statistical mechanics.
  *Edwin T. Jaynes.* `Physical review, 1957`  [[paper]](https://journals.aps.org/pr/abstract/10.1103/PhysRev.106.620)
- Axiomatic derivation of the principle of maximum entropy and the principle of minimum cross-entropy.
  *JE Shore, RW Johnson.* `IEEE Transactions on information theory, 1980` [[paper]](https://ieeexplore.ieee.org/abstract/document/1056144/)
- On the rationale of maximum-entropy methods.
  *Edwin T. Jaynes.* `Proceedings of the IEEE, 1982` [[paper]](https://ieeexplore.ieee.org/abstract/document/1456693)    
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
- Semi-supervised learning by entropy minimization.
  *Yves Grandvalet, Yoshua Bengio.* `NeurIPS, 2004` [[paper]](https://proceedings.neurips.cc/paper/2004/hash/96f2b50b5d3613adf9c27049b2a888c7-Abstract.html)  
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
  *Kari Torkkola.* ` J. Mach. Learn. Res., 2003` [[paper]](https://jmlr.org/papers/v3/torkkola03a.html)
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
TODO
## Applications
TODO





