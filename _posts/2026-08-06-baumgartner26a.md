---
title: Anomaly detection in time-series via inductive biases in the latent space of
  conditional normalizing flows
abstract: Deep generative models for anomaly detection in multivariate time-series
  are typically trained by maximizing observed data likelihood. However, likelihood
  in observation space measures marginal density rather than conformity to structured
  temporal dynamics, and therefore can assign high probability to anomalous or out-of-distribution
  samples. We address this structural limitation by relocating the notion of anomaly
  to a prescribed latent space. We introduce explicit inductive biases in conditional
  normalizing flows, modeling time-series observations within a discrete-time state-space
  framework that constrains latent representations to evolve according to prescribed
  temporal dynamics. Under this formulation, expected behavior corresponds to compliance
  with a specified distribution over latent trajectories, while anomalies are defined
  as violations of these dynamics. Anomaly detection is consequently reformulated
  as a statistically grounded compliance test, such that observations are mapped to
  latent space and evaluated via goodness-of-fit tests against the prescribed latent
  evolution. This yields a principled decision rule that remains effective even in
  regions of high observation likelihood. Experiments on synthetic and real-world
  time-series demonstrate reliable detection of anomalies in frequency, amplitude,
  and observation noise, while providing interpretable diagnostics of model compliance.
openreview: aAVCqBm8SF
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: baumgartner26a
month: 0
tex_title: Anomaly detection in time-series via inductive biases in the latent space
  of conditional normalizing flows
firstpage: 448
lastpage: 468
page: 448-468
order: 448
cycles: false
bibtex_author: Baumgartner, David and da Silva, Eliezer de Souza and Urteaga, I\~{n}igo
author:
- given: David
  family: Baumgartner
- given: Eliezer de Souza
  family: Silva
  prefix: da
- given: Iñigo
  family: Urteaga
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
pdf: https://raw.githubusercontent.com/mlresearch/v337/main/assets/baumgartner26a/baumgartner26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
