# Awesome 3D Object Reconstruction from Single-View [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

A curated list of related resources for 3d reconstruction from single view, including 3d object reconstruction, 6D object pose estimation and hand-object reconstruction.

Due to my personal interests, multi-view based work (SFM-based or SLAM-based work) are not collected here. Those papers can be found [here](https://github.com/openMVG/awesome_3DReconstruction_list).

Another related paper list is about the hand pose estimation, which can be found [here](https://github.com/xinghaochen/awesome-hand-pose-estimation).

## Contents
 <!-- - [Evaluation](#evaluation) -->
 - [arXiv Papers](#arxiv-papers)
 - [Journal Papers](#journal-papers)
   - [TPAMI / IJCV](#tpami--ijcv)
   - [Others](#other-journals)
 - [Conference Papers](#conference-papers)
   - 2020: [CVPR](#2020-cvpr), [ECCV](#2020-eccv), [Others](#2020-others)
 - [Theses](#theses)
 - [Datasets](#datasets)
   - [Depth](#depth)
   - [RGB+Depth](#rgbdepth)
   - [RGB](#rgb)
 - [Workshops](#workshops)
 - [Challenges](#challenges)
 - [Researchers](#Researchers)

\* indicates equal contribution

<!-- ## Evaluation
See folder [``evaluation``](./evaluation) to get more details about performance evaluation for hand pose estimation. -->

## arXiv Papers

##### • [\[arXiv:2012.06475\]](https://arxiv.org/abs/2012.06475) EventHands: Real-Time Neural 3D Hand Reconstruction from an Event Stream. [\[PDF\]](https://arxiv.org/pdf/2012.06475.pdf)  [\[Project\]](https://gvv.mpi-inf.mpg.de/projects/EventHands/)
_Viktor Rudnev, Vladislav Golyanik, Jiayi Wang, Hans-Peter Seidel, Franziska Mueller, Mohamed Elgharib, Christian Theobalt_


[\[back to top\]](#contents)

## Journal Papers

### TPAMI / IJCV

##### • \[2018 TPAMI\] Dense 3D Object Reconstruction from a Single Depth View. [\[PDF\]](https://arxiv.org/pdf/1802.00411.pdf)
_Bo Yang, Stefano Rosa, Andrew Markham, Niki Trigoni, Hongkai Wen_

[\[back to top\]](#contents)

### Other Journals

##### • \[2020 TIP\] Weakly-supervised Learning for Single Depth based Hand Shape Recovery. [\[PDF\]](https://ieeexplore.ieee.org/document/9262071)
_Xiaoming Deng, Yuying Zhu, Yinda Zhang, Zhaopeng Cui, Ping Tan, Wentian Qu, Cuixia Ma, Hongan Wang_


[\[back to top\]](#contents)

## Conference Papers

### 2020 ECCV

##### • GRAB: A Dataset of Whole-Body Human Grasping of Objects. [\[PDF\]](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123490562.pdf) [\[Project\]](https://grab.is.tue.mpg.de/) [\[Code\]](https://github.com/otaheri/GrabNet)
_Omid Taheri, Nima Ghorbani, Michael J. Black, Dimitrios Tzionas_

##### • Monocular Expressive Body Regression through Body-Driven Attention. [\[PDF\]](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123550018.pdf) [\[Project\]](https://expose.is.tue.mpg.de/en) [\[Code\]](https://github.com/vchoutas/expose)
_Vasileios Choutas, Georgios Pavlakos, Timo Bolkart, Dimitrios Tzionas , Michael J. Black_

##### • The Phong Surface: Efficient 3D Model Fitting using Lifted Optimization. [\[PDF\]](https://arxiv.org/pdf/2007.04940) *(Oral)*
_Jingjing Shen, Thomas J. Cashman, Qi Ye, Tim Hutton, Toby Sharp, Federica Bogo, Andrew William Fitzgibbon, Jamie Shotton_

##### • Whole-Body Human Pose Estimation in the Wild. [\[PDF\]](https://arxiv.org/pdf/2007.11858.pdf) [\[Code\]](https://github.com/jin-s13/COCO-WholeBody)
_Sheng Jin, Lumin Xu, Jin Xu, Can Wang, Wentao Liu, Chen Qian, Wanli Ouyang, Ping Luo_

##### • Dual Grid Net: hand mesh vertex regression from single depth maps. [\[PDF\]](https://arxiv.org/pdf/1907.10695.pdf)
_Chengde Wan, Thomas Probst, Luc Van Gool, Angela Yao_

##### • Hand-Transformer: Non-Autoregressive Structured Modeling for 3D Hand Pose Estimation. [\[PDF\]](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123700018.pdf)
_Lin Huang, Jianchao Tan, Ji Liu, and Junsong Yuan_

##### • ContactPose: A Dataset of Grasps with Object Contact and Hand Pose. [\[PDF\]](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123580358.pdf)  [\[Project\]](https://contactpose.cc.gatech.edu/) [\[Code\]](https://github.com/facebookresearch/ContactPose)
_Samarth Brahmbhatt, Chengcheng Tang, Chris Twigg, Charles C. Kemp, and James Hays_

##### • SeqHAND: RGB-Sequence-Based 3D Hand Pose and Shape Estimation. [\[PDF\]](http://arxiv.org/pdf/2007.05168)
_John Yang, Hyung Jin Chang, Seungeui Lee, Nojun Kwak_

##### • HTML: A Parametric Hand Texture Model for 3D Hand Reconstruction and Personalizationm. [\[PDF\]](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123560052.pdf) [\[Project\]](https://handtracker.mpi-inf.mpg.de/projects/HandTextureModel/)
_Neng Qian, Jiayi Wang, Franziska Mueller, Florian Bernard, Vladislav Golyanik, Christian Theobalt_

##### • JGR-P2O: Joint Graph Reasoning based Pixel-to-Offset Prediction Network for 3D Hand Pose Estimation from a Single Depth Image. [\[PDF\]](https://arxiv.org/pdf/2007.04646)  [\[Code\]](https://github.com/fanglinpu/JGR-P2O) *(Spotlight)*
_Linpu Fang, Xingyan Liu, Li Liu, Hang Xu, Wenxiong Kang_

##### • Adaptive Computationally Efficient Network for Monocular 3D Hand Pose Estimation. [\[PDF\]](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123490120.pdf) *(Spotlight)*
_Zhipeng Fan, Jun Liu, Yao Wang_

##### • Collaborative Learning of Gesture Recognition and 3D Hand Pose Estimation with Multi-Order Feature Analysis.  [\[PDF\]](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123480766.pdf) *(Spotlight)*
_Siyuan Yang, Jun Liu, Shijian Lu, Meng Hwa Er, Alex C. Kot_

##### • DeepHandMesh: Weakly-supervised Deep Encoder-Decoder Framework for High-fidelity Hand Mesh Modeling from a Single RGB Image. [\[PDF\]](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123470426.pdf) [\[Project\]](https://mks0601.github.io/DeepHandMesh/) *(Oral)*
_Gyeongsik Moon, Takaaki Shiratori, Kyoung Mu Lee_

##### • InterHand2.6M: A New Large-scale Dataset and Baseline for 3D Single and Interacting Hand Pose Estimation from a Single RGB Image. [\[PDF\]](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123650545.pdf) [\[Project\]](https://mks0601.github.io/InterHand2.6M/) \[[Code\]](https://github.com/facebookresearch/InterHand2.6M)
_Gyeongsik Moon, Shoou-i Yu, He Wen, Takaaki Shiratori, Kyoung Mu Lee_

##### • I2L-MeshNet: Image-to-Lixel Prediction Network for Accurate 3D Human Pose and Mesh Estimation from a Single RGB Image. [\[PDF\]](https://arxiv.org/abs/2008.03713) \[[Code\]](https://github.com/mks0601/I2L-MeshNet_RELEASE)
_Gyeongsik Moon, Kyoung Mu Lee_

##### • Weakly-Supervised 3D Hand Pose Estimation via Biomechanical Constraints. [\[PDF\]](https://arxiv.org/pdf/2003.09282.pdf)
_Adrian Spurr, Umar Iqbal, Pavlo Molchanov, Otmar Hilliges, Jan Kautz_

##### • Measuring Generalisation to Unseen Viewpoints, Articulations, Shapes and Objects for 3D Hand Pose Estimation under Hand-Object Interaction. [\[PDF\]](https://arxiv.org/pdf/2003.13764.pdf) \[[Code\]](https://github.com/anilarmagan/HANDS19-Challenge-Toolbox)
_Anil Armagan, Guillermo Garcia-Hernando, Seungryul Baek, Shreyas Hampali, Mahdi Rad, Zhaohui Zhang, Shipeng Xie, MingXiu Chen, Boshen Zhang, Fu Xiong, Yang Xiao, Zhiguo Cao, Junsong Yuan, Pengfei Ren, Weiting Huang, Haifeng Sun, Marek Hrúz, Jakub Kanis, Zdeněk Krňoul, Qingfu Wan, Shile Li, Linlin Yang, Dongheui Lee, Angela Yao, Weiguo Zhou, Sijia Mei, Yunhui Liu, Adrian Spurr, Umar Iqbal, Pavlo Molchanov, Philippe Weinzaepfel, Romain Brégier, Gregory Rogez, Vincent Lepetit, Tae-Kyun Kim_

[\[back to top\]](#contents)

### 2020 CVPR

##### • Weakly-Supervised Mesh-Convolutional Hand Reconstruction in the Wild. [\[PDF\]](https://arxiv.org/pdf/2004.01946.pdf) [\[Project\]](https://www.arielai.com/mesh_hands/)  *(Oral)* *([Paper Award Nominees](http://cvpr2020.thecvf.com/node/817))*
_Dominik Kulon, Riza Alp Güler, Iasonas Kokkinos, Michael Bronstein, Stefanos Zafeiriou_

##### • Weakly-supervised Domain Adaptation via GAN and Mesh Model for Estimating 3D Hand Poses Interacting Objects.  [\[PDF\]](http://openaccess.thecvf.com/content_CVPR_2020/papers/Baek_Weakly-Supervised_Domain_Adaptation_via_GAN_and_Mesh_Model_for_Estimating_CVPR_2020_paper.pdf) [\[Code\]](https://github.com/bsrvision/weak_da_hands) *(Oral)* *([Paper Award Nominees](http://cvpr2020.thecvf.com/node/817))*
_Seungryul Baek, Kwang In Kim, Tae-Kyun Kim_

##### • GanHand: Predicting Human Grasp Affordances in Multi-Object Scenes. [\[PDF\]](http://openaccess.thecvf.com/content_CVPR_2020/papers/Corona_GanHand_Predicting_Human_Grasp_Affordances_in_Multi-Object_Scenes_CVPR_2020_paper.pdf)
_Enric Corona, Albert Pumarola, Guillem Alenya, Francesc Moreno-Noguer, Gregory Rogez_

##### • Cross-Modal Variational Alignment of Latent Spaces. [\[PDF\]](http://openaccess.thecvf.com/content_CVPRW_2020/papers/w56/Theodoridis_Cross-Modal_Variational_Alignment_of_Latent_Spaces_CVPRW_2020_paper.pdf)
_Thomas Theodoridis, Theocharis Chatzis, Vassilios Solachidis, Kosmas Dimitropoulos, Petros Daras_

##### • HUMBI: A Large Multiview Dataset of Human Body Expressions. [\[PDF\]](https://arxiv.org/pdf/1812.00281.pdf) [\[Project\]](https://humbi-data.net/hand/)
_Zhixuan Yu\*, Jae Shin Yoon\*, Prashanth Venkatesh, Jaesik Park, Jihun Yu, Hyun Soo Park_

##### • Epipolar Transformers. [\[PDF\]](https://arxiv.org/pdf/2005.04551.pdf) [\[Code\]](https://github.com/yihui-he/epipolar-transformers)
_Yihui He\*, Rui Yan\*, Shoou-I Yu, Katerina Fragkiadaki_

##### • HandVoxNet: Deep Voxel-Based Network for 3D Hand Shape and Pose Estimation from a Single Depth Map. [\[PDF\]](https://arxiv.org/pdf/2004.01588.pdf)
_Jameel Malik, Ibrahim Abdelaziz, Ahmed Elhayek, Soshi Shimada, Sk Aziz Ali, Vladislav Golyanik, Christian Theobalt, Didier Stricker_

##### • Knowledge as Priors: Cross-Modal Knowledge Generalization for Datasets without Superior Knowledge. [\[PDF\]](https://arxiv.org/pdf/2004.00176.pdf)
_Long Zhao, Xi Peng, Yuxiao Chen, Mubbasir Kapadia, Dimitris N. Metaxas_

##### • Leveraging Photometric Consistency over Time for Sparsely Supervised Hand-Object Reconstruction. [\[PDF\]](http://arxiv.org/pdf/2004.13449.pdf) [\[Project\]](https://hassony2.github.io/handobjectconsist.html) [\[Code\]](https://github.com/hassony2/handobjectconsist)
_Yana Hasson, Bugra Tekin, Federica Bogo, Ivan Laptev, Marc Pollefeys, Cordelia Schmid_

##### • Monocular Real-time Hand Shape and Motion Capture using Multi-modal Data. [\[PDF\]](https://arxiv.org/pdf/2003.09572.pdf) [\[Project\]](https://calciferzh.github.io/publications/zhou2020monocular) [\[Code\]](https://github.com/CalciferZh/minimal-hand)
_Yuxiao Zhou, Marc Habermann, Weipeng Xu, Ikhsanul Habibie, Christian Theobalt, Feng Xu_

##### • HOPE-Net: A Graph-based Model for Hand-Object Pose Estimation. [\[PDF\]](http://openaccess.thecvf.com/content_CVPR_2020/papers/Doosti_HOPE-Net_A_Graph-Based_Model_for_Hand-Object_Pose_Estimation_CVPR_2020_paper.pdf) [\[Code\]](https://github.com/bardiadoosti/HOPE)
_Bardia Doosti, Shujon Naha, David Crandall, Majid Mirbagheri_

##### • HOnnotate: A method for 3D Annotation of Hand and Objects Poses. [\[PDF\]](https://arxiv.org/pdf/1907.01481.pdf) [\[Project\]](https://www.tugraz.at/institute/icg/research/team-lepetit/research-projects/hand-object-3d-pose-annotation/) [\[Code\]](https://github.com/shreyashampali/ho3d)
_Shreyas Hampali, Mahdi Rad, Markus Oberweger, Vincent Lepetit_

[\[back to top\]](#contents)

### 2020 Others

##### • [2020 3DV] Grasping Field: Learning Implicit Representations for Human Grasps. [\[PDF\]](https://arxiv.org/pdf/2008.04451.pdf) [\[Code\]](https://github.com/korrawe/grasping_field) *(Best Paper Award)*
_Korrawe Karunratanakul, Jinlong Yang, Yan Zhang, Michael Black, Krikamol Muandet, Siyu Tang_

##### • [2020 UIST] DeepFisheye: Near-Surface Multi-Finger Tracking Technology Using Fisheye Camera. [\[PDF\]](https://dl.acm.org/doi/abs/10.1145/3379337.3415818)  [\[Project\]](http://kwpark.io/deepfisheye) [\[Code\]](https://github.com/KAIST-HCIL/DeepFisheyeNet) 
_Keunwoo Park, Sunbum Kim, Youngwoo Yoon, Tae-Kyun Kim, Geehyuk Lee_

##### • [2020 SIGGRAPH Asia] Constraining Dense Hand Surface Tracking With Elasticity. [\[PDF\]](https://research.fb.com/wp-content/uploads/2020/11/Constraining-Dense-Hand-Surface-Tracking-with-Elasticity.pdf)  [\[Project\]](https://research.fb.com/publications/constraining-dense-hand-surface-tracking-with-elasticity/)
_Breannan Smith, Chenglei Wu, He Wen, Patrick Peluse, Yaser Sheikh, Jessica Hodgins, Takaaki Shiratori_

##### • [2020 SIGGRAPH Asia] RGB2Hands: Real-Time Tracking of 3D Hand Interactions from Monocular RGB Video. [\[PDF\]](https://handtracker.mpi-inf.mpg.de/projects/RGB2Hands/content/RGB2Hands_author_version.pdf)  [\[Project\]](https://handtracker.mpi-inf.mpg.de/projects/RGB2Hands/)
_Jiayi Wang, Franziska Mueller, Florian Bernard, Suzanne Sorli, Oleksandr Sotnychenko, Neng Qian, Miguel A. Otaduy, Dan Casas, and Christian Theobalt_

##### • [2020 SIGGRAPH] MEgATrack: Monochrome Egocentric Articulated Hand-Tracking for Virtual Reality. [\[PDF\]](https://dl.acm.org/doi/abs/10.1145/3386569.3392452)
_Shangchen Han, Beibei Liu, Randi Cabezas, Christopher D. Twigg, Peizhao Zhang, Jeff Petkau, Tsz-Ho Yu, Chun-Jung Tai, Muzaffer Akbay, Zheng Wang, Asaf Nitzan, Gang Dong, Yuting Ye, Lingling Tao, Chengde Wan, Robert Wang_

##### • [2020 MM] MM-Hand: 3D-Aware Multi-Modal Guided Hand Generation for 3D Hand Pose Synthesis. [\[PDF\]](http://vllab.cs.nctu.edu.tw/images/paper/mm-wu20.pdf) [\[Code\]](https://github.com/ScottHoang/mm-hand)
_Zhenyu Wu, Duc Hoang, Shih-Yao Lin, Yusheng Xie, Liangjian Chen, Yen-Yu Lin, Zhangyang Wang, Wei Fan_

##### • [2020 MM] Adaptive Wasserstein Hourglass for Weakly Supervised Hand Pose Estimation from Monocular RGB. [\[PDF\]](https://arxiv.org/pdf/1909.05666.pdf)
_Yumeng Zhang, Li Chen, Yufeng Liu, Junhai Yong, Wen Zheng_

##### • [2020 MM] HOT-Net: Non-Autoregressive Transformer for 3D Hand-Object Pose Estimation. [\[PDF\]](https://cse.buffalo.edu/~jsyuan/papers/2020/lin_mm20.pdf)
_Lin Huang, Jianchao Tan, Jingjing Meng, Ji Liu, and Junsong Yuan_

##### • [2020 BMVC] PMD-Net: Privileged Modality Distillation Network for 3D Hand Pose Estimation from a Single RGB Image. [\[PDF\]](https://www.bmvc2020-conference.com/assets/papers/0413.pdf)
_Kewen Wang and Xilin Chen_

##### • [2020 BMVC] SIA-GCN: A Spatial Information Aware Graph Neural Network with 2D Convolutions for Hand Pose Estimation. [\[PDF\]](https://www.bmvc2020-conference.com/assets/papers/0066.pdf)
_Deying Kong, Haoyu Ma and Xiaohui Xie_

##### • [2020 BMVC] Explicit Knowledge Distillation for 3D Hand Pose Estimation from Monocular RGB. [\[PDF\]](https://www.bmvc2020-conference.com/assets/papers/0242.pdf)
_Yumeng Zhang, Li Chen, Yufeng Liu, Wen Zheng and JunHai Yong_

##### • [2020 BMVC] BiHand: Recovering Hand Mesh with Multi-stage Bisected Hourglass Networks. [\[PDF\]](https://arxiv.org/pdf/2008.05079.pdf) [\[Code\]](https://github.com/lixiny/bihand)
_Lixin Yang, Jiasen Li, Wenqiang Xu, Yiqun Diao, Cewu Lu_

##### • [2020 Ubicomp] FingerTrak: Continuous 3D Hand Pose Tracking by Deep Learning Hand Silhouettes Captured by Miniature Thermal Cameras on Wrist. [\[PDF\]](https://dl.acm.org/doi/10.1145/3397306) (*ECCV 2020 Demo Award Nominee*)
_Fang Hu, Peng He, Songlin Xu, Yin Li, Cheng Zhang_

##### • [2020 FG] Hand tracking from monocular RGB with dense semantic labels. [\[PDF\]](https://www.computer.org/csdl/pds/api/csdl/proceedings/download-article/1kecISCOYgw/pdf)
_Peter Thompson, Aphrodite Galata_

##### • [2020 FG] Generative Model-Based Loss to the Rescue: A Method to Overcome Annotation Errors for Depth-Based Hand Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2007.03073.pdf)
_Jiayi Wang, Franziska Mueller, Florian Bernard, Christian Theobalt_

##### • [2020 IROS] Physics-Based Dexterous Manipulations with Estimated Hand Poses and Residual Reinforcement Learning. [\[PDF\]](https://arxiv.org/pdf/2008.03285)
_Guillermo Garcia-Hernando, Edward Johns, Tae-Kyun Kim_

##### • [2020 CHI] Evaluation of Machine Learning Techniques for Hand Pose Estimation on Handheld Device with Proximity Sensor. [\[PDF\]](https://dl.acm.org/doi/pdf/10.1145/3313831.3376712)
_Kazuyuki Arimatsu, Hideki Mori_

##### • [2020 AAAI] AWR: Adaptive Weighting Regression for 3D Hand Pose Estimation. [\[PDF\]](https://www.aaai.org//Papers//AAAI//2020GB//AAAI-HuangW.4059.pdf)  [\[Code\]](https://github.com/Elody-07/AWR-Adaptive-Weighting-Regression)
_Weiting Huang, Pengfei Ren, Jingyu Wang, Qi Qi, Haifeng Sun_

##### • [2020 WACV] Nonparametric Structure Regularization Machine for 2D Hand Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2001.08869.pdf) [\[Code\]](https://github.com/HowieMa/NSRMhand)
_Yifei Chen\*, Haoyu Ma\*, Deying Kong, Xiangyi Yan, Jianbao Wu, Wei Fan, Xiaohui Xie_

##### • [2020 WACV] 3D Hand Pose Estimation with Disentangled Cross-Modal Latent Space. [\[PDF\]](http://openaccess.thecvf.com/content_WACV_2020/papers/Gu_3D_Hand_Pose_Estimation_with_Disentangled_Cross-Modal_Latent_Space_WACV_2020_paper.pdf)
_Jiajun Gu, Zhiyong Wang, Wanli Ouyang, Weichen Zhang, Jiafeng Li, Li Zhuo_

##### • [2020 WACV] DGGAN: Depth-image Guided Generative Adversarial Networks for Disentangling RGB and Depth Images in 3D Hand Pose Estimation. [\[PDF\]](http://openaccess.thecvf.com/content_WACV_2020/papers/Chen_DGGAN_Depth-image_Guided_Generative_Adversarial_Networks_forDisentangling_RGB_and_Depth_WACV_2020_paper.pdf)
_Liangjian Chen, Shih-Yao Lin, Yusheng Xie, Yen-Yu Lin, Wei Fan, Xiaohui Xie_

##### • [2020 WACV] Rotation-invariant Mixed Graphical Model Network for 2D Hand Pose Estimation. [\[PDF\]](http://openaccess.thecvf.com/content_WACV_2020/papers/Kong_Rotation-invariant_Mixed_Graphical_Model_Network_for_2D_Hand_Pose_Estimation_WACV_2020_paper.pdf)
_Deying Kong, Haoyu Ma, Yifei Chen, Xiaohui Xie_

##### • [2020 ICASSP] Weakly Supervised Segmentation Guided Hand Pose Estimation During Interaction With Unknown Objects. [\[PDF\]](https://ieeexplore.ieee.org/abstract/document/9053082)
_Cairong Zhang, Guijin Wang, Xinghao Chen, Pengwei Xie, Toshihiko Yamasaki_

##### • [2020 ICASSP] Hand-3D-Studio: A New Multi-view System for 3D Hand Reconstruction. [\[PDF\]](https://www.yangangwang.com/papers/ZHAO-H3D-2020-02.pdf) [\[Project\]](https://www.yangangwang.com/papers/ZHAO-H3S-2020-02.html)
_Zhengyi Zhao, Tianyao Wang, Siyu Xia, Yangang Wang_

[\[back to top\]](#contents)

## Theses

##### • \[2020\] Learning to Reconstruct and Segment 3D Objects. [\[PDF\]](https://arxiv.org/pdf/2010.09582.pdf)
*[Bo Yang](https://yang7879.github.io/), University of Oxford*

[\[back to top\]](#contents)

## Datasets

- S/R: Synthetic (S) or Real (R) or Both (B)
- C/D: Color (RGB) or Depth (D)
- Obj: Interaction with objects or not
- #J:  No. of joints or Mesh (M)
- V: view (3rd or egocentric)
- #S: No. of subjects
- #F: No. of frames (train/test)
- Mesh: Mesh annotations

### Depth

|Dataset|Year|S/R|Mesh|Obj|#J|V|#S|#F|Paper|
|------|------|------|------|------|------|------|------|------|----------------|
|[NYU](http://cims.nyu.edu/~tompson/NYU_Hand_Pose_Dataset.htm) | 2014 | R |❌|❌| 36 | 3rd | 2 | 72k/8k | SIGGRAPH 2014 [\[PDF\]](http://cims.nyu.edu/~tompson/others/TOG_2014_paper_PREPRINT.pdf)|
|[ICVL](https://labicvl.github.io/hand.html) | 2014 | R |❌|❌|  16 | 3rd  |  10 | 331k/1.5k | CVPR 2014 [\[PDF\]](https://labicvl.github.io/docs/pubs/Danny_CVPR_2014.pdf)|
|[MSRA15](https://github.com/geliuhao/CVPR2016_HandPoseEstimation/issues/4) | 2015 | R |❌|❌|  21 | 3rd  |  9 | 76,375 | CVPR 2015 [\[PDF\]](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Sun_Cascaded_Hand_Pose_2015_CVPR_paper.pdf)|
|[BigHand2.2M](http://icvl.ee.ic.ac.uk/hands17/challenge/) | 2017 | R |❌|❌|  21 | 3rd  |  10 | 2.2M | CVPR 2017 [\[PDF\]](https://labicvl.github.io/docs/pubs/Shanxin_CVPR_2017.pdf)|
|[SynHandEgo](https://bit.ly/2WMWM5u) | 2019 | R |✅|❌| - | ego | - | - | Computers & Graphics 2019 [\[PDF\]](https://www.dfki.de/fileadmin/user_upload/import/10684_CAG_Jameel.pdf)|
|[FHAD](https://guiggh.github.io/publications/first-person-hands/) | 2018 | R |❌| ✅ |  21 | ego  |  6 | 100k | CVPR 2018 [\[PDF\]](https://arxiv.org/pdf/1704.02463)|
|[SynHand5M](https://cloud.dfki.de/owncloud/index.php/s/iCMRF7a5FkXrdpn) | 2018 | S | - |❌|  M | 3rd  |  - | 5M | 3DV 2018 [\[PDF\]](https://arxiv.org/pdf/1808.09208.pdf)|
|[MSRC (FingerPaint)](https://www.microsoft.com/en-us/download/details.aspx?id=52288)  | 2015| S |❌|❌|  21 | both  |  1 | 100k | CHI 2015 [\[PDF\]](http://www.cs.toronto.edu/~jtaylor/papers/CHI2015-HandTracking.pdf)|
|[HandNet](http://www.cs.technion.ac.il/~twerd/HandNet/) | 2015 | R |❌|❌|  6 | 3rd  |  10 | 202k/10k  | BMVC 2015 [\[PDF\]](http://www.cs.technion.ac.il/~twerd/WetzlerSlossbergKimmel-BMVC15.pdf)|
|[Hands in Action](http://files.is.tue.mpg.de/dtzionas/Hand-Object-Capture/) | 2014 | R | - | ✅ |  - | 3rd  |  - | - | IJCV 2016 [\[PDF\]](http://files.is.tue.mpg.de/dtzionas/Hand-Object-Capture/IJCV_Hand_Object_Capture.pdf)|
|[MSRA14](https://jimmysuen.github.io/) | 2014|  R |❌|❌|  21 | 3rd  |  6 | 2,400 | CVPR 2014 [\[PDF\]](http://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Qian_Realtime_and_Robust_2014_CVPR_paper.pdf)|
|[ASTAR](http://hpes.bii.a-star.edu.sg/) | 2013 | R | - |❌|  20 | 3rd  |  30 | 870 | ICCV 2013 [\[PDF\]](http://www.cv-foundation.org/openaccess/content_iccv_2013/papers/Xu_Efficient_Hand_Pose_2013_ICCV_paper.pdf)|


### RGB+Depth

|Dataset|Year|S/R|Mesh|Obj|#J|V|#S|#F|Paper|
|------|------|------|------|------|------|------|------|------|----------------|
|[ContactPose](https://contactpose.cc.gatech.edu/) | 2020 | - | - |✅| 21 | - | 1 | 2.9M | ECCV 2020 [\[PDF\]](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123580358.pdf)|
|[Ego3DHands](https://github.com/AlextheEngineer/Ego3DHands) | 2020 | S | - |❌| 21 | ego | 1 | 50k/5k | arXiv 2020 [\[PDF\]](https://arxiv.org/pdf/2006.01320.pdf)|
|[ObMan](https://www.di.ens.fr/willow/research/obman/data/) | 2019 | S | ✅ |✅| - | - | - | 150k | CVPR 2019 [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Hasson_Learning_Joint_Reconstruction_of_Hands_and_Manipulated_Objects_CVPR_2019_paper.pdf)|
|[EgoDexter](http://handtracker.mpi-inf.mpg.de/projects/OccludedHands/EgoDexter.htm) | 2017 | R | - | ✅ |  5 | ego  |  4 | 1485 | ICCV 2017 [\[PDF\]](http://handtracker.mpi-inf.mpg.de/projects/OccludedHands/content/OccludedHands_ICCV2017.pdf)|
|[SynthHands](http://handtracker.mpi-inf.mpg.de/projects/OccludedHands/SynthHands.htm) | 2017 | S | - | Both |  21 | ego  |  2 | 63,530  | ICCV 2017 [\[PDF\]](http://handtracker.mpi-inf.mpg.de/projects/OccludedHands/content/OccludedHands_ICCV2017.pdf)|
|[RHD](https://lmb.informatik.uni-freiburg.de/resources/datasets/RenderedHandposeDataset.en.html) | 2017 | S | - |❌|  21 | 3rd  |  20 | 41k/2.7k  |ICCV 2017 [\[PDF\]](https://arxiv.org/pdf/1705.01389.pdf)|
|[STB](https://sites.google.com/site/zhjw1988/) | 2017 | R | - |❌|  21 | 3rd |  1 | 18k | ICIP 2017 [\[PDF\]](http://www.cs.cityu.edu.hk/~jianbjiao2/pdfs/icip.pdf)|
|[Dexter+Object](http://handtracker.mpi-inf.mpg.de/projects/RealtimeHO/dexter+object.htm) | 2016 | R | - | ✅ |  5 | 3rd  |  2 | 3,014 | ECCV 2016 [\[PDF\]](http://handtracker.mpi-inf.mpg.de/projects/RealtimeHO/content/RealtimeHO_ECCV2016.pdf)|
|[UCI-EGO](http://pascal.inrialpes.fr/data2/grogez/UCI-EGO/UCI-EGO.tar.gz) | 2014 | R |-|❌|  26 | ego  |  2 | 400 | ECCVW 2014 [\[PDF\]](https://www.cs.cmu.edu/~deva/papers/egocentric_depth_workshop.pdf)|
|[Dexter1](http://handtracker.mpi-inf.mpg.de/projects/handtracker_iccv2013/dexter1.htm) | 2013 | R |- |❌|  6 | 3rd |  1 | 2,137 | ICCV 2013 [\[PDF\]](http://handtracker.mpi-inf.mpg.de/projects/handtracker_iccv2013/content/handtracker_iccv2013.pdf)|

### RGB

|Dataset|Year|S/R|Mesh|Obj|#J|V|#S|#F|Paper|
|------|------|------|------|------|------|------|------|------|----------------|
|[InterHand2.6M](https://mks0601.github.io/InterHand2.6M/) | 2020 | R | ❌ | ❌ | 21 | 3rd | 27 | 2.6M | ECCV 2020 [\[PDF\]](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123650545.pdf)|
|[YouTube 3D Hands](https://github.com/arielai/youtube_3d_hands) | 2020 | R | ✅ | ✅ | - | 3rd | - | 47,125/1525/1525 | CVPR 2020 [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Kulon_Weakly-Supervised_Mesh-Convolutional_Hand_Reconstruction_in_the_Wild_CVPR_2020_paper.pdf)|
|[OneHand10K](https://yangangwang.com/papers/WANG-MCC-2018-10.html) | 2019 | R | - |❌| 21 | 3rd | 1 | 10k/1.3k | TCSVT 2019 [\[PDF\]](https://yangangwang.com/papers/WANG-MCC-2018-10.pdf)|
|[FreiHAND](https://lmb.informatik.uni-freiburg.de/resources/datasets/FreihandDataset.en.html) | 2019 | R | - | ✅ |  21 | 3rd  |  - | 130k/3960  | ICCV 2019 [\[PDF\]](https://arxiv.org/pdf/1909.04349.pdf)|
|[GANerated Hands](https://handtracker.mpi-inf.mpg.de/projects/GANeratedHands/GANeratedDataset.htm) | 2018 | S | - | Both |  21 | ego  |  - | 330k | CVPR 2018 [\[PDF\]](https://handtracker.mpi-inf.mpg.de/projects/GANeratedHands/content/GANeratedHands_CVPR2018.pdf)|
|[CMU Panoptic HandDB](http://domedb.perception.cs.cmu.edu/handdb.html) | 2017 | B | - |❌|  21 | 3rd  |  - | 14,817 | CVPR 2017 [\[PDF\]](https://arxiv.org/pdf/1704.07809)|
|[MHP](http://www.rovit.ua.es/dataset/mhpdataset/) | 2017 | R | - | ❌  | 21 | 3rd | 9 | 80k | IVC 2017 [\[PDF\]](https://arxiv.org/pdf/1707.03742.pdf)  |

**Credits:**
- [1] Big Hand 2.2M Benchmark: Hand Pose Data Set and State of the Art Analysis, CVPR 2017 [\[PDF\]](https://labicvl.github.io/docs/pubs/Shanxin_CVPR_2017.pdf)
- [2] Depth-based hand pose estimation: methods, data, and challenges, ICCV 2015  [Link](http://arrummzen.net/#HandData)
- [3] Capturing Hand-Object Interaction and Reconstruction of Manipulated Objects, IJCV 2016 [\[PDF\]](http://ps.is.tue.mpg.de/uploads_file/attachment/attachment/340/Thesis_FINAL_online.pdf)
- [4] [MPI Hand Tracking Central](http://handtracker.mpi-inf.mpg.de/)

[\[back to top\]](#contents)

## Workshops

#### [1] *Workshop on Recovering 6D Object Pose:*
##### • [SIXD 2020](http://cmp.felk.cvut.cz/sixd/workshop_2020/), In conjunction with ECCV 2020

##### • [SIXD 2018](https://sites.google.com/view/hands2018/), In conjunction with ECCV 2018
  - HANDS18: Methods, Techniques and Applications for Hand Observation. [\[PDF\]](https://arxiv.org/abs/1810.10818)

##### • [HANDS 2017](http://icvl.ee.ic.ac.uk/hands17/), In conjunction with ICCV 2017
  - Depth-Based 3D Hand Pose Estimation: From Current Achievements to Future Goals. [\[PDF\]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Yuan_Depth-Based_3D_Hand_CVPR_2018_paper.pdf)

##### • [HANDS 2016](https://labicvl.github.io/hand/Hands2016/), In conjunction with CVPR 2016
##### • [HANDS 2015](http://www.ics.uci.edu/~jsupanci/HANDS-2015/), In conjunction with CVPR 2015

#### [2] *Workshops on Learning 3D Representations for Shape and Appearance:*

##### • [3DReps 2020](https://geometry.stanford.edu/3DReps/index.html), In conjunction with ECCV 2020

[\[back to top\]](#contents)

## Challenges

#### [1] [BOP Challenge 2020](http://cmp.felk.cvut.cz/sixd/workshop_2020/#challenge)
*[HANDS 2019](https://sites.google.com/view/hands2019/), [ICCV 2019](http://iccv2019.thecvf.com/)*
- Submission Website: [Depth-Based Task](https://competitions.codalab.org/competitions/20913), [Depth-Based Hand-Object Task](https://competitions.codalab.org/competitions/20449), [RGB-Based Hand-Object Task](https://competitions.codalab.org/competitions/21116)
- Documents
    - [Measuring Generalisation to Unseen Viewpoints, Articulations, Shapes and Objects for 3D Hand Pose Estimation under Hand-Object Interaction](https://arxiv.org/pdf/2003.13764.pdf), ECCV 2020

#### [2] [The 2017 Hands in the Million Challenge on 3D Hand Pose Estimation](http://icvl.ee.ic.ac.uk/hands17/challenge/)
*[HANDS 2017](http://icvl.ee.ic.ac.uk/hands17/), [ICCV 2017](http://iccv2017.thecvf.com/)*
- Submission Website: [Frame and Tracking Task](https://competitions.codalab.org/competitions/17356#results), [Hand-Object Task](https://competitions.codalab.org/competitions/17452#results)
- Documents
    - [The 2017 Hands in the Million Challenge on 3D Hand Pose Estimation](https://arxiv.org/pdf/1707.02237.pdf), arXiv 2017
    - [Depth-Based 3D Hand Pose Estimation: From Current Achievements to Future Goals.](https://arxiv.org/pdf/1712.03917.pdf), CVPR 2018

[\[back to top\]](#contents)

## Researchers

### U.S. / Canada

##### • \[2018 TPAMI\] Dense 3D Object Reconstruction from a Single Depth View. [\[PDF\]](https://arxiv.org/pdf/1802.00411.pdf)

### Europe
##### • [Niloy J. Mitra](http://www0.cs.ucl.ac.uk/staff/n.mitra/), [Smart Geometry Processing Group](http://geometry.cs.ucl.ac.uk/index.php), University College London (UCL).
##### • [TAE-KYUN (T-K) KIM](https://sites.google.com/view/tkkim/home), [Imperial Computer Vision & Learning Lab](https://labicvl.github.io/), Imperial College London.
##### • [Ales Leonardis](https://www.cs.bham.ac.uk/~leonarda/), [Intelligent Robotics Lab](https://www.birmingham.ac.uk/research/activity/computer-science/artificial-intelligence/robotics-and-computer-vision/index.aspx), University of Birmingham.

### Asia
##### • [Cewu Lu](http://www.cs.sjtu.edu.cn/PeopleDetail.aspx?id=366), [Machine Vision and Intelligence Group ](http://mvig.sjtu.edu.cn/), Shanghai JiaoTong University (SJTU).
### Australia

[\[back to top\]](#contents)
