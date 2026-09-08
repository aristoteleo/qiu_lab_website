---
layout: paper
title: "Read our work"
type: preprints
paper_title: "Generative Modeling with Flux Matching"
author_list: "Peter Pao-Huang, Xiaojie Qiu, Stefano Ermon."
journal: "arXiv"
paper_url: https://arxiv.org/abs/2605.07319
year: 2026
rank: 5
image_url: /assets/images/papers/flux_matching.png
paper_alt: Flux Matching Paper Image
pdf_url: /assets/PDFs/flux_matching.pdf
doi: 10.48550/arXiv.2605.07319
---

We introduce Flux Matching, a new paradigm for generative modeling that generalizes existing score-based models to a broader family of vector fields that need not be conservative. Rather than requiring the model to equal the data score, the Flux Matching objective imposes a weaker condition that admits infinitely many vector fields whose stationary distribution is the data. This flexibility enables a class of generative models that cannot be learned under score matching, in which inductive biases, structural priors, and properties of the dynamics can be directly imposed or optimized. We show that Flux Matching performs strongly on high-dimensional image datasets and, more importantly, that our added freedom unlocks a range of applications including faster sampling, interpretable and mechanistic models, and dynamics that encode directed dependencies between variables. More broadly, Flux Matching opens a new dimension in generative modeling by turning the vector field itself into a design choice rather than a fixed target. Code is available at https://github.com/peterpaohuang/flux_matching.
