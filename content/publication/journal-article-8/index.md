---
title: "Understanding Language Model Scaling for Protein Fitness Prediction"

authors:
- admin
- Di Liu
- Aziz Zafar
- Yufeng Shen
author_notes:
- "Equal contribution"

date: "2026-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Nature Computational Science"
publication_short: ""

abstract: Protein language models, and models that incorporate structure or homologous sequences, estimate sequence likelihoods p(sequence) that reflect the protein fitness landscape and are commonly used in mutation effect prediction and protein design. It is widely believed in deep learning field that larger model performs better across tasks. However, for fitness prediction, language model performance declines beyond a certain size, raising concerns about their scalability. Here, we showed that model size, training dataset, and stochastic elements can bias the predicted p(sequence) away from real fitness. Model performance on fitness prediction depends on how well p(sequence) matches evolutionary patterns in homologs, which is best achieved at a moderate p(sequence) level for most proteins. At extreme predicted wild-type sequence likelihoods, models predict uniformly low or high likelihoods for nearly all mutations, failing to reflect the real fitness landscape. Notably, larger models tend to predict proteins with higher p(sequence), which may exceed the moderate range and thus reduce performance. Our findings clarify the scaling behavior of protein models on fitness prediction and provide practical guidelines for their application and future development.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.biorxiv.org/content/10.1101/2025.04.25.650688v3
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
projects: [plm_fitness]

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
