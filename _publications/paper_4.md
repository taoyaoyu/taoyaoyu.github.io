---
title: "Accelerating Neural-ODE Inference on FPGAs with Two-Stage Structured Pruning and History-based Stepsize Search"
collection: publications
category: conferences
permalink: /publication/paper_4
excerpt: ''
date: 2023-02-12
venue: '2023 ACM/SIGDA International Symposium on Field Programmable Gate Arrays (FPGA)'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3543622.3573044'
citation: 'Lei Cai, Jing Wang, Lianfeng Yu, Bonan Yan, Yaoyu Tao*, Yuchao Yang*'
---

Neural ordinary differential equation (Neural-ODE) outperforms conventional deep neural networks (DNNs) in modeling continuous-time or dynamical systems by adopting numerical ODE integration onto a shallow embedded NN. However, Neural-ODE suffers from slow inference due to the costly iterative stepsize search in numerical integration, especially when using higher-order Runge-Kutta (RK) methods and smaller error tolerance for improved integration accuracy. In this work, we first present algorithmic techniques to speedup RK-based Neural-ODE inference: a two-stage coarse-grained/fine-grained structured pruning method based on top-K sparsification that reduces the overall computations by more than 60% in the embedded NN and a history-based stepsize search method based on past integration steps that reduces the latency for reaching accepted stepsize by up to 77% in RK methods. A reconfigurable hardware architecture is co-designed based on proposed speedup techniques, featuring three processing loops to support programmable embedded NN and a variety of higher-order RK methods. Sparse activation processor with multi-dimensional sorters is designed to exploit structured sparsity in activations. Implemented on a Xilinx Virtex-7 XC7VX690T FPGA and experimented on a variety of datasets, the prototype accelerator using a more complex 3rd-order RK method achieves more than 2.6x speedup compared to the latest Neural-ODE FPGA accelerator using the simplest Euler method. Compared to a software execution on Nvidia A100 GPU, the inference speedup can be up to 18x.
