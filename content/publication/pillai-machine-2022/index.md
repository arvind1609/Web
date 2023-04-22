---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Machine Learning Enabled Non-invasive Diagnosis of Nonalcoholic Fatty Liver
  Disease and Assessment of Abdominal Fat from MRI Data
subtitle: ''
summary: ''
authors:
- Arvind Pillai
- Kamen Bliznashki
- Emmette Hutchison
- Chanchal Kumar
- Benjamin Challis
- Mishal Patel
tags: []
categories: []
date: '2022-03-01'
lastmod: 2022-04-03T16:39:40-04:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-04-03T20:39:39.901548Z'
publication_types:
- '4'
abstract: Abstract Nonalcoholic fatty liver disease (NAFLD) is the most rapidly growing
  contributor to chronic liver disease worldwide with high disease burden and suffers
  from limitations in diagnosis. Inspired by recent advances in machine learning digital
  diagnostics, we explored the efficacy of training a neural network to classify high
  risk NAFLD vs. non-NAFLD patients in the UK Biobank dataset based on proton density
  fat fraction (PDFF). We compared the performance of several ResNet-derived architectures
  in the context of whole abdomen MRI, segmented liver and abdomen excluding liver
  (sans-liver). Non-local ResNet trained on whole abdomen MRI images yielded the highest
  precision (0.88 for NAFLD) and F1 (0.89 for NAFLD). Furthermore, our work on a second,
  larger cohort explored multi-task learning and the relationship among PDFF, visceral
  adipose tissue (VAT) and abdominal subcutaneous adipose tissue (ASAT). Interestingly,
  multi-task learning experiments found a decline in performance for PDFF when combined
  with VAT and ASAT. We address this deterioration using Multi-gate Mixture-of-Experts
  (MMoE) approaches. Our work opens the possibility for using a non-invasive deep
  learning-based diagnostic for NAFLD, and directly enables clinical and genomic research
  using a larger cohort of potential NAFLD patients in the UK Biobank study.
publication: 'medRxiv'
url_pdf: http://medrxiv.org/lookup/doi/10.1101/2022.03.25.22272965
doi: 10.1101/2022.03.25.22272965
---
