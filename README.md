# Awesome-Evaluation-Perspective-CV

This repository is designed to collect excellent CV work and explores the evolution of computer vision from an evaluation perspective. The goal is to provide a platform for researchers (e.g., informal reviews) to keep track of recently published and previous literature in the community. Divided into five sections: Visual Capabilities, Agent Tasks, Data Environment, Evaluation Systems, and Test Executors, the survey provides a systematic analysis of how the evaluation approach has shaped the development of vision algorithms.


Introduction

* [**IEEE'2021**]"***Explaining deep neural networks and beyond: A review of methods and applications***",W. Samek, G. Montavon, S. Lapuschkin,C.J.Anders,andK.R.M¨uller.[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9369420)
* [**IEEE'2023**]"***Object Detection in 20 Years: A Survey***",Z. Zou, K. Chen, Z. Shi, Y. Guo, and J. Ye.[paper](https://arxiv.org/pdf/1905.05055)
* [**IEEE'1998**]"***Gradient-based learning applied to document recognition***",Y. LeCun, L. Bottou, Y. Bengio, and P. Haffner.[paper](https://axon.cs.byu.edu/~martinez/classes/678/Papers/Convolution_nets.pdf)
* [**CVPR'2004**]"***Learning generative visual models from few training examples: An incremental bayesian approach tested on 101 object categories***",L. Fei-Fei, R. Fergus, and P. Perona.[paper](https://cs.nyu.edu/~fergus/papers/Fei-Fei_GMBV04.pdf)
* [**CVPR'2009**]"***Imagenet: A large-scale hierarchical image database***",J. Deng, W. Dong, R. Socher, L.-J. Li, K. Li, and L. Fei-Fei.[paper](https://image-net.org/static_files/papers/imagenet_cvpr09.pdf) [Dataset](https://www.image-net.org)
* [**IJCV'2015**]"***Imagenet large scale visual recognition challenge***",O. Russakovsky, J. Deng, H. Su, J. Krause, S. Satheesh, S. Ma, Z. Huang, A. Karpathy, A. Khosla, M. Bernstein et al.[paper](https://arxiv.org/pdf/1409.0575)
* [**CVIU'2017**]"***Computer vision for assistive technologies***",M. Leo, G. Medioni, M. Trivedi, T. Kanade, and G. M. Farinella.
* "***Ai and the everything in the whole wide world benchmark***",I. D. Raji, E. M. Bender, A. Paullada, E. Denton, and A. Hanna.[paper](https://arxiv.org/pdf/2111.15366)
* [**PAMI'2024**]"***Physical adversarial attack meets computer vision: A decade survey***",H. Wei, H. Tang, X. Jia, Z. Wang, H. Yu, Z. Li, S. Satoh, L. Van Gool, and Z. Wang.[paper](https://arxiv.org/pdf/2209.15179)
* "***Large language models for robotics: Opportunities, challenges, and perspectives***",
J. Wang, Z. Wu, Y. Li, H. Jiang, P. Shu, E. Shi, H. Hu, C. Ma, Y. Liu, X. Wang et al.[paper](https://arxiv.org/pdf/2401.04334)
* "***Large language models meet computer vision: A brief survey***",R. Hamadi.[paper](https://arxiv.org/pdf/2311.16673)
* [**IJCV'2015**]"***The pascal visual object classes challenge: A retrospective***",M. Everingham, S. A. Eslami, L. Van Gool, C. K. Williams, J. Winn, and A. Zisserman[paper](https://homepages.inf.ed.ac.uk/ckiw/postscript/ijcv_voc14.pdf)

Visual Capability - Clarifying The Evaluation Goals

1.Biologically Inspired Visual Capabilities

* [**JCN'2021**]"***Convolutional neural networks as a model of the visual system: Past, present, and future***",G. W. Lindsay.[paper](https://arxiv.org/pdf/2001.07092)
* [**nature'2015**]"***Deep learning***",Y. LeCun, Y. Bengio, and G. Hinton.[paper](https://www.nature.com/articles/nature14539)
* [**CVPR'2016**]"***Deep residual learning for image recognition***",K. He, X. Zhang, S. Ren, and J. Sun.[paper](https://arxiv.org/pdf/1512.03385)
* [**NIPS'2015**]"***Learning both weights and connections for efffcient neural network***",S. Han, J. Pool, J. Tran, and W. Dally.[paper](https://arxiv.org/pdf/1506.02626)
* [**NIPS'2017**]"***Attention is all you need***",A. Vaswani, N. Shazeer, N. Parmar, J. Uszkoreit, L. Jones, A. N. Gomez, Ł. Kaiser, and I. Polosukhin.[paper](https://arxiv.org/pdf/1706.03762)

2.Cognitive Science Inspiration in Computer Vision

* [**Compr. Physiol'2018**],"***Neural mechanisms of high-level vision***",J. Hegde´.[paper](https://www.researchgate.net/publication/326227744_Neural_Mechanisms_of_High-Level_Vision)
* [**NIPS'2015**]"***Faster r-cnn: Towards real-time object detection with region proposal networks***",S. Ren, K. He, R. Girshick, and J. Sun.[paper](https://arxiv.org/pdf/1506.01497)
* [**CVPR'2007**]***"Image representations beyond histograms of gradients: The role of gestalt descriptors***",S. Bileschi and L. Wolf.[paper](https://www.cs.tau.ac.il/~wolf/papers/gestalt.pdf)
* [**PAMI'2007**]"***Robust object recognition with cortex-like mechanisms***",T. Serre, L. Wolf, S. Bileschi, M. Riesenhuber, and T. Poggio.[paper](https://mcgovern.mit.edu/wp-content/uploads/2019/01/04069258.pdf)
* [**NIPS'2014**]"***Two-stream convolutional networks for action recognition in videos***",K. Simonyan and A. Zisserman.[paper](https://arxiv.org/pdf/1406.2199)
* [**IJCV'2000**]"***How optimal depth cue integration depends on the task***",P. R. Schrater and D. Kersten.[paper](http://vision.psych.umn.edu/users/schrater/SchraterKerstenIJCV2000.pdf)
* "***Long short-term memory***",A. Graves and A. Graves.[paper](https://arxiv.org/pdf/1308.0850)
* [**CVPR'2015**]"***Long-term recurrent convolutional networks for visual recognition and description***",J. Donahue, L. Anne Hendricks, S. Guadarrama, M. Rohrbach, S. Venugopalan, K. Saenko, and T. Darrell.[paper](https://arxiv.org/pdf/1411.4389)
* "***The ecological approach to visual perception: classic edition***",J. J. Gibson.[paper](https://daughtersofchaos.wordpress.com/wp-content/uploads/2014/05/gibson_occluding-edge_1979.pdf)
* [**PAMI'2012**]"***3d convolutional neural networks for human action recognition***",S. Ji, W. Xu, M. Yang, and K. Yu.[paper](http://users.ece.northwestern.edu/~mya671/mypapers/TPAMI13_Ji_Xu_Yang_Yu.pdf)
* [**CVPR'2017**]"***Quo vadis, action recognition? a new model and the kinetics dataset***",J. Carreira and A. Zisserman.[paper](https://arxiv.org/pdf/1705.07750)
* "***Perception of human motion***",R. Blake and M. Shiffrar.[paper](https://www.cs.princeton.edu/courses/archive/spring08/cos598B/Readings/BlakeShiffrar_2007.pdf)
* [**T-KDE'2020**]"***Deep learning on graphs: A survey***",Z. Zhang, P. Cui, and W. Zhu[paper](https://arxiv.org/pdf/1812.04202)
* [**AAAI'2018**]"***Spatial temporal graph convolutional networks for skeleton-based action recognition***",S. Yan, Y. Xiong, and D. Lin.[paper](https://arxiv.org/pdf/1801.07455)
* [**ICCV'2013**]"***Action recognition with improved trajectories***",H. Wang and C. Schmid[paper](https://www.cv-foundation.org/openaccess/content_iccv_2013/papers/Wang_Action_Recognition_with_2013_ICCV_paper.pdf)
* [**ECCV'2014**]"***Categoryspeciffc video summarization***",D. Potapov, M. Douze, Z. Harchaoui, and C. Schmid.[paper](https://inria.hal.science/file/index/docid/1022967/filename/video_summarization.pdf)


Proxy Task - Defining the Scope of Evaluation

1.Classification and Recognition

* [**MIT'2010**]"***Vision: A computational investigation into the human representation and processing of visual information***",D. Marr.[paper](https://qiongzhang.github.io/Marr.pdf)

2.Detection

* [**IJCV'2013**]"***Selective search for object recognition***",J. R. Uijlings, K. E. Van De Sande, T. Gevers, and A. W. Smeulders.[paper](https://pure.uva.nl/ws/files/19494140/UijlingsIJCV2013.pdf)
* [**CVPR'2015**]"***Deep visual-semantic alignments for generating image descriptions***",A. Karpathy and L. Fei-Fei.[paper](https://arxiv.org/pdf/1412.2306)
* [**ICML'2015**]"***Show, attend and tell: Neural image caption generation with visual attention***",K. Xu, J. Ba, R. Kiros, K. Cho, A. Courville, R. Salakhudinov, R. Zemel, and Y. Bengio.[paper](https://arxiv.org/pdf/1502.03044)
* [**TPAMI'2017**]"***Image captioning and visual question answering based on attributes and external knowledge***",Q. Wu, C. Shen, P. Wang, A. Dick, and A. Van Den Hengel.[paper](https://arxiv.org/pdf/1603.02814)
* [**CVPR'2018**]"***High performance visual tracking with siamese region proposal network***",B. Li, J. Yan, W. Wu, Z. Zhu, and X. Hu.[paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Li_High_Performance_Visual_CVPR_2018_paper.pdf)
* [**T-AES'2016**]"***Open set recognition for automatic target classiffcation with rejection***",M. D. Scherreik and B. D. Rigling.[paper](https://ieeexplore.ieee.org/document/7472960)
* [**PAMI'2020**]"***Recent advances in open set recognition: A survey***",C. Geng, S.-j. Huang, and S. Chen.[paper](https://arxiv.org/pdf/1811.08581)

3.Segmentation

* [**PAMI'2017**]"***Deeplab: Semantic image segmentation with deep convolutional nets,atrous convolution, and fully connected crfs***",L.-C. Chen, G. Papandreou, I. Kokkinos, K. Murphy, and A. L. Yuille.[paper](https://arxiv.org/pdf/1606.00915)
* [**ECCV'2018**]"***Encoder-decoder with atrous separable convolution for semantic image segmentation***",L.-C. Chen, Y. Zhu, G. Papandreou, F. Schroff, and H. Adam.[paper](https://arxiv.org/pdf/1802.02611) [Code](https://github.com/tensorflow/models/tree/master/research/deeplab"%3Emodels/research/deeplab)
* [**MICCAI'2015**]"***U-net: Convolutional networks for biomedical image segmentation***",O. Ronneberger, P. Fischer, and T. Brox.[paper](https://arxiv.org/pdf/1505.04597) [Code](https://lmb.informatik.uni-freiburg.de/people/ronneber/u-net/)

4.Tracking

* [**TAMI'2021**]"***Got-10k: A large high-diversity benchmark for generic object tracking in the wild***",L. Huang, X. Zhao, and K. Huang.[paper](https://arxiv.org/pdf/1810.11981) [Dataset](http://got-10k.aitestunion.com)
* [**TAMI'2023**]"***Global Instance Tracking: Locating Target More Like Humans***",S. Hu, X. Zhao, L. Huang, and K. Huang.[paper](https://www.semanticscholar.org/reader/1f0cb95449984a4346e2a3deca0370cc74cba470) [Dataset](http://videocube.aitestunion.com/)
* [**PAMI'2016**]"***A novel performance evaluation methodology for single-target trackers***",M. Kristan, J. Matas, A. Leonardis, T. Voj´ıˇr, R. Pffugfelder, G. Fernandez, G. Nebehay, F. Porikli, and L. Cˇ ehovin.[paper](https://arxiv.org/pdf/1503.01313)
* [**IEEE'2020**]"***Performance evaluation methodology for long-term single-object tracking***",A. Lukez´icˇ, L. Cˇ . Zajc, T. Voj´ıˇr, J. Matas, and M. Kristan.[paper](https://ieeexplore.ieee.org/document/9054960)

5.Task Challenges

* [**PAMI'2015**]"***Nus-pro: A new visual tracking challenge***",A. Li, M. Lin, Y. Wu, M.-H. Yang, and S. Yan.[paper](https://faculty.ucmerced.edu/mhyang/papers/pami15_nus_pro.pdf)
* [**ECCV'2016**]"***A benchmark and simulator for uav tracking***",M. Mueller, N. Smith, and B. Ghanem.[paper](https://link.springer.com/chapter/10.1007/978-3-319-46448-0_27#Sec10)
* [**IJCV'2023**]"***Biodrone: A bionic drone-based single object tracking benchmark for robust vision***",X. Zhao, S. Hu, Y. Wang, J. Zhang, Y. Hu, R. Liu, H. Ling, Y. Li, R. Li, K. Liu, and J. Li.[paper](http://biodrone.aitestunion.com/static/BioDrone.pdf) [Dataset](http://biodrone.aitestunion.com/downloads)
* [**ICCV'2021**]"***Transparent object tracking benchmark***",H. Fan, H. A. Miththanthaya, S. R. Rajan, X. Liu, Z. Zou, Y. Lin, H. Ling et al.[paper](https://arxiv.org/pdf/2011.10875) [Dataset](https://hengfan2010.github.io/projects/TOTB/)
* [**CVPR'2018**]"***High performance visual tracking with siamese region proposal network***",B. Li, J. Yan, W. Wu, Z. Zhu, and X. Hu.[paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Li_High_Performance_Visual_CVPR_2018_paper.pdf)
* [**ECCV'2018**]"***Distractor-aware siamese networks for visual object tracking***",Z. Zhu, Q. Wang, B. Li, W. Wu, J. Yan, and W. Hu.[paper](https://link.springer.com/chapter/10.1007/978-3-030-01240-3_7)



## Content
- [Data Environment](#data-environment)

- [Evaluation System](#evaluation-system)

- [Summary and Outlook](#summary-and-outlook)




#### `Data Environment`

##### `Classical Small-scale Datasets`

* [**IEEE'1998**] ***"Gradient-based learning applied to document recognition"***, Y. LeCun, L. Bottou, Y. Bengio, and P. Haffner.[[`paper`]](https://ieeexplore.ieee.org/document/726791)

* [**TR'2009**] ***"Learning multiple layers of features from tiny images"***, A Krizhevsky，G. Hinton. [[`paper`]](https://www.cs.toronto.edu/~kriz/learning-features-2009-TR.pdf) [[`Dataset`🌟]](https://www.cs.toronto.edu/~kriz/cifar.html)

* [**CVPR'2004**] ***"Learning generative visual models from few training examples: An incremental bayesian approach tested on 101 object categories"***, L. Fei-Fei, R. Fergus, and P. Perona.[[`paper`]](https://www.sciencedirect.com/science/article/abs/pii/S1077314206001688?via%3Dihub) [[`Dataset`🌟]](https://data.caltech.edu/records/mzrjq-6wc02)

* [**TR'2007**] ***"Caltech-256 object category dataset"***, G. Griffin, A. Holub, P. Perona et al. [[`Dataset`🌟]](https://data.caltech.edu/records/nyy15-4j048)

* [**TPAMI'2015**] ***"Object tracking benchmark"***, Y. Wu, J. Lim, and M.-H. Yang. [[`paper`]](https://ieeexplore.ieee.org/document/7001050) [[`Dataset`🌟]](http://cvlab.hanyang.ac.kr/tracker_benchmark/datasets.html)

* [**CVPR'2013**] ***"Online object tracking: A benchmark"***, Y. Wu, J. Lim, and M.-H. Yang. [[`paper`]](https://ieeexplore.ieee.org/document/6619156) [[`Dataset`🌟]](http://cvlab.hanyang.ac.kr/tracker_benchmark/datasets.html)

* [**TR'2009**] ***"Learning multiple layers of features from tiny images"***, A Krizhevsky，G. Hinton. [[`paper`]](https://www.cs.toronto.edu/~kriz/learning-features-2009-TR.pdf) [[`Dataset`🌟]](https://www.cs.toronto.edu/~kriz/cifar.html)

##### `Challenge and Competition Datasets`

* [**IJCV'2015**] ***"The pascal visual object classes challenge: A retrospective"***, M. Everingham, S. A. Eslami, L. Van Gool, C. K. Williams, J. Winn, and A. Zisserman. [[`paper`]](https://link.springer.com/article/10.1007/s11263-014-0733-5) [[`Dataset`🌟]](http://host.robots.ox.ac.uk/pascal/VOC/)

* [**CVPR'2014**] ***"The role of context for object detection and semantic segmentation in the wild"***, R. Mottaghi, X. Chen, X. Liu, N.-G. Cho, S.-W. Lee, S. Fidler, R. Urtasun, and A. Yuille. [[`paper`]](https://ieeexplore.ieee.org/document/6909514) [[`Dataset`🌟]](https://cs.stanford.edu/~roozbeh/pascal-context/)

* [**IJCV'2015**] ***"Imagenet large scale visual recognition challenge"***, O. Russakovsky, J. Deng, H. Su, J. Krause, S. Satheesh, S. Ma, Z. Huang, A. Karpathy, A. Khosla, M. Bernstein et al. [[`paper`]](https://arxiv.org/pdf/1409.0575) [[`Dataset`🌟]](https://www.image-net.org/challenges/LSVRC/)

* [**ICCV'2013**] ***"The visual object tracking vot2013 challenge results"***, M. Kristan, R. Pflugfelder, A. Leonardis, J. Matas, F. Porikli, L. Cehovin, G. Nebehay, G. Fernandez, T. Vojir, A. Gatt, A. Khajenezhad, A. Salahledin et al. [[`paper`]](https://ieeexplore.ieee.org/document/6755885) [[`Dataset`🌟]](https://votchallenge.net/vot2013/dataset.html)

* [**ECCV'2014**] ***"The visual object tracking vot2014 challenge results"***, M. Kristan, R. P. Pflugfelder, A. Leonardis, J. Matas, L. Cehovin, G. Nebehay, T. Voj ́ır, G. Fern ́andez, A. Lukezic, A. Dimitriev, A. Petrosino, A. Saffari, B. Li, B. Han, C. Heng, C. Garcia et al. [[`paper`]](https://votchallenge.net/vot2014/download/visual-object-tracking.pdf) [[`Dataset`🌟]](https://votchallenge.net/vot2014/dataset.html)

* [**ICCV'2015**] ***"The visual object tracking vot2015 challenge results"***, M. Kristan, J. Matas, A. Leonardis, M. Felsberg, L. Cehovin, G. Fernandez, T. Vojir, G. Hager, G. Nebehay, R. Pflugfelder, A. Gupta, A. Bibi, A. Lukezic, A. Garcia-Martin, A. Saffari, A. Petrosino, and A. Solis Montero. [[`paper`]]https://ieeexplore.ieee.org/document/7406428) [[`Dataset`🌟]](https://votchallenge.net/vot2015/dataset.html)

* [**ECCV'2016**] ***"The visual object tracking vot2016 challenge results"***, M. Kristan, A. Leonardis, J. Matas, M. Felsberg, R. Pflugfelder, L. ˇCehovin, T. Vojı ́ ̃r, G. H ̈ager, A. Lukeˇzicˇ, G. Fern ́andez et al. [[`paper`]](https://data.votchallenge.net/vot2016/presentations/vot_2016_paper.pdf) [[`Dataset`🌟]](https://votchallenge.net/vot2016/dataset.html)

* [**ICCV'2017**] ***"The visual object tracking vot2017 challenge results"***, M. Kristan, A. Leonardis, J. Matas, M. Felsberg, R. Pflugfelder, L. C. Zajc, T. Vojı ́r, G. Ha ̈ger, A. Lukeˇzic, A. Eldesokey et al. [[`paper`]](https://ieeexplore.ieee.org/document/8265440) [[`Dataset`🌟]](https://votchallenge.net/vot2017/dataset.html)

* [**ECCV'2018**] ***"The sixth visual object tracking vot2018 challenge results"***, M. Kristan, A. Leonardis, J. Matas, M. Felsberg, R. Pflugfelder, L. ˇCehovin Zajc, T. Vojir, G. Bhat, A. Lukezic, A. Eldesokey et al. [[`paper`]](https://data.votchallenge.net/vot2018/presentations/vot2018_presentation.pdf) [[`Dataset`🌟]](https://votchallenge.net/vot2018/dataset.html)

* [**ICCV'2019**] ***"The seventh visual object tracking vot2019 challenge results"***, M. Kristan, J. Matas, A. Leonardis, M. Felsberg, R. Pflugfelder, J.K. Kamarainen, L. ˇCehovin Zajc, O. Drbohlav, A. Lukezic, A. Berg et al. [[`paper`]](https://ieeexplore.ieee.org/document/9022051) [[`Dataset`🌟]](https://votchallenge.net/vot2019/dataset.html)

* [**ECCV'2020**] ***"The eighth visual object tracking vot2020 challenge results"***, M. Kristan, A. Leonardis, J. Matas, M. Felsberg, R. Pflugfelder, J.K. K ̈am ̈ar ̈ainen, M. Danelljan, L. ˇC. Zajc, A. Lukezˇiˇc, O. Drbohlav et al. [[`paper`]](https://link.springer.com/chapter/10.1007/978-3-030-68238-5_39) [[`Dataset`🌟]](https://votchallenge.net/vot2020/dataset.html)

* [**ICCV'2021**] ***"The ninth visual object tracking vot2021 challenge results"***, M. Kristan, J. Matas, A. Leonardis, M. Felsberg, R. Pflugfelder, J.K. K ̈am ̈ar ̈ainen, H. J. Chang, M. Danelljan, L. Cehovin, A. Lukezˇiˇc et al. [[`paper`]](https://ieeexplore.ieee.org/document/9607833) [[`Dataset`🌟]](https://votchallenge.net/vot2021/dataset.html)

* [**ECCV'2022**] ***"The tenth visual object tracking vot2022 challenge results"***, M. Kristan, A. Leonardis, J. Matas, M. Felsberg, R. Pflugfelder, J.K. Ka ̈m ̈ara ̈inen, H. J. Chang, M. Danelljan, L. ˇC. Zajc, A. Lukezˇiˇc et al. [[`paper`]](https://link.springer.com/chapter/10.1007/978-3-031-25085-9_25) [[`Dataset`🌟]](https://votchallenge.net/vot2022/dataset.html)

* [**ICCV'2023**] ***"The first visual object tracking segmentation vots2023 challenge results"***, M. Kristan, J. Matas, M. Danelljan, M. Felsberg, H. J. Chang, L. ˇC. Zajc, A. Lukeˇziˇc, O. Drbohlav, Z. Zhang, K.-T. Tran et al. [[`paper`]](https://ieeexplore.ieee.org/document/10350713) [[`Dataset`🌟]](https://votchallenge.net/vot2023/dataset.html)

##### `Large-scall Datasets for Data-centric Research`

* [**CVPR'2009**] ***"Imagenet: A large-scale hierarchical image database"***, J. Deng, W. Dong, R. Socher, L.-J. Li, K. Li, and L. Fei-Fei. [[`paper`]](https://ieeexplore.ieee.org/document/5206848) [[`Dataset`🌟]](https://image-net.org/)

* [**ACM'1995**] ***"Wordnet: a lexical database for english"***, G. A. Miller. [[`paper`]](https://dl.acm.org/doi/pdf/10.1145/219717.219748) [[`Dataset`🌟]](https://wordnet.princeton.edu/)

* [**ECCV'2014**] ***"Microsoft coco: Common objects in context"***, T.-Y. Lin, M. Maire, S. Belongie, J. Hays, P. Perona, D. Ramanan, P. Dolla ́r, and C. L. Zitnick. [[`paper`]](https://arxiv.org/pdf/1405.0312) [[`Dataset`🌟]](https://cocodataset.org/)

* [**CVPR'2019**] ***"Lvis: A dataset for large vocabulary instance segmentation"***, A. Gupta, P. Dollar, and R. Girshick. [[`paper`]](https://ieeexplore.ieee.org/document/8954457) [[`Dataset`🌟]](https://www.lvisdataset.org/)

* [**IJCV'2015**] ***"Imagenet large scale visual recognition challenge"***, O. Russakovsky, J. Deng, H. Su, J. Krause, S. Satheesh, S. Ma, Z. Huang, A. Karpathy, A. Khosla, M. Bernstein et al. [[`paper`]](https://link.springer.com/article/10.1007/s11263-015-0816-y) [[`Dataset`🌟]](https://image-net.org/index.php)

* [**CVPR'2017**] ***"Youtubeboundingboxes: A large high-precision human-annotated data set for object detection in video"***, E. Real, J. Shlens, S. Mazzocchi, X. Pan, and V. Vanhoucke. [[`paper`]](https://arxiv.org/abs/1702.00824) [[`Dataset`🌟]](https://github.com/mbuckler/youtube-bb)

* [**ECCV'2018**] ***"Trackingnet: A large-scale dataset and benchmark for object tracking in the wild"***, M. Muller, A. Bibi, S. Giancola, S. Alsubaihi, and B. Ghanem. [[`paper`]](https://arxiv.org/abs/1803.10794) [[`Dataset`🌟]](https://paperswithcode.com/dataset/trackingnet)

* [**TPAMI'2021**] ***"Got-10k: A large high-diversity benchmark for generic object tracking in the wild"***, L. Huang, X. Zhao, and K. Huang. [[`paper`]](https://ieeexplore.ieee.org/document/8922619) [[`Dataset`🌟]](http://got-10k.aitestunion.com)

* [**ECCV'2018**] ***"Long-term tracking in the wild: A benchmark"***, J. Valmadre, L. Bertinetto, J. F. Henriques, R. Tao, A. Vedaldi, A. W. Smeulders, P. H. Torr, and E. Gavves. [[`paper`]](https://arxiv.org/abs/1803.09502) [[`Dataset`🌟]](https://oxuva.github.io/long-term-tracking-benchmark/)

* [**CVPR'2019**] ***"Lasot: A high-quality benchmark for large-scale single object tracking"***, H. Fan, L. Lin, F. Yang, P. Chu, G. Deng, S. Yu, H. Bai, Y. Xu, C. Liao, and H. Ling. [[`paper`]](https://arxiv.org/abs/2009.03465) [[`Dataset`🌟]](https://cis.temple.edu/lasot/)

* [**TPAMI'2023**] ***"Global Instance Tracking: Locating Target More Like Humans"***, S. Hu, X. Zhao, L. Huang, and K. Huang. [[`paper`]](https://ieeexplore.ieee.org/document/9720246) [[`Dataset`🌟]](http://videocube.aitestunion.com/)

##### `Specialized Scenario Datasets`

* [**CVPR'2012**] ***"Are we ready for autonomous driving? The KITTI vision benchmark suite"***, A. Geiger, P. Lenz, and R. Urtasun. [[`paper`]](https://ieeexplore.ieee.org/document/6248074) [[`Dataset`🌟]](https://www.cvlibs.net/datasets/kitti/)

* [**CVPR'2020**] ***"Bdd100k: A diverse driving dataset for heterogeneous multitask learning"***, F. Yu, H. Chen, X. Wang, W. Xian, Y. Chen, F. Liu, V. Madhavan, and T. Darrell. [[`paper`]](https://arxiv.org/abs/1805.04687) [[`Dataset`🌟]](https://doc.bdd100k.com/download.html)

* [**TPAMI'2016**] ***"Nus-pro: A new visual tracking challenge"***, A. Li, M. Lin, Y. Wu, M.-H. Yang, and S. Yan. [[`paper`]](https://ieeexplore.ieee.org/document/7072555) [[`Dataset`🌟]](https://irip.buaa.edu.cn/anli/buaa)

* [**ICCV'2021**] ***"Transparent object tracking benchmark"***,  H. Fan, H. A. Miththanthaya, S. R. Rajan, X. Liu, Z. Zou, Y. Lin, H. Ling et al. [[`paper`]](https://arxiv.org/abs/2011.10875) [[`Dataset`🌟]](https://hengfan2010.github.io/projects/TOTB/)

* [**AAAI'2017**] ***"Visual object tracking for unmanned aerial vehicles: A benchmark and new motion models"***, S. Li and D.-Y. Yeung. [[`paper`]](https://ojs.aaai.org/index.php/AAAI/article/view/11205) [[`Dataset`🌟]](https://github.com/flyers/drone-tracking)

* [**IJCV'2020**] ***"The unmanned aerial vehicle benchmark: Object detection, tracking and baseline"***, H. Yu, G. Li, W. Zhang, Q. Huang, D. Du, Q. Tian, and N. Sebe. [[`paper`]](https://arxiv.org/abs/1804.00518) [[`Dataset`🌟]](https://sites.google.com/site/daviddo0323/projects/uavdt)

* [**IJCV'2024**] ***"Biodrone: A bionic drone-based single object tracking benchmark for robust vision"***,  X. Zhao, S. Hu, Y. Wang, J. Zhang, Y. Hu, R. Liu, H. Ling, Y. Li, R. Li, K. Liu, and J. Li. [[`paper`]](https://link.springer.com/article/10.1007/s11263-023-01937-0) [[`Dataset`🌟]](http://biodrone.aitestunion.com/)

##### `Datasets in The Era of Large Models`

* [**IJCV'2017**] ***"Visual genome: Connecting language and vision using crowdsourced dense image annotations"***, R. Krishna, Y. Zhu, O. Groth, J. Johnson, K. Hata, J. Kravitz, S. Chen, Y. Kalantidis, L.-J. Li, D. A. Shamma et al. [[`paper`]](https://arxiv.org/abs/1602.07332) [[`Dataset`🌟]](https://homes.cs.washington.edu/~ranjay/visualgenome/api.html)

* [**NeurIPS'2023**] ***"Datacomp: In search of the next generation of multimodal datasets"***,S. Y. Gadre, G. Ilharco, A. Fang, J. Hayase, G. Smyrnis, T. Nguyen, R. Marten, M. Wortsman, D. Ghosh, J. Zhang et al. [[`paper`]](https://arxiv.org/abs/2304.14108) [[`Dataset`🌟]](https://www.datacomp.ai/)

* [**NeurIPS'2022**] ***"Laion-5b: An open large-scale dataset for training next generation image-text models"***,  C. Schuhmann, R. Beaumont, R. Vencu, C. Gordon, R. Wightman, M. Cherti, T. Coombes, A. Katta, C. Mullis, M. Wortsman et al. [[`paper`]](https://arxiv.org/abs/2210.08402) [[`Dataset`🌟]](https://laion.ai/)

* [**CVPR'2022**] ***"Grit: General robust image task benchmark"***, T. Gupta, R. Marten, A. Kembhavi, and D. Hoiem. [[`paper`]](https://arxiv.org/abs/2204.13653) [[`Dataset`🌟]](https://aka.ms/kosmos-2/)

#### `Evaluation System`

##### `Classification and Recognition`
**无
##### `Detection`

* [**CVPR'2019**] ***"Generalized intersection over union: A metric and a loss for bounding box regression"***, H. Rezatofighi, N. Tsoi, J. Gwak, A. Sadeghian, I. Reid, and S. Savarese. [[`paper`]](https://ieeexplore.ieee.org/document/8953982)

* [**AAAI'2020**] ***"Distance-iou loss: Faster and better learning for bounding box regression"***,  Z. Zheng, P. Wang, W. Liu, J. Li, R. Ye, and D. Ren. [[`paper`]](https://ojs.aaai.org/index.php/AAAI/article/view/6999)

* [**ECCV'2014**] ***"Microsoft coco: Common objects in context"***, T.-Y. Lin, M. Maire, S. Belongie, J. Hays, P. Perona, D. Ramanan, P. Dolla ́r, and C. L. Zitnick. [[`paper`]](https://link.springer.com/chapter/10.1007/978-3-319-10602-1_48) [[`Dataset`🌟]](https://cocodataset.org/)

##### `Segmentation`

* [**CVPR'2019**] ***"Panoptic segmentation"***, A. Kirillov, K. He, R. Girshick, C. Rother, and P. Doll ́ar. [[`paper`]](https://arxiv.org/abs/1801.00868)

##### `Tracking`

* [**CVPR'2013**] ***"Online object tracking: A benchmark"***, Y. Wu, J. Lim, and M.-H. Yang. [[`paper`]](https://ieeexplore.ieee.org/document/6619156) [[`Dataset`🌟]](http://cvlab.hanyang.ac.kr/tracker_benchmark/datasets.html)

* [**TPAMI'2021**] ***"Got-10k: A large high-diversity benchmark for generic object tracking in the wild"***, L. Huang, X. Zhao, and K. Huang. [[`paper`]](https://ieeexplore.ieee.org/document/8922619) [[`Dataset`🌟]](http://got-10k.aitestunion.com)

* [**CVPR'2019**] ***"Lasot: A high-quality benchmark for large-scale single object tracking"***, H. Fan, L. Lin, F. Yang, P. Chu, G. Deng, S. Yu, H. Bai, Y. Xu, C. Liao, and H. Ling. [[`paper`]](https://arxiv.org/abs/2009.03465) [[`Dataset`🌟]](https://cis.temple.edu/lasot/)

* [**TPAMI'2015**] ***"Object tracking benchmark"***, Y. Wu, J. Lim, and M.-H. Yang. [[`paper`]](https://ieeexplore.ieee.org/document/7001050) [[`Dataset`🌟]](http://cvlab.hanyang.ac.kr/tracker_benchmark/datasets.html)

* [**CVPR'2013**] ***"Online object tracking: A benchmark"***, Y. Wu, J. Lim, and M.-H. Yang. [[`paper`]](https://ieeexplore.ieee.org/document/6619156) [[`Dataset`🌟]](http://cvlab.hanyang.ac.kr/tracker_benchmark/datasets.html)

* [**ICCV'2015**] ***"The visual object tracking vot2015 challenge results"***, M. Kristan, J. Matas, A. Leonardis, M. Felsberg, L. Cehovin, G. Fernandez, T. Vojir, G. Hager, G. Nebehay, R. Pflugfelder, A. Gupta, A. Bibi, A. Lukezic, A. Garcia-Martin, A. Saffari, A. Petrosino, and A. Solis Montero. [[`paper`]]https://ieeexplore.ieee.org/document/7406428) [[`Dataset`🌟]](https://votchallenge.net/vot2015/dataset.html)

* [**IJCV'2024**] ***"Sotverse: A user-defined task space of single object tracking"***,S. Hu, X. Zhao, and K. Huang. [[`paper`]](https://arxiv.org/abs/2204.07414)

##### `Evaluations in The Era of Large Models`

* [**ECCV'2024**] ***"Mmbench: Is your multi-modal model an all-around player?"***, Z. Y. Liu Yuan, Duan Haodong and L. Dahua. [[`paper`]](https://arxiv.org/abs/2307.06281)

* [**arXiV'2023**] ***"Gpt-4 technical report"***,  J. Achiam, S. Adler, S. Agarwal, L. Ahmad, I. Akkaya, F. L. Aleman, D. Almeida, J. Altenschmidt, S. Altman, S. Anadkat et al. [[`paper`]](https://arxiv.org/abs/2303.08774)

* [**CVPR'2019**] ***"Generalized intersection over union: A metric and a loss for bounding box regression"***, H. Rezatofighi, N. Tsoi, J. Gwak, A. Sadeghian, I. Reid, and S. Savarese. [[`paper`]](https://ieeexplore.ieee.org/document/8953982) [[`Dataset`🌟]](https://www.cs.toronto.edu/~kriz/cifar.html)

#### `Summary and Outlook`

##### `Visual Capability`

* [**Nature'2015**] ***"Deep learning"***, Y. LeCun, Y. Bengio, and G. Hinton. [[`paper`]](https://www.nature.com/articles/nature14539)

* [**ACM'2009**] ***"Imagenet classification with deep convolutional neural networks"***, A. Krizhevsky, I. Sutskever, and G. E. Hinton. [[`paper`]](https://dl.acm.org/doi/10.1145/3065386)

* [**ICLR'2021**] ***"An image is worth 16x16 words: Transformers for image recognition at scale"***, A. Dosovitskiy. [[`paper`]](https://arxiv.org/abs/2010.11929)

* [**NeurIPS'2009**] ***"Attention is all you need"***, A. Vaswani, N. Shazeer, N. Parmar, J. Uszkoreit, L. Jones, A. N. Gomez, Ł. Kaiser, and I. Polosukhin. [[`paper`]](https://arxiv.org/abs/1706.03762)

* [**ECCV'2016**] ***"Fully-convolutional siamese networks for object tracking"***, L. Bertinetto, J. Valmadre, J. F. Henriques, A. Vedaldi, and P. H. Torr. [[`paper`]](https://arxiv.org/abs/1606.09549)

* [**ECCV'2016**] ***"Learning to track at 100 fps with deep regression networks"***,  D. Held, S. Thrun, and S. Savarese. [[`paper`]](https://arxiv.org/abs/1604.01802)

* [**CVPR'2019**] ***"Atom: Accurate tracking by overlap maximization"***,  M. Danelljan, G. Bhat, F. S. Khan, and M. Felsberg. [[`paper`]](https://ieeexplore.ieee.org/document/8953466)

* [**ICCV'2019**] ***"Learning discriminative model prediction for tracking"***,G. Bhat, M. Danelljan, L. V. Gool, and R. Timofte. [[`paper`]](https://arxiv.org/abs/1904.07220)

* [**NeurIPS'2023**] ***"A multi-modal global instance tracking benchmark (mgit): Better locating target in complex spatio-temporal and causal relationship"***, S. Hu, D. Zhang, M. Wu, X. Feng, X. Li, X. Zhao, and K. Huang. [[`paper`]](https://papers.nips.cc/paper_files/paper/2023/file/4ea14e6090343523ddcd5d3ca449695f-Paper-Datasets_and_Benchmarks.pdf)

* [**BBS'2017**] ***"Building machines that learn and think like people"***, B. M. Lake, T. D. Ullman, J. B. Tenenbaum, and S. J. Gershman. [[`paper`]](https://arxiv.org/abs/1604.00289)

##### `Proxy Task`

* [**CVPR'2024**] ***"Visual language tracking with multi-modal interaction: A robust benchmark"***, X. Li, S. Hu, X. Feng, D. Zhang, M. Wu, J. Zhang, and K. Huang. [[`paper`]](https://arxiv.org/abs/2409.08887)

* [**CVPR'2022**] ***"Grit: General robust image task benchmark"***, T. Gupta, R. Marten, A. Kembhavi, and D. Hoiem. [[`paper`]](https://www.cs.toronto.edu/~kriz/learning-features-2009-TR.pdf)

* [**CVPR'2021**] ***"Next-qa: Next phase of question-answering to explaining temporal actions"***,  J. Xiao, X. Shang, A. Yao, and T.-S. Chua. [[`paper`]](https://arxiv.org/abs/2105.08276)

##### `Data Environment`

* [**IEEE'1998**] ***"Gradient-based learning applied to document recognition"***, Y. LeCun, L. Bottou, Y. Bengio, and P. Haffner.[[`paper`]](https://ieeexplore.ieee.org/document/726791)

* [**TR'2009**] ***"Learning multiple layers of features from tiny images"***, A Krizhevsky，G. Hinton. [[`paper`]](https://www.cs.toronto.edu/~kriz/learning-features-2009-TR.pdf) [[`Dataset`🌟]](https://www.cs.toronto.edu/~kriz/cifar.html)

* [**CVPR'2009**] ***"Imagenet: A large-scale hierarchical image database"***, J. Deng, W. Dong, R. Socher, L.-J. Li, K. Li, and L. Fei-Fei. [[`paper`]](https://ieeexplore.ieee.org/document/5206848) [[`Dataset`🌟]](https://image-net.org/)

* [**CVPR'2024**] ***"Dtllm-vlt: Diverse text generation for visual language tracking based on llm"***, X. Li, X. Feng, S. Hu, M. Wu, D. Zhang, J. Zhang, and K. Huang. [[`paper`]](https://arxiv.org/abs/2405.12139)

* [**arXiV'2024**] ***"Dtvlt: A multi-modal diverse text benchmark for visual language tracking based on llm"***, A Krizhevsky，G. Hinton. [[`paper`]](https://arxiv.org/abs/2410.02492)

* [**CVPR'2022**] ***"Ego4d: Around the world in 3,000 hours of egocentric video"***, K. Grauman, A. Westbury, E. Byrne, Z. Chavis, A. Furnari, R. Girdhar, J. Hamburger, H. Jiang, M. Liu, X. Liu et al. [[`paper`]](https://arxiv.org/abs/2110.07058)

* [**CVPR'2018**] ***"Gibson env: Real-world perception for embodied agents"***, F. Xia, A. R. Zamir, Z. He, A. Sax, J. Malik, and S. Savarese. [[`paper`]](https://arxiv.org/abs/1808.10654)

* [**CVPR'2019**] ***"Gqa: A new dataset for realworld visual reasoning and compositional question answering"***,  D. A. Hudson and C. D. Manning. [[`paper`]](https://arxiv.org/abs/1902.09506)

* [**arXiV'2017**] ***"Ai2-thor: An interactive 3d environment for visual ai"***, E. Kolve, R. Mottaghi, W. Han, E. VanderBilt, L. Weihs, A. Herrasti, M. Deitke, K. Ehsani, D. Gordon, Y. Zhu et al. [[`paper`]](https://arxiv.org/abs/1712.05474)

##### `Evaluation System`

* [**arxiv'2017**] ***"Ai2-thor: An interactive 3d environment for visual ai"***, E. Kolve, R. Mottaghi, W. Han, E. VanderBilt, L. Weihs, A. Herrasti, M. Deitke, K. Ehsani, D. Gordon, Y. Zhu et al. [[`paper`]](https://arxiv.org/abs/1712.05474)

* [**NeurIPS'2024**] ***"Beyond accuracy: Tracking more like human via visual search"***, D. Zhang, S. Hu, X. Feng, X. Li, M. Wu, J. Zhang, and K. Huang. [[`paper`]](https://proceedings.neurips.cc/paper_files/paper/2024/hash/050f8591be3874b52fdac4e1060eeb29-Abstract-Conference.html)

* [**CVPR'2018**] ***"Embodied question answering"***, A. Das, S. Datta, G. Gkioxari, S. Lee, D. Parikh, and D. Batra. [[`paper`]](https://arxiv.org/abs/1711.11543)

##### `Evaluation Models`

* [**NeurIPS'2024**] ***"MemVLT: Vision-language tracking with adaptive memory-based prompts"***, X. Feng, X. Li, S. Hu, D. Zhang, M. Wu, J. Zhang, X. Chen, and K. Huang. [[`paper`]](https://openreview.net/forum?id=ZK1CZXKgG5)

* [**arXiv'2023**] ***"Track anything: Segment anything meets videos"***,J. Yang, M. Gao, Z. Li, S. Gao, F. Wang, and F. Zheng. [[`paper`]](https://arxiv.org/abs/2304.11968)

* [**NeurIPS'2022**] ***"Flamingo: a visual language model for few-shot learning"***,  J.-B. Alayrac, J. Donahue, P. Luc, A. Miech, I. Barr, Y. Hasson, K. Lenc, A. Mensch, K. Millican, M. Reynolds et al. [[`paper`]](https://arxiv.org/abs/2204.14198)

* [**ECCV'2022**] ***"Towards grand unification of object tracking"***,  B. Yan, Y. Jiang, P. Sun, D. Wang, Z. Yuan, P. Luo, and H. Lu. [[`paper`]](https://arxiv.org/abs/2207.07078)



6



Evaluation Models - Analyzing The Subject Of Evaluation

1.*Classifcation and Recognition*

- [**ECCV'2004**] ***“Visual categorization with bags of keypoints”***, Gabriella Csurka, Christopher R. Dance, Lixin Fan, Jutta Willamowski, Cédric Bray.[[paper](https://people.eecs.berkeley.edu/~efros/courses/AP06/Papers/csurka-eccv-04.pdf)]
- [**CVPR'2005**] ***“Histograms of oriented gradients for human detection”***,Navneet Dalal and Bill Triggs.[[paper](https://www.computer.org/csdl/proceedings-article/cvpr/2005/237210886/12OmNBgQFOD)]
- [**IEEE'2002**] ***“Multiresolution gray-scale and rotation invariant texture classification with local binary patterns”***,Timo Ojala, Matti PietikaÈinen, Senior Member, IEEE, and Topi MaÈenpaÈa.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1017623)
- [**IEEE'2003**]  ***“Video google: A text retrieval approach to object matching in videos”***, Sivic and Zisserman.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1238663)
- [**IEEE'2006**] ***“Beyond bags of features: Spatial pyramid matching for recognizing natural scene categories”***,Svetlana Lazebnik, Cordelia Schmid, and Jean Ponce.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1641019)
- [**IEEE'1998**]***“Support vector machines”***,M. A. Hearst, S. T. Dumais, E. Osuna, J. Platt, and B. Scholkopf.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=708428)
- [**IEEE'2010**]***“Performance and scalability of gpu-based convolutional neural networks”***,D. Strigl, K. Kofler, and S. Podlipnig .[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=708428)
- [**IVC'2015**] ***“How to use bag-of-words model better for image classification”***,C. Wang and K. Huang.[[paper]](https://dl.acm.org/doi/10.1016/j.imavis.2014.10.013)
- [**IEEE'2009**]***“Linear spatial pyramid matching using sparse coding for image classification”***,J. Yang, K. Yu, Y. Gong, and T. Huang.[[paper]](https://ieeexplore.ieee.org/document/5206757)
- [**science'2006**]***“Reducing the dimensionality of data with neural networks”***,G. E. Hinton and R. R. Salakhutdinov.[[paper]](https://www.science.org/doi/10.1126/science.1127647?url_ver=Z39.88-2003&rfr_id=ori:rid:crossref.org&rfr_dat=cr_pub%20%200pubmed)
- [**NeurIPS'1989**] ***“Handwritten digit recognition with a back-propagation network”***,Y. LeCun, B. Boser, J. Denker, D. Henderson, R. Howard, W. Hubbard, and L. Jackel.[[paper]](https://dl.acm.org/doi/abs/10.5555/2969830.2969879)
- [**NeurIPS'2012**]***“Imagenet classification with deep convolutional neural networks”***,A. Krizhevsky, I. Sutskever, and G. E. Hinton.[[paper]](https://www.nvidia.cn/content/tesla/pdf/machine-learning/imagenet-classification-with-deep-convolutional-nn.pdf)
- [**arXiv'2014**]***“Very deep convolutional networks for large-scale image recognition”***,K. Simonyan and A. Zisserman.[[paper]](https://arxiv.org/pdf/1409.1556)
- [**IEEE'2015**]***“Going deeper with convolutions”***,C. Szegedy, W. Liu, Y. Jia, P. Sermanet, S. Reed, D. Anguelov, D. Erhan, V. Vanhoucke, and A. Rabinovich[.[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7298594)
- [**CVPR'2016**]***“Deep residual learning for image recognition”***,K. He, X. Zhang, S. Ren, and J. Sun.[[paper]](https://ieeexplore.ieee.org/document/7780459)
- [**IEEE'2017**]***“Densely connected convolutional networks”***,G. Huang, Z. Liu, L. Van Der Maaten, and K. Q. Weinberger[.[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8099726)[[code🌟]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8099726)
- [**IEEE'2018**]***“Squeeze-and-excitation networks”***,  J. Hu, L. Shen, and G. Sun.[[paper]](https://arxiv.org/pdf/1709.01507v1)
- [**arXiv'2018**]***“A new channel boosted convolutional neural network using transfer learning”***,A. Khan, A. Sohail, and A. Ali.[[paper]](https://arxiv.org/pdf/1804.08528)
- [**IEEE'2017**]***“Residual attention network for image classification”***,F. Wang, M. Jiang, C. Qian, S. Yang, C. Li, H. Zhang, X. Wang, and X. Tang.[[paper]](https://ieeexplore.ieee.org/document/8100166)
- [**ECCV'2018**]***“Cbam: Convolutional block attention module”***,S. Woo, J. Park, J.-Y. Lee, and I. S. Kweon.[[paper]](https://link.springer.com/chapter/10.1007/978-3-030-01234-2_1)
- [**arXiv'2015**]***“Deep compression: Compressing deep neural networks with pruning, trained quantization and huffman coding”***,S. Han, H. Mao, and W. J. Dally.[[paper]](https://arxiv.org/pdf/1510.00149v2)
- [**IEEE'2016**]***“Quantized convolutional neural networks for mobile devices”***,J. Wu, C. Leng, Y. Wang, Q. Hu, and J. Cheng.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7780890)
- [**arXiv'2016**]***“Paying more attention to attention: Improving the performance of convolutional neural networks via attention transfer”***,S. Zagoruyko and N. Komodakis.[[paper]](https://www.semanticscholar.org/reader/f7b032a4df721d4ed2bab97f6acd33d62477b7a5)[[code🌟]](https://github.com/szagoruyko/attention-transfer)
- [**arXiv'2016**]***“Squeezenet: Alexnet-level accuracy with 50x fewer parameters and¡ 0.5 mb model size”***,F. N. Iandola, S. Han, M. W. Moskewicz, K. Ashraf, W. J. Dally, and K. Keutzer.[[paper]](https://arxiv.org/pdf/1602.07360)[[code🌟]](https://github.com/forresti/SqueezeNet)
- [**arXiv'2017**]***“Mobilenets: Efficient convolutional neural networks for mobile vision applications”***,A. G. Howard, M. Zhu, B. Chen, D. Kalenichenko, W. Wang, T. Weyand, M. Andreetto, and H. Adam.[[paper]](https://arxiv.org/pdf/1704.04861)
- [**IEEE'2018**]***“Shufflenet: An extremely efficient convolutional neural network for mobile devices”***,X. Zhang, X. Zhou, M. Lin, and J. Sun.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8578814)
- [**CVPR'2009**] ***“Imagenet: A large-scale hierarchical image database”***,J. Deng, W. Dong, R. Socher, L.-J. Li, K. Li, and L. Fei-Fei.[[paper]](https://ieeexplore.ieee.org/document/5206848)

2.*Detection*

- [**IJCV'2004**] ***“Robust real-time face detection”***,P. Viola and M. J. Jones.[[paper]](https://link.springer.com/article/10.1023/B:VISI.0000013087.49260.fb)
- [**CVPR'2005**] ***“Histograms of oriented gradients for human detection”***,Navneet Dalal and Bill Triggs.[[paper](https://www.computer.org/csdl/proceedings-article/cvpr/2005/237210886/12OmNBgQFOD)]
- [**IEEE'2008**]***“A discriminatively trained, multiscale, deformable part model”***,P. Felzenszwalb, D. McAllester, and D. Ramanan.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4587597)
- [**IEEE'2014**]***“Rich feature hierarchies for accurate object detection and semantic segmentation”***,R. Girshick, J. Donahue, T. Darrell, and J. Malik.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6909475)[[code🌟]](http://www.cs.berkeley.edu/~rbg/rcnn)
- [**IEEE'2015**]**“Fast r-*cnn*****”**,R. Girshick.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7410526)[[code🌟]](https://github.com/rbgirshick/fast-rcnn)
- [**NIPS'2016**]“Faster r-cnn: Towards real-time object detection with region proposal networks”,S. Ren, K. He, R. Girshick, and J. Sun.[[paper]](https://ieeexplore.ieee.org/document/7485869)
- [**IEEE'2017**]“***Feature pyramid networks for object detection”***,T.-Y. Lin, P. Doll´ar, R. Girshick, K. He, B. Hariharan, and S. Belongie.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8099589)
- [**IEEE'2016**]***“You only look once: Unified, real-time object detection”***,J. Redmon, S. Divvala, R. Girshick, and A. Farhadi.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7780460)
- [**IEEE'2017**]***“Yolo9000: better, faster, stronger”***,J. Redmon and A. Farhadi.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8100173)
- [**ECCV'2016**]***“Ssd: Single shot multibox detector”***,W. Liu, D. Anguelov, D. Erhan, C. Szegedy, S. Reed, C.-Y. Fu, and A. C. Berg.[[paper]](https://link.springer.com/content/pdf/10.1007/978-3-319-46448-0_2.pdf)[[code🌟]](https://github.com/weiliu89/caffe/tree/ssd)
- [**IEEE'2017**]***“Focal loss for dense object detection”***,T.-Y. Lin, P. Goyal, R. Girshick, K. He, and P. Doll´ar.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8237586)
- [**ICCV'2019**]***“FCOS: Fully convolutional one stage object detection”***,Z. Tian, C. Shen, H. Chen, and T. He Z. Tian, C. Shen, H. Chen, and T. He.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9010746)[[code🌟]](https://tinyurl.com/FCOSv1)
- [**arXiv'2020**]***“Deformable detr: Deformable transformers for end-to-end object detection”***,X. Zhu, W. Su, L. Lu, B. Li, X. Wang, and J. Dai.[[paper]](https://arxiv.org/pdf/2010.04159v1)
- [**ECCV'2020**]***“End-to-end object detection with transformers”***,N. Carion, F. Massa, G. Synnaeve, N. Usunier, A. Kirillov, and S. Zagoruyko.[[paper]](https://link.springer.com/chapter/10.1007/978-3-030-58452-8_13)[[code🌟]](https://github.com/facebookresearch/detr)
- [**ICCV'2021**]***“Swin transformer: Hierarchical vision transformer using shifted windows”***,Z. Liu, Y. Lin, Y. Cao, H. Hu, Y. Wei, Z. Zhang, S. Lin, and B. Guo.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9710580)[[code🌟]](https://github.com/microsoft/Swin-Transformer)
- [**CVPR'2023**]***“Feature aggregated queries for transformer-based video object detectors”***,Y. Cui.[[paper]](https://ieeexplore.ieee.org/document/10204854)[[code🌟]](https://github.com/YimingCuiCuiCui/FAQ)
- [**IEEE'2018**]***“Non-local neural networks”***,X. Wang, R. Girshick, A. Gupta, and K. He.[[paper]](https://ieeexplore.ieee.org/document/8578911)
- [**CVPR'2021**]***“You only look one-level feature”***,Q. Chen, Y. Wang, T. Yang, X. Zhang, J. Cheng, and J. Sun.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9578360)[[code🌟]](https://github.com/megvii-model/YOLOF)
- [**arXiv'2020**]***“Segment anything”***,A. Kirillov, E. Mintun, N. Ravi, H. Mao, C. Rolland, L. Gustafson,
-  T. Xiao, S. Whitehead, A. C. Berg, W.-Y. Lo *et al*.[[paper]](https://arxiv.org/pdf/2304.02643)

3.*Segmentation*

- [**IEEE'2001**]***“Interactive graph cuts for optimal boundary & region segmentation of objects in nd images”***,Y. Y. Boykov and M.-P. Jolly.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=937505)
- [**TOG'2004**]***“” grabcut” interactive foreground extraction using iterated graph cuts”***,C. Rother, V. Kolmogorov, and A. Blake.[[paper]](https://dl.acm.org/doi/pdf/10.1145/1186562.1015720)
- [**IEEE'2010**]***“Image segmentation and shape analysis for road-sign detection”***, J. F. Khan, S. M. Bhuiyan, and R. R. Adhami.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=5597944)
- [**IEEE'1986**]***“A computational approach to edge detection”***,J. Canny.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4767851)
- [**IEEE'1991**]***“Watersheds in digital spaces: an efficient algorithm based on immersion simulations”***,L. Vincent and P. Soille.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=87344)
- [**IEEE'1995**]***“Mean shift, mode seeking, and clustering”***, Y. Cheng.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=400568)
- [**IEEE'2012**]***“Slic superpixels compared to state-of-the-art superpixel methods”***,R. Achanta, A. Shaji, K. Smith, A. Lucchi, P. Fua, and S. S¨usstrunk.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6205760)
- [**IEEE'2001**]***“Interactive graph cuts for optimal boundary & region segmentation of objects in nd images”***,Y. Y. Boykov and M.-P. Jolly.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=937505)
- [**TOG'2004**]***“” grabcut” interactive foreground extraction using iterated graph cuts”***,C. Rother, V. Kolmogorov, and A. Blake.[[paper]](https://dl.acm.org/doi/pdf/10.1145/1186562.1015720)
- [**IEEE'2015**]***“Fully convolutional networks for semantic segmentation”***,J. Long, E. Shelhamer, and T. Darrell.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7298965)
- [**IEEE'2016**]***“Efficient piecewise training of deep structured models for semantic segmentation”***,G. Lin, C. Shen, A. Van Den Hengel, and I. Reid.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7780717)
- [**IEEE'2018**]***“Context encoding for semantic segmentation”***,H. Zhang, K. Dana, J. Shi, Z. Zhang, X. Wang, A. Tyagi, and A. Agrawal.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8578845)
- [**arXiv'2022**]***“Vision transformer adapter for dense predictions”***,Z. Chen, Y. Duan, W. Wang, J. He, T. Lu, J. Dai, and Y. Qiao.[[paper]](https://www.semanticscholar.org/reader/c431408780586268e8bcf2483b01a80728d10960)[[code🌟]](https://github.com/czczup/ViT-Adapter)
- [**arXiv'2021**]***“Efficient self-ensemble for semantic segmentation”***, W. Bousselham, G. Thibault, L. Pagano, A. Machireddy, J. Gray, Y. H. Chang, and X. Song.[[paper]](https://arxiv.org/pdf/2111.13280v1)[[code🌟]](https://github.com/WalBouss/SenFormer)
- [**arXiv'2018**]***“Panoptic segmentation with a joint semantic and instance segmentation network”***,D. De Geus, P. Meletis, and G. Dubbelman.[[paper]](https://www.semanticscholar.org/reader/50d6dcec7f1fcbde647237d43950fa5ec59d6984)
- [**CVPR'2021**]***“Detectors: Detecting objects with recursive feature pyramid and switchable atrous convolution”***,S. Qiao, L.-C. Chen, and A. Yuille.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9578795)[[code🌟]](https://github.com/joe-siyuan-qiao/DetectoRS)
- [**CVPR'2022**]***“Panoptic segformer: Delving deeper into panoptic segmentation with transformers”***,Z. Li, W. Wang, E. Xie, Z. Yu, A. Anandkumar, J. M. Alvarez, P. Luo, and T. Lu.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9878498)
- [**CVPR'2023**]***“Mask dino: Towards a unified transformer-based framework for object detection and segmentation”***,F. Li, H. Zhang, H. Xu, S. Liu, L. Zhang, L. M. Ni, and H.-Y.Shum.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10204168)[[code🌟]](https://github.com/IDEA-Research/MaskDINO)
- [**IEEE'2017**]***“Segnet: A deep convolutional encoder-decoder architecture for image segmentation”***,V. Badrinarayanan, A. Kendall, and R. Cipolla.[[paper]](https://arxiv.org/pdf/1511.00561)
- [**CVPR'2019**]***“Auto-deeplab: Hierarchical neural architecture search for semantic image segmentation”***,C. Liu, L.-C. Chen, F. Schroff, H. Adam, W. Hua, A. L. Yuille, and L. Fei-Fei.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8954247)
- [**IEEE'2017**]***“Pyramid scene parsing network”***,H. Zhao, J. Shi, X. Qi, X. Wang, and J. Jia.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8100143)
- [**IEEE'2017**]***“Deeplab: Semantic image segmentation with deep convolutional nets, atrous convolution, and fully connected crfs”***，L.-C. Chen, G. Papandreou, I. Kokkinos, K. Murphy, and A. L. Yuille[.[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7913730)
- [***MICCAI*'2015**] “U-net: Convolutional networks for biomedical image segmentation”,O. Ronneberger, P. Fischer, and T. Brox.[[paper]](https://link.springer.com/chapter/10.1007/978-3-319-24574-4_28?utm_source=commission_junction_authors&utm_content=deeplink)[[code🌟]](https://lmb.informatik.uni-freiburg.de/people/ronneber/u-net/)
- [**IEEE'2017**]***“Refinenet: Multi-path refinement networks for high-resolution semantic segmentation”***,G. Lin, A. Milan, C. Shen, and I. Reid.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8100032)
- [**IEEE'2018**]***“Path aggregation network for instance segmentation”***,S. Liu, L. Qi, H. Qin, J. Shi, and J. Jia.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8579011)
- [**arXiv'2014**]***“Fully convolutional multi-class multiple instance learning”***,D. Pathak, E. Shelhamer, J. Long, and T. Darrell.[[paper]](https://www.semanticscholar.org/reader/3b2ccc97f1433cf8750a2ad5a05555ccd10e9cdf)
- [**IEEE'2015**]***“Constrained convolutional neural networks for weakly supervised segmentation”***,D. Pathak, P. Krahenbuhl, and T. Darrell.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7410566)
- [**IEEE'2015**]***“Boxsup: Exploiting bounding boxes to supervise convolutional networks for semantic segmentation”***,J. Dai, K. He, and J. Sun.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7410548)
- [**ECCV'2016**]***“What’s the point: Semantic segmentation with point supervision”***,A. Bearman, O. Russakovsky, V. Ferrari, and L. Fei-Fei.[[paper]](https://link.springer.com/content/pdf/10.1007/978-3-319-46478-7_34.pdf)
- [**IEEE'2016**]***“Scribblesup: Scribble supervised convolutional networks for semantic segmentation”***,D. Lin, J. Dai, J. Jia, K. He, and J. Sun.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7780713)
- [**IEEE'2017**]***“Deep watershed transform for instance segmentation”***,M. Bai and R. Urtasun.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8099788)
- [**IEEE'2017**]***“Instancecut: from edges to instances with multicut”***,A. Kirillov, E. Levinkov, B. Andres, B. Savchynskyy, and C. Rother.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8100257)
- [**IEEE'2017**]***“Proposal-free network for instance-level object segmentation”***,X. Liang, L. Lin, Y. Wei, X. Shen, J. Yang, and S. Yan.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8118129)
- [**IEEE'2017**]***“Mask r-cnn”***,K. He, G. Gkioxari, P. Doll´ar, and R. Girshick.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8237584)
- [**IEEE'2018**]***“Masklab: Instance segmentation by refining object detection with semantic and direction features”***,L.-C. Chen, A. Hermans, G. Papandreou, F. Schroff, P. Wang, and H. Adam.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8578520)
- [**IEEE'2018**]***“Path aggregation network for instance segmentation”***,S. Liu, L. Qi, H. Qin, J. Shi, and J. Jia.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8579011)
- [**CVPR'2019**]***“Tensormask: A foundation for dense object segmentation”***,X. Chen, R. Girshick, K. He, and P. Doll´ar.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9010024)
- [**CVPR'2020**]***“Polarmask: Single shot instance segmentation with polar representation”***,E. Xie, P. Sun, X. Song, W. Wang, X. Liu, D. Liang, C. Shen, and P. Luo.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9157078)
- [**CVPR'2019**]***“Panoptic feature pyramid networks”***,A. Kirillov, R. Girshick, K. He, and P. Doll´ar.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8954091)
- [**CVPR'2019**]***“Attention-guided unified network for panoptic segmentation”***,Y. Li, X. Chen, Z. Zhu, L. Xie, G. Huang, D. Du, and X. Wang.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8953369)
- [**CVPR'2020**]***“Banet: Bidirectional aggregation network with occlusion handling for panoptic segmentation”***,Y. Chen, G. Lin, S. Li, O. Bourahla, Y. Wu, F. Wang, J. Feng, M. Xu, and X. Li.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9156743)[[code🌟]]()
- [**CVPR'2020**]***“Bidirectional graph reasoning network for panoptic segmentation”***,Y. Wu, G. Zhang, Y. Gao, X. Deng, K. Gong, X. Liang, and L. Lin.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9157651)
- [**CVPR'2020**]***“Learning instance occlusion for panoptic segmentation”***,J. Lazarow, K. Lee, K. Shi, and Z. Tu.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9156930)
- [**IEEE'2015**]***“Fully convolutional networks for semantic segmentation”***,J. Long, E. Shelhamer, and T. Darrell.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7298965)
- [**arXiv'2022**]***“Vision transformer adapter for dense predictions”***,Z. Chen, Y. Duan, W. Wang, J. He, T. Lu, J. Dai, and Y. Qiao.[[paper]](https://www.semanticscholar.org/reader/c431408780586268e8bcf2483b01a80728d10960)[[code🌟]](https://github.com/czczup/ViT-Adapter)
- [**CVPR'2019**]***“Atom: Accurate tracking by overlap maximization”***,M. Danelljan, G. Bhat, F. S. Khan, and M. Felsberg.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8953466)[[code🌟]](https://github.com/visionml/pytracking)
- [**CVPR'2019**]***“Learning discriminative model prediction for tracking”***,G. Bhat, M. Danelljan, L. V. Gool, and R. Timofte.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9010649)[[code🌟]](https://github.com/visionml/pytracking)
- [**CVPR'2020**]***“Siam r-cnn: Visual tracking by re-detection”***,P. Voigtlaender, J. Luiten, P. H. Torr, and B. Leibe.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9156711)[[code🌟]](www.vision.rwth-aachen.de/page/siamrcnn)
- [**CVPR'2021**] ***“Transformer tracking”***,X. Chen, B. Yan, J. Zhu, D. Wang, X. Yang, and H. Lu.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9578609)[[code🌟]](https://github.com/chenxin-dlut/TransT)
- [**ECCV'2025**]***“Tracking meets lora: Faster training, larger model, stronger performance”***, L. Lin, H. Fan, Z. Zhang, Y. Wang, Y. Xu, and H. Ling.[[paper]](https://link.springer.com/chapter/10.1007/978-3-031-73232-4_17)[[code🌟]](https://github.com/LitingLin/LoRAT)
- [**CVPR'2022**]***“Mixformer: End-to-end tracking with iterative mixed attention”***,Y. Cui, C. Jiang, L. Wang, and G. Wu.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10380715)
- [**CVPR'2023**]***“Integrating boxes and masks: A multi object framework for unified visual tracking and segmentation”***,Y. Xu, Z. Yang, and Y. Yang.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10378149)[[code🌟]](https://github.com/yoxu515/MITS)

4.*Tracking*

- [**IJCV'2008**]***“Incremental learning for robust visual tracking”***,D. A. Ross, J. Lim, R.-S. Lin, and M.-H. Yang.[[paper]](https://link.springer.com/article/10.1007/s11263-007-0075-7)
- [**IEEE'2015**]***“Tensor pooling for online visual tracking”***,L. Huang and B. Ma.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7177452)
- [**Conference on Computer Vision'2014**]***“Meem: robust tracking via multiple experts using entropy minimization”***,J. Zhang, S. Ma, and S. Sclaroff.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7177452)
- [**ECCV'2012**]***“Exploiting the circulant structure of tracking-by-detection with kernels”***,J. F. Henriques, R. Caseiro, P. Martins, and J. Batista.[[paper]](https://link.springer.com/chapter/10.1007/978-3-642-33765-9_50)
- [**IEEE'2015**]***“Struck: Structured output tracking with kernels”***,S. Hare, S. Golodetz, A. Saffari, V. Vineet, M.-M. Cheng, S. L. Hicks, and P. H. Torr.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7360205)
- [**IEEE'2014**]***“High-speed tracking with kernelized correlation filters”***, J. F. Henriques, R. Caseiro, P. Martins, and J. Batista.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6870486)
- [**IEEE'2017**]***“Visual tracking by sampling in part space”***, L. Huang, B. Ma, J. Shen, H. He, L. Shao, and F. Porikli.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8016595)
- [**IJCV'2013**]“***Robust visual tracking via structured multi-task sparse learning”***,T. Zhang, B. Ghanem, S. Liu, and N. Ahuja.[[paper]](https://ieeexplore.ieee.org/document/6247908)
- [**CVPR'2012**] ***“Real time robust l1 tracker using accelerated proximal gradient approach”***,C. Bao, Y. Wu, H. Ling, and H. Ji.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6247881)
- [**CVPR'2017**]***“Eco: Efficient convolution operators for tracking”***, M. Danelljan, G. Bhat, F. Shahbaz Khan, and M. Felsberg.[[paper]](https://ieeexplore.ieee.org/document/8100216)
- [**CVPR'2010**]***“Visual object tracking using adaptive correlation filters”***,D. S. Bolme, J. R. Beveridge, B. A. Draper, and Y. M. Lui.[[paper]](https://ieeexplore.ieee.org/document/5539960)
- [**CVPR'2015**]***“Convolutional features for correlation filter based visual tracking”***,M. Danelljan, G. Hager, F. Shahbaz Khan, and M. Felsberg.[[paper]](https://ieeexplore.ieee.org/document/7406433)
- [**ICCV'2015**]***“Hierarchical convolutional features for visual tracking”***,C. Ma, J.-B. Huang, X. Yang, and M.-H. Yang.[[paper]](https://ieeexplore.ieee.org/document/7410709)
- [**ECCV'2018**]***“Unveiling the power of deep tracking”***,G. Bhat, J. Johnander, M. Danelljan, F. S. Khan, and M. Felsberg.[[paper]](https://arxiv.org/pdf/1804.06833)
- [**CVPR'2019**]***“Siamrpn++: Evolution of siamese visual tracking with very deep networks”***,B. Li, W. Wu, Q. Wang, F. Zhang, J. Xing, and J. Yan.[[paper]](https://ieeexplore.ieee.org/document/8954116)
- [**ECCV'**]***“Ocean: Object-aware anchor-free tracking”***,Z. Zhang, H. Peng, J. Fu, B. Li, and W. Hu.[[paper]](https://arxiv.org/pdf/2006.10721)[[code🌟]](https://github.com/researchmm/TracKit)
- [**AAAI'2020**]***“Siamfc++: Towards robust and accurate visual tracking with target estimation guidelines”***, Y. Xu, Z. Wang, Z. Li, Y. Yuan, and G. Yu.[[paper]](https://www.researchgate.net/publication/342535862_SiamFC_Towards_Robust_and_Accurate_Visual_Tracking_with_Target_Estimation_Guidelines)
- [**CVPR'2020**]***“Siamcar: Siamese fully convolutional classification and regression for visual tracking”***,D. Guo, J. Wang, Y. Cui, Z. Wang, and S. Chen.[[paper]](https://ieeexplore.ieee.org/document/9157720)[[code🌟]](https://github.com/ohhhyeahhh/SiamCAR)
- [**CVPR'2019**]***“Atom: Accurate tracking by overlap maximization”***,M. Danelljan, G. Bhat, F. S. Khan, and M. Felsberg.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8953466)[[code🌟]](https://github.com/visionml/pytracking)
- [**CVPR'2019**]***“Learning discriminative model prediction for tracking”***,G. Bhat, M. Danelljan, L. V. Gool, and R. Timofte.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9010649)[[code🌟]](https://github.com/visionml/pytracking)
- [**CVPR'2021**]***“Learning target candidate association to keep track of what not to track”***,C. Mayer, M. Danelljan, D. P. Paudel, and L. Van Gool.[[paper]](https://ieeexplore.ieee.org/document/9710884)[[code🌟]](https://github.com/visionml/pytracking)
- [**AAAI'2020**]***“Globaltrack: A simple and strong baseline for long-term tracking”***,L. Huang, X. Zhao, and K. Huang.[[paper]](https://www.researchgate.net/publication/342540676_GlobalTrack_A_Simple_and_Strong_Baseline_for_Long-Term_Tracking)
- [**IEEE'2011**]***“Tracking-learning-detection”***,Z. Kalal, K. Mikolajczyk, and J. Matas.[[paper]](https://ieeexplore.ieee.org/document/6104061)
- [**ICCV'2019**]***“Skimming-perusal tracking: A framework for real-time and robust long-term tracking”***, B. Yan, H. Zhao, D. Wang, H. Lu, and X. Yang.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9009511&tag=1)[[code🌟]](https://github.com/iiau-tracker/SPLT)
- [**CVPR'2020**]***“Siam r-cnn: Visual tracking by re-detection”***,P. Voigtlaender, J. Luiten, P. H. Torr, and B. Leibe.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9156711)[[code🌟]](www.vision.rwth-aachen.de/page/siamrcnn)
- [**arXiv'2021**]***“Target transformed regression for accurate tracking”***,Y. Cui, C. Jiang, L. Wang, and G. Wu.[[paper]](https://www.semanticscholar.org/reader/0841aef61d9459d5809a2b9d2230a7a433979d80)[[code🌟]](https://github.com/MCG-NJU/TREG)
- [**CVPR'2021**]***“Transformer meets tracker: Exploiting temporal context for robust visual tracking”***,N. Wang, W. Zhou, J. Wang, and H. Li.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9578157)
- [**ICCV'2021**]***“Learning spatio-temporal transformer for visual tracking”***,B. Yan, H. Peng, J. Fu, D. Wang, and H. Lu.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9710846)[[code🌟]](https://github.com/researchmm/Stark)
- [**ICCV'2021**] ***“High-performance discriminative tracking with transformers”***,B. Yu, M. Tang, L. Zheng, G. Zhu, J. Wang, H. Feng, X. Feng, and H. Lu.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9710969)
- [**NeurIPS'2022**]***“Swintrack: A simple and strong baseline for transformer tracking”***,L. Lin, H. Fan, Z. Zhang, Y. Xu, and H. Ling.[[paper]](https://arxiv.org/pdf/2112.00995)[[code🌟]](https://github.com/LitingLin/SwinTrack)
- [**arXiv'2024**]***“Correlation-embedded transformer tracking: A single-branch framework”***,F. Xie, W. Yang, C. Wang, L. Chu, Y. Cao, C. Ma, and W. Zeng.[[paper]](https://arxiv.org/pdf/2401.12743)
- [**ECCV'2022**]***“Joint feature learning and relation modeling for tracking: A one-stream framework”***,B. Ye, H. Chang, B. Ma, S. Shan, and X. Chen.[[paper]](https://www.semanticscholar.org/reader/c1329f91cfa11011712227c8765fbbe38b9f2b7e)[[code🌟]](https://github.com/botaoye/OSTrack)
- [**IEEE'2024**]***“Overlapped trajectory-enhanced visual tracking”***,L. Shen, X. Fan, and H. Li.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10630872)[[code🌟]](https://github.com/OrigamiSL/OTETrac)
- [**CVPR'2019**]***“Atom: Accurate tracking by overlap maximization”***,M. Danelljan, G. Bhat, F. S. Khan, and M. Felsberg.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8953466)[[code🌟]](https://github.com/visionml/pytracking)
- [**CVPR'2019**]***“Learning discriminative model prediction for tracking”***,G. Bhat, M. Danelljan, L. V. Gool, and R. Timofte.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9010649)[[code🌟]](https://github.com/visionml/pytracking)
- [**CVPR'2020**]***“Siam r-cnn: Visual tracking by re-detection”***,P. Voigtlaender, J. Luiten, P. H. Torr, and B. Leibe.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9156711)[[code🌟]](www.vision.rwth-aachen.de/page/siamrcnn)
- [**CVPR'2021**] ***“Transformer tracking”***,X. Chen, B. Yan, J. Zhu, D. Wang, X. Yang, and H. Lu.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9578609)[[code🌟]](https://github.com/chenxin-dlut/TransT)
- [**ECCV'2025**]***“Tracking meets lora: Faster training, larger model, stronger performance”***, L. Lin, H. Fan, Z. Zhang, Y. Wang, Y. Xu, and H. Ling.[[paper]](https://link.springer.com/chapter/10.1007/978-3-031-73232-4_17)[[code🌟]](https://github.com/LitingLin/LoRAT)
- [**CVPR'2022**]***“Mixformer: End-to-end tracking with iterative mixed attention”***,Y. Cui, C. Jiang, L. Wang, and G. Wu.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10380715)
- [**CVPR'2023**]***“Integrating boxes and masks: A multi object framework for unified visual tracking and segmentation”***,Y. Xu, Z. Yang, and Y. Yang.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10378149)[[code🌟]](https://github.com/yoxu515/MITS)

5.*Algorithms in The Era of Large Models*

- [**PMLR'2021**]***“Learning transferable visual models from natural language supervision”***,A. Radford, J. W. Kim, C. Hallacy, A. Ramesh, G. Goh, S. Agarwal, G. Sastry, A. Askell, P. Mishkin, J. Clark *et al*.[[paper]](https://www.semanticscholar.org/reader/6f870f7f02a8c59c3e23f407f3ef00dd1dcf8fc4)[[code🌟]](https://github.com/OpenAI/CLIP)
- [**PMLR'2022**]***“Blip: Bootstrapping language-image pre-training for unified vision-language understanding and generation”***,J. Li, D. Li, C. Xiong, and S. Hoi.[[paper]](https://arxiv.org/pdf/2201.12086v2)[[code🌟]](https://github.com/salesforce/BLIP)
- [**PMLR'2023**]***“Blip-2: Bootstrapping language image pre-training with frozen image encoders and large language models”***,J. Li, D. Li, S. Savarese, and S. Hoi.[[paper]](https://arxiv.org/pdf/2301.12597v1)[[code🌟]](https://github.com/salesforce/LAVIS/tree/main/projects/blip2)
- [**NeurIPS'2021**]***“Align before fuse: Vision and language representation learning with momentum distillation”***,J. Li, R. Selvaraju, A. Gotmare, S. Joty, C. Xiong, and S. C. H. Hoi.[[paper]](https://www.semanticscholar.org/reader/b82c5f9efdb2ae56baa084ca41aeddd8a665c1d1)[[code🌟]](https://github.com/salesforce/ALBEF)
- [**arXiv'2023**]***“Qwen-vl: A frontier large vision-language model with versatile abilities”***,J. Bai, S. Bai, S. Yang, S. Wang, S. Tan, P. Wang, J. Lin, C. Zhou, and J. Zhou.[[paper]](https://arxiv.org/pdf/2308.12966)[[code🌟]](https://github.com/QwenLM/Qwen-VL)
- [**arXiv'2023**]***“Grounding dino: Marrying dino with grounded pre-training for open-set object detection”***,S. Liu, Z. Zeng, T. Ren, F. Li, H. Zhang, J. Yang, C. Li, J. Yang, H. Su, J. Zhu *et al.[[paper]](https://dl.acm.org/doi/abs/10.1007/978-3-031-72970-6_3)
- [**CVPR'2024**]***“Osprey: Pixel understanding with visual instruction tuning”***,Y. Yuan, W. Li, J. Liu, D. Tang, X. Luo, C. Qin, L. Zhang, and J. Zhu.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10656218)[[code🌟]](https://github.com/CircleRadon/Osprey)
- [**ECCV'2025**]***“Controlcap: Controllable region-level captioning”***,Y. Zhao, Y. Liu, Z. Guo, W. Wu, C. Gong, Q. Ye, and F. Wan.[[paper]](https://link.springer.com/chapter/10.1007/978-3-031-72920-1_2)[[code🌟]](https://github.com/callsys/ControlCap)
- [**ECCV'2022**]***“Towards grand unification of object tracking”***,B. Yan, Y. Jiang, P. Sun, D. Wang, Z. Yuan, P. Luo, and H. Lu.[[paper]](https://dl.acm.org/doi/10.1007/978-3-031-19803-8_43)[[code🌟]](https://github.com/MasterBin-IIAU/Unicorn)
- [**CVPR'2023**]***“Universal instance perception as object discovery and retrieval”***,B. Yan, Y. Jiang, J. Wu, D. Wang, P. Luo, Z. Yuan, and H. Lu.[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10205057)[[code🌟]](https://github.com/MasterBin-IIAU/UNINEXT)
- [**arXiv'2023**]***“Track anything: Segment anything meets videos”***,J. Yang, M. Gao, Z. Li, S. Gao, F. Wang, and F. Zheng.[[paper]](https://arxiv.org/abs/2304.11968)[[code🌟]](https://github.com/gaomingqi/Track-Anything)
- [**ECCV'2022**]“***Xmem: Long-term video object segmentation with an atkinson-shiffrin memory model”***,H. K. Cheng and A. G. Schwing.[[paper]](https://link.springer.com/chapter/10.1007/978-3-031-19815-1_37)[[code🌟]](https://hkchengrex.github.io/XMem)
- [**arXiv'2023**]***“Segment and track anything”***,Y. Cheng, L. Li, Y. Xu, X. Li, Z. Yang, W. Wang, and Y. Yang.[[paper]](https://www.semanticscholar.org/reader/bbdc4118df106d4ba7af9d7d94d7f0a1144c11e2)[[code🌟]](https://github.com/z-x-yang/Segment-and-Track-Anything)

6.*Summary*




