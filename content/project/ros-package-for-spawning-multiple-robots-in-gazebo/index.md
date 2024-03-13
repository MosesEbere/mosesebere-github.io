---
title: ROS Package for Spawning Multiple Robots in Gazebo
date: 2024-03-13T20:57:53.530Z
summary: M﻿ulti-robots ROS Package
draft: false
featured: false
authors:
  - Moses Chuka Ebere
  - Joseph Oloruntoba Adeola
tags:
  - Robotics
links:
  - icon: code
    icon_pack: fas
    name: code
    url: https://github.com/MosesEbere/gazebo_multi_robot_spawn
image:
  filename: three_lines_spawn_30.gif
  focal_point: Smart
  preview_only: false
---
In the last couple of months, I've had the opportunity to work on three multi-robot systems projects and one challenge I encountered in the early days was spawning any number of robots in a desired formation without having to rewrite cumbersome launch files all the time. Unable to find an open-source solution to this, My colleague (Joseph) and I wrote a lightweight ROS package to allow for seamless spawning of any number of robots in Gazebo, simply by altering a central configuration file. 

T﻿his is my first open-source ROS package, so I'm excited to share this with the robotics community as it significantly improved my workflow and allowed me to test my algorithms much more extensively.