---
title: "A scalable universal Ising machine based on interaction-centric storage and compute-in-memory"
collection: publications
category: manuscripts
permalink: /publication/paper_1
excerpt: ''
date: 2024-08-13
venue: 'Nature Electronics volume 7, pages904–913'
paperurl: 'https://www.nature.com/articles/s41928-024-01228-7'
citation: 'Wenshuo Yue, Teng Zhang, Zhaokun Jing, Kai Wu, Yuxiang Yang, Zhen Yang, Yongqin Wu, Weihai Bu, Kai Zheng, Jin Kang, Yibo Lin, Yaoyu Tao, Bonan Yan*, Ru Huang, Yuchao Yang*'
---

Ising machines are annealing processors that can solve combinatorial optimization problems via the physical evolution of the corresponding Ising graphs. Such machines are, however, typically restricted to solving problems with certain kinds of graph topology because the spin location and connections are fixed. Here, we report a universal Ising machine that supports arbitrary Ising graph topology with reasonable hardware resources using a coarse-grained compressed sparse row method to compress and store sparse Ising graph adjacency matrices. The approach, which we term interaction-centric storage, is suitable for any kind of Ising graph and reduces the memory scaling cost. We experimentally implement the Ising machine using compute-in-memory hardware based on a 40 nm resistive random-access memory arrays. We use the machine to solve max-cut and graph colouring problems, with the latter showing a 442–1,450 factor improvement in speed and 4.1 × 10^5–6.0 × 10^5 factor reduction in energy consumption compared to a general-purpose graphics processing unit. We also use our Ising machine to solve a realistic electronic design automation problem—multiple patterning lithography layout decomposition—with 390–65,550 times speedup compared to the integer linear programming algorithm on a typical central processing unit.


