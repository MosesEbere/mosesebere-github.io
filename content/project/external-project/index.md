---
title: Task-Priority Redundancy Resolution Algorithm for a Mobile-base
  Manipulator Robot
date: 2023-09-29T16:03:44.825Z
summary: R﻿obot Manipulation/Intervention Project
tags:
  - Robotics
external_link: ""
links:
  - url: https://twitter.com/mosescebere
    name: Follow
    icon_pack: fab
    icon: twitter
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
