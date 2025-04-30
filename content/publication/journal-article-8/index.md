---
title: "Understanding Protein Language Model Scaling on Mutation Effect Prediction"

authors:
- admin
- Di Liu
- Aziz Zafar
- Yufeng Shen
author_notes:
- "Equal contribution"

date: "2025-04-29T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-04-29T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "BioRxiv"
publication_short: ""

abstract: Protein language models (pLMs) can predict mutation effects by computing log-likelihood ratios between mutant and wild-type amino acids, but larger models do not always perform better. We found that the performance of ESM2 peaks when the predicted perplexity for a given protein falls within the range of 3 to 6. Models that yield excessively high or low perplexity tend to predict uniformly near-zero or large negative log-likelihood ratios for all mutations on the protein, limiting their ability to discriminate between deleterious and neutral mutations. Larger models often assign uniformly high probabilities across all positions, reducing specificity for functionally important residues. We also demonstrated how the evolutionary information implicitly captured by pLMs can be linked with the conservation patterns observed in homologous sequences. Our findings highlight the importance of perplexity in mutation effect prediction and suggest a direction for developing pLMs optimized for this application.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.biorxiv.org/content/10.1101/2025.04.25.650688v1
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
