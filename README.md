# Awesome Object Pose Estimation and Reconstruction [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

A curated list of related resources for object recovery used learning-based method (especially from single view), including 3d object reconstruction, 6d object pose estimation, and hand-object reconstruction. Since the pose estimation and reconstruction of the human body are similar to that of hands (objects), I also collect some papers about human body, but I will not pay more attention to it.

Due to my personal interests, geometry-based work (SFM-based or SLAM-based work) are not collected here. Those papers can be found [here](https://github.com/openMVG/awesome_3DReconstruction_list).

Another related paper list is about the hand pose estimation, which can be found [here](https://github.com/xinghaochen/awesome-hand-pose-estimation).

All of these papers are collected by programme, not manual collection. So, if you find any mistakes or missing papers in this project, please feel free to let me know (zhongqunzhang@outlook.com).

## Contents
 <!-- - [Evaluation](#evaluation) -->
 - [arXiv Papers](#arxiv-papers)
 - [Journal Papers](#journal-papers)
   - [TPAMI / IJCV](#tpami--ijcv)
   - [Others](#other-journals)
 - [Conference Papers](#conference-papers)
   - 2020: [CVPR](#2020-cvpr), [ECCV](#2020-eccv), [Others](#2020-others)
   - 2019: [CVPR](#2019-cvpr), [ICCV](#2019-iccv), [Others](#2019-others)
   - 2018: [CVPR](#2018-cvpr), [ECCV](#2018-eccv), [Others](#2018-others)
   - 2017: [CVPR](#2017-cvpr), [ICCV](#2017-iccv), [Others](#2017-others)
   - 2016: [CVPR](#2016-cvpr), [Others](#2016-others)
   - 2015: [CVPR](#2015-cvpr), [ICCV](#2015-iccv), [Others](#2015-others)
   - 2014: [CVPR](#2014-cvpr), [Others](#2014-others-&-before)
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

#### ***Object Pose Esimation and Reconstruction***
##### • Self6D: Self-Supervised Monocular 6D Object Pose Estimation. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123460103.pdf) 
 _Gu Wang, Fabian Manhardt, Jianzhun Shao, Xiangyang Ji, Nassir Navab , Federico Tombari_
##### • Neural Object Learning for 6D Pose Estimation Using a Few Cluttered Images. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123490630.pdf) 
 _Kiru Park, Timothy Patten, Markus Vincze_
##### • Point-Set Anchors for Object Detection, Instance Segmentation and Pose Estimation. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123550528.pdf) 
 _Fangyun Wei, Xiao Sun, Hongyang Li, Jingdong Wang, Stephen Lin_
##### • ContactPose: A Dataset of Grasps with Object Contact and Hand Pose. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123580358.pdf) 
 _Samarth Brahmbhatt, Chengcheng Tang, Christopher D. Twigg, Charles C. Kemp, James Hays_
##### • Shape Prior Deformation for Categorical 6D Object Pose and Size Estimation. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660528.pdf) 
 _Meng Tian, Marcelo H Ang Jr, Gim Hee Lee_
##### • Measuring Generalisation to Unseen Viewpoints, Articulations, Shapes and Objects for 3D Hand Pose Estimation under Hand-Object Interaction. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123680086.pdf) 
 _Anil Armagan, Guillermo Garcia-Hernando, Seungryul Baek, Shreyas Hampali, Mahdi Rad, Zhaohui Zhang, Shipeng Xie, MingXiu Chen, Boshen Zhang, Fu Xiong, Yang Xiao, Zhiguo Cao, Junsong Yuan, Pengfei Ren⁸, Weiting Huang⁸, Haifeng Sun⁸, Marek Hrúz⁹, Jakub Kanis⁹, Zdeněk Krňoul⁹, Qingfu Wan, Shile Li, Linlin Yang, Dongheui Lee, Angela Yao, Weiguo Zhou, Sijia Mei, Yunhui Liu, Adrian Spurr, Umar Iqbal, Pavlo Molchanov, Philippe Weinzaepfel, Romain Brégier, Grégory Rogez, Vincent Lepetit, Tae-Kyun Kim_
##### • Category Level Object Pose Estimation via Neural Analysis-by-Synthesis. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123710137.pdf) 
 _Xu Chen, Zijian Dong, Jie Song, Andreas Geiger, Otmar Hilliges_
##### • Pose Augmentation: Class-agnostic Object Pose Transformation for Object Recognition. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123730137.pdf) 
 _Yunhao Ge, Jiaping Zhao, Laurent Itti_
##### • Pose Augmentation: Class-agnostic Object Pose Transformation for Object Recognition. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123730137.pdf) 
 _Yunhao Ge, Jiaping Zhao, Laurent Itti_
##### • Few-Shot Single-View 3-D Object Reconstruction with Compositional Priors. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123700613.pdf) 
 _Mateusz Michalkiewicz, Sarah Parisot, Stavros Tsogkas, Mahsa Baktashmotlagh, Anders Eriksson, Eugene Belilovsky_
 ##### • ContactPose: A Dataset of Grasps with Object Contact and Hand Pose. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123580358.pdf) 
 _Samarth Brahmbhatt, Chengcheng Tang, Christopher D. Twigg, Charles C. Kemp, James Hays_
##### • Measuring Generalisation to Unseen Viewpoints, Articulations, Shapes and Objects for 3D Hand Pose Estimation under Hand-Object Interaction. [\[PDF\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123680086.pdf) 
 _Anil Armagan, Guillermo Garcia-Hernando, Seungryul Baek, Shreyas Hampali, Mahdi Rad, Zhaohui Zhang, Shipeng Xie, MingXiu Chen, Boshen Zhang, Fu Xiong, Yang Xiao, Zhiguo Cao, Junsong Yuan, Pengfei Ren⁸, Weiting Huang⁸, Haifeng Sun⁸, Marek Hrúz⁹, Jakub Kanis⁹, Zdeněk Krňoul⁹, Qingfu Wan, Shile Li, Linlin Yang, Dongheui Lee, Angela Yao, Weiguo Zhou, Sijia Mei, Yunhui Liu, Adrian Spurr, Umar Iqbal, Pavlo Molchanov, Philippe Weinzaepfel, Romain Brégier, Grégory Rogez, Vincent Lepetit, Tae-Kyun Kim_

#### ***Human Pose Estimation and Body Reconstruction***
<details>
<summary>Show More</summary>

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

#### ***Object Pose Esimation and Reconstruction***
##### • Total3DUnderstanding: Joint Layout, Object Pose and Mesh Reconstruction for Indoor Scenes From a Single Image. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Nie_Total3DUnderstanding_Joint_Layout_Object_Pose_and_Mesh_Reconstruction_for_Indoor_CVPR_2020_paper.pdf) 
 _Nie, Yinyu and Han, Xiaoguang and Guo, Shihui and Zheng, Yujian and Chang, Jian and Zhang, Jian Jun_
##### • Category-Level Articulated Object Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Category-Level_Articulated_Object_Pose_Estimation_CVPR_2020_paper.pdf) 
 _Li, Xiaolong and Wang, He and Yi, Li and Guibas, Leonidas J. and Abbott, A. Lynn and Song, Shuran_
##### • Reconstruct Locally, Localize Globally: A Model Free Method for Object Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Cai_Reconstruct_Locally_Localize_Globally_A_Model_Free_Method_for_Object_CVPR_2020_paper.pdf) 
 _Cai, Ming and Reid, Ian_
##### • HybridPose: 6D Object Pose Estimation Under Hybrid Representations. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Song_HybridPose_6D_Object_Pose_Estimation_Under_Hybrid_Representations_CVPR_2020_paper.pdf) 
 _Song, Chen and Song, Jiaru and Huang, Qixing_
##### • Single-Stage 6D Object Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Hu_Single-Stage_6D_Object_Pose_Estimation_CVPR_2020_paper.pdf) 
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
##### • LatentFusion: End-to-End Differentiable Reconstruction and Rendering for Unseen Object Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Park_LatentFusion_End-to-End_Differentiable_Reconstruction_and_Rendering_for_Unseen_Object_Pose_CVPR_2020_paper.pdf) 
 _Park, Keunhong and Mousavian, Arsalan and Xiang, Yu and Fox, Dieter_
##### • Mixture Dense Regression for Object Detection and Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Varamesh_Mixture_Dense_Regression_for_Object_Detection_and_Human_Pose_Estimation_CVPR_2020_paper.pdf) 
 _Varamesh, Ali and Tuytelaars, Tinne_
##### • Learning Canonical Shape Space for Category-Level 6D Object Pose and Size Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Chen_Learning_Canonical_Shape_Space_for_Category-Level_6D_Object_Pose_and_CVPR_2020_paper.pdf) 
 _Chen, Dengsheng and Li, Jun and Wang, Zheng and Xu, Kai_
##### • Multi-Path Learning for Object Pose Estimation Across Domains. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Sundermeyer_Multi-Path_Learning_for_Object_Pose_Estimation_Across_Domains_CVPR_2020_paper.pdf) 
 _Sundermeyer, Martin and Durner, Maximilian and Puang, En Yen and Marton, Zoltan-Csaba and Vaskevicius, Narunas and Arras, Kai O. and Triebel, Rudolph_
##### • EPOS: Estimating 6D Pose of Objects With Symmetries. [\[PDF\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Hodan_EPOS_Estimating_6D_Pose_of_Objects_With_Symmetries_CVPR_2020_paper.pdf) 
 _Hodan, Tomas and Barath, Daniel and Matas, Jiri_

#### ***Human Pose Estimation and Body Reconstruction***
<details>
<summary>Show More</summary>

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
#### ***Object Pose Esimation and Reconstruction***
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
 ##### • [2020 ICRA] 6D Object Pose Regression Via Supervised Learning on Point Clouds. [\[arXiv\]](https://arxiv.org/pdf/2001.08942.pdf) 
 _Ge Gao, Mikko Lauri, Yulong Wang, Xiaolin Hu, Jianwei Zhang and Simone Frintrop_
 ##### • [2020 ICRA] Self-Supervised 6D Object Pose Estimation for Robot Manipulation. [\[arXiv\]](https://arxiv.org/pdf/1909.10159.pdf) [\[Video\]](https://youtu.be/W1Y0Mmh1Gd8)
 _Xinke Deng, Yu Xiang, Arsalan Mousavian, Clemens Eppner, Timothy Bretl, Dieter Fox_
##### • [2020 ICRA] Pose-Guided Auto-Encoder and Feature-Based Refinement for 6-DoF Object Pose Regression. [\[arXiv\]](http://xiangyangji.com/uploadfile/upload/2020072017405951.pdf) 
 _Zhigang Li, Xiangyang Ji_

#### ***Human Pose Estimation and Body Reconstruction***
<details>
<summary>Show More</summary>

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

#### ***Object Pose Esimation and Reconstruction***
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

 #### ***Human Pose Estimation and Body Reconstruction***
<details>
<summary>Show More</summary>

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

#### ***Object Pose Esimation and Reconstruction***
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

#### ***Human Pose Estimation and Body Reconstruction***
<details>
<summary>Show More</summary>

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

#### ***Object Pose Esimation and Reconstruction***
##### • Real-Time Seamless Single Shot 6D Object Pose Prediction. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Tekin_Real-Time_Seamless_Single_CVPR_2018_paper.pdf) 
 _Tekin, Bugra and Sinha, Sudipta N. and Fua, Pascal_
##### • 3D Pose Estimation and 3D Model Retrieval for Objects in the Wild. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Grabner_3D_Pose_Estimation_CVPR_2018_paper.pdf) 
 _Grabner, Alexander and Roth, Peter M. and Lepetit, Vincent_
##### • RotationNet: Joint Object Categorization and Pose Estimation Using Multiviews From Unsupervised Viewpoints. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Kanezaki_RotationNet_Joint_Object_CVPR_2018_paper.pdf) 
 _Kanezaki, Asako and Matsushita, Yasuyuki and Nishida, Yoshifumi_
##### • 3D-RCNN: Instance-Level 3D Object Reconstruction via Render-and-Compare. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Kundu_3D-RCNN_Instance-Level_3D_CVPR_2018_paper.pdf) 
 _Kundu, Abhijit and Li, Yin and Rehg, James M._

#### ***Human Pose Estimation and Body Reconstruction***
<details>
<summary>Show More</summary>

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

#### ***Object Pose Esimation and Reconstruction***
##### • BOP: Benchmark for 6D Object Pose Estimation. [\[PDF\]](https://www.ecva.net/papers/eccv_2018/papers_ECCV/papers/Tomas_Hodan_PESTO_6D_Object_ECCV_2018_paper.pdf) 
 _Hodan, Tomas and Michel, Frank and Brachmann, Eric and Kehl, Wadim and GlentBuch, Anders and Kraft, Dirk and Drost, Bertram and Vidal, Joel and Ihrke, Stephan and Zabulis, Xenophon and Sahin, Caner and Manhardt, Fabian and Tombari, Federico and Kim, Tae-Kyun and Matas, Jiri and Rother, Carsten_
##### • Making Deep Heatmaps Robust to Partial Occlusions for 3D Object Pose Estimation. [\[PDF\]](https://www.ecva.net/papers/eccv_2018/papers_ECCV/papers/Markus_Oberweger_Making_Deep_Heatmaps_ECCV_2018_paper.pdf) 
 _Oberweger, Markus and Rad, Mahdi and Lepetit, Vincent_
##### • A Unified Framework for Multi-View Multi-Class Object Pose Estimation. [\[PDF\]](https://www.ecva.net/papers/eccv_2018/papers_ECCV/papers/Chi_Li_A_Unified_Framework_ECCV_2018_paper.pdf) 
 _Li, Chi and Bai, Jin and Hager, Gregory D._
##### • Efficient Dense Point Cloud Object Reconstruction using Deformation Vector Fields. [\[PDF\]](https://www.ecva.net/papers/eccv_2018/papers_ECCV/papers/Kejie_Li_Efficient_Dense_Point_ECCV_2018_paper.pdf) 
 _Li Kejie, Pham Trung, Zhan Huangying, Reid Ian_

#### ***Human Pose Estimation and Body Reconstruction***
<details>
<summary>Show More</summary>

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
#### ***Object Pose Esimation and Reconstruction***

#### ***Human Pose Estimation and Body Reconstruction***
<details>
<summary>Show More</summary>
</details>

[\[back to top\]](#contents)

### 2017 CVPR
#### ***Object Pose Esimation and Reconstruction***
##### • Global Hypothesis Generation for 6D Object Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Michel_Global_Hypothesis_Generation_CVPR_2017_paper.pdf) 
 _Michel, Frank and Kirillov, Alexander and Brachmann, Eric and Krull, Alexander and Gumhold, Stefan and Savchynskyy, Bogdan and Rother, Carsten_
##### • PoseAgent: Budget-Constrained 6D Object Pose Estimation via Reinforcement Learning. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Krull_PoseAgent_Budget-Constrained_6D_CVPR_2017_paper.pdf) 
 _Krull, Alexander and Brachmann, Eric and Nowozin, Sebastian and Michel, Frank and Shotton, Jamie and Rother, Carsten_
##### • A Point Set Generation Network for 3D Object Reconstruction From a Single Image. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Fan_A_Point_Set_CVPR_2017_paper.pdf) 
 _Fan, Haoqiang and Su, Hao and Guibas, Leonidas J._
##### • DUST: Dual Union of Spatio-Temporal Subspaces for Monocular Multiple Object 3D Reconstruction. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Agudo_DUST_Dual_Union_CVPR_2017_paper.pdf) 
 _Agudo, Antonio and Moreno-Noguer, Francesc_

#### ***Human Pose Estimation and Body Reconstruction***
<details>
<summary>Show More</summary>

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
#### ***Object Pose Esimation and Reconstruction***
##### • Real-Time Monocular Pose Estimation of 3D Objects Using Temporally Consistent Local Color Histograms. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Tjaden_Real-Time_Monocular_Pose_ICCV_2017_paper.pdf) 
 _Tjaden, Henning and Schwanecke, Ulrich and Schomer, Elmar_
##### • Pose Guided RGBD Feature Learning for 3D Object Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Balntas_Pose_Guided_RGBD_ICCV_2017_paper.pdf) 
 _Balntas, Vassileios and Doumanoglou, Andreas and Sahin, Caner and Sock, Juil and Kouskouridas, Rigas and Kim, Tae-Kyun_
##### • Rotational Subgroup Voting and Pose Clustering for Robust 3D Object Recognition. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Buch_Rotational_Subgroup_Voting_ICCV_2017_paper.pdf) 
 _Glent Buch, Anders and Kiforenko, Lilita and Kraft, Dirk_
##### • Robust Hand Pose Estimation During the Interaction With an Unknown Object. [\[PDF\]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Choi_Robust_Hand_Pose_ICCV_2017_paper.pdf) 
 _Choi, Chiho and Ho Yoon, Sang and Chen, Chin-Ning and Ramani, Karthik_

#### ***Human Pose Estimation and Body Reconstruction***
<details>
<summary>Show More</summary>

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


### 2016 CVPR
#### ***Object Pose Esimation and Reconstruction***
##### • Uncertainty-Driven 6D Pose Estimation of Objects and Scenes From a Single RGB Image. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2016/papers/Brachmann_Uncertainty-Driven_6D_Pose_CVPR_2016_paper.pdf) 
 _Brachmann, Eric and Michel, Frank and Krull, Alexander and Yang, Michael Ying and Gumhold, Stefan and Rother, carsten_
##### • Recovering 6D Object Pose and Predicting Next-Best-View in the Crowd. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2016/papers/Doumanoglou_Recovering_6D_Object_CVPR_2016_paper.pdf) 
 _Doumanoglou, Andreas and Kouskouridas, Rigas and Malassiotis, Sotiris and Kim, Tae-Kyun_
##### • 3D Reconstruction of Transparent Objects With Position-Normal Consistency. [\[PDF\]](https://openaccess.thecvf.com/content_cvpr_2016/papers/Qian_3D_Reconstruction_of_CVPR_2016_paper.pdf) 
 _Qian, Yiming and Gong, Minglun and Yang, Yee Hong_

#### ***Human Pose Estimation and Body Reconstruction***
<details>
<summary>Show More</summary>

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
#### ***Object Pose Esimation and Reconstruction***

#### ***Human Pose Estimation and Body Reconstruction***
<details>
<summary>Show More</summary>
</details>


[\[back to top\]](#contents)

### 2015 CVPR
#### ***Object Pose Esimation and Reconstruction***
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

#### ***Human Pose Estimation and Body Reconstruction***
<details>
<summary>Show More</summary>

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
#### ***Object Pose Esimation and Reconstruction***
##### • BodyPrint: Pose Invariant 3D Shape Matching of Human Bodies. [\[PDF\]](https://openaccess.thecvf.com/content_iccv_2015/papers/Wang_BodyPrint_Pose_Invariant_ICCV_2015_paper.pdf) 
 _Wang, Jiangping and Ma, Kai and Singh, Vivek Kumar and Huang, Thomas and Chen, Terrence_
##### • Flowing ConvNets for Human Pose Estimation in Videos. [\[PDF\]](https://openaccess.thecvf.com/content_iccv_2015/papers/Pfister_Flowing_ConvNets_for_ICCV_2015_paper.pdf) 
 _Pfister, Tomas and Charles, James and Zisserman, Andrew_
##### • Beyond Tree Structure Models: A New Occlusion Aware Graphical Model for Human Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content_iccv_2015/papers/Fu_Beyond_Tree_Structure_ICCV_2015_paper.pdf) 
 _Fu, Lianrui and Zhang, Junge and Huang, Kaiqi_

#### ***Human Pose Estimation and Body Reconstruction***
<details>
<summary>Show More</summary>

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
#### ***Object Pose Esimation and Reconstruction***

#### ***Human Pose Estimation and Body Reconstruction***
<details>
<summary>Show More</summary>
</details>


[\[back to top\]](#contents)

### 2014 CVPR
#### ***Object Pose Esimation and Reconstruction***
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

#### ***Human Pose Estimation and Body Reconstruction***
<details>
<summary>Show More</summary>

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
#### ***Object Pose Esimation and Reconstruction***
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

#### ***Human Pose Estimation and Body Reconstruction***
<details>
<summary>Show More</summary>

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

## Theses
#### ***Object Pose Esimation and Reconstruction***
##### • \[2020\] Learning to Reconstruct and Segment 3D Objects. [\[PDF\]](https://arxiv.org/pdf/2010.09582.pdf)
*[Bo Yang](https://yang7879.github.io/), University of Oxford*

#### ***Human Pose Estimation and Body Reconstruction***

[\[back to top\]](#contents)

## Datasets


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

##### • [Dieter Fox](https://homes.cs.washington.edu/~fox/), [UW Robotics and State Estimation Lab](http://rse-lab.cs.washington.edu/), University of Washington.

### Europe
##### • [Niloy J. Mitra](http://www0.cs.ucl.ac.uk/staff/n.mitra/), [Smart Geometry Processing Group](http://geometry.cs.ucl.ac.uk/index.php), University College London (UCL).
##### • [TAE-KYUN (T-K) KIM](https://sites.google.com/view/tkkim/home), [Imperial Computer Vision & Learning Lab](https://labicvl.github.io/), Imperial College London.
##### • [Ales Leonardis](https://www.cs.bham.ac.uk/~leonarda/), [Intelligent Robotics Lab](https://www.birmingham.ac.uk/research/activity/computer-science/artificial-intelligence/robotics-and-computer-vision/index.aspx), University of Birmingham.

### Asia
##### • [Cewu Lu](http://www.cs.sjtu.edu.cn/PeopleDetail.aspx?id=366), [Machine Vision and Intelligence Group ](http://mvig.sjtu.edu.cn/), Shanghai JiaoTong University (SJTU).
##### • [Gim Hee Lee](https://www.researchgate.net/profile/Gim_Lee), [CVRP LAB](https://www.comp.nus.edu.sg/~leegh/#), National University of Singapore (NUS).

### Australia
##### • [Hongdong Li](http://users.cecs.anu.edu.au/~hongdong/), [Australia ARC Centre of Excellence for Robotic Vision](http://roboticvision.org/), The Australian National University (ANU).

[\[back to top\]](#contents)
