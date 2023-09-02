---
layout: paper
title: "Design Optimization and Motion Dynamics of Mobility System for Mars Rover"
project: BTP
year: 2014
shortref: "Kshirsagar BTech 2014"
shorttitle: 
nickname: bachelors-thesis
journal: "Bachelor's Thesis, IIT Bombay"
volume:
issue:
pages:
authors: "Kshirsagar, A."
image: rockerbogie.png
pdf: 2014-05-07-btech-dissertation.pdf
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
tags: [design-optimization, rockerbogie, rover]
---
{% include JB/setup %}

# Abstract
Planetary exploration rovers offer promising alternatives for conducting in-situ experiments on earth’s neighbour planet -Mars. Several configurations have been suggested for the mobility system of such rovers, some of which have been successfully tested in past missions or are being implemented in the upcoming missions. Considering the huge costs of such exploration missions, it becomes necessary to design an optimal mobility system configuration to meet the mission goals. Furthermore given the costs and efforts of building test-beds for evaluating the performance of mobility system and on-board control software, it is also important to develop simulation tools to serve the purpose. The first half of this thesis focuses on obtaining an optimal design configuration of mobility system for mars rover. Various configurations of suspension systems were studied and certain performance metrics were devised to compare their performance. After the preliminary analysis, six-wheel rocker bogie suspension was determined to be most suitable amongst the evaluated configurations. Two performance metrics were considered in the objective funtion for design optimization viz. Power Consumption and Effective Ground Pressure. Geometric trafficability and load equalization conditions were evaluated to obtain the constraints on design parameters. Analytical expression for driving power was obtained using an established wheel-soil interaction model. The second half of this thesis focuses on development of motion dynamics simulation model for the rocker-bogie suspension system. More recently, researchers have proposed the idea of using reconfigurable wheels, which would be able to change their shape according to the terrain, to improve rover’s performance. One of the major challenges in implementation of such wheels is their control and autonomy. To avoid complex on-board calculations, the method of using look-up table for autonomously changing the wheel dimensions is proposed in this thesis. For obtaining this look-up table, a physics based motion dynamics simulation model was developed, incorporating the wheel-soil contact mechanics, drive motor characteristics and motion dynamics of the rocker bogie suspension system. This model was implemented in MATLAB and the simulated motion of rocker bogie system was shown for some test cases. This simulated motion of rocker bogie was found to be in conformance with the ground profile. Another important performance metric called as ’Slip Ratio’ was evaluated through the motion simulations. Finally, a lookup table for autonomous shape changing wheels was developed for certain terrain characteristics.