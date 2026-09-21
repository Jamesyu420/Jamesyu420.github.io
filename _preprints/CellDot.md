---
title: "Accurate and scalable decontamination of imaging-based spatial transcriptomics via optimal transport"
collection: preprints
# Use a unique permalink for each paper.
permalink: /preprints/CellDot/
date: 2026-09-20
venue: 'Preprint'
paperurl: 'https://www.biorxiv.org/content/10.64898/2026.09.09.750350v1'
citation: 'Chen, Y., Liu, Y., Chao, Z., Han, S., Zeng, Y., Yu, B., ... & Yang, C. (2026). Accurate and scalable decontamination of imaging-based spatial transcriptomics via optimal transport. bioRxiv, 2026-09.'
---

[bioRxiv version](https://www.biorxiv.org/content/10.64898/2026.09.09.750350v1.full.pdf)

## Abstract

Imaging-based spatial transcriptomics enables molecule-resolved profiling of gene expression and tissue organization in situ. However, segmentation errors, transcript spillover and three-dimensional cell overlap can introduce misassigned transcripts into cell-level expression profiles, compromising biological interpretation and obscuring genuine signals. Existing methods either remove suspect expression at the cost of signal loss or lack a biologically grounded criterion for transcript assignment. Here we present CellDot, an optimal-transport framework that determines the fate of each transcript by retaining it in its host cell, reassigning it to a plausible neighboring cell or removing it as background. By integrating reference-guided expression compatibility with spatial information and data-adaptive constraints, CellDot enables accurate and traceable molecule-level correction while preserving biologically meaningful variation. In evaluations across multiple human tumor datasets, CellDot exhibited superior performance compared to existing decontamination methods, successfully restoring spatial expression patterns that matched independent cross-platform measurements. Moreover, it significantly enhanced the recovery of cellular states, intercellular communication, and spatial niche programs. Our experiments using real data demonstrated CellDot’s scalability and established it as the only method applicable to a whole-transcriptome Atera dataset, underscoring its distinct advantages in the field of spatial transcriptomics.

