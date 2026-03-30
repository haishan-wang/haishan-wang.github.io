---
title: "Compressing 3D Gaussian Splatting by Noise-Substituted Vector Quantization"
collection: publications
category: conferences
permalink: /publication/2025-04-03-paper-nsvqgs-1
excerpt: 'Create codebooks to store 3DGS features via vector quantization'
date: 2025-04-03
venue: 'Scandinavian Conference on Image Analysis (SCIA)'
paperurl: 'https://arxiv.org/abs/2504.03059'
githuburl: 'https://github.com/AaltoML/nsvqgs'
authors:
  - name: "Haishan Wang"
    url: "https://haishan-wang.github.io/"
  - name: "Mohammad Vali Hassan"
    url: "https://mhvali.github.io/"
  - name: "Arno Solin"
    url: "https://users.aalto.fi/~asolin/"
---

3D Gaussian Splatting (3DGS) has demonstrated remarkable effectiveness in 3D reconstruction, achieving high-quality results with real-time radiance field rendering. However, a key challenge is the substantial storage cost: reconstructing a single scene typically requires millions of Gaussian splats, each represented by 59 floating-point parameters, resulting in approximately 1 GB of memory. To address this challenge, we propose a compression method by building separate attribute codebooks and storing only discrete code indices. Specifically, we employ noise-substituted vector quantization technique to jointly train the codebooks and model features, ensuring consistency between gradient descent optimization and parameter discretization. Our method reduces the memory consumption efficiently (around 45×) while maintaining competitive reconstruction quality on standard 3D benchmark scenes. Experiments on different codebook sizes show the trade-off between compression ratio and image quality. Furthermore, the trained compressed model remains fully compatible with popular 3DGS viewers and enables faster rendering speed, making it well-suited for practical applications.