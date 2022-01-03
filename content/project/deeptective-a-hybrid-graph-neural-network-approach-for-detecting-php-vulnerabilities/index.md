---
title: "DeepTective: A Hybrid Graph Neural Network Approach for Detecting PHP
  Vulnerabilities"
subtitle: Experimental paper
date: 2022-01-03T18:00:08.091Z
summary: "**Proceedings of the 36th Annual ACM Symposium on Applied Computing
  (ACM SAC) 2021**"
draft: false
featured: false
authors:
  - Rishi Rabheru
  - Hazim Hanif
  - Sergio Maffeis
tags:
  - vuldet
links:
  - url: https://arxiv.org/abs/2012.08835
    name: Article
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
---
This paper presents DeepTective, a deep learning approach to detect vulnerabilities in PHP source code. Our approach implements a novel hybrid technique that combines Gated Recurrent Units and Graph Convolutional Networks to detect SQLi, XSS and OSCI vulnerabilities leveraging both syntactic and semantic information. We evaluate DeepTective and compare it to the state of the art on an established synthetic dataset and on a novel real-world dataset collected from GitHub. Experimental results show that DeepTective achieves near perfect classification on the synthetic dataset, and an F1 score of 88.12% on the realistic dataset, outperforming related approaches. We validate DeepTective in the wild by discovering 4 novel vulnerabilities in established WordPress plugins.