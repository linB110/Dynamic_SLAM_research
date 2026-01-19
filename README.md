# ⭐ Dynamic Visual SLAM

A curated list of **Dynamic Visual SLAM** papers and resources, focusing on SLAM systems that robustly operate in **dynamic environments** with moving objects, non-rigid scenes, and scene changes.

This repository covers topics such as **motion segmentation, dynamic object handling, semantic SLAM, optical flow, scene flow, multi-view geometry, and learning-based approaches** for dynamic scenes.

If you find missing or ignored papers, feel free to **open issues or submit pull requests**.
Contributions of any kind are welcome!

If you find this repository useful, a ⭐ would be greatly appreciated 😊

---


## 🧭 Dynamic Visual SLAM

| Year | Venue       | Paper Title                                                                                                                                                                                        | Repository                                                                                                                   | Tags                           |
| ---- | ----------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- | ------------------------------ |
| 2018 | IEEE RA-L   | [**DynaSLAM: Tracking, Mapping and Inpainting in Dynamic Scenes**](https://arxiv.org/pdf/1806.05620)                                                                                               | [![GitHub](https://img.shields.io/badge/GitHub-DynaSLAM-black?logo=github)](https://github.com/BertaBescos/DynaSLAM)         | Deep learning                  |
| 2018 | IEEE IROS   | [**DS-SLAM: A Semantic Visual SLAM towards Dynamic Environments**](https://arxiv.org/pdf/1809.08379)                                                                                               | [![GitHub](https://img.shields.io/badge/GitHub-DS--SLAM-black?logo=github)](https://github.com/ivipsourcecode/DS-SLAM)       | Optical flow                   |
| 2018 | IEEE WACV   | [**Detect-SLAM: Making Object Detection and SLAM Mutually Beneficial**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8354219)                                                          | —                                                                                                                            | SSD & moving probability       |
| 2019 | IEEE Access  | [**SOF-SLAM: A Semantic Visual SLAM for Dynamic Environments**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8894002)                                                                 | —                                                                                                                            | SegNet, Optical flow & optical flow    |
| 2019 | IEEE RAS     | [**Pixel-Wise Motion Segmentation for SLAM in Dynamic Environments**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9187601)                                                    | [![GitHub](https://img.shields.io/badge/GitHub-DynamicSLAM-black?logo=github)](https://github.com/linhuixiao/Dynamic-SLAM?tab=readme-ov-file) | selective tracking & missed detection        |
| 2020 | IEEE Access | [**Dynamic-SLAM: Semantic monocular visual localization and mapping based on deep learning in dynamic environment**](https://www.sciencedirect.com/science/article/pii/S0921889018308029?ref=pdf_download&fr=RR-2&rr=9bf370f6cb4da361)                                                    | —            | optical flow fuse with depth        |
| 2020 | ISPRS IJGI  | [**DM-SLAM: A Feature-Based SLAM System for Rigid Dynamic Scenes**](https://www.researchgate.net/publication/340330756_DM-SLAM_A_Feature-Based_SLAM_System_for_Rigid_Dynamic_Scenes)               | —                                                                                                                            | Segmentation & optical flow    |
| 2020 | IEEE IROS      | [**VDO-SLAM: A Visual Dynamic Object-aware SLAM System**](https://arxiv.org/pdf/2005.11052)                                                                                                        | [![GitHub](https://img.shields.io/badge/GitHub-VDO--SLAM-black?logo=github)](https://github.com/halajun/VDO_SLAM)            | Optical flow & moving factor   |
| 2021 | IEEE ICRA      | [**Towards Real-time Semantic RGB-D SLAM in Dynamic Environments**](https://arxiv.org/pdf/2104.01316)                                                                                                        | —             | geometry and optical flow on keyframe detection  |
| 2021 | IEEE RA-L   | [**DynaSLAM II: Tightly-Coupled Multi-Object Tracking and SLAM**](https://arxiv.org/pdf/2010.07820)                                                                                                | —                                                                                                                            | Dynamic object estimation      |
| 2021 | IEEE Access | [**RDS-SLAM: Real-Time Dynamic SLAM Using Semantic Segmentation Methods**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9318990)                                                       | [![GitHub](https://img.shields.io/badge/GitHub-RDS--SLAM-black?logo=github)](https://github.com/yubaoliu/RDS-SLAM)           | Semantic segmentation          |
| 2021 | Springer JINT |  [**Crowd-SLAM is a visual SLAM system that is robust in crowded scenarios**](https://link.springer.com/article/10.1007/s10846-021-01414-1)                                                       | [![GitHub](https://img.shields.io/badge/GitHub-Crowd--SLAM-black?logo=github)](https://github.com/virgolinosoares/Crowd-SLAM) | YOLOv3 & Kpts update |
| 2022 | IEEE Access | [**Real-Time Dynamic SLAM Algorithm Based on Deep Learning**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9858152)                                                                    | —                                                                                                                            | YOLOv5 & optical search        |
| 2022 | IEEE RA-L   | [**Dynavins: A visual-inertial slam for dynamic environments**](https://arxiv.org/abs/2208.11500)                                            | [![GitHub](https://img.shields.io/badge/GitHub-DynaVINS-black?logo=github)](https://github.com/url-kaist/dynaVINS) | BA & refine constriant in FP dynamic points |
| 2022 | IEEE RA-L   | [**RGB-D Inertial Odometry for a Resource-Restricted Robot in Dynamic Environments**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9830851)                                            | [![GitHub](https://img.shields.io/badge/GitHub-DynamicVINS-black?logo=github)](https://github.com/HITSZ-NRSL/Dynamic-VINS) | YOLOv3 & semantic segmentation |
| 2022 | IEEE IROS   | [**Cfp-slam: A real-time visual slam based on coarse-to-fine probability in dynamic environments**](https://ieeexplore.ieee.org/document/9981826)                                            |  | YOLOv5 & static probability & miss detection compensation |
| 2023 | IEEE T-RO   | [**Dynam-SLAM: An Accurate, Robust Stereo Visual-Inertial SLAM Method in Dynamic Environments**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9866888)                                 | —                                                                                                                            | Scene flow → rigid flow        |
| 2023 | IEEE TIM  | [**SG-SLAM: A Real-Time RGB-D Visual SLAM Toward Dynamic Scenes With Semantic and Geometric Information**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9978699)                                | [![GitHub](https://img.shields.io/badge/GitHub--SG-SLAM-black?logo=github)](https://github.com/silencht/SG-SLAM)              | semantic map & optical flow & detection        |
| 2024 | IEEE T-ITS  | [**RSO-SLAM: A Robust Semantic Visual SLAM With Optical Flow in Complex Dynamic Environments**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10542573)                                 | —                                                                                                                            | YOLOv5 & optical flow          |
| 2024 | IEEE TIM    | [**CD-SLAM: A Real-Time Stereo Visual–Inertial SLAM for Complex Dynamic Environments With Semantic and Geometric Information**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10521603) | —                                                                                                                            | YOLOv5 & scene flow            |
| 2024 | IEEE RA-L   | [**DFS-SLAM: A Visual SLAM Algorithm for Deep Fusion of Semantic Information**](https://ieeexplore.ieee.org/document/10753049)                                                                     | —                                                                                                                            | mask R-CNN & static point optimization         |
| 2025 | arXiv       | [**VAR-SLAM: Visual Adaptive and Robust SLAM for Dynamic Environments**](https://arxiv.org/html/2510.16205v1)                                                                                      | [![GitHub](https://img.shields.io/badge/GitHub-VAR--SLAM-black?logo=github)](https://github.com/iit-DLSLab/VAR-SLAM)         | YOLOv4 & Barron loss           |
| 2025 | IEEE RA-L   | [**DDN-SLAM: Real-Time Dense Dynamic Neural Implicit SLAM**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10904342)                                                                    | [![GitHub](https://img.shields.io/badge/GitHub-DDN--SLAM-black?logo=github)](https://github.com/DrLi-Ming/DDN-SLAM)          | YOLOv5 & optical flow          |
| 2025 | IEEE IROS   | [**NGD-SLAM: Towards Real-Time Dynamic SLAM without GPU**](https://arxiv.org/pdf/2405.07392)                                                                  | [![GitHub](https://img.shields.io/badge/GitHub-NGD--SLAM-black?logo=github)](https://github.com/yuhaozhang7/NGD-SLAM)  | YOLO & maks propagation & optical flow          |
| 2026 | ISPRS IJGI  | [**TAS-SLAM: A Visual SLAM System for Complex Dynamic Environments Integrating Instance-Level Motion Classification and Temporally Adaptive Super-Pixel Segmentation**](https://www.mdpi.com/2220-9964/15/1/7)                                                                   |   —       |      motion classification & segmentation     |

--- 

## 🧠 Helpful paper 

| Year | Venue | Paper Title | Repository | Description |
|------|------------|-------|------|-------------|
| 2015 | IEEE ICCV | **[FlowNet: Learning Optical Flow with Convolutional Networks](https://arxiv.org/abs/1504.06852)** | [![GitHub](https://img.shields.io/badge/GitHub-flownet-black?logo=github)](https://github.com/lmb-freiburg/flownet2) | Optical flow detection by DL |
| 2020 | IEEE ICRA | **[FlowFusion: Dynamic Dense RGB-D SLAM Based on Optical Flow](https://arxiv.org/pdf/2003.05102)** | — | Optical flow, Scene flow & feature update |
| 2025 | IEEE ICCV | **[Back on Track: Bundle Adjustment for Dynamic Scene Reconstruction](https://arxiv.org/abs/2504.14516)** | [![GitHub](https://img.shields.io/badge/GitHub-BA--dynamic-black?logo=github)](https://github.com/wrchen530/batrack) | Reconstruction with dynamic objects |

---

[![GitHub](https://img.shields.io/badge/GitHub-Dynamic-black?logo=github)]() 


---
