---
title: Predicting E3 ligase binding site
summary: Degpred predicts degron and binding E3 via deep learning
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
Degrons are short motifs recognized by E3 ubiquitin ligases, marking proteins for degradation via the ubiquitin-proteasome system. Mutations in degrons can disrupt protein degradation, leading to diseases. Despite their critical role, degron identification remains challenging. To address this, we developed Degpred, a deep learning model that predicts degrons directly from protein sequences. Degpred, based on the BERT architecture, accurately predicts degrons on a proteome-wide scale, capturing key degron-related sequence properties and surpassing traditional motif-based methods. Unlike previous approaches, which rely on known E3 motifs to identify degrons, Degpred can predict novel degrons beyond those defined by existing motif-based methods. Additionally, we identified E3 ligase motifs by analyzing degrons predicted in our collected E3-substrate interaction dataset. This allowed us to construct a regulatory network for protein degradation, assigning predicted degrons to specific E3s. Experimentally, we validated a predicted degron on CBX6, demonstrating its role in mediating CBX6 degradation via interaction with SPOP. Degpred expands the known degron landscape, offering new insights into protein degradation and the potential for drug development. Data and predictions are available at http://degron.phasep.pro/.