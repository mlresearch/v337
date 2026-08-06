---
title: 'EpiRDN: A Learnable Anisotropic Reaction-Diffusion Network for Epidemic Time
  Series Prediction'
abstract: Epidemic spread on graphs involves local infection dynamics and directional
  propagation through population movement. Current epidemic graph neural networks
  combine these aspects using a single symmetric aggregation operator, which limits
  the learning of their distinct timescales and fails to capture the asymmetry of
  real epidemic spread. This leads to node representations collapsing to a common
  state, losing diversity necessary for distinguishing infection stages. To address
  these issues, we propose EpiRDN, which discretizes the reaction-diffusion equation
  on graphs and learns its components end-to-end. EpiRDN features a local reaction
  network for region-level transitions and an anisotropic diffusion operator that
  utilizes asymmetric attention for directional infection flow. A feature-conditioned
  damping coefficient balances preserving local identity and neighborhood aggregation.
  We demonstrate that feature diversity in EpiRDN decays at most geometrically with
  depth, providing a significant advantage over existing methods. Experiments on four
  real-world datasets related to influenza and COVID-19 show consistent improvements,
  especially at longer forecasting horizons.
openreview: PJX5hivxN5
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: hevapathige26a
month: 0
tex_title: 'EpiRDN: A Learnable Anisotropic Reaction-Diffusion Network for Epidemic
  Time Series Prediction'
firstpage: 2137
lastpage: 2151
page: 2137-2151
order: 2137
cycles: false
bibtex_author: Hevapathige, Asela
author:
- given: Asela
  family: Hevapathige
date: 2026-08-06
address:
container-title: Proceedings of the 42nd Conference on Uncertainty in Artificial Intelligence
volume: '337'
genre: inproceedings
issued:
  date-parts:
  - 2026
  - 8
  - 6
pdf: https://raw.githubusercontent.com/mlresearch/v337/main/assets/hevapathige26a/hevapathige26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
