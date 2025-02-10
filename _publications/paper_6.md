---
title: "DNC-Aided SCL-Flip Decoding of Polar Codes"
collection: publications
category: conferences
permalink: /publication/paper_6
excerpt: ''
date: 2021-12-07
venue: '2021 IEEE Global Communications Conference (GLOBECOM)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9685277/'
slidesurl: 'https://github.com/taoyaoyu/Polar_SCL_C_ModuleBased'
citation: 'Yaoyu Tao, Zhengya Zhang'
---

Successive-cancellation list (SCL) decoding of polar codes has been adopted for 5G wireless communications. How-ever, the performance of moderate code length is not satisfactory. Heuristic or deep-learning-aided (DL-aided) flip algorithms have been developed to improve the performance by locating error bit positions after SCL decoding. In this work, we propose a new flip algorithm with the help of differentiable neural computer (DNC). New state and action encoding are developed to improve DNC training and inference efficiency. The proposed two-phase method is done by a flip DNC (F-DNC) to rank the most likely flip positions for multi-bit flipping, and if decoding still fails, a flip-validate DNC (FV-DNC) is applied to re-select error bit positions in successive flip decoding trials. Supervised training methods are designed for the two DNCs. Simulation results show that the proposed DNC-aided SCL-Flip (DNC-SCLF) decoding demonstrates up to 0.34 dB coding gain or 54.2% reduction in the average number of decoding attempts over prior work.
