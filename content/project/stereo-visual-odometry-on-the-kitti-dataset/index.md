---
title: Stereo Visual Odometry on the KITTI Dataset
date: 2024-02-17T20:53:01.387Z
summary: V﻿isual Odometry Project
draft: false
featured: true
authors:
  - Moses Chuka Ebere
  - Joseph Oloruntoba Adeola
tags:
  - Computer Vision
links:
  - name: Code
    icon: code
    icon_pack: fas
    url: https://github.com/AdeolaJoseph/Stereo-Visual-Odometry
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
  caption: Trajectory Evaluation
---
**Project Overview**: In our endeavor, we, a team of four robotics master's students, tackled the challenge of implementing a 3D-2D stereo visual odometry algorithm for road vehicles using the renowned KITTI dataset. This project aimed at refining vehicle localization by leveraging stereo image pairs to estimate the vehicle's trajectory with high precision, a fundamental aspect of autonomous vehicle navigation.

\
**Innovative Contributions**:

* Developed a comprehensive pipeline for feature detection, matching, and motion estimation, utilizing PyTorch for structured data loading and OpenCV for computer vision tasks (such as SIFT, RANSAC, PnP, etc.). 
* Evaluated the estimated trajectories using standard VO and SLAM toolboxes such as evo and rpg trajectory evaluation
* Achieved remarkable accuracy in trajectory estimation against ground truth data, demonstrating the effectiveness of our approach without the need for advanced refinement strategies.

**Technical and Research Impact**: Our project contributes significantly to the field of visual odometry, showcasing the potential of stereo image processing in improving autonomous vehicle localization. By achieving outstanding results on the KITTI dataset, we've highlighted the robustness of our algorithm in various driving scenarios.\
\
**Personal Contributions and Skills Development**: I played a crucial role in algorithm development, pipeline construction, and performance evaluation. This project has immensely enhanced my skills in computer vision and collaborative software development, preparing me for future challenges in robotics and autonomous systems.