---
title: Representation learning of protein dynamics
summary: SeqDance-A Protein Language Model for Representing Protein Dynamic Properties
tags:
  - Protein dynamics
date: '2024-10-15T00:00:00Z'

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
Proteins perform their functions by folding amino acid sequences into dynamic structural ensembles. Despite the important role of protein dynamics, their complexity and the absence of efficient representation methods have limited their integration into studies on protein function and mutation fitness, especially in deep learning applications. To address this, we present SeqDance, a protein language model designed to learn representation of protein dynamic properties directly from sequence alone. SeqDance is pre-trained on dynamic biophysical properties derived from over 30,400 molecular dynamics trajectories and 28,600 normal mode analyses. Our results show that SeqDance effectively captures local dynamic interactions, co-movement patterns, and global conformational features, even for proteins lacking homologs in the pre-training set. Additionally, we showed that SeqDance enhances the prediction of protein fitness landscapes, disorder-to-order transition binding regions, and phase-separating proteins. By learning dynamic properties from sequence, SeqDance complements conventional evolution- and static structure-based methods, offering new insights into protein behavior and function.