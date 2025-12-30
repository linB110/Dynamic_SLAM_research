# ⭐ Dynamic Visual SLAM

A curated list of **Dynamic Visual SLAM** papers and resources, focusing on SLAM systems that robustly operate in **dynamic environments** with moving objects, non-rigid scenes, and scene changes.

This repository covers topics such as **motion segmentation, dynamic object handling, semantic SLAM, optical flow, scene flow, multi-view geometry, and learning-based approaches** for dynamic scenes.

If you find missing or ignored papers, feel free to **open issues or submit pull requests**.
Contributions of any kind are welcome!

If you find this repository useful, a ⭐ would be greatly appreciated 😊

---


## 🧭 Dynamic Visual SLAM

**Full SLAM systems designed for dynamic environments**

| Year | Venue | Paper Title                                                       | Repository | Tags   |
| ---- | ----- | ----------------------------------------------------------------- | ---------- | ------- |
| 2018 | IEEE RA-L | [**DynaSLAM: Tracking, Mapping and Inpainting in Dynamic Scenes**](https://arxiv.org/pdf/1806.05620) | [![GitHub Repo](https://img.shields.io/github/stars/BertaBescos/DynaSLAM?style=social)](https://github.com/BertaBescos/DynaSLAM) | Deep learning |
| 2021 | IEEE RA-L | [DynaSLAM II: Tightly-Coupled Multi-Object Tracking and SLAM](https://arxiv.org/pdf/2010.07820) | X | Dynamic object estimation |
| 2018 | IEEE IROS | [DS-SLAM: A Semantic Visual SLAM towards Dynamic Environments](https://arxiv.org/pdf/1809.08379) | https://github.com/ivipsourcecode/DS-SLAM | optical flow |
| 2021 | IEEE Access | [RDS-SLAM: Real-Time Dynamic SLAM Using Semantic Segmentation Methods](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9318990) | https://github.com/yubaoliu/RDS-SLAM | Semantic segmentation |
| 2020 | ISPRS IJGI | [DM-SLAM: A Feature-Based SLAM System for Rigid Dynamic Scenes](https://www.researchgate.net/publication/340330756_DM-SLAM_A_Feature-Based_SLAM_System_for_Rigid_Dynamic_Scenes) | x | segmentation & optical flow |
| 2018 | IEEE WACV | [Detect-SLAM: Making Object Detection and SLAM Mutually Beneficial](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8354219) | x | SSD & moving probability |
| 2020 | arsiv | [VDO-SLAM: A Visual Dynamic Object-aware SLAM System](https://arxiv.org/pdf/2005.11052) | https://github.com/halajun/VDO_SLAM | optical flow & moving factor |
| 2022 | IEEE Access | [Real-Time Dynamic SLAM Algorithm Based on Deep Learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9858152) | x | YOLOv5 & optical searcg |
| 2022 | IEEE RA-L | [RGB-D Inertial Odometry for a Resource-Restricted Robot in Dynamic Environments](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9830851) | https://github.com/HITSZ-NRSL/Dynamic-VINS | YOLOv3 & semantic segmentation |
| 2024 | IEEE T-ITS | [RSO-SLAM: A Robust Semantic Visual SLAM With Optical Flow in Complex Dynamic Environments](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10542573) | x | YOLOv5 & optical flow |
| 2025 | IEEE RA-L | [DDN-SLAM: Real Time Dense Dynamic Neural Implicit SLAM](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10904342) | https://github.com/DrLi-Ming/DDN-SLAM | YOLOv5 & optical flow |
| 2024 | IEEE TIM | [CD-SLAM: A Real-Time Stereo Visual–Inertial SLAM for Complex Dynamic Environments With Semantic and Geometric Information](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10521603) | x | YOLOv5 & scene flow |
| 20223 | IEEE T-RO | [Dynam-SLAM: An Accurate, Robust Stereo Visual-Inertial SLAM Method in Dynamic Environments](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9866888) | x | scene flow -> rigid flow |
| 2025 | arxiv | [VAR-SLAM: Visual Adaptive and Robust SLAM for Dynamic Environments](https://arxiv.org/html/2510.16205v1) | https://github.com/iit-DLSLab/VAR-SLAM | YOLOv4 & Barron's loss|
| ---- | ----- | ----------------------------------------------------------------- | ---------- | ------- |
| ---- | ----- | ----------------------------------------------------------------- | ---------- | ------- |

| Year | Venue       | Paper Title                                                                                                                                                                                        | Repository                                                                                                                   | Tags                           |
| ---- | ----------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- | ------------------------------ |
| 2018 | IEEE RA-L   | [**DynaSLAM: Tracking, Mapping and Inpainting in Dynamic Scenes**](https://arxiv.org/pdf/1806.05620)                                                                                               | [![GitHub](https://img.shields.io/badge/GitHub-DynaSLAM-black?logo=github)](https://github.com/BertaBescos/DynaSLAM)         | Deep learning                  |
| 2021 | IEEE RA-L   | [**DynaSLAM II: Tightly-Coupled Multi-Object Tracking and SLAM**](https://arxiv.org/pdf/2010.07820)                                                                                                | —                                                                                                                            | Dynamic object estimation      |
| 2018 | IEEE IROS   | [**DS-SLAM: A Semantic Visual SLAM towards Dynamic Environments**](https://arxiv.org/pdf/1809.08379)                                                                                               | [![GitHub](https://img.shields.io/badge/GitHub-DS--SLAM-black?logo=github)](https://github.com/ivipsourcecode/DS-SLAM)       | Optical flow                   |
| 2021 | IEEE Access | [**RDS-SLAM: Real-Time Dynamic SLAM Using Semantic Segmentation Methods**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9318990)                                                       | [![GitHub](https://img.shields.io/badge/GitHub-RDS--SLAM-black?logo=github)](https://github.com/yubaoliu/RDS-SLAM)           | Semantic segmentation          |
| 2020 | ISPRS IJGI  | [**DM-SLAM: A Feature-Based SLAM System for Rigid Dynamic Scenes**](https://www.researchgate.net/publication/340330756_DM-SLAM_A_Feature-Based_SLAM_System_for_Rigid_Dynamic_Scenes)               | —                                                                                                                            | Segmentation & optical flow    |
| 2018 | IEEE WACV   | [**Detect-SLAM: Making Object Detection and SLAM Mutually Beneficial**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8354219)                                                          | —                                                                                                                            | SSD & moving probability       |
| 2020 | arXiv       | [**VDO-SLAM: A Visual Dynamic Object-aware SLAM System**](https://arxiv.org/pdf/2005.11052)                                                                                                        | [![GitHub](https://img.shields.io/badge/GitHub-VDO--SLAM-black?logo=github)](https://github.com/halajun/VDO_SLAM)            | Optical flow & moving factor   |
| 2022 | IEEE Access | [**Real-Time Dynamic SLAM Algorithm Based on Deep Learning**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9858152)                                                                    | —                                                                                                                            | YOLOv5 & optical search        |
| 2022 | IEEE RA-L   | [**RGB-D Inertial Odometry for a Resource-Restricted Robot in Dynamic Environments**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9830851)                                            | [![GitHub](https://img.shields.io/badge/GitHub-Dynamic--VINS-black?logo=github)](https://github.com/HITSZ-NRSL/Dynamic-VINS) | YOLOv3 & semantic segmentation |
| 2024 | IEEE T-ITS  | [**RSO-SLAM: A Robust Semantic Visual SLAM With Optical Flow in Complex Dynamic Environments**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10542573)                                 | —                                                                                                                            | YOLOv5 & optical flow          |
| 2025 | IEEE RA-L   | [**DDN-SLAM: Real-Time Dense Dynamic Neural Implicit SLAM**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10904342)                                                                    | [![GitHub](https://img.shields.io/badge/GitHub-DDN--SLAM-black?logo=github)](https://github.com/DrLi-Ming/DDN-SLAM)          | YOLOv5 & optical flow          |
| 2024 | IEEE TIM    | [**CD-SLAM: A Real-Time Stereo Visual–Inertial SLAM for Complex Dynamic Environments With Semantic and Geometric Information**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10521603) | —                                                                                                                            | YOLOv5 & scene flow            |
| 2023 | IEEE T-RO   | [**Dynam-SLAM: An Accurate, Robust Stereo Visual-Inertial SLAM Method in Dynamic Environments**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9866888)                                 | —                                                                                                                            | Scene flow → rigid flow        |
| 2025 | arXiv       | [**VAR-SLAM: Visual Adaptive and Robust SLAM for Dynamic Environments**](https://arxiv.org/html/2510.16205v1)                                                                                      | [![GitHub](https://img.shields.io/badge/GitHub-VAR--SLAM-black?logo=github)](https://github.com/iit-DLSLab/VAR-SLAM)         | YOLOv4 & Barron loss           |


---
