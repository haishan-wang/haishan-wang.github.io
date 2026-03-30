---
title: "Smol-GS: Compact Representations for Abstract 3D Gaussian Splatting"
collection: publications
category: conferences
permalink: /publication/2025-11-30-paper_smolgs-3
excerpt: 'Compress 3DGS by compact representation and positional encoding.'
date: 2025-11-30
venue: 'Arxiv'
webpageurl: 'https://aaltoml.github.io/Smol-GS/'
paperurl: 'https://arxiv.org/abs/2512.00850'
githuburl: 'https://github.com/AaltoML/Smol-GS'
authors:
  - name: "Haishan Wang"
    url: "https://haishan-wang.github.io/"
  - name: "Mohammad Vali Hassan"
    url: "https://mhvali.github.io/"
  - name: "Arno Solin"
    url: "https://users.aalto.fi/~asolin/"
---

We present Smol-GS, a novel method for learning compact representations for 3D Gaussian Splatting (3DGS). Our approach learns highly efficient splat-wise features to model 3D space which capture abstracted cues, including color, opacity, transformation, and material properties. We propose octree-derived positional encoding, which explicitly models spatial locality and enhances representation efficiency. We further apply entropy-based compression to exploit feature redundancy, and compress splat coordinates using a recursive voxel hierarchy. This design enables orders-of-magnitude storage reduction while preserving representation flexibility. Smol-GS achieves state-of-the-art compression performance on standard benchmarks with high-level rendering quality.