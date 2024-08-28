---
title: "Pose-based EKF SLAM using ICP for Scan Registration"
date: 2023-10-01T15:08:31.338Z
summary: SLAM Project
authors:
  - Moses Ebere
  - Joseph Adeola
  - Preeti Verma
external_link: ""
aliases:
  - /project/pose-based-ekf-slam/
tags:
  - Robotics
  - State Estimation/SLAM
links:
  - name: Code
    icon: code
    icon_pack: fas
    url: https://github.com/adeola-jo/Pose-Based-EKF-SLAM-ICP
  - icon: video
    icon_pack: fas
    name: Video
    url: https://drive.google.com/file/d/1PEf_F3UzkBr-r8IKw35gX7s7DPliBYtB/view?usp=sharing
  - icon: file-powerpoint
    icon_pack: fas
    name: Slides
    url: https://drive.google.com/file/d/1JyMfuOR27wxJiWWq6XvO4kKM0-gFEU43/view?usp=sharing
  - icon: book
    icon_pack: fas
    name: Report
    url: https://drive.google.com/file/d/1oSkCsCm-WVmKDD7IK5GAbs2VEl246Cdo/view?usp=sharing
image:
  filename: featured.gif
  focal_point: Smart
  preview_only: false
  caption: SLAM
<!-- filename: featured.jpg -->
---
A comprehensive ROS-based project that involved developing and implementing a pose-based SLAM algorithm for the robot (in simulation and in the real world) where the iterative closest point (ICP) algorithm was used for registering LiDAR scans. By fusing the registration outcome with data from the robot’s IMU, the robot’s pose was updated in a timely manner. Additionally, we developed an algorithmic method of constraining the size of the state vector while maintaining the fidelity of the robot’s entire trajectory.



T﻿he aforementioned algorithms were first implemented and evaluated extensively in different Stonefish simulation environments to verify their robustness. Finally, the overall SLAM pipeline was deployed on the actual hardware (alongside perception, planning, exploration, and manipulation modules) for fully autonomous pick-transport-and-place applications.
