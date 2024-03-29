---
title: PQLM - Multilingual Decentralized Portable Quantum Language Model
date: 2022-11-07T18:40:34.379Z
draft: false
featured: false
tags:
  - Speech Processing
links:
  - url: https://ieeexplore.ieee.org/abstract/document/10095215
    name: Paper Link
image:
  filename: model.jpeg
  focal_point: Smart
  preview_only: false
---
With careful manipulation, malicious agents can reverse engineer private information encoded in pre-trained language models. Security concerns motivate the development of quantum pre-training. In this work, we propose a highly portable quantum language model (PQLM) that can easily transmit information to downstream tasks on classical machines. The framework consists of a cloud PQLM built with random Variational Quantum Classifiers (VQC) and local models for downstream applications. We demonstrate the ad hoc portability of the quantum model by extracting only the word embeddings and effectively applying them to downstream tasks on classical machines. Our PQLM exhibits comparable performance to its classical counterpart on both intrinsic evaluation (loss, perplexity) and extrinsic evaluation (multilingual sentiment analysis accuracy) metrics. We also perform ablation studies on the factors affecting PQLM performance to analyze model stability. Our work establishes a theoretical foundation for a portable quantum pre-trained language model that could be trained on private data and made available for public use with privacy protection guarantees.
