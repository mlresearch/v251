---
title: 3D Shape Completion with Test-Time Training
abstract: This work addresses the problem of <em> shape completion</em>, i.e., the
  task of restoring incomplete shapes by predicting their missing parts. While previous
  works have often predicted the fractured and restored shape in one step, we approach
  the task by separately predicting the fractured and newly restored parts, but ensuring
  these predictions are interconnected. We use a decoder network motivated by related
  work on the prediction of signed distance functions (DeepSDF). In particular, our
  representation allows us to consider <em> test-time-training</em>, i.e., finetuning
  network parameters to match the given incomplete shape more accurately during inference.
  While previous works often have difficulties with artifacts around the fracture
  boundary, we demonstrate that our overfitting to the fractured parts leads to significant
  improvements in the restoration of eight different shape categories of the ShapeNet
  data set in terms of their chamfer distances.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: schopf-kuester24a
month: 0
tex_title: 3{D} {S}hape {C}ompletion with {T}est-{T}ime {T}raining
firstpage: 92
lastpage: 102
page: 92-102
order: 92
cycles: false
bibtex_author: Schopf-Kuester, Michael and L\"{a}hner, Zorah and Moeller, Michael
author:
- given: Michael
  family: Schopf-Kuester
- given: Zorah
  family: Lähner
- given: Michael
  family: Moeller
date: 2024-10-12
address:
container-title: Proceedings of the Geometry-grounded Representation Learning and
  Generative Modeling Workshop (GRaM)
volume: '251'
genre: inproceedings
issued:
  date-parts:
  - 2024
  - 10
  - 12
pdf: https://raw.githubusercontent.com/mlresearch/v251/main/assets/schopf-kuester24a/schopf-kuester24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
