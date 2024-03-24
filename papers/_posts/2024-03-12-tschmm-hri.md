---
layout: paper
title: "Transition State Clustering for Interaction Segmentation and Learning"
year: 2024
shortref:
shorttitle: 
nickname: tschmm-hri
journal: "ACM/IEEE International Conference on Human-Robot Interaction (HRI) - Late Breaking Report"
volume:
issue:
pages:
authors: "Hahne, F., Prasad, V., Kshirsagar, A., Koert, D., Stock-Homburg, R.M., Peters, J., Chalvatzaki, G."
image: handover-bihsmm-hri.jpg
pdf: 2024-03-12-tschmm-hri.pdf
pdflink: 
fulltext:
pubtype: workshop
github:
pmid:  
pmcid:
f1000:
figshare:
doi: 10.1145/3610978.3640738 
category: papers
published: true
tags: [Hidden Markov Models, Human-Robot Interaction, Learning from Demonstrations]
---
{% include JB/setup %}

# Abstract
Hidden Markov Models with an underlying Mixture of Gaussian structure have proven effective in learning Human-Robot Interactions from demonstrations for various interactive tasks via Gaussian Mixture Regression. However, a mismatch occurs when segmenting the interaction using only the observed state of the human compared to the joint state of the human and the robot. To enhance this underlying segmentation and subsequently the predictive abilities of such Gaussian Mixture-based approaches, we take a hierarchical approach by learning an additional mixture distribution on the states at the transition boundary. This helps prevent misclassifications that usually occur in such states. We find that our framework improves the performance of the underlying Gaussian Mixture-based approach, which we evaluate on various interactive tasks such as handshaking and fistbumps.