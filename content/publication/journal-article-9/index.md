---
title: "MotifAE Reveals Functional Motifs from Protein Language Model: Unsupervised Discovery and Interpretability Analysis"

authors:
- admin
- Di Liu
- Yufeng Shen
author_notes:
- "Equal contribution"

date: "2025-11-04T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-11-04T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "BioRxiv"
publication_short: ""

abstract: Protein motifs are conserved elements that mediate processes such as folding, binding, catalysis, and post-translational modifications. While motif identification is critical for protein study, experimental methods are labor-intensive, only a few hundred motifs are cataloged in databases like ELM, and existing supervised models are typically limited to predicting motifs with a specific function. Here, we present MotifAE, an unsupervised framework for discovering functional motifs from the protein language model ESM2, which captures evolutionary-scale sequence regularities. MotifAE is based on the sparse autoencoder (SAE), an encoder-decoder architecture that projects ESM2 embeddings into a sparse latent space, with an additional local similarity loss that encourages coherent latent feature activations. When benchmarked against known ELM motifs, MotifAE achieves a median AUROC of 0.88, outperforming the standard SAE (0.80). We also calculated Position-specific scoring matrices (PSSMs) for MotifAE features and found that features with similar decoder weights share similar PSSMs. Furthermore, by aligning MotifAE features with experimental data through gated feature selection, we identified features associated with specific properties such as folding stability. Steering these features enabled designing proteins with enhanced stability, as evaluated in silico. Overall, MotifAE provides a general framework for systematic motif discovery and interpretation, with the potential to advance protein function analysis, mutation effect interpretation, and rational protein engineering.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.biorxiv.org/content/10.1101/2025.11.04.686576v1
url_code: 
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: Chao Hou'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
