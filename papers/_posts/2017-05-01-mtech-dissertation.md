---
layout: paper
title: "iGPS Based Motion Control of a Robotic Manipulator using Robot Operating System"
project: MTP
year: 2017
shortref: "Kshirsagar MTech 2017"
shorttitle: 
nickname: masters-thesis
journal: "Master's Thesis, IIT Madras"
volume:
issue:
pages:
authors: "Kshirsagar, A."
image: ur5.jpg
pdf: 2017-05-01-mtech-dissertation.pdf
pdflink:
fulltext:  
pubtype: thesis
github:
pmid:  
pmcid:
f1000:
figshare:
doi:
category: papers
published: true
tags: [Robot Operating System, Indoor GPS, Robot Control]
---
{% include JB/setup %}

# Abstract

Robotic manipulators have become the key components of industrial automation. The accuracy of robotic manipulator’s end effector determines the quality of products and dictates versatility of the system. Usually, the motion of the end effector is estimated and controlled by using the encoder feedback only. But the resulting end effector trajectory is inaccurate due to link deformations, joint flexibilities, external vibrations, non-linearities of the gear mechanisms, manipulator dynamics etc. To overcome these effects, the use of external sensor for direct measurement of end effector’s position and orientation was proposed decades ago. Since then a lot of work has focussed on computer vision based end effector control. But vision feedback is difficult to incorporate into the control loop due to low sampling rate and delays. In this work, a new technology called iGPS is used to get accurate measurements of end effector’s position and orientation. Indoor-GPS or iGPS is a cutting edge metrology system which allows monitoring several sensors simultaneously and has accuracy up to ±0.1mm for 3D positions. Also the latency for the iGPS system is lower than other systems. Thus iGPS can be used for improving the accuracy of robotic manipulators. In recent years, Robot Operating System has revolutionized the software development process for novel robotics algorithms and applications. This open source framework facilitates modularity, customizability, extensions to multi-robot systems and global collaborations. Therefore, in this work ROS is chosen as the platform for establishing communication between different components of the system and developing software for iGPS feedback based robot motion control. Three different control structures are presented for including the iGPS feedback in the motion control system of a robotic manipulator. The motion control system consists of motion planner, joint controller and the joint states publisher. The first approach includes iGPS feedback before the motion planning stage. The second approach involves iGPS correction in the joint state trajectory and the third approach includes iGPS feedback in the joint control loop through the joint states publisher. The last two approaches require transformation from end-effector co-ordinates to joint states. These transformed joint states can be fused with the encoder data to reduce error and overcome difficulties arrising due to missing data. The use of Kalman Filter for fusion of multifrequency and delayed sensor data is described. The structures for iGPS feedback based robot motion control are implemented in the ROS framework and tested in a robot simulator ‘Gazebo’ and also on physical ‘Universal Robot-5’ manipulator. Results of conducted experiments show that the error in end-effector trajectory can be reduced to 25% using the iGPS feedback.