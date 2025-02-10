---
title: "A configurable successive-cancellation list polar decoder using split-tree architecture"
collection: publications
category: manuscripts
permalink: /publication/paper_8
excerpt: ''
date: 2021-02-13
venue: 'IEEE Journal of Solid-State Circuits, Volume 56, Issue 2'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9144240'
citation: 'Yaoyu Tao, Sung-Gun Cho, Zhengya Zhang'
---

Polar codes are capacity-achieving channel codes and they have recently been adopted for fifth-generation (5G) enhanced mobile broadband (eMBB) control channels. Using successive cancellation list (SCL) decoding, the error-correction performance of polar codes can surpass state-of-the-art codes of a comparable length. However, the sequential SC decoding incurs a long latency, and list decoding requires complex tracking of candidates. We present a split-tree SCL decoder that works by dividing a polar code's decoding tree to sub-trees following a split-tree decoding algorithm. The sub-trees are decoded in parallel by smaller sub-decoders that reconcile their decisions in every decoding stage. The split-tree list decoder architecture improves the throughput and latency proportionally to the split factor. By exploiting under-utilized hardware resources, we apply frame interleaving to further increase throughput and employ dynamic clock gating to reduce energy. The results are demonstrated in a 0.64-mm2 40-nm test chip that implements a split-4, list-2, eight-frame-interleaved decoding architecture. The chip supports configurable code lengths up to 1024 bit and variable code rates. At 0.9 V and room temperature, the chip achieves 3.25 Gb/s with 42.8-mW power, or 13.2 pJ/b, and demonstrates competitive error-correction performance.



