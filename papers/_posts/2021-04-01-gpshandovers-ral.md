---
layout: paper
title: "Evaluating Guided Policy Search for Human-Robot Handovers"
year: 2021
shortref: "Kshirsagar et al. RAL 2021"
shorttitle: "Evaluating Guided Policy Search for Human-Robot Handovers"
nickname: gpshandovers-ral
journal: "IEEE Robotics and Automation Letters"
volume: 6
issue: 2
pages: 3933-3940
authors: "Kshirsagar, A., *Hoffman, G., & *Biess, A."
image: handover-gps-ral.png
pdf: 2021-04-01-gpshandovers-ral.pdf
pdflink:
fulltext:  
pubtype: journal
github:
pmid:  
pmcid:
f1000:
figshare:
doi: 10.1109/LRA.2021.3067299
category: papers
published: true
tags: [handovers, reinforcement learning]
---
{% include JB/setup %}

# Abstract

We evaluate the potential of Guided Policy Search
(GPS), a model-based reinforcement learning (RL) method, to train
a robot controller for human-robot object handovers. Handovers
are a key competency for collaborative robots and GPS could be a
promising approach for this task, as it is data efficient and does
not require prior knowledge of the robot and environment dynamics. However, existing uses of GPS did not consider important
aspects of human-robot handovers, namely large spatial variations
in reach locations, moving targets, and generalizing over mass
changes induced by the object being handed over. In this work, we
formulate the reach phase of handovers as an RL problem and then
train a collaborative robot arm in a simulation environment. Our
results indicate that GPS is limited in the spatial generalizability
over variations in the target location, but that this issue can be
mitigated with the addition of local controllers trained over target
locations in the high error regions. Moreover, learned policies
generalize well over a large range of end-effector masses. Moving
targets can be reached with comparable errors using a global policy
trained on static targets, but this results in inefficient, high-torque, trajectories. Training on moving targets improves trajectories, but
results in worse worst-case performance. Initial results suggest
that lower-dimensional state representations are beneficial for GPS
performance in handovers.
