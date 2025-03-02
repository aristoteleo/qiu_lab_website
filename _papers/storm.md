---
layout: paper
title: "Read our work"
type: previous involved work
paper_title: "Storm: Incorporating transient stochastic dynamics to infer the RNA velocity with metabolic labeling information"
author_list: Qiangwei Peng, Xiaojie Qiu+, Tiejun Li+
journal: PLOS computational biology
doi: doi.org/10.1371/journal.pcbi.1012606
year: 2024
pdf_url: /assets/PDFs/qiangwei_storm_2024.pdf
image_url: /assets/images/papers/storm.png
paper_alt: storm Paper Image
rank: 0
---

The time-resolved scRNA-seq (tscRNA-seq) provides the possibility to infer physically meaningful kinetic parameters, e.g., the transcription, splicing or RNA degradation rate constants with correct magnitudes, and RNA velocities by incorporating temporal information. Previous approaches utilizing the deterministic dynamics and steady-state assumption on gene expression states are insufficient to achieve favorable results for the data involving transient process. We present a dynamical approach, Storm (Stochastic models of RNA metabolic-labeling), to overcome these limitations by solving stochastic differential equations of gene expression dynamics. The derivation reveals that the new mRNA sequencing data obeys different types of cell-specific Poisson distributions when jointly considering both biological and cell-specific technical noise. Storm deals with measured counts data directly and extends the RNA velocity methodology based on metabolic labeling scRNA-seq data to transient stochastic systems. Furthermore, we relax the constant parameter assumption over genes/cells to obtain gene-cell-specific transcription/splicing rates and gene-specific degradation rates, thus revealing time-dependent and cell-state-specific transcriptional regulations. Storm will facilitate the study of the statistical properties of tscRNA-seq data, eventually advancing our understanding of the dynamic transcription regulation during development and disease.