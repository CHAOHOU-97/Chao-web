---
title: pLM interpretation
summary: Unsupervised discovery of functional motifs from pLM
tags:
  - pLM interpretation
date: '2025-11-04T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: By Chao Hou
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/chaohou1
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---
Protein motifs are conserved elements that mediate processes such as folding, binding, catalysis, and post-translational modifications. While motif identification is critical for protein study, experimental methods are labor-intensive, only a few hundred motifs are cataloged in databases like ELM, and existing supervised models are typically limited to predicting motifs with a specific function. Here, we present MotifAE, an unsupervised framework for discovering functional motifs from the protein language model ESM2, which captures evolutionary-scale sequence regularities. MotifAE is based on the sparse autoencoder (SAE), an encoder-decoder architecture that projects ESM2 embeddings into a sparse latent space, with an additional local similarity loss that encourages coherent latent feature activations. When benchmarked against known ELM motifs, MotifAE achieves a median AUROC of 0.88, outperforming the standard SAE (0.80). We also calculated Position-specific scoring matrices (PSSMs) for MotifAE features and found that features with similar decoder weights share similar PSSMs. Furthermore, by aligning MotifAE features with experimental data through gated feature selection, we identified features associated with specific properties such as folding stability. Steering these features enabled designing proteins with enhanced stability, as evaluated in silico. Overall, MotifAE provides a general framework for systematic motif discovery and interpretation, with the potential to advance protein function analysis, mutation effect interpretation, and rational protein engineering.