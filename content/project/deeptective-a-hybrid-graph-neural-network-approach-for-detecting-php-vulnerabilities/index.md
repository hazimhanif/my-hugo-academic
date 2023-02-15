---
title: "DeepTective: A Hybrid Graph Neural Network Approach for Detecting PHP
  Vulnerabilities"
subtitle: ﻿ IEEE Conference on Dependable and Secure Computing (DSC) 2022
date: 2022-01-03T18:00:08.091Z
summary: >-
  Full paper:\

  **IEEE Conference on Dependable and Secure Computing (DSC) 2022**




  Poster version:\

  **Proceedings of the 36th Annual ACM Symposium on Applied Computing (ACM SAC) 2021**
draft: false
featured: false
authors:
  - Rishi Rabheru
  - Hazim Hanif
  - Sergio Maffeis
tags:
  - vuldet
links:
  - url: https://ieeexplore.ieee.org/abstract/document/9888816
    name: Article
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
---
This paper presents DeepTective, a deep learning-based approach to detect vulnerabilities in PHP source code. Our approach implements a novel hybrid technique that combines Gated Recurrent Units and Graph Convolutional Networks to detect SQLi, XSS and OSCI vulnerabilities leveraging both syntactic and semantic information. We evaluate DeepTective and compare it to the state of the art on an established synthetic dataset and on a novel real-world dataset collected from GitHub. Experimental results show that DeepTective outperformed other solutions, including recent machine learning-based vulnerability detection approaches, on both datasets. The gap is noticeable on the synthetic dataset, where our approach achieves very high classification performance, but grows even wider on the realistic dataset, where most existing tools fail to transfer their detection ability, whereas DeepTective achieves an F1 score of 88.12%. We validate our approach in the wild by discovering 4 novel vulnerabilities in established WordPress plugins.