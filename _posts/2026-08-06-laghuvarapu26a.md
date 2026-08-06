---
title: 'KMM-CP: Practical Conformal Prediction under Covariate Shift via Selective
  Kernel Mean Matching'
abstract: Uncertainty quantification is essential for deploying machine learning models
  in high-stakes domains such as scientific discovery and healthcare. Conformal Prediction
  ({CP}) provides finite-sample coverage guarantees under exchangeability, an assumption
  often violated in practice due to distribution shift. Under covariate shift, restoring
  validity requires importance weighting, yet accurate density-ratio estimation becomes
  unstable when training and test distributions exhibit limited support overlap. We
  propose KMM-{CP}, a conformal prediction framework based on Kernel Mean Matching
  (KMM) for covariate-shift correction. We show that KMM directly controls the bias–variance
  components governing conformal coverage error by minimizing RKHS moment discrepancy
  under explicit weight constraints, and establish asymptotic coverage guarantees
  under mild conditions. We then introduce a selective extension that identifies regions
  of reliable support overlap and restricts conformal correction to this subset, further
  improving stability in low-overlap regimes. Experiments on molecular property prediction
  benchmarks with realistic distribution shifts show that KMM-{CP} reduces coverage
  gap by over 50% compared to existing approaches.
openreview: QtIRxPElFs
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: laghuvarapu26a
month: 0
tex_title: 'KMM-{CP}: Practical Conformal Prediction under Covariate Shift via Selective
  Kernel Mean Matching'
firstpage: 3237
lastpage: 3261
page: 3237-3261
order: 3237
cycles: false
bibtex_author: Laghuvarapu, Siddhartha and Deb, Rohan and Sun, Jimeng
author:
- given: Siddhartha
  family: Laghuvarapu
- given: Rohan
  family: Deb
- given: Jimeng
  family: Sun
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
pdf: https://raw.githubusercontent.com/mlresearch/v337/main/assets/laghuvarapu26a/laghuvarapu26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
