---
layout: paper
title: "Read our work"
type: selected work
paper_title: "Tabula: A Tabular Self-Supervised Foundation Model for Single-Cell Transcriptomics"
paper_subtitle: -published at NeurIPS 2025
author_list: "Jiayuan Ding, Jianhui Lin, Shiyu Jiang, Yixin Wang, Ziyang Miao, Zhaoyu Fang, Jiliang Tang+, Min Li+, Xiaojie Qiu+."
journal: "Advances in Neural Information Processing Systems (NeurIPS 2025)"
paper_url: https://openreview.net/forum?id=isC4tDSrTZ
year: 2025
pdf_url: /assets/PDFs/tabula_neurips.pdf
image_url: /assets/images/papers/tabula_neurips.png
paper_alt: Tabula NeurIPS Paper Image
rank: 0.5
---

Foundation models (FMs) have shown great promise in single-cell genomics, yet current approaches, such as scGPT, Geneformer, and scFoundation, rely on centralized training and language modeling objectives that overlook the tabular nature of single-cell data and raise significant privacy concerns. We present TABULA, a foundation model designed for single-cell transcriptomics, which integrates a novel tabular modeling objective and federated learning framework to enable privacy-preserving pretraining across decentralized datasets. TABULA directly models the cell-by-gene expression matrix through column-wise gene reconstruction and row-wise cell contrastive learning, capturing both gene-level relationships and cell-level heterogeneity without imposing artificial gene sequence order. Extensive experiments demonstrate the effectiveness of TABULA: despite using only half the pretraining data, TABULA achieves state-of-the-art performance across key tasks, including gene imputation, perturbation prediction, cell type annotation, and multi-omics integration. It is important to note that as public single-cell datasets continue to grow, TABULA provides a scalable and privacy-aware foundation that not only validates the feasibility of federated tabular modeling but also establishes a generalizable framework for training future models under similar privacy-preserving settings.
