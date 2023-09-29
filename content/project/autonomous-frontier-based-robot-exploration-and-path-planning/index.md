---
title: " Autonomous Frontier-Based Robot Exploration and Path Planning"
date: 2023-09-29T15:08:31.338Z
summary: R﻿obotics Planning Project
draft: false
featured: false
authors:
  - Moses Ebere
  - Joseph Adeola
  - Preeti Verma
tags:
  - Robotics
links:
  - name: Follow
    icon_pack: fab
    icon: twitter
    url: https://twitter.com/mosescebere
image:
  filename: path_plan.png
  focal_point: Smart
  preview_only: false
  caption: Autonomous Exploration
---
The goal was to design an autonomous robot exploration algorithm for a Kobuki Turtlebot 2 robot.

The developed ROS-based architecture integrates key modules, including a frontier-based exploration algorithm that combines Multiple Rapidly-exploring Random Trees (MRRTs), Mean Shift clustering, and a cost function in determining the Next-Best View (NBV) or frontier for the robot to explore. With a high-resolution 2D Lidar, the robot is able to build a map of its environment using the Octomap ROS stack. The path planning module utilizes this map together with the Open Motion Planning Library (OMPL) and a customized Dubins state space to generate RRT-start-based collision-free paths that fulfill the dynamic constraints of the differential-drive robot. Optimization techniques, such as comprehensive cost function and post-processing methodologies, enhance the quality of the generated path. The low-level controller, employing the Dynamic-Window Approach ensures smooth navigation and real-time obstacle avoidance for the robot. 

Subsequently, the software architecture was sufficiently evaluated in both Gazebo and Stonefish simulation environments before it was deployed on the real hardware. The results demonstrate improved exploration capabilities and collision-free path planning in dynamic environments.

\
As a final step, this project was integrated with other project modules - SLAM, perception, and manipulation - in fully autonomous pick-transport-and-place applications.