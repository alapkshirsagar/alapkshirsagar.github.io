---
layout: paper
title: "Timing-Specified Controllers with Feedback for Human-Robot Handovers"
year: 2022
shortref: "Kshirsagar et al. RO-MAN 2022"
shorttitle: 
nickname: timinghandovers-roman
journal: "IEEE International Conference on Robot and Human Interactive Communication (RO-MAN)"
volume:
issue:
pages:
authors: "*Kshirsagar, A., *Ravi R. K., Kress-Gazit, H., & Hoffman, G."
image: timinghandovers-roman.png
pdf: 2022-09-30-timinghandovers-roman.pdf
pdflink:
fulltext:  
pubtype: conference
github:
pmid:  
pmcid:
f1000:
figshare:
doi: 10.1109/RO-MAN53752.2022.9900856
category: papers
published: true
tags: [handovers, user-experience, timing]
---
{% include JB/setup %}

# Abstract

We develop and evaluate two human-robot handover controllers that allow end-users to specify timing parameters for the robot reach motion, and that provide feedback if the robot cannot satisfy those constraints. End-user tuning with feedback is a useful controller feature in settings where robots have to be re-programmed for varying task requirements but end-users do not have programming knowledge. The two controllers we propose are both receding-horizon controllers that differ in their objective function, and their user specified parameters, and subsequently their user-interface: One controller uses a minimum cumulative jerk (MCJ) objective function, and the other a minimum cumulative error (MCE) objective function. We implemented the controllers on a collaborative robot and conducted two controlled experiments to compare the user experience and performance of these controllers vis-à-vis a baseline proportional velocity (PV) controller. In each experiment, participants (n = 30) interactively tuned the controller parameters, and collaborated with a robot to perform a time-constrained repetitive task. We found that the timing controller with the MCE implementation can provide a better user experience, both while setting the parameters (p =0.011) and performing the handovers with the robot (p < 0.001), and fewer failures (p =0.016) compared to the PV controller, however the MCJ implementation did not provide better user experience compared to the PV controller. The MCJ controller also resulted in more failures than the PV controller. These results could inform the design of usable and effective end-user configurable controllers for human-robot interaction.
