---
layout: paper
title: "Robot Controllers, Gaze Behaviors and Human Motion Datasets for Object Handovers"
year: 2022
shortref: "Kshirsagar PhD 2022"
shorttitle: 
nickname: phd-thesis
journal: "Ph.D. Thesis, Cornell University"
volume:
issue:
pages:
authors: "Kshirsagar, A."
image: phd-thesis.png
pdf: 2022-08-01-phd-dissertation.pdf
pdflink:
fulltext:  
pubtype: thesis
github:
pmid:  
pmcid:
f1000:
figshare:
doi: 10.7298/v8sh-bn18
category: papers
published: true
tags: [human robot interaction]
---
{% include JB/setup %}

# Abstract

We investigate the collaborative task of object handovers between a human and a robot. Object handover is one of the most common skills required for a collaborative or an assistive robot. Tasks such as surgical assistance, housekeeping, rehabilitation assistance, and collaborative assembly require a robot to give objects to a human (robot-to-human handover) and take objects from a human (human-to-robot handover). First, we design robot controllers for previously unexplored human-robot handover scenarios involving a: robot behavior specification by end-users, b: flexibility to change handover strategies, c: unknown robot dynamics, and d: human-like bi-manual handovers. For "a", we propose two receding horizon controllers that utilize timing parameters and provide failure feedback to the user. We find that these two controllers offer contrasting user experience and task performance, vis-à-vis a baseline controller, in an industrial human-robot collaborative task. For "b", we present a controller that uses automated synthesis from specifications in Signal Temporal Logic, and illustrate the flexibility of our approach by reproducing, in a simulation environment, existing human-robot handover strategies found in the literature. For "c", we evaluate the potential of a reinforcement learning method, Guided Policy Search (GPS), both in a simulation environment and on a physical robot arm. Our evaluations provide new insights into the capabilities and limitations of GPS. For "d", we evaluate the potential of an imitation learning technique, Bayesian Interaction Primitives (BIPs), and discuss two adaptations of BIPs for generating humanlike bimanual reaching motions. Second, we investigate robot gazes in human-to-robot handovers. We design human-inspired robot gaze behaviors by analyzing the receiver's gaze patterns in human-to-human handovers. We conduct four user studies with two robot platforms to evaluate human preferences for the robot receiver's gaze behavior in handovers. Our studies reveal that the most preferred robot receiver's gaze behavior in a human-to-robot handover consists of a combination of face-oriented gaze for social engagement and task-oriented gaze directed at the giver's hand. Third, we develop two datasets of human-to-human handovers: bimanual handovers, and multiple sequential handovers in a shelving task. These datasets could help build human motion models and robot controllers for those scenarios of human-robot handovers.