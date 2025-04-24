---
title: "Online test-time adaptation for better generalization of interatomic potentials to out-of-distribution data"
collection: publications
category: manuscripts
permalink: 'https://www.nature.com/articles/s41467-025-57101-4'
excerpt: '**Taoyong Cui**, Chenyu Tang, Dongzhan Zhou, Yuqiang Li, Xingao Gong, Wanli Ouyang, Mao Su & Shufei Zhang'
date: 2025-2-22
venue: 'Nature Communications 16.1 (2025): 1891'
paperurl: 'https://www.nature.com/articles/s41467-025-57101-4'


---
Machine learning interatomic potentials (MLIPs) enable more efficient molecular dynamics (MD) simulations with ab initio accuracy, which have been used in various domains of physical science. However, distribution shift between training and test data causes deterioration of the test performance of MLIPs, and even leads to collapse of MD simulations. In this work, we propose an online Test-time Adaptation Interatomic Potential (TAIP) framework to improve the generalization on test data. Specifically, we design a dual-level self-supervised learning approach that leverages global structure and atomic local environment information to align the model with the test data. Extensive experiments demonstrate TAIP’s capability to bridge the domain gap between training and test dataset without additional data. TAIP enhances the test performance on various benchmarks, from small molecule datasets to complex periodic molecular systems with various types of elements. TAIP also enables stable MD simulations where the corresponding baseline models collapse.
