---
title: Bioinformatics tools for protein degradation
summary: Degpred-predict degron via deep learning
tags:
  - Protein Degradation
date: '2022-07-27T00:00:00Z'

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
Background:
Degrons are short linear motifs, bound by E3 ubiquitin ligase to target protein substrates to be degraded by the ubiquitin-proteasome system. Mutations leading to deregulation of degron functionality disrupt control of protein abundance due to mistargeting of proteins destined for degradation and often result in pathologies. Targeting degrons by small molecules also emerges as an exciting drug design strategy to upregulate the expression of specific proteins. Despite their essential function and disease targetability, reliable identification of degrons remains a conundrum. Here, we developed a deep learning-based model named Degpred that predicts general degrons directly from protein sequences.

Results:
We showed that the BERT-based model performed well in predicting degrons singly from protein sequences. Then, we used the deep learning model Degpred to predict degrons proteome-widely. Degpred successfully captured typical degron-related sequence properties and predicted degrons beyond those from motif-based methods which use a handful of E3 motifs to match possible degrons. Furthermore, we calculated E3 motifs using predicted degrons on the substrates in our collected E3-substrate interaction dataset and constructed a regulatory network of protein degradation by assigning predicted degrons to specific E3s with calculated motifs. Critically, we experimentally verified that a predicted SPOP binding degron on CBX6 prompts CBX6 degradation and mediates the interaction with SPOP. We also showed that the protein degradation regulatory system is important in tumorigenesis by surveying degron-related mutations in TCGA.

Conclusions:
Degpred provides an efficient tool to proteome-wide prediction of degrons and binding E3s singly from protein sequences. Degpred successfully captures typical degron-related sequence properties and predicts degrons beyond those from previously used motif-based methods, thus greatly expanding the degron landscape, which should advance the understanding of protein degradation, and allow exploration of uncharacterized alterations of proteins in diseases. To make it easier for readers to access collected and predicted datasets, we integrated these data into the website http://degron.phasep.pro/.