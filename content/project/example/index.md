---
slides: example
url_pdf: ""
summary: SLAM Project
authors:
  - Moses Ebere
  - Joseph Adeola
  - Preeti Verma
url_video: ""
date: 2023-09-29T14:36:18.102Z
external_link: ""
url_slides: ""
title: Pose-based EKF SLAM using ICP for Scan Registration
tags:
  - Robotics
links:
  - url: https://drive.google.com/file/d/1PEf_F3UzkBr-r8IKw35gX7s7DPliBYtB/view?usp=sharing
    name: Video
    icon_pack: fab
    icon: video
  - icon: file-powerpoint
    icon_pack: fab
    name: Slides
    url: https://drive.google.com/file/d/1JyMfuOR27wxJiWWq6XvO4kKM0-gFEU43/view?usp=sharing
  - name: Report
    icon_pack: fab
    icon: book
    url: https://drive.google.com/file/d/1oSkCsCm-WVmKDD7IK5GAbs2VEl246Cdo/view?usp=sharing
image:
  caption: SLAM
  focal_point: Smart
  filename: featured.jpg
url_code: ""
---
A comprehensive ROS-based project that involved developing and implementing a pose-based SLAM algorithm for the robot (in simulation and in the real world) where the iterative closest point (ICP) algorithm was used for registering LiDAR scans. By fusing the registration outcome with data from the robot’s IMU, the robot’s pose was updated in a timely manner. Additionally, we developed an algorithmic method of constraining the size of the state vector while maintaining the fidelity of the robot’s entire trajectory.



T﻿he aforementioned algorithms were first implemented and evaluated extensively in different Stonefish simulation environments to verify their robustness. Finally, the overall SLAM pipeline was deployed on the actual hardware (alongside perception, planning, exploration, and manipulation modules) for fully autonomous pick-transport-and-place applications.