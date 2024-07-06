---
layout: paper
title: "MoVEInt: Mixture of Variational Experts for Learning Human–Robot Interactions From Demonstrations"
project: LfDHRI
year: 2024
shortref: "Prasad et al. RAL 2024"
shorttitle: "Mixture of Variational Experts for Learning HRI From Demonstrations"
nickname: moveint-hri
journal: "IEEE Robotics and Automation Letters, and IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)"
volume: 9
issue: 7
pages: 6043-6050
authors: "Prasad, V., Kshirsagar, A., Koert, D., Stock-Homburg, R., Peters, J., & Chalvatzaki, G."
image: moveint-ral.png
pdf: 2024-05-01-moveint-ral.pdf
pdflink:
fulltext: https://ieeexplore.ieee.org/abstract/document/10517380  
pubtype: journal
github: https://github.com/souljaboy764/rmdn_hri
pmid:  
pmcid:
f1000:
figshare:
doi: 10.1109/LRA.2024.3396074
category: papers
published: true
tags: [physical-human-robot-interaction, imitation-learning, learning-from-demonstration]
---
{% include JB/setup %}

# Abstract

Shared dynamics models are important for capturing the complexity and variability inherent in Human-Robot Interaction (HRI). Therefore, learning such shared dynamics models can enhance coordination and adaptability to enable successful reactive interactions with a human partner. In this work, we propose a novel approach for learning a shared latent space representation for HRIs from demonstrations in a Mixture of Experts fashion for reactively generating robot actions from human observations. We train a Variational Autoencoder (VAE) to learn robot motions regularized using an informative latent space prior that captures the multimodality of the human observations via a Mixture Density Network (MDN). We show how our formulation derives from a Gaussian Mixture Regression formulation that is typically used approaches for learning HRI from demonstrations such as using an HMM/GMM for learning a joint distribution over the actions of the human and the robot. We further incorporate an additional regularization to prevent “mode collapse”, a common phenomenon when using latent space mixture models with VAEs. We find that our approach of using an informative MDN prior from human observations for a VAE generates more accurate robot motions compared to previous HMM-based or recurrent approaches of learning shared latent representations, which we validate on various HRI datasets involving interactions such as handshakes, fistbumps, waving, and handovers. Further experiments in a real-world human-to-robot handover scenario show the efficacy of our approach for generating successful interactions with four different human interaction partners.
