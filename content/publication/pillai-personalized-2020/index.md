---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Personalized Step Counting Using Wearable Sensors: A Domain Adapted LSTM Network
  Approach'
subtitle: ''
summary: ''
authors:
- Arvind Pillai
- Halsey Lea
- Faisal Khan
- Glynn Dennis
tags:
- '"Computer Science - Machine Learning"'
- '"Electrical Engineering and Systems Science - Signal Processing"'
- '"I.2.0"'
categories: []
date: '2020-12-01'
lastmod: 2022-03-20T17:28:53-04:00
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
publishDate: '2022-03-20T21:28:53.064547Z'
publication_types:
- '1'
abstract: 'Activity monitors are widely used to measure various physical activities
  (PA) as an indicator of mobility, fitness and general health. Similarly, real-time
  monitoring of longitudinal trends in step count has significant clinical potential
  as a personalized measure of disease related changes in daily activity. However,
  inconsistent step count accuracy across vendors, body locations, and individual
  gait differences limits clinical utility. The tri-axial accelerometer inside PA
  monitors can be exploited to improve step count accuracy across devices and individuals.
  In this study, we hypothesize: (1) raw tri-axial sensor data can be modeled to create
  reliable and accurate step count, and (2) a generalized step count model can then
  be efficiently adapted to each unique gait pattern using very little new data. Firstly,
  open-source raw sensor data was used to construct a long short term memory (LSTM)
  deep neural network to model step count. Then we generated a new, fully independent
  data set using a different device and different subjects. Finally, a small amount
  of subject-specific data was domain adapted to produce personalized models with
  high individualized step count accuracy. These results suggest models trained using
  large freely available datasets can be adapted to patient populations where large
  historical data sets are rare.'
publication: '*arXiv:2012.08975 [cs, eess]*'
url_pdf: http://arxiv.org/abs/2012.08975
---
