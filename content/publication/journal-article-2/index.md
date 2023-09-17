---
title: "Systematic prediction of degrons and E3 ubiquitin ligase binding via deep learning"

authors:
- admin
- Yuxuan Li
- Mengyao Wang
- Hong Wu
- Tingting Li
author_notes:
- "Equal contribution"
date: "2022-07-14T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-07-14T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*BMC Biology"
publication_short: ""

abstract: Background
Degrons are short linear motifs, bound by E3 ubiquitin ligase to target protein substrates to be degraded by the ubiquitin-proteasome system. Mutations leading to deregulation of degron functionality disrupt control of protein abundance due to mistargeting of proteins destined for degradation and often result in pathologies. Targeting degrons by small molecules also emerges as an exciting drug design strategy to upregulate the expression of specific proteins. Despite their essential function and disease targetability, reliable identification of degrons remains a conundrum. Here, we developed a deep learning-based model named Degpred that predicts general degrons directly from protein sequences.

Results
We showed that the BERT-based model performed well in predicting degrons singly from protein sequences. Then, we used the deep learning model Degpred to predict degrons proteome-widely. Degpred successfully captured typical degron-related sequence properties and predicted degrons beyond those from motif-based methods which use a handful of E3 motifs to match possible degrons. Furthermore, we calculated E3 motifs using predicted degrons on the substrates in our collected E3-substrate interaction dataset and constructed a regulatory network of protein degradation by assigning predicted degrons to specific E3s with calculated motifs. Critically, we experimentally verified that a predicted SPOP binding degron on CBX6 prompts CBX6 degradation and mediates the interaction with SPOP. We also showed that the protein degradation regulatory system is important in tumorigenesis by surveying degron-related mutations in TCGA.

Conclusions
Degpred provides an efficient tool to proteome-wide prediction of degrons and binding E3s singly from protein sequences. Degpred successfully captures typical degron-related sequence properties and predicts degrons beyond those from previously used motif-based methods, thus greatly expanding the degron landscape, which should advance the understanding of protein degradation, and allow exploration of uncharacterized alterations of proteins in diseases. To make it easier for readers to access collected and predicted datasets, we integrated these data into the website http://degron.phasep.pro/.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://bmcbiol.biomedcentral.com/articles/10.1186/s12915-022-01364-6
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
