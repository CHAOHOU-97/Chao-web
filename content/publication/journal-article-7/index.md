---
title: "SeqDance: A Protein Language Model for Representing Protein Dynamic Properties"

authors:
- admin
- Yufeng Shen
author_notes:
- "Equal contribution"

date: "2024-10-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-10-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "BioRxiv"
publication_short: ""

abstract: Proteins perform their functions by folding amino acid sequences into dynamic structural ensembles. Despite the important role of protein dynamics, their complexity and the absence of efficient representation methods have limited their integration into studies on protein function and mutation fitness, especially in deep learning applications. To address this, we present SeqDance, a protein language model designed to learn representation of protein dynamic properties directly from sequence alone. SeqDance is pre-trained on dynamic biophysical properties derived from over 30,400 molecular dynamics trajectories and 28,600 normal mode analyses. Our results show that SeqDance effectively captures local dynamic interactions, co-movement patterns, and global conformational features, even for proteins lacking homologs in the pre-training set. Additionally, we showed that SeqDance enhances the prediction of protein fitness landscapes, disorder-to-order transition binding regions, and phase-separating proteins. By learning dynamic properties from sequence, SeqDance complements conventional evolution- and static structure-based methods, offering new insights into protein behavior and function.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.biorxiv.org/content/10.1101/2024.10.11.617911v1
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
projects: [dynamic]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
