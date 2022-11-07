---
title: End-to-End Lyrics Recognition with Self-supervised Learning
date: 2022-11-07T18:23:45.958Z
draft: false
featured: true
tags:
  - Speech Processing
image:
  filename: music_pipeline.jpeg
  focal_point: Smart
  preview_only: false
---
Lyrics recognition is an important task in music processing. Despite traditional algorithms such as the hybrid HMM- TDNN model achieving good performance, studies on ap- plying end-to-end models and self-supervised learning (SSL) are limited. In this paper, we first establish an end-to-end baseline for lyrics recognition and then explore the perfor- mance of SSL models on lyrics recognition task. We evaluate a variety of upstream SSL models with different training methods (masked reconstruction, masked prediction, autore- gressive reconstruction, and contrastive learning). Our end- to-end self-supervised models, evaluated on the DAMP music dataset, outperform the previous state-of-the-art (SOTA) sys- tem by 5.23% for the dev set and 2.4% for the test set even without a language model trained by a large corpus. More- over, we investigate the effect of background music on the performance of self-supervised learning models and conclude that the SSL models cannot extract features efficiently in the presence of background music. Finally, we study the out-of- domain generalization ability of the SSL features considering that those models were not trained on music datasets.