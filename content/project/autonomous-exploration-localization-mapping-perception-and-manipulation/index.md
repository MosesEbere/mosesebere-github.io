---
title: Autonomous Exploration, Localization, Mapping, Perception, and Manipulation
date: 2023-10-01T20:06:40.943Z
summary: A﻿utonomous Robot Project
draft: false
featured: false
authors:
  - Moses Ebere
  - Joseph Adeola
  - Preeti Verma
tags:
  - Robotics
links:
  - icon: video
    icon_pack: fas
    name: Simulation Implementation
    url: https://drive.google.com/file/d/1LZKQDQFDvICbNO9TPoZ9PdlU2wQQhSYe/view?usp=sharing
  - icon: video
    icon_pack: fas
    name: Real Robot Implementation 
    url: https://drive.google.com/file/d/1V2GTVkTomQQViEsOUmajFos93Ll_3ju4/view?usp=sharing
image:
  filename: Robot_Manipulation.gif
  focal_point: Smart
  preview_only: false
<!-- filename: featured.jpg -->
---
T﻿he idea behind this project was to transform a differential drive robot equipped with a 4-DOF robotic arm into an autonomous explorer and mobile manipulator.  More specifically, the goal was to develop a series of algorithms for the aforementioned robot to autonomously explore its environment while localizing itself, find objects of interest using its onboard sensors, and manipulate them - i.e., pick, transport, and place the objects in set locations. 

T﻿his project was subdivided into 4 sub-projects - frontier-based exploration and path planning, Pose-based EKF SLAM with Scan Matching, ArUco Marker Detection, and Task-priority Redundancy Resolution for a Mobile-base Manipulator. Each of these sub-projects is explained in other pages. 

I﻿n this integration project, modules from the above sub-projects were combined into a unified behavior-tree-based framework in the ROS ecosystem on the robot.
