---
title: Strongly Isomorphic Neural Optimal Transport Across Incomparable Spaces
abstract: 'Optimal Transport (OT) has recently emerged as a powerful framework for
  learning minimal-displacement maps between distributions. The predominant approach
  involves a neural parametrization of the Monge formulation of OT, typically assuming
  the same space for both distributions. However, the setting across “incomparable
  spaces” (e.g., of different dimensionality), corresponding to the Gromov-Wasserstein
  distance, remains underexplored, with existing methods often imposing restrictive
  assumptions on the cost function. In this paper, we present a novel neural formulation
  of the Gromov-Monge (GM) problem rooted in one of its fundamental properties: invariance
  to strong isomorphisms. We operationalize this property by decomposing the learnable
  OT map into two components: (i) an approximate strong isomorphism between the source
  distribution and an intermediate reference distribution, and (ii) a GM-optimal map
  between this reference and the target distribution. Our formulation leverages and
  extends the Monge gap regularizer of \citet{gap_monge} to eliminate the need for
  complex architectural requirements of other neural OT methods, yielding a simple
  but practical method that enjoys favorable theoretical guarantees. Our preliminary
  empirical results show that our framework provides a promising approach to learn
  OT maps across diverse spaces.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: sotiropoulou24a
month: 0
tex_title: Strongly Isomorphic Neural Optimal Transport Across Incomparable Spaces
firstpage: 381
lastpage: 393
page: 381-393
order: 381
cycles: false
bibtex_author: Sotiropoulou, Athina and Alvarez-Melis, David
author:
- given: Athina
  family: Sotiropoulou
- given: David
  family: Alvarez-Melis
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
pdf: https://raw.githubusercontent.com/mlresearch/v251/main/assets/sotiropoulou24a/sotiropoulou24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
