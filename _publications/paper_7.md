---
title: "HiMA: A Fast and Scalable History-based Memory Access Engine for Differentiable Neural Computer"
collection: publications
category: conferences
permalink: /publication/paper_7
excerpt: ''
date: 2021-10-18
venue: '54th IEEE/ACM International Symposium on Microarchitecture (MICRO)'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3466752.3480052'
citation: 'Yaoyu Tao, Zhengya Zhang'
---

Memory-augmented neural networks (MANNs) provide better inference performance in many tasks with the help of an external memory. The recently developed differentiable neural computer (DNC) is a MANN that has been shown to outperform in representing complicated data structures and learning long-term dependencies. DNC’s higher performance is derived from new history-based attention mechanisms in addition to the previously used content-based attention mechanisms. History-based mechanisms require a variety of new compute primitives and state memories, which are not supported by existing neural network (NN) or MANN accelerators. We present HiMA, a tiled, history-based memory access engine with distributed memories in tiles. HiMA incorporates a multi-mode network-on-chip (NoC) to reduce the communication latency and improve scalability. An optimal submatrix-wise memory partition strategy is applied to reduce the amount of NoC traffic; and a two-stage usage sort method leverages distributed tiles to improve computation speed. To make HiMA fundamentally scalable, we create a distributed version of DNC called DNC-D to allow almost all memory operations to be applied to local memories with trainable weighted summation to produce the global memory output. Two approximation techniques, usage skimming and softmax approximation, are proposed to further enhance hardware efficiency. HiMA prototypes are created in RTL and synthesized in a 40nm technology. By simulations, HiMA running DNC and DNC-D demonstrates 6.47 × and 39.1 × higher speed, 22.8 × and 164.3 × better area efficiency, and 6.1 × and 61.2 × better energy efficiency over the state-of-the-art MANN accelerator. Compared to an Nvidia 3080Ti GPU, HiMA demonstrates speedup by up to 437 × and 2,646 × when running DNC and DNC-D, respectively.
