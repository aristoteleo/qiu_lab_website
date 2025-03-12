---
layout: paper
title: "Read our work"
type: preprints
paper_title: Toward a privacy-preserving predictive foundation model of single-cell transcriptomics with federated learning and tabular modeling
author_list: Jiayuan Ding, Jianhui Lin, Shiyu Jiang, Yixin Wang, Ziyang Miao, Zhaoyu Fang, Jiliang Tang+, Min Li+, Xiaojie Qiu+.
journal: Biorxiv
doi: 10.1101/2025.01.06.631427
year: 2025
pdf_url: /assets/PDFs/tabula_biorxiv.pdf
image_url: /assets/images/papers/tabula_biorxiv.png
paper_alt: tabula_biorxiv Paper Image
rank: 2
---

The ability to pre-train on vast amounts of data to build foundation models (FMs) has achieved remarkable success in numerous domains, including natural language processing, computer vision, and, more recently, single-cell genomics—epitomized by GeneFormer, scGPT, and scFoundation. However, as single-cell FMs begin to train on increasingly large corpora, significant privacy and ethical concerns arise. Moreover, unlike text data, single-cell data is unordered and exhibits a unique tabular structure that most existing single-cell FMs overlook. In this study, we propose Tabula, a privacy-preserving and tabular-structure aware FM designed with federated learning (FL) and tabular modeling. Tabula combines the advantages of FMs and FL, enabling collaborative model training across multiple clients without compromising data privacy. In contrast to earlier single-cell FMs—which treat single-cell data like natural language (viewing cells as “words” defined by genes)—Tabula introduces a novel pretraining strategy that explicitly models the tabular structure of single-cell data. Extensive experimental results show that Tabula outperforms state-of-the-art methods in various downstream tasks (including cell type annotation, gene imputation, gene perturbation, multi-batch integration, and multi-omics integration) while requiring only half the data for pretraining and preserving data privacy. Furthermore, Tabula accurately reveals pairwise and even combinatorial regulatory logic across diverse biological systems, including hematopoiesis, pancreatic endogenesis, neurogenesis, and cardiogenesis. Thus, Tabula provides a new foundation model that explicitly incorporates the tabular nature of single-cell data alongside FL, paving the way for creating a “virtual cell” for human health under critical privacy preservation.