---
title: Task-Priority Redundancy Resolution Algorithm for a Mobile-base
  Manipulator Robot
date: 2023-09-29T16:03:44.825Z
summary: R﻿obot Manipulation/Intervention Project
tags:
  - Robotics
  - Manipulation
external_link: ""
aliases:
  - /project/task-priority-redundancy-resolution-algorithm-for-a-mobile-base-manipulator-robot
links:
  - icon: video
    icon_pack: fas
    name: Move-to-point
    url: https://drive.google.com/file/d/1kn2_gko-IFSkljblYQMjXANdpQjNa0rN/view?usp=sharing
  - icon: video
    icon_pack: fas
    name: Pick-and-place
    url: https://drive.google.com/file/d/1KHs2diTsSIVnFagZMXMcA8l_p_WiexcS/view?usp=sharing
  - icon: video
    icon_pack: fas
    name: Pick-transport-and-place
    url: https://drive.google.com/file/d/1K6A4IXmg--vPBryF4WTcQLSJuJ77wXlQ/view?usp=sharing
  - icon: video
    icon_pack: fas
    name: Pick-transport-and-place with Visual Feedback
    url: https://drive.google.com/file/d/1lAg9mKXbvocwgNylMy-xydm41HCEizhB/view?usp=sharing
  - icon: file-powerpoint
    icon_pack: fas
    name: Slides
    url: https://drive.google.com/file/d/1GWa_pOjubxcN2Xha_cPQEmdidF82-esj/view?usp=sharing
  - icon: book
    icon_pack: fas
    name: Report
    url: https://drive.google.com/file/d/1zYYLAgOqRJE_yjYbQvPuM748Q1R_CwFf/view?usp=sharing
image:
  caption: Robot Manipulation
  focal_point: Smart
  filename: control-system-diagram2.drawio
---
The goal of this project was to explore the exciting discipline of mobile manipulation in robotics.\
To accomplish this, we completed the following:\
• Fitted a 4 DOF manipulator (uFactory uArm Swift Pro) on a differential-drive robot (Kobuki Turtlebot 2).\
• Modeled the system with URDF on the ROS ecosystem.\
• Derived the forward and inverse kinematics for the entire system, and coded the kinematics pipeline in Python.\
• Using the kinematics of the robot, we implemented the Task-priority Redundancy Resolution algorithm that leverages ROS communication mechanisms.\
• Simulated the kinematic control of the mobile-base manipulator in the Stonefish Simulator using different scenarios.\
• Once the simulation results were satisfactory, we implemented the control architecture on the hardware and deployed the robot (using perception, localization, mapping, planning, and exploration modules we also developed) for autonomous pick-transport-and-place applications.
