---
title: "Twin-S: A Digital Twin for Skull-base Surgery"
date: 2022-11-23T20:50:03.608Z
draft: false
featured: false
categories:
  - Multimodal
links:
  - name: Paper Link
    url: https://arxiv.org/abs/2211.11863
image:
  filename: digital-twin.png
  focal_point: Smart
  preview_only: false
---
Purpose: Digital twins are virtual interactive models of the real world, exhibiting identical behavior and properties. In surgical applications, computational analysis from digital twins can be used, for example, to enhance situational awareness. Methods: We present a digital twin framework for skull-base surgeries, named Twin-S, which can be integrated within various image-guided interventions seamlessly. Twin-S combines high-precision optical tracking and real-time simulation. We rely on rigorous calibration routines to ensure that the digital twin representation precisely mimics all real-world processes. Twin-S models and tracks the critical components of skull-base surgery, including the surgical tool, patient anatomy, and surgical camera. Significantly, Twin-S updates and reflects real-world drilling of the anatomical model in frame rate. Results: We extensively evaluate the accuracy of Twin-S, which achieves an average 1.39 mm error during the drilling process. We further illustrate how segmentation masks derived from the continuously updated digital twin can augment the surgical microscope view in a mixed reality setting, where bone requiring ablation is highlighted to provide surgeons additional situational awareness. Conclusion: We present Twin-S, a digital twin environment for skull-base surgery. Twin-S tracks and updates the virtual model in real-time given measurements from modern tracking technologies. Future research on complementing optical tracking with higher-precision vision-based approaches may further increase the accuracy of Twin-S.