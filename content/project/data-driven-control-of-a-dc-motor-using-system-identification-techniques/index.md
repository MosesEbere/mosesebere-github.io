---
title: Data-Driven Control of a DC Motor Using System Identification Techniques
date: 2023-09-28T14:08:31.338Z
summary: S﻿ystem Identification Project
draft: false
featured: false
authors:
  - Moses Ebere
tags:
  - Control
links:
  - url: https://drive.google.com/file/d/1esJOlisD_2k7si9GXBIEib8wpJPTJlW5/view?usp=sharing
    name: Report
    icon_pack: fas
    icon: book
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
  caption: Data-Driven Control Cycle
---
This project is a formal implementation of the 2018 IEEE conference paper by Ye Naung et al. titled, “Implementation of Data-Driven Control System of DC Motor by Using System Identification Process.” The contribution made here is the more exhaustive approach to tackling the research problem, which is, “How do we derive a control law that sufficiently controls the motor when the plant model is not available, all without making use of any hardware?”. Additionally, the concept of persistent excitation was explored briefly by developing a pseudo-random binary input signal for the data acquisition process. In the system identification section, a more broadened approach was taken to ascertain the reasons behind the decision to focus on transfer function models. For a balanced treatment of the topic, a NARX neural network was developed, albeit without the desired results. Finally, two controllers were designed for the DC motor. A PID controller was tuned using the PID Tuner App in MATLAB. This offered a certain level of robustness as a controlled system could properly accommodate external loads on the DC motor that are not classical inputs. Also, an LQ optimal controller coupled with an online recursive least squares algorithm was developed. The upshot of this paper is the validation that a properly identified system model can be used for myriads of applications - in this case, a control application.
