# Awesome Object Pose Estimation and Reconstruction [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

A curated list of related resources for 6D object pose estimation, also including 3D objects reconstruction from a single view, and 3D hand-object pose estimation. 🔥 means new update.

Due to my personal interests, geometry-based work (SFM-based or SLAM-based work) are not collected here. Those papers can be found [here](https://github.com/openMVG/awesome_3DReconstruction_list).

Another related paper list is about the hand pose estimation, which can be found [here](https://github.com/xinghaochen/awesome-hand-pose-estimation).

Some awesome open-source demos ([CenterSnap](https://github.com/zubair-irshad/CenterSnap),  [NOCS](https://hughw19.github.io/NOCS_CVPR2019), [BundleTrack](https://github.com/wenbowen123/BundleTrack) and [se(3)-TrackNet](https://github.com/wenbowen123/iros20-6d-pose-tracking))：

<p float="left">
  <img src="./media/centersnap_reconstruction.gif" width="600" />
</p>

<p float="left">
  <img src="./media/6dtracking.gif" width="300" />
  <img src="./media/ycbineoat.gif" width="300" />
</p>
<p float="left">
  <img src="./media/ycb_packing.gif" width="600" />
</p>

## Contents
 <!-- - [Evaluation](#evaluation) -->
 - [arXiv Papers🔥](#arxiv-papers)
 - [Journal Papers](#journal-papers)
   - [TPAMI / IJCV](#tpami--ijcv)
   - [Others](#other-journals)
 - [Conference Papers](#conference-papers)
   - 2022: [CVPR🔥](#2022-cvpr), [ECCV🔥](#2022-eccv), [ICRA🔥](#2022-icra), [IROS🔥](#2022-iros), [Others🔥](#2022-others)
   - 2021: [CVPR](#2021-cvpr), [ICCV](#2021-iccv), [ICRA](#2021-icra), [IROS](#2021-iros), [Others](#2021-others)
   - 2020: [CVPR](#2020-cvpr), [ECCV](#2020-eccv), [Others](#2020-others)
   - 2019: [CVPR](#2019-cvpr), [ICCV](#2019-iccv), [Others](#2019-others)
   - 2018: [CVPR](#2018-cvpr), [ECCV](#2018-eccv), [Others](#2018-others)
   - 2017: [CVPR](#2017-cvpr), [ICCV](#2017-iccv), [Others](#2017-others)
   - 2016: [CVPR](#2016-cvpr), [Others](#2016-others)
   - 2015: [CVPR](#2015-cvpr), [ICCV](#2015-iccv), [Others](#2015-others)
   - 2014: [CVPR](#2014-cvpr), [Others](#2014-others-&-before)
 - [Thesis](#thesis)
 - [Datasets](#datasets)
   - [Benchmark 6D Object Pose Estimation](#Benchmark-6D-Object-Pose-Estimation)
 - [Workshops](#workshops)
   - [Workshops on 3D Vision and Robotics](#Workshops-on-3D-Vision-and-Robotics)
     - 3DV&R 2021: Workshop Papers
   - [Workshops on Recovering 6D Object Pose](#Workshops-on-Recovering-6D-Object-Pose)
     - R6D 2020: Talk Slides, Workshop Papers
     - R6D 2019: Talk Slides, Workshop Papers
     - R6D 2018: Talk Slides, Workshop Papers
   - [Workshops on Learning 3D Representations for Shape and Appearance](#Workshops-on-Learning-3D-Representations-for-Shape-and-Appearance)
     - 3DReps 2020: Workshop Videos, Workshop Papers
 - [Challenges](#challenges)
   - [BOP Challenge 2020](#BOP-Challenge-2020)
     - Datasets, Documents, Slides
   - [BOP Challenge 2019](#BOP-Challenge-2019)
     - Documents
 - [Researchers](#Researchers)
   - [U.S./Canada](#U.S./Canada)
   - [Europe](#Europe)
   - [Asia](#Asia)
   - [Australia](#Australia)

\* indicates equal contribution

<!-- ## Evaluation
See folder [``evaluation``](./evaluation) to get more details about performance evaluation for hand pose estimation. -->

## arXiv Papers

##### • [\[arXiv:2205.02536\]](https://arxiv.org/abs/2205.02536) YOLOPose: Transformer-based Multi-Object 6D Pose Estimation using Keypoint Regression. [\[PDF\]](https://arxiv.org/pdf/2205.02536)
_Arash Amini, Arul Selvam Periyasamy, Sven Behnke_
##### • [\[arXiv:2204.09429\]](https://arxiv.org/abs/2204.09429) HRPose: Real-Time High-Resolution 6D Pose Estimation Network Using Knowledge Distillation. [\[PDF\]](https://arxiv.org/pdf/2204.09429)
_Qi Guan, Zihao Sheng, Shibei Xue_
##### • [\[arXiv:2204.07049\]](https://arxiv.org/abs/2204.07049) Sim-to-Real 6D Object Pose Estimation via Iterative Self-training for Robotic Bin-picking. [\[PDF\]](https://arxiv.org/pdf/2204.07049)
_Kai Chen, Rui Cao, Stephen James, Yichuan Li, Yun-Hui Liu, Pieter Abbeel, Qi Dou_
##### • [\[arXiv:2204.01586\]](https://arxiv.org/abs/2204.01586) Object Level Depth Reconstruction for Category Level 6D Object Pose Estimation From Monocular RGB Image. [\[PDF\]](https://arxiv.org/pdf/2204.01586)
_Zhaoxin Fan, Zhenbo Song, Jian Xu, Zhicheng Wang, Kejian Wu, Hongyan Liu, Jun He_
##### • [\[arXiv:2203.15309\]](https://arxiv.org/abs/2203.15309) Learning-based Point Cloud Registration for 6D Object Pose Estimation in the Real World. [\[PDF\]](https://arxiv.org/pdf/2203.15309)
_Zheng Dang, Lizhou Wang, Yu Guo, Mathieu Salzmann_
##### • [\[arXiv:2203.04802\]](https://arxiv.org/abs/2203.04802) NeRF-Pose: A First-Reconstruct-Then-Regress Approach for Weakly-supervised 6D Object Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2203.04802)
_Fu Li, Hao Yu, Ivan Shugurov, Benjamin Busam, Shaowu Yang, Slobodan Ilic_
##### • [\[arXiv:2203.04424\]](https://arxiv.org/abs/2203.04424) Probabilistic Rotation Representation With an Efficiently Computable Bingham Loss Function and Its Application to Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2203.04424)
_Ziqi Lu, Yihao Zhang, Kevin Doherty, Odin Severinsen, Ethan Yang, John Leonard_
##### • [\[arXiv:2203.04424\]](https://arxiv.org/abs/2203.04424) SLAM-Supported Self-Training for 6D Object Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2203.04424)
_Ziqi Lu, Yihao Zhang, Kevin Doherty, Odin Severinsen, Ethan Yang, John Leonard_
##### • [\[arXiv:2203.03498\]](https://arxiv.org/abs/2203.03498) Weakly Supervised Learning of Keypoints for 6D Object Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2203.03498)
_Meng Tian, Gim Hee Lee_
##### • [\[arXiv:2203.02069\]](https://arxiv.org/abs/2203.02069) Sim2Real Instance-Level Style Transfer for 6D Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2203.02069)
_Takuya Ikeda, Suomi Tanishige, Ayako Amma, Michael Sudano, Hervé Audren, Koichi Nishiwaki_
##### • [\[arXiv:2203.01051\]](https://arxiv.org/abs/2203.01051) 3D object reconstruction and 6D-pose estimation from 2D shape for robotic grasping of objects. [\[PDF\]](https://arxiv.org/pdf/2203.01051)
_Marcell Wolnitza, Osman Kaya, Tomas Kulvicius, Florentin Wörgötter, Babette Dellen_
##### • [\[arXiv:2203.00945\]](https://arxiv.org/abs/2203.00945) ParaPose: Parameter and Domain Randomization Optimization for Pose Estimation using Synthetic Data. [\[PDF\]](https://arxiv.org/pdf/2203.00945)
_Frederik Hagelskjaer, Anders Glent Buch_
##### • [\[arXiv:2203.00302\]](https://arxiv.org/abs/2203.00302) Adversarial samples for deep monocular 6D object pose estimation. [\[PDF\]](https://arxiv.org/pdf/2203.00302)
_Jinlai Zhang, Weiming Li, Shuang Liang, Hao Wang, Jihong Zhu_
##### • [\[arXiv:2203.00283\]](https://arxiv.org/abs/2203.00283) ProgressLabeller: Visual Data Stream Annotation for Training Object-Centric 3D Perception. [\[PDF\]](https://arxiv.org/pdf/2203.00283)
_Xiaotong Chen, Huijie Zhang, Zeren Yu, Stanley Lewis, Odest Chadwicke Jenkins_
##### • [\[arXiv:2202.12555\]](https://arxiv.org/abs/2202.12555) 6D Rotation Representation For Unconstrained Head Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2202.12555) [\[Code\]](https://github.com/thohemp/6DRepNet)
_Thorsten Hempel, Ahmed A. Abdelrahman, Ayoub Al-Hamadi_
##### • [\[arXiv:2202.10346\]](https://arxiv.org/abs/2202.10346) On the Evaluation of RGB-D-based Categorical Pose and Shape Estimation. [\[PDF\]](https://arxiv.org/pdf/2202.10346)
_Leonard Bruns, Patric Jensfelt_
##### • [\[arXiv:2202.03574\]](https://arxiv.org/abs/2202.03574) Structured Prediction Problem Archive. [\[PDF\]](https://arxiv.org/pdf/2202.03574)
_Paul Swoboda, Andrea Hornakova, Paul Roetzer, Bogdan Savchynskyy, Ahmed Abbas_
##### • [\[arXiv:2201.13065\]](https://arxiv.org/abs/2201.13065) Rigidity Preserving Image Transformations and Equivariance in Perspective. [\[PDF\]](https://arxiv.org/pdf/2201.13065)
_Xinke Deng, Junyi Geng, Timothy Bretl, Yu Xiang, Dieter Fox_
##### • [\[arXiv:2201.00059\]](https://arxiv.org/abs/2201.00059) iCaps: Iterative Category-level Object Pose and Shape Estimation. [\[PDF\]](https://arxiv.org/pdf/2201.00059)
_Xinke Deng, Junyi Geng, Timothy Bretl, Yu Xiang, Dieter Fox_
##### • [\[arXiv:2112.15075\]](https://arxiv.org/abs/2112.15075) Pose Estimation of Specific Rigid Objects. [\[PDF\]](https://arxiv.org/pdf/2112.15075)
_Tomas Hodan_
##### • [\[arXiv:2112.03810\]](https://arxiv.org/abs/2112.03810) Polarimetric Pose Prediction. [\[PDF\]](https://arxiv.org/pdf/2112.03810)
_Daoyi Gao, Yitong Li, Patrick Ruhkamp, Iuliia Skobleva, Magdalena Wysock, HyunJun Jung, Pengyuan Wang, Arturo Guridi, Nassir Navab, Benjamin Busamh_
_Rasmus Laurvig Haugaard, Anders Glent Buch_
##### • [\[arXiv:2111.10677\]](https://arxiv.org/abs/2111.10677) VideoPose: Estimating 6D object pose from videos. [\[PDF\]](https://arxiv.org/pdf/2111.10677)
_Apoorva Beedu, Zhile Ren, Varun Agrawal, Irfan Essa_
##### • [\[arXiv:2111.10524\]](https://arxiv.org/abs/2111.09378) ACR-Pose: Adversarial Canonical Representation Reconstruction Network for Category Level 6D Object Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2111.10524)
_Zhaoxin Fan, Zhengbo Song, Jian Xu, Zhicheng Wang, Kejian Wu, Hongyan Liu, Jun He_
##### • [\[arXiv:2111.09378\]](https://arxiv.org/abs/2111.09378) MPF6D: Masked Pyramid Fusion 6D Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2111.09378)
_Nuno Pereira, Luís A. Alexandre_
##### • [\[arXiv:2111.07383\]](https://arxiv.org/abs/2111.07383) Sparse Steerable Convolutions: An Efficient Learning of SE(3)-Equivariant Features for Estimation and Tracking of Object Poses in 3D Space. [\[PDF\]](https://arxiv.org/pdf/2111.07383)
_Jiehong Lin, Hongyang Li, Ke Chen, Jiangbo Lu, Kui Jia_
##### • [\[arXiv:2111.06276\]](https://arxiv.org/abs/2111.06276) 6D Pose Estimation with Combined Deep Learning and 3D Vision Techniques for a Fast and Accurate Object Grasping. [\[PDF\]](https://arxiv.org/pdf/2111.06276)
_Tuan-Tang Le, Trung-Son Le, Yu-Ru Chen, Joel Vidal, Chyi-Yeu Lin_
##### • [\[arXiv:2111.03821\]](https://arxiv.org/abs/2111.10524) ROFT: Real-Time Optical Flow-Aided 6D Object Pose and Velocity Tracking. [\[PDF\]](https://arxiv.org/pdf/2111.03821)
_Nicola A. Piga, Yuriy Onyshchuk, Giulia Pasquale, Ugo Pattacini, Lorenzo Natale_
##### • [\[arXiv:2111.00190\]](https://arxiv.org/pdf/2111.00190) Leveraging SE(3) Equivariance for Self-Supervised Category-Level Object Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2111.00190)
_Xiaolong Li, Yijia Weng, Li Yi, Leonidas Guibas, A. Lynn Abbott, Shuran Song, He Wang_
##### • [\[arXiv:2110.04792\]](https://arxiv.org/pdf/2110.04792) 6D-ViT: Category-Level 6D Object Pose Estimation via Transformer-based Instance Representation Learning. [\[PDF\]](https://arxiv.org/pdf/2110.04792)
_Lu Zou, Zhangjin Huang, Naijie Gu, Guoping Wang_
##### • [\[arXiv:2110.00992\]](https://arxiv.org/pdf/2110.00992) Learning Stereopsis from Geometric Synthesis for 6D Object Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2110.00992)
_Jun Wu, Lilu Liu, Yue Wang, Rong Xiong_
##### • [\[arXiv:2107.12549\]](https://arxiv.org/abs/2107.12549) Disentangled Implicit Shape and Pose Learning for Scalable 6D Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2107.12549)
_Yilin Wen, Xiangyu Li, Hao Pan, Lei Yang, Zheng Wang, Taku Komura, Wenping Wang_
##### • [\[arXiv:2107.02057\]](https://arxiv.org/abs/2107.02057) 6D Object Pose Estimation using Keypoints and Part Affinity Fields. [\[PDF\]](https://arxiv.org/pdf/2107.02057)
_Moritz Zappel, Simon Bultmann, Sven Behnke_
##### • [\[arXiv:2106.14193\]](https://arxiv.org/abs/2106.14193) DONet: Learning Category-Level 6D Object Pose and Size Estimation from Depth Observation. [\[PDF\]](https://arxiv.org/pdf/2106.14193)
_Haitao Lin, Zichang Liu, Chilam Cheang, Lingwei Zhang, Yanwei Fu, Xiangyang Xue_
##### • [\[arXiv:2106.08045\]](https://arxiv.org/abs/2106.08045) Object detection and Autoencoder-based 6D pose estimation for highly cluttered Bin Picking. [\[PDF\]](https://arxiv.org/pdf/2106.08045)
_Timon Höfer, Faranak Shamsafar, Nuri Benbarka, Andreas Zell_
##### • [\[arXiv:2106.06684\]](https://arxiv.org/abs/2106.06684) Multistream ValidNet: Improving 6D Object Pose Estimation by Automatic Multistream Validation. [\[PDF\]](https://arxiv.org/pdf/2106.06684)
_Joy Mazumder, Mohsen Zand, Michael Greenspan_
##### • [\[arXiv:2105.04112\]](https://arxiv.org/abs/2105.04112) ROBI: A Multi-View Dataset for Reflective Objects in Robotic Bin-Picking. [\[PDF\]](https://arxiv.org/pdf/2105.04112)
_Jun Yang, Yizhou Gao, Dong Li, Steven L. Waslander_
##### • [\[arXiv:2103.09696\]](https://arxiv.org/abs/2103.09696) Generating Annotated Training Data for 6D Object Pose Estimation in Operational Environments with Minimal User Interaction. [\[PDF\]](https://arxiv.org/pdf/2104.00337)
_Paul Koch, Marian Schlüter, Serge Thill_
##### • [\[arXiv:2101.08895\]](https://arxiv.org/abs/2101.08895) Iterative Optimisation with an Innovation CNN for Pose Refinement. [\[PDF\]](https://arxiv.org/pdf/2101.08895)
_Junwen Huang, Yifei Shi, Xin Xu, Yifan Zhang, Kai Xu_
##### • [\[arXiv:2012.11938\]](https://arxiv.org/abs/2012.11938) 3D Point-to-Keypoint Voting Network for 6D Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2012.11938)
_Weitong Hua, Jiaxin Guo, Yue Wang, Rong Xiong_
##### • [\[arXiv:2012.11260\]](https://arxiv.org/abs/2012.11260) Unsupervised Domain Adaptation with Temporal-Consistent Self-Training for 3D Hand-Object Joint Reconstruction. [\[PDF\]](https://arxiv.org/pdf/2012.11260)
_Mengshi Qi, Edoardo Remelli, Mathieu Salzmann, Pascal Fua_
##### • [\[arXiv:2012.01788\]](https://arxiv.org/abs/2012.01788) Object-Driven Active Mapping for More Accurate Object Pose Estimation and Robotic Grasping. [\[PDF\]](https://arxiv.org/pdf/2012.01788) [\[Project Page\]](https://yanmin-wu.github.io/project/active-mapping/)
_Yanmin Wu, Yunzhou Zhang, Delong Zhu, Xin Chen, Sonya Coleman, Wenkai Sun, Xinggang Hu, Zhiqiang Deng_
##### • [\[arXiv:2012.00088\]](https://arxiv.org/abs/2012.00088) Nothing But Geometric Constraints: A Model-Free Method for Articulated Object Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2012.00088)
_Qihao Liu, Weichao Qiu, Weiyao Wang, Gregory D. Hager, Alan L. Yuille_
##### • [\[arXiv:2011.13669\]](https://arxiv.org/abs/2011.13669) Towards real-time object recognition and pose estimation in point clouds. [\[PDF\]](https://arxiv.org/pdf/2011.13669)
_Marlon Marcon, Olga Regina Pereira Bellon, Luciano Silva_
##### • [\[arXiv:2011.11078\]](https://arxiv.org/abs/2011.11078) End-to-End Differentiable 6DoF Object Pose Estimation with Local and Global Constraints. [\[PDF\]](https://arxiv.org/pdf/2011.11078)
_Anshul Gupta, Joydeep Medhi, Aratrik Chattopadhyay, Vikram Gupta_
##### • [\[arXiv:2011.08771\]](https://arxiv.org/abs/2011.08771) A Method to Generate High Precision Mesh Model and RGB-D Datasetfor 6D Pose Estimation Task. [\[PDF\]](https://arxiv.org/pdf/2011.08771)
_Minglei Lu, Yu Guo, Fei Wang, Zheng Dang_
##### • [\[arXiv:2011.04307\]](https://arxiv.org/abs/2011.04307) EfficientPose: An efficient, accurate and scalable end-to-end 6D multi object pose estimation approach. [\[PDF\]](https://arxiv.org/pdf/2011.04307) [\[Code\]](https://github.com/ybkscht/EfficientPose)
_Yannick Bukschat, Marcus Vetter_
##### • [\[arXiv:2011.00372\]](https://arxiv.org/abs/2011.00372) Pose Estimation of Specular and Symmetrical Objects. [\[PDF\]](https://arxiv.org/pdf/2011.00372)
_Jiaming Hu, Hongyi Ling, Priyam Parashar, Aayush Naik, Henrik Christensen_
##### • [\[arXiv:2010.16117\]](https://arxiv.org/abs/2010.16117) PyraPose: Feature Pyramids for Fast and Accurate Object Pose Estimation under Domain Shift. [\[PDF\]](https://arxiv.org/pdf/2010.16117)
_Stefan Thalhammer, Markus Leitner, Timothy Patten, Markus Vincze_
##### • [\[arXiv:2010.09355\]](https://arxiv.org/abs/2010.09355) SHREC 2020 track: 6D Object Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2010.09355)
_Honglin Yuan, Remco C. Veltkamp, Georgios Albanis, Nikolaos Zioulis, Dimitrios Zarpalas, Petros Daras_
##### • [\[arXiv:2010.00829\]](https://arxiv.org/abs/2010.00829) Continuous close-range 3D object pose estimation. [\[PDF\]](https://arxiv.org/pdf/2010.00829)
_Bjarne Grossmann, Francesco Rovida, Volker Krueger_
##### • [\[arXiv:2009.12678\]](https://arxiv.org/abs/2009.12678) I Like to Move It: 6D Pose Estimation as an Action Decision Process. [\[PDF\]](https://arxiv.org/pdf/2009.12678)
_Benjamin Busam, Hyun Jun Jung, Nassir Navab_
##### • [\[arXiv:2009.06887\]](https://arxiv.org/abs/2009.06887) 3DPVNet: Patch-level 3D Hough Voting Network for 6D Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2009.06887)
_Yuanpeng Liu, Jun Zhou, Yuqi Zhang, Chao Ding, Jun Wang_
##### • [\[arXiv:2008.08391\]](https://arxiv.org/abs/2008.08391) Robust RGB-based 6-DoF Pose Estimation without Real Pose Annotations. [\[PDF\]](https://arxiv.org/pdf/2008.08391)
_Zhigang Li, Yinlin Hu, Mathieu Salzmann, Xiangyang Ji_
##### • [\[arXiv:2008.05242\]](https://arxiv.org/abs/2008.05242) PAM:Point-wise Attention Module for 6D Object Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2008.05242)
_Myoungha Song, Jeongho Lee, Donghwan Kim_
##### • [\[arXiv:2002.03923\]](https://arxiv.org/abs/2002.03923) 6DoF Object Pose Estimation via Differentiable Proxy Voting Loss. [\[PDF\]](https://arxiv.org/pdf/2002.03923.pdf)
_Xin Yu, Zheyu Zhuang, Piotr Koniusz, Hongdong Li_
##### • [\[arXiv:1912.07333\]](https://arxiv.org/abs/1912.07333v1) ConvPoseCNN: Dense Convolutional 6D Object Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/1912.07333v1.pdf)
_Catherine Capellen, Max Schwarz, Sven Behnke_
##### • [\[arXiv:1910.10653\]](https://arxiv.org/abs/1910.10653) Accurate 6D Object Pose Estimation by Pose Conditioned Mesh Reconstruction. [\[PDF\]](https://arxiv.org/pdf/1910.10653.pdf)
_Pedro Castro, Anil Armagan, Tae-Kyun Kim_
##### • [\[arXiv:1809.06893\]](https://arxiv.org/abs/1809.06893) SilhoNet: An RGB Method for 6D Object Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/1809.06893.pdf)
_Gideon Billings and Matthew Johnson-Roberson_




[\[back to top\]](#contents)

## Journal Papers

### TPAMI / IJCV

##### • \[2021 TPAMI\] Occlusion-Aware Self-Supervised Monocular 6D Object Pose Estimation. [\[PDF\]](https://doi.org/10.1109/TPAMI.2021.3136301) [\[Code\]](https://github.com/THU-DA-6D-Pose-Group/self6dpp)
_Gu Wang, Fabian Manhardt, Xingyu Liu, Xiangyang Ji, Federico Tombari_
##### • \[2021 TPAMI\] RotationNet for Joint Object Categorization and Unsupervised Pose Estimation from Multi-View Images. [\[PDF\]](https://doi.org/10.1109/TPAMI.2019.2922640)
_Asako Kanezaki, Yasuyuki Matsushita, Yoshifumi Nishida_
##### • \[2020 TPAMI\] Generalized Feedback Loop for Joint Hand-Object Pose Estimation. [\[PDF\]](https://doi.org/10.1109/TPAMI.2019.2905607)
_Markus Oberweger, Paul Wohlhart, Vincent Lepetit_
##### • \[2020 IJCV\] Pix2Vox++: Multi-scale Context-aware 3D Object Reconstruction from Single and Multiple Images. [\[PDF\]](https://doi.org/10.1007/s11263-020-01347-6)
_Haozhe Xie, Hongxun Yao, Shengping Zhang, Shangchen Zhou, Wenxiu Sun_
##### • \[2020 IJCV\] Learning Single-Image 3D Reconstruction by Generative Modelling of Shape, Pose and Shading. [\[PDF\]](https://doi.org/10.1007/s11263-019-01219-8)
_Paul Henderson, Vittorio Ferrarin_
##### • \[2020 TPAMI\] SurfelMeshing: Online Surfel-Based Mesh Reconstruction. [\[PDF\]](https://doi.org/10.1109/TPAMI.2019.2947048)
_Thomas Schöps, Torsten Sattler, Marc Pollefeys_
##### • \[2020 TPAMI\] Shape and Reflectance Reconstruction Using Concentric Multi-Spectral Light Field. [\[PDF\]](https://doi.org/10.1109/TPAMI.2020.2986764)
_Mingyuan Zhou, Yuqi Ding, Yu Ji, S. Susan Young, Jingyi Yu, Jinwei Ye_
##### • \[2019 TPAMI\] Dense 3D Object Reconstruction from a Single Depth View. [\[PDF\]](https://arxiv.org/pdf/1802.00411.pdf)
_Bo Yang, Stefano Rosa, Andrew Markham, Niki Trigoni, Hongkai Wen_
##### • \[2018 TPAMI\] Latent-Class Hough Forests for 6 DoF Object Pose Estimation. [\[PDF\]](https://doi.org/10.1109/TPAMI.2017.2665623)
_Alykhan Tejani, Rigas Kouskouridas, Andreas Doumanoglou, Danhang Tang, Tae-Kyun Kim_
##### • \[2018 TPAMI\] Hand-Object Contact Force Estimation from Markerless Visual Tracking. [\[PDF\]](https://doi.org/10.1109/TPAMI.2017.2759736)
_Tu-Hoa Pham, Nikolaos Kyriazis, Antonis A. Argyros, Abderrahmane Kheddar_
##### • \[2018 TPAMI\] Single-View 3D Scene Reconstruction and Parsing by Attribute Grammar. [\[PDF\]](https://doi.org/10.1109/TPAMI.2017.2689007)
_Xiaobai Liu, Yibiao Zhao, Song-Chun Zhu_
##### • \[2018 IJCV\] Defining the Pose of Any 3D Rigid Object and an Associated Distance. [\[PDF\]](https://doi.org/10.1007/s11263-017-1052-4)
_Romain Brégier, Frédéric Devernay, Laetitia Leyrit, James L. Crowley_
##### • \[2018 IJCV\] Correction to: Lie-X: Depth Image Based Articulated Object Pose Estimation, Tracking, and Action Recognition on Lie Groups. [\[PDF\]](https://doi.org/10.1007/s11263-018-1069-3)
_Chi Xu, Lakshmi Narasimhan Govindarajan, Yu Zhang, James Stewart, Zoe Bichler, Suresh Jesuthasan, Adam Claridge-Chang, Ajay Sriram Mathuru, Wenlong Tang, Peixin Zhu, Li Cheng_
##### • \[2017 TPAMI\] Learning Category-Specific Deformable 3D Models for Object Reconstruction. [\[PDF\]](https://doi.org/10.1109/TPAMI.2016.2574713)
_Shubham Tulsiani, Abhishek Kar, João Carreira, Jitendra Malik_
##### • \[2017 TPAMI\] Novel Views of Objects from a Single Image. [\[PDF\]](https://doi.org/10.1109/TPAMI.2016.2601093)
_Konstantinos Rematas, Chuong H. Nguyen, Tobias Ritschel, Mario Fritz, Tinne Tuytelaars_
##### • \[2017 TPAMI\] Dense Semantic 3D Reconstruction. [\[PDF\]](https://doi.org/10.1109/TPAMI.2016.2613051)
_Christian Hane, Christopher Zach, Andrea Cohen, Marc Pollefeys_
##### • \[2017 IJCV\] Growing Regression Tree Forests by Classification for Continuous Object Pose Estimation. [\[PDF\]](https://doi.org/10.1007/s11263-016-0942-1)
_Kota Hara, Rama Chellappa_
##### • \[2016 TPAMI\] Lifting Object Detection Datasets into 3D. [\[PDF\]](https://doi.org/10.1109/TPAMI.2015.2435707)
_João Carreira, Sara Vicente, Lourdes Agapito, Jorge Batista_
##### • \[2016 TPAMI\] Real-Time Simultaneous Pose and Shape Estimation for Articulated Objects Using a Single Depth Camera. [\[PDF\]](https://doi.org/10.1109/TPAMI.2016.2557783)
_Mao Ye, Yang Shen, Chao Du, Zhigeng Pan, Ruigang Yang_
##### • \[2016 TPAMI\] Template-Based Monocular 3D Shape Recovery Using Laplacian Meshes. [\[PDF\]](https://doi.org/10.1109/TPAMI.2015.2435739)
_Dat Tien Ngo, Jonas Östlund, Pascal Fua_
##### • \[2016 IJCV\] 2D-3D Pose Estimation of Heterogeneous Objects Using a Region Based Approach. [\[PDF\]](https://link.springer.com/article/10.1007%2Fs11263-015-0873-2)
_Jonathan Hexner & Rami R. Hagege_



[\[back to top\]](#contents)

### Other Journals

##### • \[2022 RAL\] iCaps: Iterative Category-level Object Pose and Shape Estimation. [\[PDF\]](https://arxiv.org/pdf/2201.00059.pdf)
_X Deng, J Geng, T Bretl, Y Xiang, D Fox_
##### • \[2022 TIP\] Towards Real-World Category-level Articulation Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2105.03260.pdf)
_Liu Liu , Han Xue , Wenqiang Xu , Haoyuan Fu , Cewu Lu_
##### • \[2022 Transactions on MultiMedia\] A Novel Depth and Color Feature Fusion Framework for 6D Object Pose Estimation. [\[PDF\]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9115222)
_Guangliang Zhou, Yi Yan, Deming Wang, and Qijun Chen_
##### • \[2021 IEEE Transactions on Robotics\] PoseRBPF: A Rao–Blackwellized Particle Filter for 6-D Object Pose Tracking. [\[PDF\]](https://ieeexplore.ieee.org/iel7/8860/4359257/09363455.pdf)
_Xinke Deng, Arsalan Mousavian, Yu Xiang, Fei Xia, Timothy Bretl, Dieter Fox_
##### • \[2022 TIP\] Efficient Center Voting for Object Detection and 6D Pose Estimation in 3D Point Cloud. [\[PDF\]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9429889)
_Jianwei Guo, Xuejun Xing, Weize Quan, Dong-Ming Yan, Qingyi Gu , Yang Liu, and Xiaopeng Zhang_
##### • \[2020 TIP\] Domain-Translated 3D Object Pose Estimation. [\[PDF\]](https://doi.org/10.1109/TIP.2020.3025447)
_Christos Papaioannidis, Vasileios Mygdalis, Ioannis Pitas_


[\[back to top\]](#contents)

## Conference Papers

### 2022 CVPR
##### • [2022 CVPR Best Student Paper] EPro-PnP: Generalized End-to-End Probabilistic Perspective-n-Points for Monocular Object Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2203.13254.pdf) [\[Code\]](https://github.com/tjiiv-cprg/EPro-PnP)
_Hansheng Chen, Pichao Wang, Fan Wang, Wei Tian, Lu Xiong, Hao Li_
##### • [2022 CVPR] Focal length and object pose estimation via render and compare. [\[PDF\]](https://arxiv.org/abs/2204.05145) [\[Code\]](https://github.com/ponimatkin/focalpose)
_Georgy E. Ponimatkin; Yann Labbe; Mathieu Aubry; Bryan Russell; Josef Sivic_
##### • [2022 CVPR] RNNPose: Recurrent 6-DoF Object Pose Refinement with Robust Correspondence Field Estimation and Pose Optimization. [\[PDF\]](https://arxiv.org/pdf/2203.12870.pdf) [\[Code\]](https://github.com/DecaYale/RNNPose)
_Yan Xu, Kwan-Yee Lin, Guofeng Zhang, Xiaogang Wang, Hongsheng Li_
##### • [2022 CVPR] UDA-COPE: Unsupervised Domain Adaptation for Category-level Object Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2111.12580.pdf)
_Taeyeop Lee, Byeong-Uk Lee, Inkyu Shin, Jaesung Choe, Ukcheol Shin, In So Kweon, Kuk-Jin Yoon_
##### • [2022 CVPR] Templates for 3D Object Pose Estimation Revisited: Generalization to New Objects and Robustness to Occlusions. [\[PDF\]](https://arxiv.org/pdf/2203.17234.pdf) [\[Code\]](https://github.com/nv-nguyen/template-pose)
_Van Nguyen Nguyen, Yinlin Hu, Yang Xiao, Mathieu Salzmann, Vincent Lepetit_
##### • [2022 CVPR] OnePose: One-Shot Object Pose Estimation without CAD Models. [\[PDF\]]()
_Jiaming Sun, Zihao Wang, Siyu Zhang, Xingyi He, Hongcheng Zhao, Guofeng Zhang, Xiaowei Zhou_
##### • [2022 CVPR] SurfEmb: Dense and Continuous Correspondence Distributions for Object Pose Estimation with Learnt Surface Embeddings. [\[PDF\]](https://arxiv.org/pdf/2111.13489.pdf) [\[Code\]](https://github.com/rasmushaugaard/surfemb) [\[Project\]](https://surfemb.github.io)
_Rasmus Laurvig Haugaard, Anders Glent Buch_
##### • [2022 CVPR] PhoCaL: A Multi-Modal Dataset for Category-Level Object Pose Estimation with Photometrically Challenging Objects. [\[PDF\]]()
_Pengyuan Wang, HyunJun Jung, Yitong Li, Siyuan Shen, Rahul Parthasarathy Srikanth, Lorenzo Garattoni, Sven Meier, Nassir Navab, Benjamin Busam_
##### • [2022 CVPR] Uni6D: A Unified CNN Framework without Projection Breakdown in 6D Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2203.14531.pdf)
_Xiaoke Jiang, Donghai Li, Hao Chen, Ye Zheng, Rui Zhao, Liwei Wu_
##### • [2022 CVPR] Symmetry and Uncertainty-Aware Object SLAM for 6DoF Object Pose Estimation. [\[PDF\]]()
_Nathaniel W Merrill, Yuliang Guo, Xingxing Zuo, Xinyu Huang, Stefan Leutenegger, Xi Peng, Liu Ren, Guoquan Huang_
##### • [2022 CVPR] DGECN: A Depth-Guided Edge Convolutional Network For End-to-End 6D Pose Estimation. [\[PDF\]](https://arxiv.org/abs/2204.09983)
_Tuo Cao, Fei Luo, Yanping Fu, Wenxiao Zhang, Shengjie Zheng, Chunxia Xiao_
##### • [2022 CVPR] SAR-Net: Shape Alignment and Recovery Network for Category-level 6D Object Pose and Size Estimation. [\[PDF\]]()
_Haitao Lin, Zichang Liu, Chilam Cheang, Yanwei Fu, Guodong Guo, Xiangyang Xue_
##### • [2022 CVPR] ES6D: A Computation Efficient and Symmetry-Aware 6D Pose Regression Framework. [\[PDF\]]()
_Ningkai Mo, Wanshui Gan, Naoto Yokoya, Shifeng Chen_
##### • [2022 CVPR] FS6D: Few-Shot 6D Pose Estimation of Novel Objects. [\[PDF\]](https://arxiv.org/pdf/2203.14628.pdf) [\[Project\]](https://fs6d.github.io/)
_Yisheng He, Yao Wang, Haoqiang Fan, Jian Sun, Qifeng Chen_
##### • [2022 CVPR] Coupled Iterative Refinement for 6D Multi-Object Pose Estimation. [\[PDF\]](https://arxiv.org/abs/2204.12516) [\[Code\]](https://github.com/princeton-vl/Coupled-Iterative-Refinement)
_Lahav O Lipson, Zachary Teed, Ankit Goyal, Jia Deng_
##### • [2022 CVPR] Iterative Corresponding Geometry: Fusing Region and Depth for Highly Efficient 3D Tracking of Textureless Objects. [\[PDF\]](https://arxiv.org/pdf/2203.05334v1.pdf)
_Manuel Stoiber, Martin Sundermeyer, and Rudolph Triebel_
##### • [2022 CVPR] ZebraPose: Coarse to Fine Surface Encoding for 6DoF Object Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2203.09418.pdf) [\[Code\]](https://github.com/suyz526/ZebraPose)
_Yongzhi Su, Mahdi Saleh, Torben Fetzer, Jason Rambach, Benjamin Busam, Nassir Navab, Didier Stricker, Federico Tombari_
##### • [2022 CVPR] OSOP: A Multi-Stage One Shot Object Pose Estimation Framework. [\[PDF\]](https://arxiv.org/pdf/2203.15533.pdf)
_Ivan Shugurov, Fu Li, Benjamin Busam, Slobodan Ilic_
##### • [2022 CVPR] GPV-Pose: Category-level Object Pose Estimation via Geometry-guided Point-wise Voting. [\[PDF\]](https://arxiv.org/pdf/2203.07918.pdf)
_Yan Di, Ruida Zhang, Zhiqiang Lou, Fabian Manhardt, Xiangyang Ji, Nassir Navab, Federico Tombari_
##### • [2022 CVPR] OVE6D: Object Viewpoint Encoding for Depth-based 6D Object Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2203.01072.pdf)
_Dingding Cai, Janne Heikkila, Esa Rahtu_
##### • [2022 CVPR] Understanding 3D Object Articulation in Internet Videos. [\[PDF\]](https://arxiv.org/pdf/2203.16531.pdf) [\[Code\]](https://github.com/JasonQSY/Articulation3D) [\[Project\]](https://jasonqsy.github.io/Articulation3D/)
_Shengyi Qian, Linyi Jin, Chris Rockwell, Siyi Chen, David F. Fouhey_



### 2022 ECCV

##### • [2022 ECCV] ShAPO :tophat:: Implicit Representations for Multi-Object Shape, Appearance, and Pose Optimization. [\[Webpage\]](https://zubair-irshad.github.io/projects/ShAPO.html) [\[PDF\]](https://arxiv.org/pdf/2207.13691.pdf)[\[Video\]](https://youtu.be/LMg7NDcLDcA)
_Muhammad Zubair Irshad, Sergey Zakharov, Rares Ambrus, Thomas Kollar, Zsolt Kira, Adrien Gaidon_

##### • [2022 ECCV] Gen6D: Generalizable Model-Free 6-DoF Object Pose Estimation from RGB Images. [\[PDF\]](https://arxiv.org/pdf/2204.10776) [\[Code\]](https://github.com/liuyuan-pal/Gen6D) [\[Project\]](https://github.com/liuyuan-pal/Gen6D) [\[Dataset\]](https://connecthkuhk-my.sharepoint.com/:f:/g/personal/yuanly_connect_hku_hk/EkWESLayIVdEov4YlVrRShQBkOVTJwgK0bjF7chFg2GrBg?e=Y8UpXu)
_Yuan Liu, Yilin Wen, Sida Peng, Cheng Lin, Xiaoxiao Long, Taku Komura, Wenping Wang_

##### • [2022 ECCV] Perspective Flow Aggregation for Data-Limited 6D Object Pose Estimation. [\[PDF\]](https://arxiv.org/abs/2203.09836)
_Yinlin Hu, Pascal Fua, Mathieu Salzmann_

##### • [2022 ECCV] Neural Correspondence Field for Object Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2208.00113.pdf) [\[Code\]](https://github.com/LinHuang17/NCF-code) [\[Project\]](https://linhuang17.github.io/NCF/)
_Lin Huang, Tomas Hodan, Lingni Ma, Linguang Zhang, Luan Tran, Christopher Twigg, Po-Chen Wu, Junsong Yuan, Cem Keskin, Robert Wang_

##### • [2022 ECCV] Fusing Local Similarities for Retrieval-based 3D Orientation Estimation of Unseen Objects. [\[PDF\]](https://arxiv.org/abs/2203.08472) [\[Project\]](https://sailor-z.github.io/projects/Unseen_Object_Pose.html) [\[Code\]](https://github.com/sailor-z/Unseen_Object_Pose)
_Chen Zhao, Yinlin Hu, Mathieu Salzmann_

##### • [2022 ECCV] DProST: Dynamic Projective Spatial Transformer Network for 6D Pose Estimation. [\[PDF\]](https://arxiv.org/abs/2112.08775) [\[Code\]](https://github.com/parkjaewoo0611/DProST)
_Jaewoo Park, Nam Ik Cho_

##### • [2022 ECCV] Category-Level 6D Object Pose and Size Estimation using Self-Supervised Deep Prior Deformation Networks. [\[PDF\]](https://arxiv.org/abs/2207.05444) [\[Code\]](https://github.com/jiehonglin/self-dpdn)
_Jiehong Lin, Zewei Wei, Changxing Ding, Kui Jia_

##### • [2022 ECCV] Vote from the Center: 6 DoF Pose Estimation in RGB-D Images by Radial Keypoint Voting. [\[PDF\]](https://arxiv.org/abs/2104.02527) [\[Code\]](https://github.com/aaronwool/rcvpose)
_Yangzheng Wu, Mohsen Zand, Ali Etemad, Michael Greenspan_

##### • [2022 ECCV] RelPose: Predicting Probabilistic Relative Rotation for Single Objects in the Wild. [\[PDF\]](https://arxiv.org/abs/2208.05963) [\[Project\]](https://jasonyzhang.com/relpose/) 
_Jason Y. Zhang, Deva Ramanan, Shubham Tulsiani_

##### • [2022 ECCV] RBP-Pose: Residual Bounding Box Projection for Category-Level Pose Estimation. [\[PDF\]](https://arxiv.org/abs/2208.00237) [\[Code\]](https://github.com/lolrudy/RBP_Pose) 
_Ruida Zhang, Yan Di, Zhiqiang Lou, Fabian Manhardt, Nassir Navab, Federico Tombari, Xiangyang Ji_

##### • [2022 ECCV] CATRE: Iterative Point Clouds Alignment for Category-level Object Pose Refinement. [\[PDF\]](https://arxiv.org/abs/2207.08082) [\[Code\]](https://github.com/THU-DA-6D-Pose-Group/CATRE) 
_Xingyu Liu, Gu Wang, Yi Li, Xiangyang Ji_

[\[back to top\]](#contents)

### 2022 ICRA

##### • [2022 ICRA] TP-AE: Temporally Primed 6D Object Pose Tracking with Auto-Encoders. [\[PDF\]](http://pure-oai.bham.ac.uk/ws/portalfiles/portal/164770788/_ICRA_TP_AE_6D_Object_Tracking.pdf)
_Zheng, Linfang, Leonardis, Ales, Tse, Tze Ho Elden, Horanyi, Nora, Chen, Hua, Zhang, Wei, and Chang, Hyung Jin_
##### • [2022 ICRA] CenterSnap: Single-Shot Multi-Object 3D Shape Reconstruction and Categorical 6D Pose and Size Estimation. [\[PDF\]](https://arxiv.org/pdf/2203.01929) [\[Project\]](https://zubair-irshad.github.io/projects/CenterSnap.html) [\[Code\]](https://github.com/zubair-irshad/CenterSnap) [\[Video\]](https://www.youtube.com/watch?v=Bg5vi6DSMdM)
_Muhammad Zubair Irshad, Thomas Kollar, Michael Laskey, Kevin Stone, Zsolt Kira_
##### • [2022 ICRA] NeRF-Supervision: Learning Dense Object Descriptors from Neural Radiance Fields. [\[PDF\]](https://arxiv.org/pdf/2203.01913) [\[Code\]](https://github.com/yenchenlin/nerf-supervision-public) [\[Project\]](https://yenchenlin.me/nerf-supervision/)
_Lin Yen-Chen, Pete Florence, Jonathan T. Barron, Tsung-Yi Lin, Alberto Rodriguez, Phillip Isola_

[\[back to top\]](#contents)

### 2022 IROS

##### • [2022 IROS] Category-agnostic Segmentation for Robotic Grasping. [\[PDF\]](https://arxiv.org/pdf/2204.13613)
_Anas Gouda, Abraham Ghanem, Christopher Reining_

[\[back to top\]](#contents)


### 2022 Others

##### • [2022 IJCAI] BiCo-Net: Regress Globally, Match Locally for Robust 6D Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2205.03536)
_Zelin Xu, Yichen Zhang, Ke Chen, Kui Jia_
##### • [2022 AAAI] Sim2Real Object-Centric Keypoint Detection and Description. [\[PDF\]](https://arxiv.org/pdf/2202.00448)
_Chengliang Zhong, Chao Yang, Jinshan Qi, Fuchun Sun, Huaping Liu, Xiaodong Mu, Wenbing Huang_
##### • [2022 VISAPP] Combining Local and Global Pose Estimation for Precise Tracking of Similar Objects. [\[PDF\]](https://arxiv.org/pdf/2201.13278)
_Niklas Gard, Anna Hilsmann, Peter Eisert_
##### • [2022 VISAPP] Towards Deep Learning-based 6D Bin Pose Estimation in 3D Scans. [\[PDF\]](https://arxiv.org/pdf/2112.09598)
_Lukáš Gajdošech, Viktor Kocur, Martin Stuchlík, Lukáš Hudec, Martin Madaras_


[\[back to top\]](#contents)


### 2021 ICCV

##### • [2021 ICCV Oral] CAPTRA: CAtegory-level Pose Tracking for Rigid and Articulated Objects from Point Clouds. [\[PDF\]](https://arxiv.org/abs/2104.03437) [\[Code\]](https://github.com/halfsummer11/CAPTRA) [\[Project\]](https://yijiaweng.github.io/CAPTRA/) [\[Video\]](https://youtu.be/JFPcOHCH2O0)
 _Yijia Weng*, He Wang*†, Qiang Zhou, Yuzhe Qin, Yueqi Duan, Qingnan Fan, Baoquan Chen, Hao Su, Leonidas J. Guibas_

##### • [2021 ICCV] SO-Pose: Exploiting Self-Occlusion for Direct 6D Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2108.08367) [\[Code\]](https://github.com/sh8/RePOSE)
 _Yan Di, Fabian Manhardt, Gu Wang, Xiangyang Ji, Nassir Navab, Federico Tombari_

##### • [2021 ICCV] RePOSE: Real-Time Iterative Rendering and Refinement for 6D Object Pose Estimation. [\[PDF\]](https://arxiv.org/abs/2104.00633) [\[Code\]](https://github.com/sh8/RePOSE) [\[Project\]](https://www.sh8.io/#/repose)
 _Shun Iwase, Xingyu Liu, Rawal Khirodkar, Rio Yokota, Kris M. Kitani_

##### • [2021 ICCV] StereOBJ-2M: Large-scale Stereo Image Dataset for 6D Object Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2109.10115)
 _Xingyu Liu, Shun Iwase, Kris M. Kitani_

##### • [2021 ICCV] DualPoseNet: Category-Level 6D Object Pose and Size Estimation Using Dual Pose Network With Refined Learning of Pose Consistency. [\[PDF\]](https://openaccess.thecvf.com/content/ICCV2021/papers/Lin_DualPoseNet_Category-Level_6D_Object_Pose_and_Size_Estimation_Using_Dual_ICCV_2021_paper.pdf) [\[Code\]](https://github.com/Gorilla-Lab-SCUT/DualPoseNet)
 _Jiehong Lin, Zewei Wei, Zhihao Li, Songcen Xu, Kui Jia, and Yuanqing Li_

##### • [2021 ICCV] SGPA: Structure-Guided Prior Adaptation for Category-Level 6D Object Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content/ICCV2021/papers/Chen_SGPA_Structure-Guided_Prior_Adaptation_for_Category-Level_6D_Object_Pose_Estimation_ICCV_2021_paper.pdf) [\[Project\]](https://www.cse.cuhk.edu.hk/˜kaichen/projects/sgpa/sgpa.html)
 _Kai Chen and Qi Dou_

 ##### • [2021 ICCV] PR-GCN: A Deep Graph Convolutional Network With Point Refinement for 6D Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content/ICCV2021/papers/Zhou_PR-GCN_A_Deep_Graph_Convolutional_Network_With_Point_Refinement_for_ICCV_2021_paper.pdf)
 _Guangyuan Zhou, Huiqun Wang, Jiaxin Chen, and Di Huang_

[\[back to top\]](#contents)

### 2021 CVPR

##### • [2021 CVPR Oral] FS-Net: Fast Shape-based Network for Category-Level 6D Object Pose Estimation with Decoupled Rotation Mechanism. [\[PDF\]](https://arxiv.org/pdf/2103.07054.pdf) [\[Code\]](https://github.com/DC1991/FS-Net) [\[Supp\]](https://openaccess.thecvf.com/content/CVPR2021/papers/Chen_FS-Net_Fast_Shape-Based_Network_for_Category-Level_6D_Object_Pose_Estimation_CVPR_2021_paper.pdf)
 _Wei Chen, Xi Jia, Hyung Jin Chang, Jinming Duan, Linlin Shen, Ales Leonardis_

##### • [2021 CVPR] DexYCB: A Benchmark for Capturing Hand Grasping of Objects. [\[PDF\]](https://arxiv.org/pdf/2104.04631.pdf) [\[Code\]](https://github.com/NVlabs/dex-ycb-toolkit) [\[Project\]](https://dex-ycb.github.io/)
 _Yu-Wei Chao, Wei Yang, Yu Xiang, Pavlo Molchanov, Ankur Handa, Jonathan Tremblay, Yashraj S. Narang, Karl Van Wyk, Umar Iqbal, Stan Birchfield, Jan Kautz, Dieter Fox_

##### • [2021 CVPR Oral] FFB6D: A Full Flow Bidirectional Fusion Network for 6D Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2103.02242.pdf) [\[Code\]](https://github.com/ethnhe/FFB6D) [\[Supp\]](https://openaccess.thecvf.com/content/CVPR2021/supplemental/He_FFB6D_A_Full_CVPR_2021_supplemental.pdf)
 _Yisheng He, Haibin Huang, Haoqiang Fan, Qifeng Chen, Jian Sun_

##### • [2021 CVPR] GDR-Net: Geometry-Guided Direct Regression Network for Monocular 6D Object Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2102.12145) [\[Code\]](https://github.com/THU-DA-6D-Pose-Group/GDR-Net) [\[Supp\]](https://openaccess.thecvf.com/content/CVPR2021/supplemental/Wang_GDR-Net_Geometry-Guided_Direct_CVPR_2021_supplemental.pdf)
_Gu Wang, Fabian Manhardt, Federico Tombari, Xiangyang Ji_

##### • [2021 CVPR] DSC-PoseNet: Learning 6DoF Object Pose Estimation via Dual-scale Consistency. [\[PDF\]](https://arxiv.org/pdf/2104.03658) [\[Supp\]](https://openaccess.thecvf.com/content/CVPR2021/supplemental/Yang_DSC-PoseNet_Learning_6DoF_CVPR_2021_supplemental.pdf)
_Zongxin Yang, Xin Yu, Yi Yang_

##### • [2021 CVPR Oral] MultiBodySync: Multi-Body Segmentation and Motion Estimation via 3D Scan Synchronizat. [\[PDF\]](https://arxiv.org/pdf/2101.06605.pdf) [\[Supp\]](https://openaccess.thecvf.com/content/CVPR2021/supplemental/Huang_MultiBodySync_Multi-Body_Segmentation_CVPR_2021_supplemental.pdf)
_Jiahui Huang, He Wang, Tolga Birdal, Minkyuk Sung, Federica Arrigoni, Shi-Min Hu, and Leonidas J. Guibas_

##### • [2021 CVPR] img2pose: Face Alignment and Detection via 6DoF, Face Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content/CVPR2021/papers/Albiero_img2pose_Face_Alignment_and_Detection_via_6DoF_Face_Pose_Estimation_CVPR_2021_paper.pdf)
_Vitor Albiero, Xingyu Chen, Xi Yin, Guan Pang, Tal Hassner_

##### • [2021 CVPR] Wide-Depth-Range 6D Object Pose Estimation in Space. [\[PDF\]](https://openaccess.thecvf.com/content/CVPR2021/papers/Hu_Wide-Depth-Range_6D_Object_Pose_Estimation_in_Space_CVPR_2021_paper.pdf)
_Yinlin Hu, Sebastien Speierer, Wenzel Jakob, Pascal Fua, Mathieu Salzmann_

##### • [2021 CVPR] Keypoint-Graph-Driven Learning Framework for Object Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_Keypoint-Graph-Driven_Learning_Framework_for_Object_Pose_Estimation_CVPR_2021_paper.pdf) [\[Supp\]](https://openaccess.thecvf.com/content/CVPR2021/supplemental/Zhang_Keypoint-Graph-Driven_Learning_Framework_CVPR_2021_supplemental.pdf)
_Shaobo Zhang, Wanqing Zhao, Ziyu Guan, Xianlin Peng, Jinye Peng_

##### • [2021 CVPR] StablePose: Learning 6D Object Poses From Geometrically Stable Patches. [\[PDF\]](https://openaccess.thecvf.com/content/CVPR2021/papers/Shi_StablePose_Learning_6D_Object_Poses_From_Geometrically_Stable_Patches_CVPR_2021_paper.pdf) [\[Supp\]](https://openaccess.thecvf.com/content/CVPR2021/supplemental/Shi_StablePose_Learning_6D_CVPR_2021_supplemental.pdf)
_Yifei Shi, Junwen Huang, Xin Xu, Yifan Zhang, Kai Xu_

[\[back to top\]](#contents)


### 2021 ICRA

##### • [2021 ICRA] Investigations on Output Parameterizations of Neural Networks for Single Shot 6D Object Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2104.07528.pdf)
 _Kilian Kleeberger, Markus Völk, Richard Bormann, Marco F. Huber_

##### • [2021 ICRA] CloudAAE: Learning 6D Object Pose Regression with On-line Data Synthesis on Point Clouds. [\[PDF\]](https://arxiv.org/pdf/2103.01977)
_Ge Gao, Mikko Lauri, Xiaolin Hu, Jianwei Zhang, Simone Frintrop_

##### • [2021 ICRA] ParametricNet: 6DoF Pose Estimation Network for Parametric Shapes in Stacked Scenarios. [\[PDF\]]()
_Tian Yu, Wang Xueqian_

##### • [2021 ICRA] REDE: End-To-End Object 6D Pose Robust Estimation Using Differentiable Outliers Elimination. [\[PDF\]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9363576)
_Weitong Hua, Zhongxiang Zhou, Jun Wu, Huang Huang, Yue Wang, and Rong Xiong_

##### • [2021 ICRA] 6D Object Pose Estimation with Pairwise Compatible Geometric Features. [\[PDF\]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9561404)
_Muyuan Lin, Varun Murali, Sertac Karaman_

##### • [2021 ICRA] Optimizing RGB-D Fusion for Accurate 6DoF Pose Estimation. [\[PDF\]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9361135)
_Lounes Saadi, Bassem Besbes, Sebastien Kramm, and Abdelaziz Bensrhair_

##### • [2021 ICRA] MFPN-6D : Real-time One-stage Pose Estimation of Objects on RGB Images. [\[PDF\]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9561878)
_Penglei Liu, Qieshi Zhang, Jin Zhang, Fei Wang, Jun Cheng_

##### • [2021 ICRA] Investigations on Output Parameterizations of Neural Networks for Single Shot 6D Object Pose Estimation. [\[PDF\]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9561712)
_Kilian Kleeberger, Markus Volk, Richard Bormann1, and Marco F. Huber1_

##### • [2021 ICRA] L6DNet: Light 6 DoF Network for Robust and Precise Object Pose Estimation with Small Datasets. [\[PDF\]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9364353)
_Mathieu Gonzalez, Amine Kacete, Albert Murienne, and Eric Marchand_

[\[back to top\]](#contents)


### 2021 IROS

##### • [2021 RA-L & IROS] Category-Level Metric Scale Object Shape and Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2109.00326)
 _Taeyeop Lee, Byeong-Uk Lee, Myungchul Kim, In So Kweon_

##### • [2021 IROS] Iterative Coarse-To-Fine 6D-Pose Estimation Using Back-Propagation. [\[PDF\]](http://mprg.jp/data/MPRG/C_group/C20210929_araki.pdf)
_Ryosuke Araki, Kohsuke Mano, Tadanori Hirano_

##### • [2021 IROS] Object Learning for 6D Pose Estimation and Grasping from RGB-D Videos of In-Hand Manipulation. [\[PDF\]](http://mprg.jp/data/MPRG/C_group/C20210929_araki.pdf)
_Ryosuke Araki, Kohsuke Mano, Tadanori Hirano_

##### • [2021 IROS] Precise Object Placement with Pose Distance Estimations for Different Objects and Grippers. [\[PDF\]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9635884)
_Timothy Patten, Kiru Park1, Markus Leitner, Kevin Wolfram and Markus Vincze_

##### • [2021 IROS] TemporalFusion: Temporal Motion Reasoning with Multi-Frame Fusion for 6D Object Pose Estimation. [\[PDF\]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9636583)
_Fengjun Mu; Rui Huang; Ao Luo; Xin Li; Jing Qiu; Hong Cheng_

##### • [2021 IROS] BundleTrack: 6D Pose Tracking for Novel Objects without Instance or Category-Level 3D Models. [\[PDF\]](https://arxiv.org/pdf/2108.00516) [\[Code\]](https://github.com/wenbowen123/BundleTrack)
 _Bowen Wen, Kostas Bekris_

##### • [2021 IROS] KDFNet: Learning Keypoint Distance Field for 6D Object Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2109.10127)
 _Xingyu Liu, Shun Iwase, Kris M. Kitani_

##### • [2021 IROS] Category-Level 6D Object Pose Estimation via Cascaded Relation and Recurrent Reconstruction Networks. [\[PDF\]](https://arxiv.org/pdf/2108.08755)
 _Jiaze Wang, Kai Chen, Qi Dou_

##### • [2021 IROS] VIPose: Real-time Visual-Inertial 6D Object Pose Tracking. [\[PDF\]](https://arxiv.org/pdf/2107.12617)
 _Rundong Ge, Giuseppe Loianno_

[\[back to top\]](#contents)


### 2021 Others

##### • [2021 BMVC] OMAD: Object Model with Articulated Deformations for Pose Estimation and Retrieval. [\[PDF\]](https://arxiv.org/pdf/2112.07334) [\[Project\]](https://sites.google.com/view/omad-bmvc/) [\[Code\]](https://www.google.com/url?q=https%3A%2F%2Fgithub.com%2Fxiaoxiaoxh%2FOMAD&sa=D&sntz=1&usg=AFQjCNHRMrL0ldm-wi5n-VBfPVYkmuWrhg)
_Han Xue, Liu Liu, Wenqiang Xu, Haoyuan Fu, Cewu Lu_

##### • [2021 GCPR] T6D-Direct: Transformers for Multi-Object 6D Pose Direct Regression. [\[PDF\]](https://arxiv.org/pdf/2109.10948)
 _Arash Amini, Arul Selvam Periyasamy, Sven Behnke_

##### • [2021 AAAI] SD-Pose: Semantic Decomposition for Cross-Domain 6D Object Pose Estimation. [\[PDF\]](https://ojs.aaai.org/index.php/AAAI/article/view/16298/16105)
 _Zhigang Li, Yinlin Hu, Mathieu Salzmann, Xiangyang Ji_

##### • [2021 WACV] A Pose Proposal and Refinement Network for Better 6D Object Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content/WACV2021/papers/Trabelsi_A_Pose_Proposal_and_Refinement_Network_for_Better_6D_Object_WACV_2021_paper.pdf)
 _Ameni Trabelsi, Mohamed Chaabane, Nathaniel Blanchard, Ross Beveridge_

##### • [2021 ICLR Oral] Do 2D GANs Know 3D Shape? Unsupervised 3D Shape Reconstruction from 2D Image GANs. [\[PDF\]](https://arxiv.org/pdf/2011.00844.pdf) [\[Code\]](https://github.com/XingangPan/GAN2Shape) [\[Project\]](https://xingangpan.github.io/projects/GAN2Shape.html)
 _Xingang Pan, Bo Dai, Ziwei Liu, Chen Change Loy, Ping Luo_

 [\[back to top\]](#contents)

### 2020 ECCV

##### • CosyPose: Consistent multi-view multi-object 6D pose estimation. [\[PDF\]](https://arxiv.org/pdf/2008.08465) [\[Project\]](https://www.di.ens.fr/willow/research/cosypose/) [\[Code\]](https://github.com/ylabbe/cosypose)
 _Yann Labbé, Justin Carpentier, Mathieu Aubry, and Josef Sivic_

##### • Self6D: Self-Supervised Monocular 6D Object Pose Estimation. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123460103.pdf)
 _Gu Wang, Fabian Manhardt, Jianzhun Shao, Xiangyang Ji, Nassir Navab , Federico Tombari_
##### • Neural Object Learning for 6D Pose Estimation Using a Few Cluttered Images. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123490630.pdf) [\[Video\]](https://www.youtube.com/watch?v=fQJPS01cmac&feature=youtu.be)
 _Kiru Park, Timothy Patten, Markus Vincze_
##### • Point-Set Anchors for Object Detection, Instance Segmentation and Pose Estimation. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123550528.pdf)
 _Fangyun Wei, Xiao Sun, Hongyang Li, Jingdong Wang, Stephen Lin_
##### • ContactPose: A Dataset of Grasps with Object Contact and Hand Pose. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123580358.pdf)
 _Samarth Brahmbhatt, Chengcheng Tang, Christopher D. Twigg, Charles C. Kemp, James Hays_
##### • Shape Prior Deformation for Categorical 6D Object Pose and Size Estimation. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660528.pdf) [\[Video\]](https://www.youtube.com/watch?v=4fkowqaYvQc) [\[Code\]](https://github.com/mentian/object-deformnet)
 _Meng Tian, Marcelo H Ang Jr, Gim Hee Lee_
##### • Category Level Object Pose Estimation via Neural Analysis-by-Synthesis. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123710137.pdf)
 _Xu Chen, Zijian Dong, Jie Song, Andreas Geiger, Otmar Hilliges_
##### • Pose Augmentation: Class-agnostic Object Pose Transformation for Object Recognition. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123730137.pdf)
 _Yunhao Ge, Jiaping Zhao, Laurent Itti_
##### • Few-Shot Single-View 3-D Object Reconstruction with Compositional Priors. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123700613.pdf)
 _Mateusz Michalkiewicz, Sarah Parisot, Stavros Tsogkas, Mahsa Baktashmotlagh, Anders Eriksson, Eugene Belilovsky_
 ##### • ContactPose: A Dataset of Grasps with Object Contact and Hand Pose. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123580358.pdf)
 _Samarth Brahmbhatt, Chengcheng Tang, Christopher D. Twigg, Charles C. Kemp, James Hays_
 ##### • Coherent full scene 3D reconstruction from a single RGB image. [\[PDF\]](https://arxiv.org/pdf/2004.12989.pdf)
 _Stefan Popov, Pablo Bauszat, Vittorio Ferrari_
##### • Measuring Generalisation to Unseen Viewpoints, Articulations, Shapes and Objects for 3D Hand Pose Estimation under Hand-Object Interaction. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123680086.pdf)
 _Anil Armagan, Guillermo Garcia-Hernando, Seungryul Baek, Shreyas Hampali, Mahdi Rad, Zhaohui Zhang, Shipeng Xie, MingXiu Chen, Boshen Zhang, Fu Xiong, Yang Xiao, Zhiguo Cao, Junsong Yuan, Pengfei Ren⁸, Weiting Huang⁸, Haifeng Sun⁸, Marek Hrúz⁹, Jakub Kanis⁹, Zdeněk Krňoul⁹, Qingfu Wan, Shile Li, Linlin Yang, Dongheui Lee, Angela Yao, Weiguo Zhou, Sijia Mei, Yunhui Liu, Adrian Spurr, Umar Iqbal, Pavlo Molchanov, Philippe Weinzaepfel, Romain Brégier, Grégory Rogez, Vincent Lepetit, Tae-Kyun Kim_

<details>
<summary>Show More</summary>

#### ***Human Pose Estimation and Body Reconstruction***

 ##### • VoxelPose: Towards Multi-Camera 3D Human Pose Estimation in Wild Environment. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123460188.pdf)
 _Hanyue Tu, Chunyu Wang, Wenjun Zeng_
##### • Towards Part-aware Monocular 3D Human Pose Estimation: An Architecture Search Approach. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123480715.pdf)
 _Zerui Chen, Yan Huang, Hongyuan Yu, Bin Xue, Ke Han, Yiru Guo, Liang Wang_
##### • View-Invariant Probabilistic Embedding for Human Pose. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123500052.pdf)
 _Jennifer J. Sun, Jiaping Zhao, Liang-Chieh Chen, Florian Schroff, Hartwig Adam, Ting Liu_
##### • Weakly Supervised 3D Human Pose and Shape Reconstruction with Normalizing Flows. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123510460.pdf)
 _Andrei Zanfir, Eduard Gabriel Bazavan, Hongyi Xu, William T. Freeman, Rahul Sukthankar, Cristian Sminchisescu_
##### • I2L-MeshNet: Image-to-Lixel Prediction Network for Accurate 3D Human Pose and Mesh Estimation from a Single RGB Image. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123520732.pdf)
 _Gyeongsik Moon, Kyoung Mu Lee_
##### • Pose2Mesh: Graph Convolutional Network for 3D Human Pose and Mesh Recovery from a 2D Human Pose. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123520749.pdf)
 _Hongsuk Choi, Gyeongsik Moon, Kyoung Mu Lee_
##### • Pose2Mesh: Graph Convolutional Network for 3D Human Pose and Mesh Recovery from a 2D Human Pose. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123520749.pdf)
 _Hongsuk Choi, Gyeongsik Moon, Kyoung Mu Lee_
##### • Whole-Body Human Pose Estimation in the Wild. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123540188.pdf)
 _Sheng Jin, Lumin Xu, Jin Xu, Can Wang, Wentao Liu, Chen Qian, Wanli Ouyang, Ping Luo_
##### • 3D Human Shape and Pose from a Single Low-Resolution Image with Self-Supervised Learning. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123540273.pdf)
 _Xiangyu Xu, Hao Chen, Francesc Moreno-Noguer, László A. Jeni, Fernando De la Torre_
##### • A Comprehensive Study of Weight Sharing in Graph Networks for 3D Human Pose Estimation. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123550324.pdf)
 _Kenkun Liu, Rongqi Ding, Zhiming Zou, Le Wang, Wei Tang_
##### • Graph-PCNN: Two Stage Human Pose Estimation with Graph Pose Refinement. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123560477.pdf)
 _Jian Wang, Xiang Long, Yuan Gao, Errui Ding, Shilei Wen_
##### • SRNet: Improving Generalization in 3D Human Pose Estimation with a Split-and-Recombine Approach. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123590494.pdf)
 _Ailing Zeng, Xiao Sun, Fuyang Huang, Minhao Liu, Qiang Xu, Stephen Lin_
##### • Unsupervised 3D Human Pose Representation with Viewpoint and Pose Disentanglement. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123640103.pdf)
 _Qiang Nie , Ziwei Liu , Yunhui Liu_
##### • Adversarial Semantic Data Augmentation for Human Pose Estimation. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123640596.pdf)
 _Yanrui Bin, Xuan Cao, Xinya Chen, Yanhao Ge, Ying Tai, Chengjie Wang, Jilin Li, Feiyue Huang, Changxin Gao, Nong Sang_
##### • Occlusion-Aware Siamese Network for Human Pose Estimation. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123650392.pdf)
 _Lu Zhou, Yingying Chen, Yunze Gao, Jinqiao Wang, Hanqing Lu_
##### • From Image to Stability: Learning Dynamics from Human Pose. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123680528.pdf)
 _Jesse Scott, Bharadwaj Ravichandran, Christopher Funk, Robert T. Collins, Yanxi Liu_
##### • Combining Implicit Function Learning and Parametric Models for 3D Human Reconstruction. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123470307.pdf)
 _Bharat Lal Bhatnagar, Cristian Sminchisescu, Christian Theobalt, Gerard Pons-Moll_
##### • Weakly Supervised 3D Human Pose and Shape Reconstruction with Normalizing Flows. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123510460.pdf)
 _Andrei Zanfir, Eduard Gabriel Bazavan, Hongyi Xu, William T. Freeman, Rahul Sukthankar, Cristian Sminchisescu_
##### • 3D Human Shape Reconstruction from a Polarization Image. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123590341.pdf)
 _Shihao Zou, Xinxin Zuo, Yiming Qian, Sen Wang, Chi Xu, Minglun Gong , Li Cheng_

</details>

[\[back to top\]](#contents)

### 2020 CVPR

##### • PVN3D: A Deep Point-wise 3D Keypoints Voting Network for 6DoF Pose Estimation. [\[PDF\]](https://arxiv.org/abs/1911.04231) [\[Code\]](https://github.com/ethnhe/PVN3D)
 _Yisheng He, Wei Sun, Haibin Huang, Jianran Liu, Haoqiang Fan, Jian Sun_
##### • Total3DUnderstanding: Joint Layout, Object Pose and Mesh Reconstruction for Indoor Scenes From a Single Image. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Nie_Total3DUnderstanding_Joint_Layout_Object_Pose_and_Mesh_Reconstruction_for_Indoor_CVPR_2020_paper.pdf)
 _Nie, Yinyu and Han, Xiaoguang and Guo, Shihui and Zheng, Yujian and Chang, Jian and Zhang, Jian Jun_
##### • Category-Level Articulated Object Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Category-Level_Articulated_Object_Pose_Estimation_CVPR_2020_paper.pdf)
 _Li, Xiaolong and Wang, He and Yi, Li and Guibas, Leonidas J. and Abbott, A. Lynn and Song, Shuran_
##### • Reconstruct Locally, Localize Globally: A Model Free Method for Object Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Cai_Reconstruct_Locally_Localize_Globally_A_Model_Free_Method_for_Object_CVPR_2020_paper.pdf)
 _Cai, Ming and Reid, Ian_
##### • HybridPose: 6D Object Pose Estimation Under Hybrid Representations. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Song_HybridPose_6D_Object_Pose_Estimation_Under_Hybrid_Representations_CVPR_2020_paper.pdf) [\[Code\]](https://github.com/chensong1995/HybridPose)
 _Song, Chen and Song, Jiaru and Huang, Qixing_
##### • Single-Stage 6D Object Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Hu_Single-Stage_6D_Object_Pose_Estimation_CVPR_2020_paper.pdf) [\[Code\]](https://github.com/cvlab-epfl/single-stage-pose)
 _Hu, Yinlin and Fua, Pascal and Wang, Wei and Salzmann, Mathieu_
##### • Novel Object Viewpoint Estimation Through Reconstruction Alignment. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Banani_Novel_Object_Viewpoint_Estimation_Through_Reconstruction_Alignment_CVPR_2020_paper.pdf)
 _El Banani, Mohamed and Corso, Jason J. and Fouhey, David F._
##### • HOnnotate: A Method for 3D Annotation of Hand and Object Poses. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Hampali_HOnnotate_A_Method_for_3D_Annotation_of_Hand_and_Object_CVPR_2020_paper.pdf)
 _Hampali, Shreyas and Rad, Mahdi and Oberweger, Markus and Lepetit, Vincent_
 ##### • Sub-Frame Appearance and 6D Pose Estimation of Fast Moving Objects. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Rozumnyi_Sub-Frame_Appearance_and_6D_Pose_Estimation_of_Fast_Moving_Objects_CVPR_2020_paper.pdf)
 _Rozumnyi, Denys and Kotera, Jan and Sroubek, Filip and Matas, Jiri_
##### • Weakly-Supervised Domain Adaptation via GAN and Mesh Model for Estimating 3D Hand Poses Interacting Objects. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Baek_Weakly-Supervised_Domain_Adaptation_via_GAN_and_Mesh_Model_for_Estimating_CVPR_2020_paper.pdf)
 _Baek, Seungryul and Kim, Kwang In and Kim, Tae-Kyun_
 ##### • Learning Geocentric Object Pose in Oblique Monocular Images. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Christie_Learning_Geocentric_Object_Pose_in_Oblique_Monocular_Images_CVPR_2020_paper.pdf)
 _Christie, Gordon and Abujder, Rodrigo Rene Rai Munoz and Foster, Kevin and Hagstrom, Shea and Hager, Gregory D. and Brown, Myron Z._
##### • LatentFusion: End-to-End Differentiable Reconstruction and Rendering for Unseen Object Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Park_LatentFusion_End-to-End_Differentiable_Reconstruction_and_Rendering_for_Unseen_Object_Pose_CVPR_2020_paper.pdf) [\[Code\]](https://github.com/NVlabs/latentfusion)
 _Park, Keunhong and Mousavian, Arsalan and Xiang, Yu and Fox, Dieter_
##### • Mixture Dense Regression for Object Detection and Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Varamesh_Mixture_Dense_Regression_for_Object_Detection_and_Human_Pose_Estimation_CVPR_2020_paper.pdf)
 _Varamesh, Ali and Tuytelaars, Tinne_
##### • Learning Canonical Shape Space for Category-Level 6D Object Pose and Size Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Chen_Learning_Canonical_Shape_Space_for_Category-Level_6D_Object_Pose_and_CVPR_2020_paper.pdf)
 _Chen, Dengsheng and Li, Jun and Wang, Zheng and Xu, Kai_
##### • Multi-Path Learning for Object Pose Estimation Across Domains. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Sundermeyer_Multi-Path_Learning_for_Object_Pose_Estimation_Across_Domains_CVPR_2020_paper.pdf)
 _Sundermeyer, Martin and Durner, Maximilian and Puang, En Yen and Marton, Zoltan-Csaba and Vaskevicius, Narunas and Arras, Kai O. and Triebel, Rudolph_
##### • EPOS: Estimating 6D Pose of Objects With Symmetries. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Hodan_EPOS_Estimating_6D_Pose_of_Objects_With_Symmetries_CVPR_2020_paper.pdf) [\[Project\]](http://cmp.felk.cvut.cz/epos/)
 _Hodan, Tomas and Barath, Daniel and Matas, Jiri_
##### • MoreFusion: Multi-object Reasoning for 6D Pose Estimation from Volumetric Fusion. [\[PDF\]](https://arxiv.org/pdf/2004.04336) [\[Code\]](https://github.com/wkentaro/morefusion)
 _Kentaro Wada; Edgar Sucar; Stephen James; Daniel Lenton; Andrew J. Davison_
 ##### • G2L-Net: Global to Local Network for Real-time 6D Pose Estimation with Embedding Vector Features. [\[PDF\]](https://arxiv.org/abs/2003.11089) [\[Code\]](https://github.com/DC1991/G2L_Net)
 _Wei Chen, Xi Jia, Hyung Jin Chang, Jinming Duan and Ales Leonardis_
##### • VN3D: A Deep Point-wise 3D Keypoints Voting Network for 6DoF Pose Estimation. [\[PDF\]](https://arxiv.org/abs/1911.04231) [\[Code\]](https://github.com/ethnhe/PVN3D)
 _Yisheng He, Wei Sun, Haibin Huang, Jianran Liu, Haoqiang Fan, Jian Sun_
##### • InPerfectShape: Certifiably Optimal 3D Shape Reconstruction from 2DLandmarks. [\[PDF\]](http://arxiv.org/abs/1911.11924v2)
 _Heng Yang, Luca Carlone_
 ##### • PFNet: Point Fractal Network for 3D Point Cloud Completion. [\[PDF\]](http://arxiv.org/abs/2003.00410v1)
 _Zitian Huang, Yikuan Yu, Jiawen Xu, Feng Ni, Xinyi Le_
 ##### • KeyPose: Multi-view 3D Labeling and Keypoint Estimation for Transparent Objects. [\[PDF\]](https://arxiv.org/abs/1912.02805) [\[Code\]](https://sites.google.com/view/keypose)
 _Xingyu Liu, Rico Jonschkowski, Anelia Angelova, Kurt Konolige_
 ##### • Reconstruct Locally, Localize Globally: A Model Free Method for Object Pose Estimation. [\[PDF\]](http://openaccess.thecvf.com/content_CVPR_2020/papers/Cai_Reconstruct_Locally_Localize_Globally_A_Model_Free_Method_for_Object_CVPR_2020_paper.pdf)
 _Ming Cai, Ian Reid_
 ##### • PFRL: Pose-Free Reinforcement Learning for 6D Pose Estimation. [\[PDF\]](http://openaccess.thecvf.com/content_CVPR_2020/papers/Shao_PFRL_Pose-Free_Reinforcement_Learning_for_6D_Pose_Estimation_CVPR_2020_paper.pdf)
 _Jianzhun Shao, Yuhang Jiang, Gu Wang, Zhigang Li, Xiangyang Ji_
 ##### • Learning deep network for detecting 3D object keypoints and 6D poses. [\[PDF\]](http://openaccess.thecvf.com/content_CVPR_2020/papers/Zhao_Learning_Deep_Network_for_Detecting_3D_Object_Keypoints_and_6D_CVPR_2020_paper.pdf)
 _Wanqing Zhao, Shaobo Zhang, Ziyu Guan, Wei Zhao, Jinye Peng, Jianping Fan_

<details>
<summary>Show More</summary>

#### ***Human Pose Estimation and Body Reconstruction***

 ##### • Deep Kinematics Analysis for Monocular 3D Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Xu_Deep_Kinematics_Analysis_for_Monocular_3D_Human_Pose_Estimation_CVPR_2020_paper.pdf)
 _Xu, Jingwei and Yu, Zhenbo and Ni, Bingbing and Yang, Jiancheng and Yang, Xiaokang and Zhang, Wenjun_
##### • Fusing Wearable IMUs With Multi-View Images for Human Pose Estimation: A Geometric Approach. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhang_Fusing_Wearable_IMUs_With_Multi-View_Images_for_Human_Pose_Estimation_CVPR_2020_paper.pdf)
 _Zhang, Zhe and Wang, Chunyu and Qin, Wenhu and Zeng, Wenjun_
 ##### • HigherHRNet: Scale-Aware Representation Learning for Bottom-Up Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Cheng_HigherHRNet_Scale-Aware_Representation_Learning_for_Bottom-Up_Human_Pose_Estimation_CVPR_2020_paper.pdf)
 _Cheng, Bowen and Xiao, Bin and Wang, Jingdong and Shi, Honghui and Huang, Thomas S. and Zhang, Lei_
##### • UniPose: Unified Human Pose Estimation in Single Images and Videos. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Artacho_UniPose_Unified_Human_Pose_Estimation_in_Single_Images_and_Videos_CVPR_2020_paper.pdf)
 _Artacho, Bruno and Savakis, Andreas_
##### • Self-Supervised 3D Human Pose Estimation via Part Guided Novel Image Synthesis. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Kundu_Self-Supervised_3D_Human_Pose_Estimation_via_Part_Guided_Novel_Image_CVPR_2020_paper.pdf)
 _Kundu, Jogendra Nath and Seth, Siddharth and Jampani, Varun and Rakesh, Mugalodi and Babu, R. Venkatesh and Chakraborty, Anirban_
##### • Distribution-Aware Coordinate Representation for Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhang_Distribution-Aware_Coordinate_Representation_for_Human_Pose_Estimation_CVPR_2020_paper.pdf)
 _Zhang, Feng and Zhu, Xiatian and Dai, Hanbin and Ye, Mao and Zhu, Ce_
##### • Attention Mechanism Exploits Temporal Contexts: Real-Time 3D Human Pose Reconstruction. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Liu_Attention_Mechanism_Exploits_Temporal_Contexts_Real-Time_3D_Human_Pose_Reconstruction_CVPR_2020_paper.pdf)
 _Liu, Ruixu and Shen, Ju and Wang, He and Chen, Chen and Cheung, Sen-ching and Asari, Vijayan_
##### • Bodies at Rest: 3D Human Pose and Shape Estimation From a Pressure Image Using Synthetic Data. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Clever_Bodies_at_Rest_3D_Human_Pose_and_Shape_Estimation_From_CVPR_2020_paper.pdf)
 _Clever, Henry M. and Erickson, Zackory and Kapusta, Ariel and Turk, Greg and Liu, Karen and Kemp, Charles C._
##### • The Devil Is in the Details: Delving Into Unbiased Data Processing for Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Huang_The_Devil_Is_in_the_Details_Delving_Into_Unbiased_Data_CVPR_2020_paper.pdf)
 _Huang, Junjie and Zhu, Zheng and Guo, Feng and Huang, Guan_
##### • Sequential 3D Human Pose and Shape Estimation From Point Clouds. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Wang_Sequential_3D_Human_Pose_and_Shape_Estimation_From_Point_Clouds_CVPR_2020_paper.pdf)
 _Wang, Kangkan and Xie, Jin and Zhang, Guofeng and Liu, Lei and Yang, Jian_
##### • Weakly-Supervised 3D Human Pose Learning via Multi-View Images in the Wild. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Iqbal_Weakly-Supervised_3D_Human_Pose_Learning_via_Multi-View_Images_in_the_CVPR_2020_paper.pdf)
 _Iqbal, Umar and Molchanov, Pavlo and Kautz, Jan_
##### • 3D Human Mesh Regression With Dense Correspondence. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zeng_3D_Human_Mesh_Regression_With_Dense_Correspondence_CVPR_2020_paper.pdf)
 _Zeng, Wang and Ouyang, Wanli and Luo, Ping and Liu, Wentao and Wang, Xiaogang_
##### • Multiview-Consistent Semi-Supervised Learning for 3D Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Mitra_Multiview-Consistent_Semi-Supervised_Learning_for_3D_Human_Pose_Estimation_CVPR_2020_paper.pdf)
 _Mitra, Rahul and Gundavarapu, Nitesh B. and Sharma, Abhishek and Jain, Arjun_
##### • Object-Occluded Human Shape and Pose Estimation From a Single Color Image. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhang_Object-Occluded_Human_Shape_and_Pose_Estimation_From_a_Single_Color_CVPR_2020_paper.pdf)
 _Zhang, Tianshu and Huang, Buzhen and Wang, Yangang_
##### • GHUM & GHUML: Generative 3D Human Shape and Articulated Pose Models. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Xu_GHUM__GHUML_Generative_3D_Human_Shape_and_Articulated_Pose_CVPR_2020_paper.pdf)
 _Xu, Hongyi and Bazavan, Eduard Gabriel and Zanfir, Andrei and Freeman, William T. and Sukthankar, Rahul and Sminchisescu, Cristian_
##### • Cascaded Deep Monocular 3D Human Pose Estimation With Evolutionary Training Data. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Cascaded_Deep_Monocular_3D_Human_Pose_Estimation_With_Evolutionary_Training_CVPR_2020_paper.pdf)
 _Li, Shichao and Ke, Lei and Pratama, Kevin and Tai, Yu-Wing and Tang, Chi-Keung and Cheng, Kwang-Ting_
##### • Optical Non-Line-of-Sight Physics-Based 3D Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Isogawa_Optical_Non-Line-of-Sight_Physics-Based_3D_Human_Pose_Estimation_CVPR_2020_paper.pdf)
 _Isogawa, Mariko and Yuan, Ye and O'Toole, Matthew and Kitani, Kris M._
##### • VIBE: Video Inference for Human Body Pose and Shape Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Kocabas_VIBE_Video_Inference_for_Human_Body_Pose_and_Shape_Estimation_CVPR_2020_paper.pdf)
 _Kocabas, Muhammed and Athanasiou, Nikos and Black, Michael J._
##### • VIBE: Video Inference for Human Body Pose and Shape Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Kocabas_VIBE_Video_Inference_for_Human_Body_Pose_and_Shape_Estimation_CVPR_2020_paper.pdf)
 _Kocabas, Muhammed and Athanasiou, Nikos and Black, Michael J._
##### • TetraTSDF: 3D Human Reconstruction From a Single Image With a Tetrahedral Outer Shell. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Onizuka_TetraTSDF_3D_Human_Reconstruction_From_a_Single_Image_With_a_CVPR_2020_paper.pdf)
 _Onizuka, Hayato and Hayirci, Zehra and Thomas, Diego and Sugimoto, Akihiro and Uchiyama, Hideaki and Taniguchi, Rin-ichiro_
##### • Attention Mechanism Exploits Temporal Contexts: Real-Time 3D Human Pose Reconstruction. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Liu_Attention_Mechanism_Exploits_Temporal_Contexts_Real-Time_3D_Human_Pose_Reconstruction_CVPR_2020_paper.pdf)
 _Liu, Ruixu and Shen, Ju and Wang, He and Chen, Chen and Cheung, Sen-ching and Asari, Vijayan_
##### • Three-Dimensional Reconstruction of Human Interactions. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Fieraru_Three-Dimensional_Reconstruction_of_Human_Interactions_CVPR_2020_paper.pdf)
 _Fieraru, Mihai and Zanfir, Mihai and Oneata, Elisabeta and Popa, Alin-Ionut and Olaru, Vlad and Sminchisescu, Cristian_
##### • MetaFuse: A Pre-trained Fusion Model for Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Xie_MetaFuse_A_Pre-trained_Fusion_Model_for_Human_Pose_Estimation_CVPR_2020_paper.pdf)
 _Xie, Rongchang and Wang, Chunyu and Wang, Yizhou_
##### • You2Me: Inferring Body Pose in Egocentric Video via First and Second Person Interactions. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Ng_You2Me_Inferring_Body_Pose_in_Egocentric_Video_via_First_and_CVPR_2020_paper.pdf)
 _Ng, Evonne and Xiang, Donglai and Joo, Hanbyul and Grauman, Kristen_
##### • Mixture Dense Regression for Object Detection and Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Varamesh_Mixture_Dense_Regression_for_Object_Detection_and_Human_Pose_Estimation_CVPR_2020_paper.pdf)
 _Varamesh, Ali and Tuytelaars, Tinne_
##### • Combining Detection and Tracking for Human Pose Estimation in Videos. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Wang_Combining_Detection_and_Tracking_for_Human_Pose_Estimation_in_Videos_CVPR_2020_paper.pdf)
 _Wang, Manchen and Tighe, Joseph and Modolo, Davide_

</details>


[\[back to top\]](#contents)

### 2020 Others
##### • [2020 IROS] se(3)-TrackNet: Data-driven 6D Pose Tracking by Calibrating Image Residuals in Synthetic Domains. [\[PDF\]](https://arxiv.org/abs/2007.13866) [\[Code\]](https://github.com/wenbowen123/iros20-6d-pose-tracking)
 _Wen, Bowen and Mitash, Chaitanya and Ren, Baozhang and Bekris, Kostas_
##### • [2020 3DV] Spatial Attention Improves Iterative 6D Object Pose Estimation. [\[PDF\]](https://arxiv.org/pdf/2101.01659.pdf)
 _Stefan Stevsic, Otmar Hilliges_
##### • [2020 3DV] Introducing Pose Consistency and Warp-Alignment for Self-Supervised 6D Object Pose Estimation in Color Images. [\[PDF\]](https://arxiv.org/abs/2003.12344)
 _Juil Sock, Guillermo Garcia-Hernando, Anil Armagan, Tae-Kyun Kim_
##### • [2020 WACV] PointPoseNet: Point Pose Network for Robust 6D Object Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_WACV_2020/papers/Chen_PonitPoseNet_Point_Pose_Network_for_Robust_6D_Object_Pose_Estimation_WACV_2020_paper.pdf)
 _Chen, Wei and Duan, Jinming and Basevi, Hector and Chang, Hyung Jin and Leonardis, Ales_
##### • [2020 BMVC] 6DoF Object Pose Estimation via Differentiable Proxy Voting Regularizer. [\[PDF\]](https://www.bmvc2020-conference.com/assets/papers/0287.pdf)
 _Xin Yu, Zheyu Zhuang, Piotr Koniusz and HONGDONG LI_
 ##### • [2020 BMVC] A Simple and Scalable Shape Representation for 3D Reconstruction. [\[PDF\]](https://www.bmvc2020-conference.com/assets/papers/0443.pdf)
 _Mateusz Michalkiewicz, Eugene Belilovsky, Mahsa Baktashmotlagh and Anders Eriksson_
  ##### • [2020 ACCV] Weakly-supervised Reconstruction of 3D Objects with Large Shape Variation from Single In-the-Wild Images. [\[PDF\]](https://openaccess.thecvf.com/content/ACCV2020/papers/Sun_Weakly-supervised_Reconstruction_of_3D_Objects_with_Large_Shape_Variation_from_ACCV_2020_paper.pdf)
 _Shichen Sun, Zhengbang Zhu, Xiaowei Dai, Qijun Zhao, Jing Li_
 ##### • [2020 ACCV] 3D Object Detection and Pose Estimation of Unseen Objects in Color Images with Local Surface Embeddings. [\[PDF\]](https://openaccess.thecvf.com/content/ACCV2020/papers/Pitteri_3D_Object_Detection_and_Pose_Estimation_of_Unseen_Objects_in_ACCV_2020_paper.pdf)
 _Giorgia Pitteri, Aurelie Bugeau, Slobodan Ilic, Vincent Lepetit_
 ##### • [2020 ICRA] Robust 6D Object Pose Estimation by Learning RGB-D Features. [\[arXiv\]](https://arxiv.org/abs/2003.00188)
 _Meng Tian, Liang Pan, Marcelo H Ang Jr, Gim Hee Lee_
 ##### • [2020 ICRA] Single Shot 6D Object Pose Estimation. [\[arXiv\]](https://www.researchgate.net/publication/340941501_Single_Shot_6D_Object_Pose_Estimation)
 _Kilian Kleeberger, Marco F. Huber_
 ##### • [2020 ICRA] 6D Object Pose Regression Via Supervised Learning on Point Clouds. [\[arXiv\]](https://arxiv.org/pdf/2001.08942.pdf)[\[Code\]](https://github.com/GeeeG/CloudPose)
 _Ge Gao, Mikko Lauri, Yulong Wang, Xiaolin Hu, Jianwei Zhang and Simone Frintrop_
 ##### • [2020 ICRA] Self-Supervised 6D Object Pose Estimation for Robot Manipulation. [\[arXiv\]](https://arxiv.org/pdf/1909.10159.pdf) [\[Video\]](https://youtu.be/W1Y0Mmh1Gd8)
 _Xinke Deng, Yu Xiang, Arsalan Mousavian, Clemens Eppner, Timothy Bretl, Dieter Fox_
##### • [2020 ICRA] Pose-Guided Auto-Encoder and Feature-Based Refinement for 6-DoF Object Pose Regression. [\[arXiv\]](http://xiangyangji.com/uploadfile/upload/2020072017405951.pdf)
 _Zhigang Li, Xiangyang Ji_

##### • [2020 ICRA] 6-PACK: Category-level 6D Pose Tracker with Anchor-Based Keypoints. [\[arXiv\]](https://arxiv.org/pdf/1910.10750)
 _Chen Wang, Roberto Martín-Martín, Danfei Xu, Jun Lv, Cewu Lu, Li Fei-Fei, Silvio Savarese, Yuke Zhu_
<details>
<summary>Show More</summary>

#### ***Human Pose Estimation and Body Reconstruction***

##### • [2020 WACV] DeepFuse: An IMU-Aware Network for Real-Time 3D Human Pose Estimation from Multi-View Image. [\[PDF\]](https://openaccess.thecvf.com/content_WACV_2020/papers/Huang_DeepFuse_An_IMU-Aware_Network_for_Real-Time_3D_Human_Pose_Estimation_WACV_2020_paper.pdf)
 _Huang, Fuyang and Zeng, Ailing and Liu, Minhao and Lai, Qiuxia and Xu, Qiang_
##### • [2020 WACV] Unsupervised Cross-Dataset Adaptation via Probabilistic Amodal 3D Human Pose Completion. [\[PDF\]](https://openaccess.thecvf.com/content_WACV_2020/papers/Kundu_Unsupervised_Cross-Dataset_Adaptation_via_Probabilistic_Amodal_3D_Human_Pose_Completion_WACV_2020_paper.pdf)
 _Kundu, Jogendra Nath and V, Rahul M and Patravali, Jay and RADHAKRISHNAN, Venkatesh Babu_
##### • [2020 WACV] Lightweight 3D Human Pose Estimation Network Training Using Teacher-Student Learning. [\[PDF\]](https://openaccess.thecvf.com/content_WACV_2020/papers/Hwang_Lightweight_3D_Human_Pose_Estimation_Network_Training_Using_Teacher-Student_Learning_WACV_2020_paper.pdf)
 _Hwang, Dong-Hyun and Kim, Suntae and Monet, Nicolas and Koike, Hideki and Bae, Soonmin_
##### • [2020 WACV] Body Pose Sonification for a View-Independent Auditory Aid to Blind Rock Climbers. [\[PDF\]](https://openaccess.thecvf.com/content_WACV_2020/papers/Ramsay_Body_Pose_Sonification_for_a_View-Independent_Auditory_Aid_to_Blind_WACV_2020_paper.pdf)
 _Ramsay, Joseph and Chang, Hyung Jin_
##### • [2020 WACV] Reducing Footskate in Human Motion Reconstruction with Ground Contact Constraints. [\[PDF\]](https://openaccess.thecvf.com/content_WACV_2020/papers/Zou_Reducing_Footskate_in_Human_Motion_Reconstruction_with_Ground_Contact_Constraints_WACV_2020_paper.pdf)
 _Zou, Yuliang and Yang, Jimei and Ceylan, Duygu and Zhang, Jianming and Perazzi, Federico and Huang, Jia-Bin_
 ##### • [2020 BMVC] High-order Graph Convolutional Networks for 3D Human Pose Estimation. [\[PDF\]](https://www.bmvc2020-conference.com/assets/papers/0550.pdf)
 _Zhiming Zou, Kenkun Liu, Le Wang and Wei Tang_
 ##### • [2020 BMVC] Weakly Supervised Generative Network for Multiple 3D Human Pose Hypotheses. [\[PDF\]](https://www.bmvc2020-conference.com/assets/papers/0330.pdf) [\[Code\]](https://github.com/chaneyddtt/weakly-supervised-3d-pose-generator)
 _Chen Li and Gim Hee Lee_
 ##### • [2020 BMVC] Explicit Residual Descent for 3D Human Pose Estimation from 2D Joint Locations. [\[PDF\]](https://www.bmvc2020-conference.com/assets/papers/0151.pdf) [\[Code\]](https://www.bmvc2020-conference.com/programme/accepted-papers/Code%20will%20be%20made%20publicly%20available%20later)
  _Yangyuxuan Kang, Anbang Yao, Shandong Wang, Ming Lu, Yurong Chen and Enhua Wu_
 ##### • [2020 BMVC] Synthetic Training for Accurate 3D Human Pose and Shape Estimation in the Wild. [\[PDF\]](https://www.bmvc2020-conference.com/assets/papers/0081.pdf) [\[Code\]](https://github.com/akashsengupta1997/STRAPS-3DHumanShapePose)
 _Akash Sengupta, Roberto Cipolla and Ignas Budvytis_
  ##### • [2020 ACCV] Learning Global Pose Features in Graph Convolutional Networks for 3D Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content/ACCV2020/papers/Liu_Learning_Global_Pose_Features_in_Graph_Convolutional_Networks_for_3D_ACCV_2020_paper.pdf)
 _Kenkun Liu, Zhiming Zou, Wei Tang_
##### • [2020 ACCV] Anatomy and Geometry Constrained One-Stage Framework for 3D Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content/ACCV2020/papers/Cao_Anatomy_and_Geometry_Constrained_One-Stage_Framework_for_3D_Human_Pose_ACCV_2020_paper.pdf)
 _Xin Cao, Xu Zhao_
##### • [2020 ACCV] Reconstructing Human Body Mesh from Point Clouds by Adversarial GP Network. [\[PDF\]](https://openaccess.thecvf.com/content/ACCV2020/papers/Zhou_Reconstructing_Human_Body_Mesh_from_Point_Clouds_by_Adversarial_GP_ACCV_2020_paper.pdf)
 _Boyao Zhou, Jean-Sebastien Franco, Federica Bogo, Bugra Tekin, Edmond Boyer_
</details>

 [\[back to top\]](#contents)


 ### 2019 CVPR

##### • DenseFusion: 6D Object Pose Estimation by Iterative Dense Fusion. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_DenseFusion_6D_Object_Pose_Estimation_by_Iterative_Dense_Fusion_CVPR_2019_paper.pdf)
 _Wang, Chen and Xu, Danfei and Zhu, Yuke and Martin-Martin, Roberto and Lu, Cewu and Fei-Fei, Li and Savarese, Silvio_
##### • Segmentation-Driven 6D Object Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Hu_Segmentation-Driven_6D_Object_Pose_Estimation_CVPR_2019_paper.pdf)
 _Hu, Yinlin and Hugonot, Joachim and Fua, Pascal and Salzmann, Mathieu_
##### • Photometric Mesh Optimization for Video-Aligned 3D Object Reconstruction. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Lin_Photometric_Mesh_Optimization_for_Video-Aligned_3D_Object_Reconstruction_CVPR_2019_paper.pdf)
 _Lin, Chen-Hsuan and Wang, Oliver and Russell, Bryan C. and Shechtman, Eli and Kim, Vladimir G. and Fisher, Matthew and Lucey, Simon_
##### • Object Tracking by Reconstruction With View-Specific Discriminative Correlation Filters. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Kart_Object_Tracking_by_Reconstruction_With_View-Specific_Discriminative_Correlation_Filters_CVPR_2019_paper.pdf)
 _Kart, Ugur and Lukezic, Alan and Kristan, Matej and Kamarainen, Joni-Kristian and Matas, Jiri_
 ##### • Learning Joint Reconstruction of Hands and Manipulated Objects. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Hasson_Learning_Joint_Reconstruction_of_Hands_and_Manipulated_Objects_CVPR_2019_paper.pdf)
 _Hasson, Yana and Varol, Gul and Tzionas, Dimitrios and Kalevatykh, Igor and Black, Michael J. and Laptev, Ivan and Schmid, Cordelia_
##### • Monocular 3D Object Detection Leveraging Accurate Proposals and Shape Reconstruction. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Ku_Monocular_3D_Object_Detection_Leveraging_Accurate_Proposals_and_Shape_Reconstruction_CVPR_2019_paper.pdf)
 _Ku, Jason and Pon, Alex D. and Waslander, Steven L._
 ##### • Normalized Object Coordinate Space for Category-Level 6D Object Pose and Size Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Normalized_Object_Coordinate_Space_for_Category-Level_6D_Object_Pose_and_CVPR_2019_paper.pdf)
 _Wang, He and Sridhar, Srinath and Huang, Jingwei and Valentin, Julien and Song, Shuran and Guibas, Leonidas J._
##### • PVNet: Pixel-wise Voting Network for 6DoF Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Peng_PVNet_Pixel-Wise_Voting_Network_for_6DoF_Pose_Estimation_CVPR_2019_paper.pdf)
 _Sida Peng, Yuan Liu, Qixing Huang, Xiaowei Zhou, and Hujun Bao_

<details>
<summary>Show More</summary>

 #### ***Human Pose Estimation and Body Reconstruction***


 ##### • Self-Supervised Learning of 3D Human Pose Using Multi-View Geometry. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Kocabas_Self-Supervised_Learning_of_3D_Human_Pose_Using_Multi-View_Geometry_CVPR_2019_paper.pdf)
 _Kocabas, Muhammed and Karagoz, Salih and Akbas, Emre_
##### • Does Learning Specific Features for Related Parts Help Human Pose Estimation?. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Tang_Does_Learning_Specific_Features_for_Related_Parts_Help_Human_Pose_CVPR_2019_paper.pdf)
 _Tang, Wei and Wu, Ying_
##### • Exploiting Temporal Context for 3D Human Pose Estimation in the Wild. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Arnab_Exploiting_Temporal_Context_for_3D_Human_Pose_Estimation_in_the_CVPR_2019_paper.pdf)
 _Arnab, Anurag and Doersch, Carl and Zisserman, Andrew_
##### • Semantic Graph Convolutional Networks for 3D Human Pose Regression. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhao_Semantic_Graph_Convolutional_Networks_for_3D_Human_Pose_Regression_CVPR_2019_paper.pdf)
 _Zhao, Long and Peng, Xi and Tian, Yu and Kapadia, Mubbasir and Metaxas, Dimitris N._
##### • Fast Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_Fast_Human_Pose_Estimation_CVPR_2019_paper.pdf)
 _Zhang, Feng and Zhu, Xiatian and Ye, Mao_
##### • Dense Intrinsic Appearance Flow for Human Pose Transfer. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Dense_Intrinsic_Appearance_Flow_for_Human_Pose_Transfer_CVPR_2019_paper.pdf)
 _Li, Yining and Huang, Chen and Loy, Chen Change_
##### • Detailed Human Shape Estimation From a Single Image by Hierarchical Mesh Deformation. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhu_Detailed_Human_Shape_Estimation_From_a_Single_Image_by_Hierarchical_CVPR_2019_paper.pdf)
 _Zhu, Hao and Zuo, Xinxin and Wang, Sen and Cao, Xun and Yang, Ruigang_
##### • Convolutional Mesh Regression for Single-Image Human Shape Reconstruction. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Kolotouros_Convolutional_Mesh_Regression_for_Single-Image_Human_Shape_Reconstruction_CVPR_2019_paper.pdf)
 _Kolotouros, Nikos and Pavlakos, Georgios and Daniilidis, Kostas_
##### • Deep High-Resolution Representation Learning for Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Sun_Deep_High-Resolution_Representation_Learning_for_Human_Pose_Estimation_CVPR_2019_paper.pdf)
 _Sun, Ke and Xiao, Bin and Liu, Dong and Wang, Jingdong_
##### • IGE-Net: Inverse Graphics Energy Networks for Human Pose Estimation and Single-View Reconstruction. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Jack_IGE-Net_Inverse_Graphics_Energy_Networks_for_Human_Pose_Estimation_and_CVPR_2019_paper.pdf)
 _Jack, Dominic and Maire, Frederic and Shirazi, Sareh and Eriksson, Anders_
##### • 3D Human Pose Estimation in Video With Temporal Convolutions and Semi-Supervised Training. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Pavllo_3D_Human_Pose_Estimation_in_Video_With_Temporal_Convolutions_and_CVPR_2019_paper.pdf)
 _Pavllo, Dario and Feichtenhofer, Christoph and Grangier, David and Auli, Michael_
##### • PoseFix: Model-Agnostic General Human Pose Refinement Network. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Moon_PoseFix_Model-Agnostic_General_Human_Pose_Refinement_Network_CVPR_2019_paper.pdf)
 _Moon, Gyeongsik and Chang, Ju Yong and Lee, Kyoung Mu_
##### • RepNet: Weakly Supervised Training of an Adversarial Reprojection Network for 3D Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Wandt_RepNet_Weakly_Supervised_Training_of_an_Adversarial_Reprojection_Network_for_CVPR_2019_paper.pdf)
 _Wandt, Bastian and Rosenhahn, Bodo_
##### • Convolutional Mesh Regression for Single-Image Human Shape Reconstruction. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Kolotouros_Convolutional_Mesh_Regression_for_Single-Image_Human_Shape_Reconstruction_CVPR_2019_paper.pdf)
 _Kolotouros, Nikos and Pavlakos, Georgios and Daniilidis, Kostas_
##### • IGE-Net: Inverse Graphics Energy Networks for Human Pose Estimation and Single-View Reconstruction. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Jack_IGE-Net_Inverse_Graphics_Energy_Networks_for_Human_Pose_Estimation_and_CVPR_2019_paper.pdf)
 _Jack, Dominic and Maire, Frederic and Shirazi, Sareh and Eriksson, Anders_
##### • Generating Multiple Hypotheses for 3D Human Pose Estimation With Mixture Density Network. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Generating_Multiple_Hypotheses_for_3D_Human_Pose_Estimation_With_Mixture_CVPR_2019_paper.pdf)
 _Li, Chen and Lee, Gim Hee_
##### • Weakly-Supervised Discovery of Geometry-Aware Representation for 3D Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Chen_Weakly-Supervised_Discovery_of_Geometry-Aware_Representation_for_3D_Human_Pose_Estimation_CVPR_2019_paper.pdf)
 _Chen, Xipeng and Lin, Kwan-Yee and Liu, Wentao and Qian, Chen and Lin, Liang_
##### • In the Wild Human Pose Estimation Using Explicit 2D Features and Intermediate 3D Representations. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Habibie_In_the_Wild_Human_Pose_Estimation_Using_Explicit_2D_Features_CVPR_2019_paper.pdf)
 _Habibie, Ikhsanul and Xu, Weipeng and Mehta, Dushyant and Pons-Moll, Gerard and Theobalt, Christian_
##### • PifPaf: Composite Fields for Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Kreiss_PifPaf_Composite_Fields_for_Human_Pose_Estimation_CVPR_2019_paper.pdf)
 _Kreiss, Sven and Bertoni, Lorenzo and Alahi, Alexandre_
##### • HoloPose: Holistic 3D Human Reconstruction In-The-Wild. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Guler_HoloPose_Holistic_3D_Human_Reconstruction_In-The-Wild_CVPR_2019_paper.pdf)
 _Guler, Riza Alp and Kokkinos, Iasonas_

 </details>

 [\[back to top\]](#contents)

### 2019 ICCV

##### • DPOD: 6D Pose Object Detector and Refiner. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Zakharov_DPOD_6D_Pose_Object_Detector_and_Refiner_ICCV_2019_paper.pdf)
 _Zakharov, Sergey and Shugurov, Ivan and Ilic, Slobodan_
 ##### • Explaining the Ambiguity of Object Detection and 6D Pose From Visual Data. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Manhardt_Explaining_the_Ambiguity_of_Object_Detection_and_6D_Pose_From_ICCV_2019_paper.pdf)
 _Manhardt, Fabian and Arroyo, Diego Martin and Rupprecht, Christian and Busam, Benjamin and Birdal, Tolga and Navab, Nassir and Tombari, Federico_
##### • Identity From Here, Pose From There: Self-Supervised Disentanglement and Generation of Objects Using Unlabeled Videos. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Xiao_Identity_From_Here_Pose_From_There_Self-Supervised_Disentanglement_and_Generation_ICCV_2019_paper.pdf)
 _Xiao, Fanyi and Liu, Haotian and Lee, Yong Jae_
##### • Accurate Monocular 3D Object Detection via Color-Embedded 3D Reconstruction for Autonomous Driving. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Ma_Accurate_Monocular_3D_Object_Detection_via_Color-Embedded_3D_Reconstruction_for_ICCV_2019_paper.pdf)
 _Ma, Xinzhu and Wang, Zhihui and Li, Haojie and Zhang, Pengbo and Ouyang, Wanli and Fan, Xin_
 ##### • Pix2Pose: Pixel-Wise Coordinate Regression of Objects for 6D Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Park_Pix2Pose_Pixel-Wise_Coordinate_Regression_of_Objects_for_6D_Pose_Estimation_ICCV_2019_paper.pdf)
 _Park, Kiru and Patten, Timothy and Vincze, Markus_
##### • CDPN: Coordinates-Based Disentangled Pose Network for Real-Time RGB-Based 6-DoF Object Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Li_CDPN_Coordinates-Based_Disentangled_Pose_Network_for_Real-Time_RGB-Based_6-DoF_Object_ICCV_2019_paper.pdf)
 _Li, Zhigang and Wang, Gu and Ji, Xiangyang_
##### • Learning Local RGB-to-CAD Correspondences for Object Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Georgakis_Learning_Local_RGB-to-CAD_Correspondences_for_Object_Pose_Estimation_ICCV_2019_paper.pdf)
 _Georgakis, Georgios and Karanam, Srikrishna and Wu, Ziyan and Kosecka, Jana_
<details>
<summary>Show More</summary>

#### ***Human Pose Estimation and Body Reconstruction***


 ##### • Occlusion-Aware Networks for 3D Human Pose Estimation in Video. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Cheng_Occlusion-Aware_Networks_for_3D_Human_Pose_Estimation_in_Video_ICCV_2019_paper.pdf)
 _Cheng, Yu and Yang, Bo and Wang, Bo and Yan, Wending and Tan, Robby T._
##### • TexturePose: Supervising Human Mesh Estimation With Texture Consistency. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Pavlakos_TexturePose_Supervising_Human_Mesh_Estimation_With_Texture_Consistency_ICCV_2019_paper.pdf)
 _Pavlakos, Georgios and Kolotouros, Nikos and Daniilidis, Kostas_
##### • On Boosting Single-Frame 3D Human Pose Estimation via Monocular Videos. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Li_On_Boosting_Single-Frame_3D_Human_Pose_Estimation_via_Monocular_Videos_ICCV_2019_paper.pdf)
 _Li, Zhi and Wang, Xuan and Wang, Fei and Jiang, Peilin_
##### • Learning to Reconstruct 3D Human Pose and Shape via Model-Fitting in the Loop. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Kolotouros_Learning_to_Reconstruct_3D_Human_Pose_and_Shape_via_Model-Fitting_ICCV_2019_paper.pdf)
 _Kolotouros, Nikos and Pavlakos, Georgios and Black, Michael J. and Daniilidis, Kostas_
##### • Optimizing Network Structure for 3D Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Ci_Optimizing_Network_Structure_for_3D_Human_Pose_Estimation_ICCV_2019_paper.pdf)
 _Ci, Hai and Wang, Chunyu and Ma, Xiaoxuan and Wang, Yizhou_
##### • Resolving 3D Human Pose Ambiguities With 3D Scene Constraints. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Hassan_Resolving_3D_Human_Pose_Ambiguities_With_3D_Scene_Constraints_ICCV_2019_paper.pdf)
 _Hassan, Mohamed and Choutas, Vasileios and Tzionas, Dimitrios and Black, Michael J._
##### • Monocular 3D Human Pose Estimation by Generation and Ordinal Ranking. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Sharma_Monocular_3D_Human_Pose_Estimation_by_Generation_and_Ordinal_Ranking_ICCV_2019_paper.pdf)
 _Sharma, Saurabh and Varigonda, Pavan Teja and Bindal, Prashast and Sharma, Abhishek and Jain, Arjun_
##### • HEMlets Pose: Learning Part-Centric Heatmap Triplets for Accurate 3D Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhou_HEMlets_Pose_Learning_Part-Centric_Heatmap_Triplets_for_Accurate_3D_Human_ICCV_2019_paper.pdf)
 _Zhou, Kun and Han, Xiaoguang and Jiang, Nianjuan and Jia, Kui and Lu, Jiangbo_
##### • Cross View Fusion for 3D Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Qiu_Cross_View_Fusion_for_3D_Human_Pose_Estimation_ICCV_2019_paper.pdf)
 _Qiu, Haibo and Wang, Chunyu and Wang, Jingdong and Wang, Naiyan and Zeng, Wenjun_
##### • Shape-Aware Human Pose and Shape Reconstruction Using Multi-View Images. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Liang_Shape-Aware_Human_Pose_and_Shape_Reconstruction_Using_Multi-View_Images_ICCV_2019_paper.pdf)
 _Liang, Junbang and Lin, Ming C._
##### • Shape-Aware Human Pose and Shape Reconstruction Using Multi-View Images. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Liang_Shape-Aware_Human_Pose_and_Shape_Reconstruction_Using_Multi-View_Images_ICCV_2019_paper.pdf)
 _Liang, Junbang and Lin, Ming C._
##### • Human Mesh Recovery From Monocular Images via a Skeleton-Disentangled Representation. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Sun_Human_Mesh_Recovery_From_Monocular_Images_via_a_Skeleton-Disentangled_Representation_ICCV_2019_paper.pdf)
 _Sun, Yu and Ye, Yun and Liu, Wu and Gao, Wenpeng and Fu, Yili and Mei, Tao_
##### • Imitation Learning for Human Pose Prediction. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Wang_Imitation_Learning_for_Human_Pose_Prediction_ICCV_2019_paper.pdf)
 _Wang, Borui and Adeli, Ehsan and Chiu, Hsu-kuang and Huang, De-An and Niebles, Juan Carlos_
##### • Skeleton-Aware 3D Human Shape Reconstruction From Point Clouds. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Jiang_Skeleton-Aware_3D_Human_Shape_Reconstruction_From_Point_Clouds_ICCV_2019_paper.pdf)
 _Jiang, Haiyong and Cai, Jianfei and Zheng, Jianmin_
##### • Learnable Triangulation of Human Pose. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Iskakov_Learnable_Triangulation_of_Human_Pose_ICCV_2019_paper.pdf)
 _Iskakov, Karim and Burkov, Egor and Lempitsky, Victor and Malkov, Yury_
##### • xR-EgoPose: Egocentric 3D Human Pose From an HMD Camera. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Tome_xR-EgoPose_Egocentric_3D_Human_Pose_From_an_HMD_Camera_ICCV_2019_paper.pdf)
 _Tome, Denis and Peluse, Patrick and Agapito, Lourdes and Badino, Hernan_
##### • Not All Parts Are Created Equal: 3D Pose Estimation by Modeling Bi-Directional Dependencies of Body Parts. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Wang_Not_All_Parts_Are_Created_Equal_3D_Pose_Estimation_by_ICCV_2019_paper.pdf)
 _Wang, Jue and Huang, Shaoli and Wang, Xinchao and Tao, Dacheng_
##### • Holistic++ Scene Understanding: Single-View 3D Holistic Scene Parsing and Human Pose Estimation With Human-Object Interaction and Physical Commonsense. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Chen_Holistic_Scene_Understanding_Single-View_3D_Holistic_Scene_Parsing_and_Human_ICCV_2019_paper.pdf)
 _Chen, Yixin and Huang, Siyuan and Yuan, Tao and Qi, Siyuan and Zhu, Yixin and Zhu, Song-Chun_
##### • Through-Wall Human Mesh Recovery Using Radio Signals. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhao_Through-Wall_Human_Mesh_Recovery_Using_Radio_Signals_ICCV_2019_paper.pdf)
 _Zhao, Mingmin and Liu, Yingcheng and Raghu, Aniruddh and Li, Tianhong and Zhao, Hang and Torralba, Antonio and Katabi, Dina_
##### • DeepHuman: 3D Human Reconstruction From a Single Image. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Zheng_DeepHuman_3D_Human_Reconstruction_From_a_Single_Image_ICCV_2019_paper.pdf)
 _Zheng, Zerong and Yu, Tao and Wei, Yixuan and Dai, Qionghai and Liu, Yebin_
</details>

 [\[back to top\]](#contents)

### 2018 CVPR

##### • Real-Time Seamless Single Shot 6D Object Pose Prediction. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Tekin_Real-Time_Seamless_Single_CVPR_2018_paper.pdf)
 _Tekin, Bugra and Sinha, Sudipta N. and Fua, Pascal_
##### • 3D Pose Estimation and 3D Model Retrieval for Objects in the Wild. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Grabner_3D_Pose_Estimation_CVPR_2018_paper.pdf)
 _Grabner, Alexander and Roth, Peter M. and Lepetit, Vincent_
##### • RotationNet: Joint Object Categorization and Pose Estimation Using Multiviews From Unsupervised Viewpoints. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Kanezaki_RotationNet_Joint_Object_CVPR_2018_paper.pdf)
 _Kanezaki, Asako and Matsushita, Yasuyuki and Nishida, Yoshifumi_
##### • 3D-RCNN: Instance-Level 3D Object Reconstruction via Render-and-Compare. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Kundu_3D-RCNN_Instance-Level_3D_CVPR_2018_paper.pdf)
 _Kundu, Abhijit and Li, Yin and Rehg, James M._
<details>
<summary>Show More</summary>

#### ***Human Pose Estimation and Body Reconstruction***

 ##### • Learning to Estimate 3D Human Pose and Shape From a Single Color Image. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Pavlakos_Learning_to_Estimate_CVPR_2018_paper.pdf)
 _Pavlakos, Georgios and Zhu, Luyang and Zhou, Xiaowei and Daniilidis, Kostas_
##### • Recognizing Human Actions as the Evolution of Pose Estimation Maps. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Liu_Recognizing_Human_Actions_CVPR_2018_paper.pdf)
 _Liu, Mengyuan and Yuan, Junsong_
##### • Human Pose Estimation With Parsing Induced Learner. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Nie_Human_Pose_Estimation_CVPR_2018_paper.pdf)
 _Nie, Xuecheng and Feng, Jiashi and Zuo, Yiming and Yan, Shuicheng_
##### • Jointly Optimize Data Augmentation and Network Training: Adversarial Data Augmentation in Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Peng_Jointly_Optimize_Data_CVPR_2018_paper.pdf)
 _Peng, Xi and Tang, Zhiqiang and Yang, Fei and Feris, Rogerio S. and Metaxas, Dimitris_
##### • V2V-PoseNet: Voxel-to-Voxel Prediction Network for Accurate 3D Hand and Human Pose Estimation From a Single Depth Map. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Moon_V2V-PoseNet_Voxel-to-Voxel_Prediction_CVPR_2018_paper.pdf)
 _Moon, Gyeongsik and Chang, Ju Yong and Lee, Kyoung Mu_
##### • PoseTrack: A Benchmark for Human Pose Estimation and Tracking. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Andriluka_PoseTrack_A_Benchmark_CVPR_2018_paper.pdf)
 _Andriluka, Mykhaylo and Iqbal, Umar and Insafutdinov, Eldar and Pishchulin, Leonid and Milan, Anton and Gall, Juergen and Schiele, Bernt_
##### • 3D Human Pose Estimation in the Wild by Adversarial Learning. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Yang_3D_Human_Pose_CVPR_2018_paper.pdf)
 _Yang, Wei and Ouyang, Wanli and Wang, Xiaolong and Ren, Jimmy and Li, Hongsheng and Wang, Xiaogang_
##### • End-to-End Recovery of Human Shape and Pose. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Kanazawa_End-to-End_Recovery_of_CVPR_2018_paper.pdf)
 _Kanazawa, Angjoo and Black, Michael J. and Jacobs, David W. and Malik, Jitendra_
##### • DensePose: Dense Human Pose Estimation in the Wild. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Guler_DensePose_Dense_Human_CVPR_2018_paper.pdf)
 _Güler, Rıza Alp and Neverova, Natalia and Kokkinos, Iasonas_
##### • Ordinal Depth Supervision for 3D Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Pavlakos_Ordinal_Depth_Supervision_CVPR_2018_paper.pdf)
 _Pavlakos, Georgios and Zhou, Xiaowei and Daniilidis, Kostas_
##### • Through-Wall Human Pose Estimation Using Radio Signals. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Zhao_Through-Wall_Human_Pose_CVPR_2018_paper.pdf)
 _Zhao, Mingmin and Li, Tianhong and Abu Alsheikh, Mohammad and Tian, Yonglong and Zhao, Hang and Torralba, Antonio and Katabi, Dina_
##### • Learning Monocular 3D Human Pose Estimation From Multi-View Images. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Rhodin_Learning_Monocular_3D_CVPR_2018_paper.pdf)
 _Rhodin, Helge and Spörri, Jörg and Katircioglu, Isinsu and Constantin, Victor and Meyer, Frédéric and Müller, Erich and Salzmann, Mathieu and Fua, Pascal_
 </details>

[\[back to top\]](#contents)


### 2018 ECCV

##### • BOP: Benchmark for 6D Object Pose Estimation. [\[PDF\]](https://www.ecva.net/papers/eccv_2018/papers_ECCV/papers/Tomas_Hodan_PESTO_6D_Object_ECCV_2018_paper.pdf)
 _Hodan, Tomas and Michel, Frank and Brachmann, Eric and Kehl, Wadim and GlentBuch, Anders and Kraft, Dirk and Drost, Bertram and Vidal, Joel and Ihrke, Stephan and Zabulis, Xenophon and Sahin, Caner and Manhardt, Fabian and Tombari, Federico and Kim, Tae-Kyun and Matas, Jiri and Rother, Carsten_
##### • Making Deep Heatmaps Robust to Partial Occlusions for 3D Object Pose Estimation. [\[PDF\]](https://www.ecva.net/papers/eccv_2018/papers_ECCV/papers/Markus_Oberweger_Making_Deep_Heatmaps_ECCV_2018_paper.pdf)
 _Oberweger, Markus and Rad, Mahdi and Lepetit, Vincent_
##### • A Unified Framework for Multi-View Multi-Class Object Pose Estimation. [\[PDF\]](https://www.ecva.net/papers/eccv_2018/papers_ECCV/papers/Chi_Li_A_Unified_Framework_ECCV_2018_paper.pdf)
 _Li, Chi and Bai, Jin and Hager, Gregory D._
##### • Efficient Dense Point Cloud Object Reconstruction using Deformation Vector Fields. [\[PDF\]](https://www.ecva.net/papers/eccv_2018/papers_ECCV/papers/Kejie_Li_Efficient_Dense_Point_ECCV_2018_paper.pdf)
 _Li Kejie, Pham Trung, Zhan Huangying, Reid Ian_
##### • DeepIM: Deep iterative matching for 6d pose estimation. [\[PDF\]](https://openaccess.thecvf.com/content_ECCV_2018/papers/Yi_Li_DeepIM_Deep_Iterative_ECCV_2018_paper.pdf)
 _Yi Li, Gu Wang, Xiangyang Ji, Yu Xiang, and Dieter Fox_

<details>
<summary>Show More</summary>

#### ***Human Pose Estimation and Body Reconstruction***

 ##### • Unsupervised Geometry-Aware Representation for 3D Human Pose Estimation. [\[PDF\]](https://www.ecva.net/papers/eccv_2018/papers_ECCV/papers/Helge_Rhodin_Unsupervised_Geometry-Aware_Representation_ECCV_2018_paper.pdf)
 _Rhodin, Helge and Salzmann, Mathieu and Fua, Pascal_
##### • Learning 3D Human Pose from Structure and Motion. [\[PDF\]](https://www.ecva.net/papers/eccv_2018/papers_ECCV/papers/Rishabh_Dabral_Learning_3D_Human_ECCV_2018_paper.pdf)
 _Dabral, Rishabh and Mundhada, Anurag and Kusupati, Uday and Afaque, Safeer and Sharma, Abhishek and Jain, Arjun_
##### • Multi-Scale Structure-Aware Network for Human Pose Estimation. [\[PDF\]](https://www.ecva.net/papers/eccv_2018/papers_ECCV/papers/Lipeng_Ke_Multi-Scale_Structure-Aware_Network_ECCV_2018_paper.pdf)
 _Ke, Lipeng and Chang, Ming-Ching and Qi, Honggang and Lyu, Siwei_
##### • Recovering Accurate 3D Human Pose in The Wild Using IMUs and a Moving Camera. [\[PDF\]](https://www.ecva.net/papers/eccv_2018/papers_ECCV/papers/Timo_von_Marcard_Recovering_Accurate_3D_ECCV_2018_paper.pdf)
 _von Marcard, Timo and Henschel, Roberto and Black, Michael J. and Rosenhahn, Bodo and Pons-Moll, Gerard_
##### • Deeply Learned Compositional Models for Human Pose Estimation. [\[PDF\]](https://www.ecva.net/papers/eccv_2018/papers_ECCV/papers/Wei_Tang_Deeply_Learned_Compositional_ECCV_2018_paper.pdf)
 _Tang, Wei and Yu, Pei and Wu, Ying_
##### • Deep Autoencoder for Combined Human Pose Estimation and Body Model Upscaling. [\[PDF\]](https://www.ecva.net/papers/eccv_2018/papers_ECCV/papers/Matthew_Trumble_Deep_Autoencoder_for_ECCV_2018_paper.pdf)
 _Trumble, Matthew and Gilbert, Andrew and Hilton, Adrian and Collomosse, John_
##### • Integral Human Pose Regression. [\[PDF\]](https://www.ecva.net/papers/eccv_2018/papers_ECCV/papers/Xiao_Sun_Integral_Human_Pose_ECCV_2018_paper.pdf)
 _Sun, Xiao and Xiao, Bin and Wei, Fangyin and Liang, Shuang and Wei, Yichen_
##### • Pose Guided Human Video Generation. [\[PDF\]](https://www.ecva.net/papers/eccv_2018/papers_ECCV/papers/Ceyuan_Yang_Pose_Guided_Human_ECCV_2018_paper.pdf)
 _Yang, Ceyuan and Wang, Zhe and Zhu, Xinge and Huang, Chen and Shi, Jianping and Lin, Dahua_
##### • Mutual Learning to Adapt for Joint Human Parsing and Pose Estimation. [\[PDF\]](https://www.ecva.net/papers/eccv_2018/papers_ECCV/papers/Xuecheng_Nie_Mutual_Learning_to_ECCV_2018_paper.pdf)
 _Nie, Xuecheng and Feng, Jiashi and Yan, Shuicheng_
##### • Simple Baselines for Human Pose Estimation and Tracking. [\[PDF\]](https://www.ecva.net/papers/eccv_2018/papers_ECCV/papers/Bin_Xiao_Simple_Baselines_for_ECCV_2018_paper.pdf)
 _Xiao, Bin and Wu, Haiping and Wei, Yichen_
 </details>

[\[back to top\]](#contents)

### 2018 Others

<details>
<summary>Show More</summary>

#### ***Human Pose Estimation and Body Reconstruction***

</details>

[\[back to top\]](#contents)

### 2017 CVPR
##### • Global Hypothesis Generation for 6D Object Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Michel_Global_Hypothesis_Generation_CVPR_2017_paper.pdf)
 _Michel, Frank and Kirillov, Alexander and Brachmann, Eric and Krull, Alexander and Gumhold, Stefan and Savchynskyy, Bogdan and Rother, Carsten_
##### • PoseAgent: Budget-Constrained 6D Object Pose Estimation via Reinforcement Learning. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Krull_PoseAgent_Budget-Constrained_6D_CVPR_2017_paper.pdf)
 _Krull, Alexander and Brachmann, Eric and Nowozin, Sebastian and Michel, Frank and Shotton, Jamie and Rother, Carsten_
##### • A Point Set Generation Network for 3D Object Reconstruction From a Single Image. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Fan_A_Point_Set_CVPR_2017_paper.pdf)
 _Fan, Haoqiang and Su, Hao and Guibas, Leonidas J._
##### • DUST: Dual Union of Spatio-Temporal Subspaces for Monocular Multiple Object 3D Reconstruction. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Agudo_DUST_Dual_Union_CVPR_2017_paper.pdf)
 _Agudo, Antonio and Moreno-Noguer, Francesc_
<details>
<summary>Show More</summary>

#### ***Human Pose Estimation and Body Reconstruction***

 ##### • Multi-Context Attention for Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Chu_Multi-Context_Attention_for_CVPR_2017_paper.pdf)
 _Chu, Xiao and Yang, Wei and Ouyang, Wanli and Ma, Cheng and Yuille, Alan L. and Wang, Xiaogang_
##### • 3D Human Pose Estimation From a Single Image via Distance Matrix Regression. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Moreno-Noguer_3D_Human_Pose_CVPR_2017_paper.pdf)
 _Moreno-Noguer, Francesc_
##### • LCR-Net: Localization-Classification-Regression for Human Pose. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Rogez_LCR-Net_Localization-Classification-Regression_for_CVPR_2017_paper.pdf)
 _Rogez, Gregory and Weinzaepfel, Philippe and Schmid, Cordelia_
##### • Seeing Invisible Poses: Estimating 3D Body Pose From Egocentric Video. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Jiang_Seeing_Invisible_Poses_CVPR_2017_paper.pdf)
 _Jiang, Hao and Grauman, Kristen_
##### • Harvesting Multiple Views for Marker-Less 3D Human Pose Annotations. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Pavlakos_Harvesting_Multiple_Views_CVPR_2017_paper.pdf)
 _Pavlakos, Georgios and Zhou, Xiaowei and Derpanis, Konstantinos G. and Daniilidis, Kostas_
##### • Coarse-To-Fine Volumetric Prediction for Single-Image 3D Human Pose. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Pavlakos_Coarse-To-Fine_Volumetric_Prediction_CVPR_2017_paper.pdf)
 _Pavlakos, Georgios and Zhou, Xiaowei and Derpanis, Konstantinos G. and Daniilidis, Kostas_
##### • 3D Human Pose Estimation = 2D Pose Estimation + Matching. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Chen_3D_Human_Pose_CVPR_2017_paper.pdf)
 _Chen, Ching-Hang and Ramanan, Deva_
 </details>

 [\[back to top\]](#contents)

### 2017 ICCV

##### • Real-Time Monocular Pose Estimation of 3D Objects Using Temporally Consistent Local Color Histograms. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Tjaden_Real-Time_Monocular_Pose_ICCV_2017_paper.pdf)
 _Tjaden, Henning and Schwanecke, Ulrich and Schomer, Elmar_
##### • Pose Guided RGBD Feature Learning for 3D Object Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Balntas_Pose_Guided_RGBD_ICCV_2017_paper.pdf)
 _Balntas, Vassileios and Doumanoglou, Andreas and Sahin, Caner and Sock, Juil and Kouskouridas, Rigas and Kim, Tae-Kyun_
##### • Rotational Subgroup Voting and Pose Clustering for Robust 3D Object Recognition. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Buch_Rotational_Subgroup_Voting_ICCV_2017_paper.pdf)
 _Glent Buch, Anders and Kiforenko, Lilita and Kraft, Dirk_
##### • Robust Hand Pose Estimation During the Interaction With an Unknown Object. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Choi_Robust_Hand_Pose_ICCV_2017_paper.pdf)
 _Choi, Chiho and Ho Yoon, Sang and Chen, Chin-Ning and Ramani, Karthik_
##### • BB8: A Scalable, Accurate, Robust to Partial Occlusion Method for Predicting the 3D Poses of Challenging Objects without Using Depth. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Rad_BB8_A_Scalable_ICCV_2017_paper.pdf)
 _Mahdi Rad and Vincent Lepetit_
 ##### • SSD-6D: Making RGB-Based 3D Detection and 6D Pose Estimation Great Again. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Kehl_SSD-6D_Making_RGB-Based_ICCV_2017_paper.pdf)[\[Code\]](https://wadimkehl.github.io/)
 _Wadim Kehl, Fabian Manhardt, Federico Tombari, Slobodan Ilic, Nassir Navab_

<details>
<summary>Show More</summary>

#### ***Human Pose Estimation and Body Reconstruction***

 ##### • Towards 3D Human Pose Estimation in the Wild: A Weakly-Supervised Approach. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Zhou_Towards_3D_Human_ICCV_2017_paper.pdf)
 _Zhou, Xingyi and Huang, Qixing and Sun, Xiao and Xue, Xiangyang and Wei, Yichen_
##### • Adversarial PoseNet: A Structure-Aware Convolutional Network for Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Chen_Adversarial_PoseNet_A_ICCV_2017_paper.pdf)
 _Chen, Yu and Shen, Chunhua and Wei, Xiu-Shen and Liu, Lingqiao and Yang, Jian_
##### • Learning Feature Pyramids for Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Yang_Learning_Feature_Pyramids_ICCV_2017_paper.pdf)
 _Yang, Wei and Li, Shuang and Ouyang, Wanli and Li, Hongsheng and Wang, Xiaogang_
##### • Compositional Human Pose Regression. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Sun_Compositional_Human_Pose_ICCV_2017_paper.pdf)
 _Sun, Xiao and Shang, Jiaxiang and Liang, Shuang and Wei, Yichen_
##### • A Simple yet Effective Baseline for 3D Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Martinez_A_Simple_yet_ICCV_2017_paper.pdf)
 _Martinez, Julieta and Hossain, Rayat and Romero, Javier and Little, James J._
##### • Transferring Objects: Joint Inference of Container and Human Pose. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Wang_Transferring_Objects_Joint_ICCV_2017_paper.pdf)
 _Wang, Hanqing and Liang, Wei and Yu, Lap-Fai_
##### • Monocular 3D Human Pose Estimation by Predicting Depth on Joints. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Nie_Monocular_3D_Human_ICCV_2017_paper.pdf)
 _Xiaohan Nie, Bruce and Wei, Ping and Zhu, Song-Chun_
##### • Deep Globally Constrained MRFs for Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Marras_Deep_Globally_Constrained_ICCV_2017_paper.pdf)
 _Marras, Ioannis and Palasek, Petar and Patras, Ioannis_
##### • Binarized Convolutional Landmark Localizers for Human Pose Estimation and Face Alignment With Limited Resources. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Bulat_Binarized_Convolutional_Landmark_ICCV_2017_paper.pdf)
 _Bulat, Adrian and Tzimiropoulos, Georgios_
##### • Learning to Fuse 2D and 3D Image Cues for Monocular Body Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Tekin_Learning_to_Fuse_ICCV_2017_paper.pdf)
 _Tekin, Bugra and Marquez-Neila, Pablo and Salzmann, Mathieu and Fua, Pascal_
##### • Active Learning for Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Liu_Active_Learning_for_ICCV_2017_paper.pdf)
 _Liu, Buyu and Ferrari, Vittorio_
##### • Human Pose Estimation Using Global and Local Normalization. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Sun_Human_Pose_Estimation_ICCV_2017_paper.pdf)
 _Sun, Ke and Lan, Cuiling and Xing, Junliang and Zeng, Wenjun and Liu, Dong and Wang, Jingdong_
</details>

[\[back to top\]](#contents)

### 2017 Others
##### • [2017 RSS] PoseCNN: A CNN for 6D Object Pose Estimation in Cluttered Scenes. [\[PDF\]](https://arxiv.org/pdf/1711.00199.pdf) [\[Code\]](https://github.com/yuxng/PoseCNN)[\[Project\]](https://rse-lab.cs.washington.edu/projects/posecnn/)
 _Yu Xiang, Tanner Schmidt, Venkatraman Narayanan and Dieter Fox_

[\[back to top\]](#contents)

### 2016 CVPR

##### • Uncertainty-Driven 6D Pose Estimation of Objects and Scenes From a Single RGB Image. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2016/papers/Brachmann_Uncertainty-Driven_6D_Pose_CVPR_2016_paper.pdf)
 _Brachmann, Eric and Michel, Frank and Krull, Alexander and Yang, Michael Ying and Gumhold, Stefan and Rother, carsten_
##### • Recovering 6D Object Pose and Predicting Next-Best-View in the Crowd. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2016/papers/Doumanoglou_Recovering_6D_Object_CVPR_2016_paper.pdf)
 _Doumanoglou, Andreas and Kouskouridas, Rigas and Malassiotis, Sotiris and Kim, Tae-Kyun_
##### • 3D Reconstruction of Transparent Objects With Position-Normal Consistency. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2016/papers/Qian_3D_Reconstruction_of_CVPR_2016_paper.pdf)
 _Qian, Yiming and Gong, Minglun and Yang, Yee Hong_
<details>
<summary>Show More</summary>

#### ***Human Pose Estimation and Body Reconstruction***

 ##### • Personalizing Human Video Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2016/papers/Charles_Personalizing_Human_Video_CVPR_2016_paper.pdf)
 _Charles, James and Pfister, Tomas and Magee, Derek and Hogg, David and Zisserman, Andrew_
##### • End-To-End Learning of Deformable Mixture of Parts and Deep Convolutional Neural Networks for Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2016/papers/Yang_End-To-End_Learning_of_CVPR_2016_paper.pdf)
 _Yang, Wei and Ouyang, Wanli and Li, Hongsheng and Wang, Xiaogang_
##### • Human Pose Estimation With Iterative Error Feedback. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2016/papers/Carreira_Human_Pose_Estimation_CVPR_2016_paper.pdf)
 _Carreira, Joao and Agrawal, Pulkit and Fragkiadaki, Katerina and Malik, Jitendra_
##### • Sparseness Meets Deepness: 3D Human Pose Estimation From Monocular Video. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2016/papers/Zhou_Sparseness_Meets_Deepness_CVPR_2016_paper.pdf)
 _Zhou, Xiaowei and Zhu, Menglong and Leonardos, Spyridon and Derpanis, Konstantinos G. and Daniilidis, Kostas_
</details>


[\[back to top\]](#contents)

### 2016 Others

<details>
<summary>Show More</summary>

#### ***Human Pose Estimation and Body Reconstruction***

</details>


[\[back to top\]](#contents)

### 2015 CVPR

##### • Pose Induction for Novel Object Categories. [\[PDF\]](https://openaccess.thecvf.com/content_iccv_2015/papers/Tulsiani_Pose_Induction_for_ICCV_2015_paper.pdf)
 _Tulsiani, Shubham and Carreira, Joao and Malik, Jitendra_
##### • Real-Time Pose Estimation Piggybacked on Object Detection. [\[PDF\]](https://openaccess.thecvf.com/content_iccv_2015/papers/Juranek_Real-Time_Pose_Estimation_ICCV_2015_paper.pdf)
 _Juranek, Roman and Herout, Adam and Dubska, Marketa and Zemcik, Pavel_
##### • 3D Object Reconstruction From Hand-Object Interactions. [\[PDF\]](https://openaccess.thecvf.com/content_iccv_2015/papers/Tzionas_3D_Object_Reconstruction_ICCV_2015_paper.pdf)
 _Tzionas, Dimitrios and Gall, Juergen_
##### • Exploiting Object Similarity in 3D Reconstruction. [\[PDF\]](https://openaccess.thecvf.com/content_iccv_2015/papers/Zhou_Exploiting_Object_Similarity_ICCV_2015_paper.pdf)
 _Zhou, Chen and Guney, Fatma and Wang, Yizhou and Geiger, Andreas_
##### • Interactive Visual Hull Refinement for Specular and Transparent Object Surface Reconstruction. [\[PDF\]](https://openaccess.thecvf.com/content_iccv_2015/papers/Zuo_Interactive_Visual_Hull_ICCV_2015_paper.pdf)
 _Zuo, Xinxin and Du, Chao and Wang, Sen and Zheng, Jiangbin and Yang, Ruigang_
##### • A Dynamic Programming Approach for Fast and Robust Object Pose Recognition From Range Images. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2015/papers/Zach_A_Dynamic_Programming_2015_CVPR_paper.pdf)
 _Zach, Christopher and Penate-Sanchez, Adrian and Pham, Minh-Tri_
##### • Learning Descriptors for Object Recognition and 3D Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2015/papers/Wohlhart_Learning_Descriptors_for_2015_CVPR_paper.pdf)
 _Wohlhart, Paul and Lepetit, Vincent_
##### • Category-Specific Object Reconstruction From a Single Image. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2015/papers/Kar_Category-Specific_Object_Reconstruction_2015_CVPR_paper.pdf)
 _Kar, Abhishek and Tulsiani, Shubham and Carreira, Joao and Malik, Jitendra_
##### • Virtual View Networks for Object Reconstruction. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2015/papers/Carreira_Virtual_View_Networks_2015_CVPR_paper.pdf)
 _Carreira, Joao and Kar, Abhishek and Tulsiani, Shubham and Malik, Jitendra_
##### • A Fixed Viewpoint Approach for Dense Reconstruction of Transparent Objects. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2015/papers/Han_A_Fixed_Viewpoint_2015_CVPR_paper.pdf)
 _Han, Kai and Wong, Kwan-Yee K. and Liu, Miaomiao_
<details>
<summary>Show More</summary>

#### ***Human Pose Estimation and Body Reconstruction***

##### • Combining Local Appearance and Holistic View: Dual-Source Deep Neural Networks for Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2015/papers/Fan_Combining_Local_Appearance_2015_CVPR_paper.pdf)
 _Fan, Xiaochuan and Zheng, Kang and Lin, Yuewei and Wang, Song_
##### • Pose-Conditioned Joint Angle Limits for 3D Human Pose Reconstruction. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2015/papers/Akhter_Pose-Conditioned_Joint_Angle_2015_CVPR_paper.pdf)
 _Akhter, Ijaz and Black, Michael J._
##### • Random Tree Walk Toward Instantaneous 3D Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2015/papers/Jung_Random_Tree_Walk_2015_CVPR_paper.pdf)
 _Yub Jung, Ho and Lee, Soochahn and Seok Heo, Yong and Dong Yun, Il_
##### • The Stitched Puppet: A Graphical Model of 3D Human Shape and Pose. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2015/papers/Zuffi_The_Stitched_Puppet_2015_CVPR_paper.pdf)
 _Zuffi, Silvia and Black, Michael J._
##### • Pose-Conditioned Joint Angle Limits for 3D Human Pose Reconstruction. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2015/papers/Akhter_Pose-Conditioned_Joint_Angle_2015_CVPR_paper.pdf)
 _Akhter, Ijaz and Black, Michael J._
</details>

[\[back to top\]](#contents)

### 2015 ICCV

##### • BodyPrint: Pose Invariant 3D Shape Matching of Human Bodies. [\[PDF\]](https://openaccess.thecvf.com/content_iccv_2015/papers/Wang_BodyPrint_Pose_Invariant_ICCV_2015_paper.pdf)
 _Wang, Jiangping and Ma, Kai and Singh, Vivek Kumar and Huang, Thomas and Chen, Terrence_
##### • Flowing ConvNets for Human Pose Estimation in Videos. [\[PDF\]](https://openaccess.thecvf.com/content_iccv_2015/papers/Pfister_Flowing_ConvNets_for_ICCV_2015_paper.pdf)
 _Pfister, Tomas and Charles, James and Zisserman, Andrew_
##### • Beyond Tree Structure Models: A New Occlusion Aware Graphical Model for Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_iccv_2015/papers/Fu_Beyond_Tree_Structure_ICCV_2015_paper.pdf)
 _Fu, Lianrui and Zhang, Junge and Huang, Kaiqi_
<details>
<summary>Show More</summary>

#### ***Human Pose Estimation and Body Reconstruction***

##### content_iccv_2015/papers/Zhang_Human_Pose_Estimation_ICCV_2015_paper.pdf)
 _Zhang, Dong and Shah, Mubarak_
##### • Attributed Grammars for Joint Estimation of Human Attributes, Part and Pose. [\[PDF\]](https://openaccess.thecvf.com/content_iccv_2015/papers/Park_Attributed_Grammars_for_ICCV_2015_paper.pdf)
 _Park, Seyoung and Zhu, Song-Chun_
##### • Maximum-Margin Structured Learning With Deep Networks for 3D Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_iccv_2015/papers/Li_Maximum-Margin_Structured_Learning_ICCV_2015_paper.pdf)
 _Li, Sijin and Zhang, Weichen and Chan, Antoni B._
##### • Opening the Black Box: Hierarchical Sampling Optimization for Estimating Human Hand Pose. [\[PDF\]](https://openaccess.thecvf.com/content_iccv_2015/papers/Tang_Opening_the_Black_ICCV_2015_paper.pdf)
 _Tang, Danhang and Taylor, Jonathan and Kohli, Pushmeet and Keskin, Cem and Kim, Tae-Kyun and Shotton, Jamie_
 </details>

[\[back to top\]](#contents)

### 2015 Others
<details>
<summary>Show More</summary>

#### ***Human Pose Estimation and Body Reconstruction***

</details>


[\[back to top\]](#contents)

### 2014 CVPR

##### • Real-time Simultaneous Pose and Shape Estimation for Articulated Objects Using a Single Depth Camera. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2014/papers/Ye_Real-time_Simultaneous_Pose_2014_CVPR_paper.pdf)
 _Ye, Mao and Yang, Ruigang_
##### • Real-time Model-based Articulated Object Pose Detection and Tracking with Variable Rigidity Constraints. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2014/papers/Pauwels_Real-time_Model-based_Articulated_2014_CVPR_paper.pdf)
 _Pauwels, Karl and Rubio, Leonardo and Ros, Eduardo_
##### • Frequency-Based 3D Reconstruction of Transparent and Specular Objects. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2014/papers/Liu_Frequency-Based_3D_Reconstruction_2014_CVPR_paper.pdf)
 _Liu, Ding and Chen, Xida and Yang, Yee-Hong_
##### • Separation of Line Drawings Based on Split Faces for 3D Object Reconstruction. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2014/papers/Zou_Separation_of_Line_2014_CVPR_paper.pdf)
 _Zou, Changqing and Yang, Heng and Liu, Jianzhuang_
##### • Analysis by Synthesis: 3D Object Recognition by Object Reconstruction. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2014/papers/Hejrati_Analysis_by_Synthesis_2014_CVPR_paper.pdf)
 _Hejrati, Mohsen and Ramanan, Deva_
##### • Analysis by Synthesis: 3D Object Recognition by Object Reconstruction. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2014/papers/Hejrati_Analysis_by_Synthesis_2014_CVPR_paper.pdf)
 _Hejrati, Mohsen and Ramanan, Deva_
##### • Transparent Object Reconstruction via Coded Transport of Intensity. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2014/papers/Ma_Transparent_Object_Reconstruction_2014_CVPR_paper.pdf)
 _Ma, Chenguang and Lin, Xing and Suo, Jinli and Dai, Qionghai and Wetzstein, Gordon_
<details>
<summary>Show More</summary>

#### ***Human Pose Estimation and Body Reconstruction***


 ##### • Towards Unified Human Parsing and Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2014/papers/Dong_Towards_Unified_Human_2014_CVPR_paper.pdf)
 _Dong, Jian and Chen, Qiang and Shen, Xiaohui and Yang, Jianchao and Yan, Shuicheng_
##### • DeepPose: Human Pose Estimation via Deep Neural Networks. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2014/papers/Toshev_DeepPose_Human_Pose_2014_CVPR_paper.pdf)
 _Toshev, Alexander and Szegedy, Christian_
##### • Iterated Second-Order Label Sensitive Pooling for 3D Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2014/papers/Ionescu_Iterated_Second-Order_Label_2014_CVPR_paper.pdf)
 _Ionescu, Catalin and Carreira, Joao and Sminchisescu, Cristian_
##### • 3D Pictorial Structures for Multiple Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2014/papers/Belagiannis_3D_Pictorial_Structures_2014_CVPR_paper.pdf)
 _Belagiannis, Vasileios and Amin, Sikandar and Andriluka, Mykhaylo and Schiele, Bernt and Navab, Nassir and Ilic, Slobodan_
##### • Multi-source Deep Learning for Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2014/papers/Ouyang_Multi-source_Deep_Learning_2014_CVPR_paper.pdf)
 _Ouyang, Wanli and Chu, Xiao and Wang, Xiaogang_
##### • Posebits for Monocular Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2014/papers/Pons-Moll_Posebits_for_Monocular_2014_CVPR_paper.pdf)
 _Pons-Moll, Gerard and Fleet, David J. and Rosenhahn, Bodo_
##### • Mixing Body-Part Sequences for Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2014/papers/Cherian_Mixing_Body-Part_Sequences_2014_CVPR_paper.pdf)
 _Cherian, Anoop and Mairal, Julien and Alahari, Karteek and Schmid, Cordelia_
##### • Human Shape and Pose Tracking Using Keyframes. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2014/papers/Huang_Human_Shape_and_2014_CVPR_paper.pdf)
 _Huang, Chun-Hao and Boyer, Edmond and Navab, Nassir and Ilic, Slobodan_
##### • 2D Human Pose Estimation: New Benchmark and State of the Art Analysis. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2014/papers/Andriluka_2D_Human_Pose_2014_CVPR_paper.pdf)
 _Andriluka, Mykhaylo and Pishchulin, Leonid and Gehler, Peter and Schiele, Bernt_
 </details>

[\[back to top\]](#contents)

### 2014 Others & Before

##### • [2013 ICCV] Alternating Regression Forests for Object Detection and Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_iccv_2013/papers/Schulter_Alternating_Regression_Forests_2013_ICCV_paper.pdf)
 _Schulter, Samuel and Leistner, Christian and Wohlhart, Paul and Roth, Peter M. and Bischof, Horst_
##### • [2013 ICCV] Complex 3D General Object Reconstruction from Line Drawings. [\[PDF\]](https://openaccess.thecvf.com/content_iccv_2013/papers/Yang_Complex_3D_General_2013_ICCV_paper.pdf)
 _Yang, Linjie and Liu, Jianzhuang and Tang, Xiaoou_
##### • [2013 ICCV] STAR3D: Simultaneous Tracking and Reconstruction of 3D Objects Using RGB-D Data. [\[PDF\]](https://openaccess.thecvf.com/content_iccv_2013/papers/Ren_STAR3D_Simultaneous_Tracking_2013_ICCV_paper.pdf)
 _Ren, Carl Yuheng and Prisacariu, Victor and Murray, David and Reid, Ian_
##### • [2013 ICCV] Multi-view Normal Field Integration for 3D Reconstruction of Mirroring Objects. [\[PDF\]](https://openaccess.thecvf.com/content_iccv_2013/papers/Weinmann_Multi-view_Normal_Field_2013_ICCV_paper.pdf)
 _Weinmann, Michael and Osep, Aljosa and Ruiters, Roland and Klein, Reinhard_
##### • [2013 ICCV] Point-Based 3D Reconstruction of Thin Objects. [\[PDF\]](https://openaccess.thecvf.com/content_iccv_2013/papers/Ummenhofer_Point-Based_3D_Reconstruction_2013_ICCV_paper.pdf)
 _Ummenhofer, Benjamin and Brox, Thomas_
##### • [2013 CVPR] Class Generative Models Based on Feature Regression for Pose Estimation of Object Categories. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2013/papers/Fenzi_Class_Generative_Models_2013_CVPR_paper.pdf)
 _Fenzi, Michele and Leal-Taixe, Laura and Rosenhahn, Bodo and Ostermann, Jorn_
##### • [2013 CVPR] Real-Time Model-Based Rigid Object Pose Estimation and Tracking Combining Dense and Sparse Visual Cues. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2013/papers/Pauwels_Real-Time_Model-Based_Rigid_2013_CVPR_paper.pdf)
 _Pauwels, Karl and Rubio, Leonardo and Diaz, Javier and Ros, Eduardo_
##### • [2013 CVPR] Dense Object Reconstruction with Semantic Priors. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2013/papers/Bao_Dense_Object_Reconstruction_2013_CVPR_paper.pdf)
 _Yingze Bao, Sid and Chandraker, Manmohan and Lin, Yuanqing and Savarese, Silvio_
##### • [2013 CVPR] Shape from Silhouette Probability Maps: Reconstruction of Thin Objects in the Presence of Silhouette Extraction and Calibration Error. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2013/papers/Tabb_Shape_from_Silhouette_2013_CVPR_paper.pdf)
 _Tabb, Amy_
##### • [2013 CVPR] Dense Reconstruction Using 3D Object Shape Priors. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2013/papers/Dame_Dense_Reconstruction_Using_2013_CVPR_paper.pdf)
 _Dame, Amaury and Prisacariu, Victor A. and Ren, Carl Y. and Reid, Ian_
<details>
<summary>Show More</summary>

#### ***Human Pose Estimation and Body Reconstruction***


 ##### • [2013 ICCV] A Non-parametric Bayesian Network Prior of Human Pose. [\[PDF\]](https://openaccess.thecvf.com/content_iccv_2013/papers/Lehrmann_A_Non-parametric_Bayesian_2013_ICCV_paper.pdf)
 _Lehrmann, Andreas M. and Gehler, Peter V. and Nowozin, Sebastian_
##### • [2013 ICCV] Strong Appearance and Expressive Spatial Models for Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_iccv_2013/papers/Pishchulin_Strong_Appearance_and_2013_ICCV_paper.pdf)
 _Pishchulin, Leonid and Andriluka, Mykhaylo and Gehler, Peter and Schiele, Bernt_
##### • [2013 ICCV] Joint Segmentation and Pose Tracking of Human in Natural Videos. [\[PDF\]](https://openaccess.thecvf.com/content_iccv_2013/papers/Lim_Joint_Segmentation_and_2013_ICCV_paper.pdf)
 _Lim, Taegyu and Hong, Seunghoon and Han, Bohyung and Han, Joon Hee_
##### • [2013 ICCV] Monocular Image 3D Human Pose Estimation under Self-Occlusion. [\[PDF\]](https://openaccess.thecvf.com/content_iccv_2013/papers/Radwan_Monocular_Image_3D_2013_ICCV_paper.pdf)
 _Radwan, Ibrahim and Dhall, Abhinav and Goecke, Roland_
##### • [2013 ICCV] Estimating Human Pose with Flowing Puppets. [\[PDF\]](https://openaccess.thecvf.com/content_iccv_2013/papers/Zuffi_Estimating_Human_Pose_2013_ICCV_paper.pdf)
 _Zuffi, Silvia and Romero, Javier and Schmid, Cordelia and Black, Michael J._
##### • [2013 CVPR] Human Pose Estimation Using Body Parts Dependent Joint Regressors. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2013/papers/Dantone_Human_Pose_Estimation_2013_CVPR_paper.pdf)
 _Dantone, Matthias and Gall, Juergen and Leistner, Christian and Van Gool, Luc_
##### • [2013 CVPR] Computationally Efficient Regression on a Dependency Graph for Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2013/papers/Hara_Computationally_Efficient_Regression_2013_CVPR_paper.pdf)
 _Hara, Kota and Chellappa, Rama_
##### • [2013 CVPR] Integrating Grammar and Segmentation for Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2013/papers/Rothrock_Integrating_Grammar_and_2013_CVPR_paper.pdf)
 _Rothrock, Brandon and Park, Seyoung and Zhu, Song-Chun_
##### • [2013 CVPR] MODEC: Multimodal Decomposable Models for Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2013/papers/Sapp_MODEC_Multimodal_Decomposable_2013_CVPR_paper.pdf)
 _Sapp, Ben and Taskar, Ben_
##### • [2013 CVPR] Unconstrained Monocular 3D Human Pose Estimation by Action Detection and Cross-Modality Regression Forest. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2013/papers/Yu_Unconstrained_Monocular_3D_2013_CVPR_paper.pdf)
 _Yu, Tsz-Ho and Kim, Tae-Kyun and Cipolla, Roberto_
##### • [2013 CVPR] Human Pose Estimation Using a Joint Pixel-wise and Part-wise Formulation. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2013/papers/Ladicky_Human_Pose_Estimation_2013_CVPR_paper.pdf)
 _Ladicky, Lubor and Torr, Philip H.S. and Zisserman, Andrew_
##### • [2013 CVPR] Tracking Human Pose by Tracking Symmetric Parts. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2013/papers/Ramakrishna_Tracking_Human_Pose_2013_CVPR_paper.pdf)
 _Ramakrishna, Varun and Kanade, Takeo and Sheikh, Yaser_
##### • [2013 CVPR] Beyond Physical Connections: Tree Models in Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2013/papers/Wang_Beyond_Physical_Connections_2013_CVPR_paper.pdf)
 _Wang, Fang and Li, Yi_
 </details>

[\[back to top\]](#contents)

## Thesis
##### • \[2020\] Learning to Reconstruct and Segment 3D Objects. [\[PDF\]](https://arxiv.org/pdf/2010.09582.pdf)
*[Bo Yang](https://yang7879.github.io/), Ph.D Thesis, University of Oxford*
##### • \[2019\] Recovering 6D object pose at the level of instances and categories. [\[PDF\]](https://spiral.imperial.ac.uk/bitstream/10044/1/67953/1/Sahin-C-2019-PhD-Thesis.pdf)
*[Sahin Caner](https://scholar.google.co.uk/citations?hl=zh-CN&user=uMnRljAAAAAJ), Ph.D Thesis, Imperial College London*
##### • \[2018\] Enforcing View Consistency With Latent Configurations for 3D Vision Tasks. [\[PDF\]](https://apps.cs.utexas.edu/apps/sites/default/files/tech_reports/thesis-view-consistency-akarpur2018.pdf)[\[Code\]](https://github.com/arjunkarpur/view-consistency-shape-gen)
*[Arjun Karpur, Qixing Huang](https://www.cs.utexas.edu/~huangqx/index.html), Undergraduate Honors Thesis, The University of Texas at Austin*
##### • \[2016\] 3D Object Representations for Recognition. [\[PDF\]](https://yuxng.github.io/Xiang_phd_thesis.pdf)
*[Yu Xiang](https://yuxng.github.io/), Ph.D Thesis, University of Michigan*
##### • \[2014\] Automatic reconstruction of digital buildings. [\[Slide\]](https://aboulch.github.io/files/thesis/slides_thesis_boulch.pdf)
*[Alexandre Boulch](https://www.boulch.eu/), Ph.D Thesis, École des Ponts ParisTech*


[\[back to top\]](#contents)

## Datasets


### Benchmark-6D-Object-Pose-Estimation
#### You can download all the BOP datasets [here](https://bop.felk.cvut.cz/datasets/) and use the [toolkit](https://github.com/thodan/bop_toolkit) provided by the organizers.
#### Another excellent summary about dataset is in [here](https://github.com/YoungXIAO13/ObjectPoseEstimationSummary)


[\[back to top\]](#contents)

## Workshops

### *Workshops on 3D Vision and Robotics:*
#### • [3DV&R 2021](https://sites.google.com/view/cvpr2021-3d-vision-robotics), In conjunction with CVPR 2021
- Workshop Papers
    - [2021 CVPRW] Synergies Between Affordance and Geometry: 6-DoF Grasp Detection via Implicit Representations, _Zhenyu Jiang, Yifeng Zhu, Maxwell Svetlik, Kuan Fang, Yuke Zhu_ [\[Paper\]](https://www.google.com/url?q=https%3A%2F%2Fcvpr20213dvr.github.io%2FJiang_3DVR21.pdf&sa=D&sntz=1&usg=AFQjCNFtJ6f4oqeom33UJjbJvq0yTQsT3w)
    - [2021 CVPRW]  Data-driven 6D Pose Tracking by Calibrating Image Residuals in Synthetic Domains, _Bowen Wen, Chaitanya Mitash, Kostas Bekris_ [\[Paper\]](https://www.google.com/url?q=https%3A%2F%2Fcvpr20213dvr.github.io%2FWen_3DVR21.pdf&sa=D&sntz=1&usg=AFQjCNGlz3rkjS7m1sb7o0IWjUh6fpLDTw) [\[Supp\]](https://www.google.com/url?q=https%3A%2F%2Fcvpr20213dvr.github.io%2FWen_3DVR21_supp.mp4&sa=D&sntz=1&usg=AFQjCNEEtDp0YNtxyUnbxUD97WWmU_e_pQ)


### *Workshops on Recovering 6D Object Pose:*
#### • [R6D 2020](http://cmp.felk.cvut.cz/sixd/workshop_2020/), In conjunction with ECCV 2020
- Talk Slides
  - [2020 CVPRW] 6th International Workshop on Recovering 6D Object Pose (R6D), _Tomáš Hodaň, Martin Sundermeyer, Rigas Kouskouridas, Tae-Kyun Kim, Jiří Matas, Carsten Rother, Vincent Lepetit, Ales Leonardis, Krzysztof Walas, Carsten Steger , Eric Brachmann , Bertram Drost, Juil Sock_ [\[Slide\]](http://cmp.felk.cvut.cz/sixd/workshop_2020/slides/r6d20_hodan_opening.pdf)

  - [Talk 1]  _[Stephen James](https://stepjam.github.io/) (Imperial College London)_, From Explicit to Implicit Pose Estimation, [\[Slide\]](http://cmp.felk.cvut.cz/sixd/workshop_2020/slides/r6d20_james.pptx)

  - [Talk 2]  _[Shuran Song](https://www.cs.columbia.edu/~shurans/) (Columbia University)_, Category-Level Object Pose Estimation,[\[Vedio\]](https://www.youtube.com/watch?v=5OB2aeMU8sU)

  - [Talk 3]  _[Leonidas Guibas](https://geometry.stanford.edu/member/guibas/) (Stanford University)_, Object-Centric Situational 3D Understanding,  [\[Slide\]](http://cmp.felk.cvut.cz/sixd/workshop_2020/slides/r6d20_guibas.pdf)
  - [Talk 4]  _[Dieter Fox ](https://homes.cs.washington.edu/~fox/) (University of Washington, Nvidia)_, 6D Object Pose Estimation for Manipulation.
- Workshop Papers
    - [2020 CVPRW] StructureFromGAN: Single Image 3D Model Reconstruction and Photorealistic Texturing, _Vladimir V Kniaz, Vladimir Knyaz, Vladimir Mizginov, Artyom Bordodymov, Mark Kozyrev, Peter Moshkantsev, Nikita Fomin_ [\[Springer\]](https://www.springerprofessional.de/en/structurefromgan-single-image-3d-model-reconstruction-and-photor/18718208)
    - [2020 CVPRW] 6 DoF Pose Estimation of Textureless Objects From Multiple RGB Frames, _Roman Kaskman, Ivan Shugurov, Sergey Zakharov, Slobodan Ilic_ [\[PDF\]](http://campar.in.tum.de/pub/kaskman2020eccvw/kaskman2020eccvw.pdf)
    - [2020 CVPRW] Semi-supervised Viewpoint Estimation with Pose-aware Conditional Generation, _Octave Mariotti, Hakan Bilen_ [\[PDF\]](http://homepages.inf.ed.ac.uk/hbilen/assets/pdf/Mariotti20.pdf)
    - [2020 CVPRW] Physical Plausibility of 6D Pose Estimates in Scenes of Static Rigid Objects, _Dominik Bauer, Timothy Patten, Markus Vincze_
    - [2020 CVPRW] DronePose: Photorealistic UAV-Assistant Dataset Synthesis for 3D Pose Estimation via a Smooth Silhouette Loss, _Georgios Albanis, Nikolaos Zioulis, Anastasios Dimou, Dimitrios Zarpalas, Petros Daras_ [\[PDF\]](https://arxiv.org/pdf/2008.08823.pdf)
    - [2020 CVPRW] How to track your dragon: A Multi-Attentional Framework for real-time RGB-D 6DOF Object Pose Tracking, _Isidoros Marougkas, Petros Koutras, Nikolaos Kardaris, George Retsinas, Georgia Chalvatzaki, Petros Maragos_ [\[PDF\]](http://cvsp.cs.ntua.gr/publications/confr/2020_MarougkasEtAl_How-to-Track-your-Dragon_ECCVW-R6D.pdf)
    - [2020 CVPRW] A Hybrid Approach for 6DoF Pose Estimation, _Rebecca König, Bertram Drost_ [\[PDF\]](https://www.researchgate.net/publication/345756794_A_Hybrid_Approach_for_6DoF_Pose_Estimation)
    - [2020 CVPRW] Leaping from 2D Detection to Effcient 6DoF Object Pose Estimation, _Jinhui Liu, Zhikang Zou, Xiaoqing Ye, Xiao Tan, Errui Ding, Feng Xu, Xin Yu_




### • [R6D 2019](http://cmp.felk.cvut.cz/sixd/workshop_2019/), In conjunction with ICCV 2019
- Talk Slides
  - [Opening] 5th International Workshop on Recovering 6D Object Pose (R6D), _Tomáš Hodaň, Rigas Kouskouridas, Tae-Kyun Kim, Jiří Matas,
Carsten Rother, Vincent Lepetit, Ales Leonardis, Krzysztof Walas,
Carsten Steger , Eric Brachmann , Bertram Drost, Juil Sock_ [\[Slide\]](http://cmp.felk.cvut.cz/sixd/workshop_2019/slides/r6d19_hodan_opening.pdf)

  - [Talk 2]  _[Eric Brachmann](https://hci.iwr.uni-heidelberg.de/vislearn/people/eric-brachmann/) (Heidelberg University)_, Robust Pose Optimization Made Differentiable, [\[Slide\]](http://cmp.felk.cvut.cz/sixd/workshop_2019/slides/r6d19_brachmann_differentiable_pose_estimation.pdf)

  - [Talk 3]  _[Vincent Lepetit](https://www.labri.fr/perso/vlepetit/) (Uni. de Bordeaux)_, 3D Pose Estimation and 3D Model Retrieval for Objects in the Wild,[\[Slide\]](http://cmp.felk.cvut.cz/sixd/workshop_2019/slides/r6d19_lepetit_3d_pose_estimation_and_model_retrieval_in_the_wild.pdf)

  - [Talk 4]  _[Matthias Nießner](https://niessnerlab.org/members/matthias_niessner/profile.html) (TU Munich)_, 9DOF Scan2CAD Alignment in 3D Scans,  [\[Slide\]](http://cmp.felk.cvut.cz/sixd/workshop_2019/slides/r6d19_niessner_from_rgb-d_scans_to_3d_cad_models.pdf)

- Workshop Papers
    - [2019 ICCVW] CullNet: Calibrated and Pose Aware Confidence Scores for Object Pose Estimation, _Kartik Gupta, Lars Petersson, Richard Hartley_ [\[PDF\]](http://openaccess.thecvf.com/content_ICCVW_2019/papers/R6D/Gupta_CullNet_Calibrated_and_Pose_Aware_Confidence_Scores_for_Object_Pose_ICCVW_2019_paper.pdf)
    - [2019 ICCVW] CorNet: Generic 3D Corners for 6D Pose Estimation of New Objects without Retraining, _Giorgia Pitteri, Vincent Lepetit, Slobodan Ilic_ [\[PDF\]](http://openaccess.thecvf.com/content_ICCVW_2019/papers/R6D/Pitteri_CorNet_Generic_3D_Corners_for_6D_Pose_Estimation_of_New_ICCVW_2019_paper.pdf)
    - [2019 ICCVW] Unsupervised Joint 3D Object Model Learning and 6D Pose Estimation for Depth-Based Instance Segmentation, _Yuanwei Wu, Tim K Marks, Anoop Cherian, Siheng Chen, Chen Feng, Guanghui Wang, Alan Sullivan_ [\[PDF\]](http://openaccess.thecvf.com/content_ICCVW_2019/papers/R6D/Wu_Unsupervised_Joint_3D_Object_Model_Learning_and_6D_Pose_Estimation_ICCVW_2019_paper.pdf)
    - [2019 ICCVW] An Annotation Saved is an Annotation Earned: Using Fully Synthetic Training for Object Detection, _Stefan Hinterstoisser, Olivier Pauly, Hauke Heibel, Martina Marek, Martin Bokeloh_ [\[PDF\]](http://openaccess.thecvf.com/content_ICCVW_2019/papers/R6D/Hinterstoisser_An_Annotation_Saved_is_an_Annotation_Earned_Using_Fully_Synthetic_ICCVW_2019_paper.pdf)
    - [2019 ICCVW] HomebrewedDB: RGB-D Dataset for 6D Pose Estimation of 3D Objects, _Roman Kaskman, Sergey Zakharov, Ivan Shugurov, Slobodan Ilic_ [\[PDF\]](http://openaccess.thecvf.com/content_ICCVW_2019/papers/R6D/Kaskman_HomebrewedDB_RGB-D_Dataset_for_6D_Pose_Estimation_of_3D_Objects_ICCVW_2019_paper.pdf)
    - [2019 ICCVW] A Refined 3D Pose Dataset for Fine-Grained Object Categories, _Yaming Wang, Yi Yang_ [\[PDF\]](http://openaccess.thecvf.com/content_ICCVW_2019/papers/R6D/Wang_A_Refined_3D_Pose_Dataset_for_Fine-Grained_Object_Categories_ICCVW_2019_paper.pdf)
    - [2019 ICCVW] Satellite Pose Estimation with Deep Landmark Regression and Nonlinear Pose Refinement, _Bo Chen, Jiewei Cao, Alvaro Parra, Tat-Jun Chin_ [\[PDF\]](hhttp://openaccess.thecvf.com/content_ICCVW_2019/papers/R6D/Chen_Satellite_Pose_Estimation_with_Deep_Landmark_Regression_and_Nonlinear_Pose_ICCVW_2019_paper.pdf)


### • [R6D 2018](http://cmp.felk.cvut.cz/sixd/workshop_2018/), In conjunction with ECCV 2018
- Talk Slides
  - [Summary] 4th International Workshop on Recovering 6D Object Pose (R6D) [\[PDF\]](https://arxiv.org/pdf/1810.03758.pdf)

  - [Talk 1]  _[Federico Tombari](http://campar.in.tum.de/Main/FedericoTombari) (TU Munich)_, From 3d descriptors to monocular 6D pose: what have we learned?, [\[Slide\]](http://cmp.felk.cvut.cz/sixd/workshop_2018/data/tombari_r6d_eccv18_talk.pdf)

  - [Talk 2]  _[Kostas Bekris](https://www.cs.rutgers.edu/faculty/kostas-bekris) (Rutgers University)_, Towards Robust 6D Pose Estimation: Physics-based Reasoning and Data Efficiency,[\[Slide\]](http://cmp.felk.cvut.cz/sixd/workshop_2018/data/bekris_r6d_eccv18_talk.pptx)

  - [Talk 3]  _[Bertram Drost](http://campar.in.tum.de/Main/BertramDrost) (MVTec)_, Detecting Geometric Primitives in 3D Data,  [\[Slide\]](http://cmp.felk.cvut.cz/sixd/workshop_2018/data/drost_r6d_eccv18_talk.pdf)
  - [Talk 4]  _[Thibault Groueix](http://imagine.enpc.fr/~groueixt/) (Ecole Nationale des Ponts et Chaussées)_, Parameteric estimation of 3D surfaces and correspondences, [\[Slide\]](http://cmp.felk.cvut.cz/sixd/workshop_2018/data/groueix_r6d_eccv18_talk.pptx)

- Workshop Papers
    - [2018 ECCVW] Image-to-Voxel Model Translation with Conditional Adversarial Networks, _V. Kniaz, F. Remondino_ [\[PDF\]](https://openaccess.thecvf.com/content_ECCVW_2018/papers/11129/Knyaz_Image-to-Voxel_Model_Translation_with_Conditional_Adversarial_Networks_ECCVW_2018_paper.pdf)
    - [2018 ECCVW] 3D Pose Estimation for Fine-Grained Object Categories, _Y. Wang, Y. Yang, X. Tan, X. Liu, E. Ding, F. Zhou, L. Davis_ [\[PDF\]](https://openaccess.thecvf.com/content_ECCVW_2018/papers/11129/Wang_3D_Pose_Estimation_for_Fine-Grained_Object_Categories_ECCVW_2018_paper.pdf)
    - [2018 ECCVW] Plane-based Humanoid Robot Navigation and Object Model Construction for Grasping, _P. Gritsenko, I. Gritsenko, A. Seidakhmet, B. Kwolek_ [\[PDF\]](https://openaccess.thecvf.com/content_ECCVW_2018/papers/11129/Gritsenko_Plane-based_Humanoid_Robot_Navigation_and_Object_Model_Construction_for_Grasping_ECCVW_2018_paper.pdf)
    - [2018 ECCVW] Seamless Color Mapping for 3D Reconstruction with Consumer-Grade Scanning Devices, _B. Wang, P. Pan, Q. Xiao, L. Luo, X. Ren, R. Jin, X. Jin_ [\[PDF\]](https://openaccess.thecvf.com/content_ECCVW_2018/papers/11129/Wang_Seamless_Color_Mapping_for_3D_Reconstruction_with_Consumer-Grade_Scanning_Devices_ECCVW_2018_paper.pdf)
    - [2018 ECCVW] Category-level 6D Object Pose Recovery in Depth Images, _C. Sahin, T-K Kim_ [\[PDF\]](https://openaccess.thecvf.com/content_ECCVW_2018/papers/11129/Sahin_Category-level_6D_Object_Pose_Recovery_in_Depth_Images_ECCVW_2018_paper.pdf)


### *Workshops on Learning 3D Representations for Shape and Appearance:*

### • [3DReps 2020](https://geometry.stanford.edu/3DReps/index.html), In conjunction with ECCV 2020
- Workshop Videos
    - [Sesseions 1](https://youtu.be/XaaiwCqEWI4)
    - [Sesseions 2](https://youtu.be/BskUrVASLB4)
- Workshop Papers
    - [2020 ECCVW] Learning a Neural 3D Texture Space from 2D Exemplars, _Philipp Henzler et. al_ [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Henzler_Learning_a_Neural_3D_Texture_Space_From_2D_Exemplars_CVPR_2020_paper.pdf)
    - [2020 ECCVW] BlockGAN: Learning 3D Object-aware Scene Representations from Unlabelled Images, _Thu Nguyen-Phuoc et. al_ [\[PDF\]](https://proceedings.neurips.cc/paper/2020/file/4b29fa4efe4fb7bc667c7b301b74d52d-Paper.pdf)
    - [2020 ECCVW] BSP-Net: Generating Compact Meshes via Binary Space Partitioning, _Zhiqin Chen et. al_ [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Chen_BSP-Net_Generating_Compact_Meshes_via_Binary_Space_Partitioning_CVPR_2020_paper.pdf)
    - [2020 ECCVW] Convolutional Occupancy Networks More, _Songyou Peng et. al_ [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123480528.pdf)
    - [2020 ECCVW] Deep Geometric Prior for Surface Reconstruction, _Francis Williams et. al_ [\[PDF\]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Williams_Deep_Geometric_Prior_for_Surface_Reconstruction_CVPR_2019_paper.pdf)
    - [2020 ECCVW] Multiview Neural Surface Reconstruction with Implicit Lighting and Material, _Lior Yariv et. al_ [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Henzler_Learning_a_Neural_3D_Texture_Space_From_2D_Exemplars_CVPR_2020_paper.pdfhttps://arxiv.org/pdf/2003.09852v2.pdf)
    - [2020 ECCVW] NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis, _Ben Mildenhall et. al_ [\[PDF\]](https://arxiv.org/pdf/2003.08934.pdf)
    - [2020 ECCVW] Pix2Surf: Learning Parametric 3D Surface Models of Objects from Images, _Jiahui Lei et. al_ [\[PDF\]](https://arxiv.org/pdf/2008.07760.pdf)[\[Project\]](https://geometry.stanford.edu/projects/pix2surf/)
    - [2020 ECCVW] Scene Representation Networks: Continuous 3D-Structure-Aware Neural Scene Representations, _Vincent Sitzmann et. al_ [\[PDF\]](https://arxiv.org/pdf/1906.01618.pdf)
    - [2020 ECCVW] Texture Fields: Learning Texture Representations in Function Space, _Michael Oechsle et. al_ [\[PDF\]](http://openaccess.thecvf.com/content_ICCV_2019/papers/Oechsle_Texture_Fields_Learning_Texture_Representations_in_Function_Space_ICCV_2019_paper.pdf)
    - [2020 ECCVW] AtlasNet: A Papier-Mâché Approach to Learning 3D Surface Generation, _Thibault Groueix et. al_ [\[PDF\]](https://arxiv.org/pdf/1802.05384.pdf)
    - [2020 ECCVW] PointFlow: 3D Point Cloud Generation with Continuous Normalizing Flows, _Guandao Yang et. al_ [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Yang_PointFlow_3D_Point_Cloud_Generation_With_Continuous_Normalizing_Flows_ICCV_2019_paper.pdf)
    - [2020 ECCVW] DeepSDF: Learning Continuous Signed Distance Functions for Shape Representation, _JJ Park et. al_ [\[PDF\]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Park_DeepSDF_Learning_Continuous_Signed_Distance_Functions_for_Shape_Representation_CVPR_2019_paper.pdf)
    - [2020 ECCVW] Deformation-Aware 3D Model Embedding and Retrieval, _Mikaela Angelina Uy et. al_ [\[PDF\]](https://arxiv.org/pdf/2004.01228.pdf)

[\[back to top\]](#contents)

## Challenges

#### [BOP Challenge 2020](http://cmp.felk.cvut.cz/sixd/workshop_2020/#challenge)
- Dataset: [BOP: Benchmark for 6D Object Pose Estimation](https://bop.felk.cvut.cz/challenges/bop-challenge-2020/)
- Documents:
    - BOP Challenge 2020 on 6D Object Localization, ECCV 2020 [\[PDF\]](https://arxiv.org/pdf/2009.07378)
- Slides:
    - [Talk 1]  _[Tomáš Hodaň](http://www.hodan.xyz/) (Czech Technical University)_, A Summary of Results, [\[Slide\]](https://bop.felk.cvut.cz/media/bop_challenge_2020_results.pdf)
    - [Talk 2]  _[Martin Sundermeyer](https://rmc.dlr.de/rm/en/staff/martin.sundermeyer/) (DLR)_, Photorealistic Training Images by BlenderProc.
    - [Talk 3]  _[Yann Labbé](https://ylabbe.github.io/) (Inria Paris)_, Presentation of the Overall Best Method, [\[Slide\]](http://cmp.felk.cvut.cz/sixd/workshop_2020/slides/r6d20_labbe.pdf)
    - [Talk 4]  _[Bertram Drost](https://hci.iwr.uni-heidelberg.de/vislearn/people/eric-brachmann/) (MVTec)_, Presentation of the Best Fast Method, [\[Slide\]](http://cmp.felk.cvut.cz/sixd/workshop_2020/slides/r6d20_drost.pdf)

#### [BOP Challenge 2019](http://cmp.felk.cvut.cz/sixd/workshop_2020/#challenge)
- Documents:
  - Results of the BOP Challenge 2019, _[Tomáš Hodaň](http://www.hodan.xyz/) (CTU in Prague)_ [\[Slide\]](http://cmp.felk.cvut.cz/sixd/workshop_2019/slides/r6d19_hodan_bop_challenge_2019.pdf)
#### [SIXD Challenge 2017](http://cmp.felk.cvut.cz/sixd/challenge_2017/)


[\[back to top\]](#contents)

## Researchers

### U.S./Canada

#### • [Dieter Fox](https://homes.cs.washington.edu/~fox/), [UW Robotics and State Estimation Lab](http://rse-lab.cs.washington.edu/), University of Washington.
#### • [Junsong Yuan](https://cse.buffalo.edu/~jsyuan/), University at Buffalo, State University of New York.
#### • [Qixing Huang](https://www.cs.utexas.edu/~huangqx/index.html), The University of Texas at Austin.
#### • [Fei-Fei Li](https://profiles.stanford.edu/fei-fei-li) and [Jiajun Wu](https://jiajunwu.com/), [STANFORD VISION AND LEARNING LAB](http://svl.stanford.edu/), Stanford University.
#### • [Leonidas Guibas](https://geometry.stanford.edu/member/guibas/), Stanford University.
#### • [Shuran Song](https://www.cs.columbia.edu/~shurans/), Columbia University.
#### • [TOMÁŠ HODAŇ](https://cmp.felk.cvut.cz/~hodanto2/), [Facebook Reality Labs](https://about.fb.com/realitylabs/).
#### • [KOSTAS BEKRIS](https://robotics.cs.rutgers.edu/pracsys/members/kostas-bekris/), [PRACSYS Lab](https://robotics.cs.rutgers.edu/pracsys/), Rutgers University.


### Europe
#### • [Niloy J. Mitra](http://www0.cs.ucl.ac.uk/staff/n.mitra/), [Smart Geometry Processing Group](http://geometry.cs.ucl.ac.uk/index.php), University College London (UCL).
#### • [TAE-KYUN (T-K) KIM](https://sites.google.com/view/tkkim/home), [Imperial Computer Vision & Learning Lab](https://labicvl.github.io/), Imperial College London.
#### • [Ales Leonardis](https://www.cs.bham.ac.uk/~leonarda/) and [Hyung Jin Chang](https://hyungjinchang.wordpress.com/), [Intelligent Robotics Lab](https://www.birmingham.ac.uk/research/activity/computer-science/artificial-intelligence/robotics-and-computer-vision/index.aspx), University of Birmingham.
#### • [Pascal Fua](https://www.epfl.ch/labs/cvlab/people/), [CVLab](https://www.epfl.ch/labs/cvlab/), EPFL.
#### • [Andrew Davison](http://www.doc.ic.ac.uk/~ajd/), [Dyson Robotics Lab](https://www.imperial.ac.uk/dyson-robotics-lab), Imperial College London.
#### • [Andrew Zisserman](http://www.robots.ox.ac.uk/~az), [Visual Geometry Group](https://www.robots.ox.ac.uk/~vgg/research/), Oxford University.
#### • [Renaud MARLET](http://imagine.enpc.fr/~marletr/) and [Mathieu Aubry](http://imagine.enpc.fr/~aubrym/), [Research Group in Computer Vision, Machine Learning and Optimization](https://imagine-lab.enpc.fr/), École des Ponts ParisTech (ENPC).
#### • [Eric Brachmann](https://hci.iwr.uni-heidelberg.de/vislearn/people/eric-brachmann/), [Visual Learning Lab](https://hci.iwr.uni-heidelberg.de/vislearn/), Heidelberg University.
#### • [Matthias Nießner](https://niessnerlab.org/members/matthias_niessner/profile.html), [Federico Tombari](http://campar.in.tum.de/Main/FedericoTombari) and [Bertram Drost](http://campar.in.tum.de/Main/BertramDrost), TU Munich (TUM).
#### • [Jiri MATAS](https://cmp.felk.cvut.cz/~matas/), Czech Technical University, Prague.
#### • [Otmar Hilliges](https://ait.ethz.ch/people/hilliges/), [Advanced Interactive Technologies Lab](https://ait.ethz.ch/index.php), ETH Zurich.


### Asia
#### • [Cewu Lu](http://www.cs.sjtu.edu.cn/PeopleDetail.aspx?id=366), [Machine Vision and Intelligence Group ](http://mvig.sjtu.edu.cn/), Shanghai JiaoTong University (SJTU).
#### • [Gim Hee Lee](https://www.researchgate.net/profile/Gim_Lee), [CVRP LAB](https://www.comp.nus.edu.sg/~leegh/#), National University of Singapore (NUS).
#### • [Yue Wang](https://ywang-zju.github.io/), [His Youtube Channel](https://www.youtube.com/channel/UCkGsUj95tueXDxf5JEhiYZQ), Zhejiang University (ZJU).
#### • [Xiaoou Tang](http://www.ie.cuhk.edu.hk/people/xotang.shtml), [Xiaogang Wang](http://www.ee.cuhk.edu.hk/~xgwang/) and [Dahua Lin](http://dahua.me/), [Multimedia Laboratory](http://mmlab.ie.cuhk.edu.hk/index.html), The Chinese University of Hong Kong (CUHK).
#### • [Xiangyang Ji](http://www.au.tsinghua.edu.cn/info/1166/2066.htm), Tsinghua University.
#### • [Xiaowei Zhou](http://www.cad.zju.edu.cn/home/xzhou/), Zhejiang University.
#### • [He Wang](https://hughw19.github.io/), Peking University.

### Australia
#### • [Hongdong Li](http://users.cecs.anu.edu.au/~hongdong/), [Australia ARC Centre of Excellence for Robotic Vision](http://roboticvision.org/), The Australian National University (ANU).
#### • [Yi Yang](https://scholar.google.co.uk/citations?hl=zh-CN&user=RMSuNFwAAAAJ) and [Xin Yu](https://sites.google.com/view/xinyus-homepage/Home), [ReLER Lab](http://reler.net/), University of Technology Sydney (UTS).

[\[back to top\]](#contents)
