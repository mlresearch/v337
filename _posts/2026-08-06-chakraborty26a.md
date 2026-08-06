---
title: 'Neural Routed Boosting: Robust Learning against Heteroscedastic Noise'
abstract: Boosting algorithms such as AdaBoost have achieved widespread success by
  iteratively focusing on hard-to-classify instances. However, this aggressive re-weighting
  mechanism makes them susceptible to label noise and overfitting. While robust variants
  like Conditional Boosting handle this by estimating conditional risk, they rely
  on global statistical approximations. We propose Neural Routed Boosting, a novel
  ensemble framework that addresses heteroscedastic noise through a structural approach.
  Neural Routed Boosting utilizes a lightweight neural network to partition the input
  space into geometrically coherent regions, training specialized weak learners for
  each. This isolates noisy subspaces, preventing them from corrupting the decision
  boundaries of clean regions. We prove that the composite model of a neural router
  and region-specific experts constitutes a valid weak learner under the boosting
  framework, guaranteeing training error convergence. Experimental results on synthetic
  and real-world datasets demonstrate that Neural Routed Boosting outperforms traditional
  and robust boosting baselines, including Conditional Boosting, in high-noise environments.
openreview: AW0Z3IYcSE
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chakraborty26a
month: 0
tex_title: 'Neural Routed Boosting: Robust Learning against Heteroscedastic Noise'
firstpage: 961
lastpage: 980
page: 961-980
order: 961
cycles: false
bibtex_author: Chakraborty, Puspak and Rajkumar, Arun
author:
- given: Puspak
  family: Chakraborty
- given: Arun
  family: Rajkumar
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
pdf: https://raw.githubusercontent.com/mlresearch/v337/main/assets/chakraborty26a/chakraborty26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
