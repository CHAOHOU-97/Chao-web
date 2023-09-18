---
title: "Screening membraneless organelle participants with machine-learning models that integrate multimodal features"

authors:
- Zhaoming Chen
- admin
- Liang Wang
- Chunyu Yu
- Taoyu Chen
- Boyan Shen
- Yaoyao Hou
- Pilong Li
- Tingting Li
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
date: "2022-06-14T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-06-14T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Proc Natl Acad Sci U S A"
publication_short: ""

abstract: Protein self-assembly is one of the formation mechanisms of biomolecular condensates. However, most phase-separating systems (PS) demand multiple partners in biological conditions. In this study, we divided PS proteins into two groups according to the mechanism by which they undergo PS, PS-Self proteins can self-assemble spontaneously to form droplets, while PS-Part proteins interact with partners to undergo PS. Analysis of the amino acid composition revealed differences in the sequence pattern between the two protein groups. Existing PS predictors, when evaluated on two test protein sets, preferentially predicted self-assembling proteins. Thus, a comprehensive predictor is required. Herein, we propose that properties other than sequence composition can provide crucial information in screening PS proteins. By incorporating phosphorylation frequencies and immunofluorescence image-based droplet-forming propensity with other PS-related features, we built two independent machine-learning models to separately predict the two protein categories. Results of independent testing suggested the superiority of integrating multimodal features. We performed experimental verification on the top-scored proteins DHX9, Ki-67, and NIFK. Their PS behavior in vitro revealed the effectiveness of our models in PS prediction. Further validation on the proteome of membraneless organelles confirmed the ability of our models to identify PS-Part proteins. We implemented a web server named PhaSePred (http://predict.phasep.pro/) that incorporates our two models together with representative PS predictors. PhaSePred displays proteome-level quantiles of different features, thus profiling PS propensity and providing crucial information for identification of candidate proteins.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.pnas.org/doi/10.1073/pnas.2115369119
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
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
