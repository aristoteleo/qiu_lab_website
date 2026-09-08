---
layout: paper
title: "Read our work"
type: selected work
paper_title: "Geometric Generative Modeling with Noise-Conditioned Graph Networks"
paper_subtitle: -published at ICML 2025
author_list: "Peter Pao-Huang, Mitchell Black, Xiaojie Qiu+."
journal: "Proceedings of the 42nd International Conference on Machine Learning (PMLR 267)"
year: 2025
rank: 0.7
pdf_url: /assets/PDFs/ncgn_icml.pdf
image_url: /assets/images/papers/ncgn_icml.png
paper_alt: Noise-Conditioned Graph Networks Paper Image
---

Generative modeling of graphs with spatial structure is essential across many applications from computer graphics to spatial genomics. Recent flow-based generative models have achieved impressive results by gradually adding and then learning to remove noise from these graphs. Existing models, however, use graph neural network architectures that are independent of the noise level, limiting their expressiveness. To address this issue, we introduce Noise-Conditioned Graph Networks (NCGNs), a class of graph neural networks that dynamically modify their architecture according to the noise level during generation. Our theoretical and empirical analysis reveals that as noise increases, (1) graphs require information from increasingly distant neighbors and (2) graphs can be effectively represented at lower resolutions. Based on these insights, we develop Dynamic Message Passing (DMP), a specific instantiation of NCGNs that adapts both the range and resolution of message passing to the noise level. DMP consistently outperforms noise-independent architectures on a variety of domains including 3D point clouds, spatiotemporal transcriptomics, and images. Code is available at https://github.com/peterpaohuang/ncgn.
