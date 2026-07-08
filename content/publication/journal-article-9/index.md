---
title: "MotifAE Reveals Functional Sequence Patterns from Protein Language Model: Unsupervised Discovery and Interpretability Analysis"

authors:
- admin
- Di Liu
- Yufeng Shen
author_notes:
- "Equal contribution"

date: "2026-07-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-07-07T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Nature Communications (accepted)"
publication_short: ""

abstract: Protein language models (pLMs) learn sequence patterns at evolutionary scale, but these patterns remain inaccessible within these “black box” models. To discover them, we developed MotifAE, an unsupervised framework based on the sparse autoencoder (SAE) architecture that projects pLM embeddings into an interpretable, sparse latent space. MotifAE introduces an additional smoothness loss to encourage coherent feature activation, which markedly improves the identification of known functional motifs compared to the standard SAE. The sequence patterns captured by MotifAE exhibit rich diversity, align with known functional motifs, and are reflected in the model’s weight space. Beyond short motifs, MotifAE also captures structural domains, with latent feature activation scores correlating with residue importance for different domain functions. By aligning MotifAE features with experimental data, we further identified features associated with domain folding stability. These features enable the prediction of a stability-specific fitness landscape that improves stability prediction and supports the engineering of domains with enhanced stability. Overall, MotifAE provides a general framework for systematic sequence pattern discovery and interpretation, with the potential to advance protein function analysis, mutation effect interpretation, and rational protein engineering.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.biorxiv.org/content/10.1101/2025.11.04.686576v2
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
projects: [plm_interpret]

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
