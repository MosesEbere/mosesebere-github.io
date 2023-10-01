---
title: " Lane Detection and Distance Estimation using a Monocular Camera"
date: 2023-10-01T22:40:54.727Z
summary: C﻿omputer Vision Project
draft: false
featured: false
authors:
  - Moses Ebere
  - Biram Bawo
tags:
  - ComputerVision
links:
  - name: Code
    icon_pack: fas
    icon: code
    url: https://github.com/MosesEbere/Lane_Detection_and_Distance_Estimation
  - name: Report
    icon_pack: fas
    icon: book
    url: https://drive.google.com/file/d/1lNm1oxBGxwG6Bx87OkI1JYe1Zfjsw9r6/view?usp=sharing
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
  caption: Detected Lanes
---
The motivation behind this project was to develop fast and robust algorithms for lane detection and distance estimation using a monocular camera onboard a moving vehicle. The algorithms were developed (using Python's OpenCV and other libraries) to run on edge devices like microcontrollers such that minimal computational power was required.

F﻿or the implementation details,  a scene-geometry-based algorithm was developed for distance estimation while Haar Features and Hough transform were used for object and lane detection. Additionally, simple data science techniques were used in the detection pipeline to eliminate outliers. Finally, the developed solution was tested on make-shift lanes and some road datasets (such as the KITTI dataset) before deploying on a Raspberry Pi.

T﻿his work was completed as a term project for the computer vision course during my time at Sabanci University.