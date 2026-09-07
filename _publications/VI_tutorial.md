---
title: "Variational Inference Methods for Single-Cell Genomics"
collection: publications
permalink: /publications/VI-tutorial
date: 2026/09/07
venue: 'SLADS'
paperurl: 'https://openreview.net/forum?id=U9fMA6omTP'
citation: 'Yu, B., Tan, Z., Chu, H., Yang, C., (2025), Variational Inference Methods for Single-Cell Genomics, Statistical Learning and Data Science, accepted.'
---

[Openreview version](https://openreview.net/pdf?id=U9fMA6omTP)
[Local version](../files/Variational_Inference_Tutorial.pdf)



## Abstract

The analysis of single-cell genomics data aims to characterize cellular heterogeneity from high-dimensional, sparse, and noisy count measurements. Many statistical approaches in this regard can be expressed as hierarchical latent-variable models to capture the underlying biological structure. However, conducting statistical inference with these methods involves estimating posterior distributions over latent variables, a process that can be computationally challenging due to the scale of single-cell datasets and the use of non-Gaussian likelihoods. Variational inference (VI) addresses this challenge by approximating the posterior with a tractable distribution. We here present variational inference from a modern machine learning perspective and demonstrate its application to single-cell genomics. We first connect it to the EM algorithm and develop a unified view of scalable approaches, including stochastic, black-box, and amortized variational inference. To bridge theory and practice, we demonstrate how these methods can be implemented within the probabilistic programming framework of Pyro and apply these methods to real data for dimension reduction and temporal trajectory inference. We also discuss how modern coding agents can assist in implementation while leaving model formulation and approximation diagnosis to the researcher. Thus, we provide a practical guide to scalable variational inference for single-cell data analysis. The code for reproducing the simulation and real data analysis results is available at https://github.com/YangLabHKUST/Variational_Inference_Tutorial.