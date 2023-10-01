---
title: " Integrated Machine Vision Application with the Stäubli TX60 Robot"
date: 2023-10-01T21:34:54.965Z
summary: I﻿ndustrial Robot Project
draft: false
featured: false
authors:
  - Moses Ebere
  - Joseph Adeola
  - Preeti Verma
tags:
  - Industrial Robots
links:
  - icon: video
    icon_pack: fas
    name: Video
    url: https://drive.google.com/file/d/1Qt3sHE5qjNmcZQxpsC_hMEyIe0jYCMcI/view?usp=sharing
  - icon: book
    icon_pack: fas
    name: Report
    url: https://drive.google.com/file/d/1uo5gHFy89dUKNRSunYBKvTdJQoX5jP0n/view?usp=sharing
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
  caption: Machine Vision with Manipulation
---
The motivation for this lab project was to explore the use of a vision system in a fruit sorting application. The designed solution involved the coupling of a perception and a manipulation system. The perception system was to be used to detect and locate good fruits, and then provide the industrial robot with the necessary information to pick and place them in a box or feed them into another machine for further processing. 

With this in mind, we implemented a Python-based perception system with the Staubli TX60 Robot. Leveraging a TCP socket connection, we successfully merged the perception system's capabilities for precise part detection with the TX60 robot's manipulation (coded using the VAL3 programming language). 

T﻿he manipulation aspect was developed using the SRS Stäubli suite and sufficiently tested in simulation before deploying on the hardware. The entire solution enabled the robot to efficiently pick and stack parts identified by the camera in pre-defined locations. This project helped us bridge the gap between vision systems and robotic control, and its success underscored our strong technical skills and problem-solving acumen in the realm of machine vision and robotics. 

Note: T﻿his project was completed as part of a series of laboratory sections in the robotics lab at the University of Girona.
