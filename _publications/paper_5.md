---
title: "eNODE: Energy-Efficient and Low-Latency Edge Inference and Training of Neural ODEs"
collection: publications
category: conferences
permalink: /publication/paper_5
excerpt: ''
date: 2023-02-25
venue: '2023 IEEE International Symposium on High-Performance Computer Architecture (HPCA)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10070935'
citation: 'Junkang Zhu*, Yaoyu Tao*, Zhengya Zhang'
---

Neural ordinary differential equations (NODEs) provide better modeling performance with smaller amount of model parameters in many tasks by embedding neural networks (NNs) in ordinary differential equations (ODEs). They have been shown to outperform in representing continuous-time data and learning dynamic systems, and are promising for on-device inference and training. However, an edge device is limited by area and energy budget, and real-time operations have a tight latency requirement. State-of-the-art NN accelerators are not optimized for the area- and power-hungry memory storage and access for NODE inference and training, and lack the flexibility to incorporate dynamic latency reduction techniques. We present eNODE by architecture-algorithm co-design to achieve efficient and fast inference and training of NODEs. eNODE adopts compact-size depth-first integration and depth-first training for higher energy efficiency. Through function reuse, packetized processing and a unified NN core design, the efficiency of eNODE’s depth-first processing is further enhanced. We propose algorithm innovations, including slope-adaptive stepsize search and priority processing with early stop, to substantially shorten the latency. A hardware prototype is synthesized in a 28 nm CMOS technology for evaluation and benchmarking. eNODE demonstrates up to 6.59× better energy efficiency, 2.38× higher speed, and better area scalability over a SIMD ASIC baseline.
