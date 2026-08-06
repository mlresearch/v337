---
title: Approximation Rates for Schrödinger Bridge Potentials via Fixed-Point ERM
abstract: The Schrödinger bridge problem (SBP) provides a principled interpolation
  between two distributions by selecting, among all path measures matching given endpoint
  marginals, the one closest in relative entropy to a reference dynamics. In modern
  applications the marginals are observed only through samples, and standard computational
  pipelines solve a discretized SBP via {Sinkhorn} iterations and then heuristically
  extend the resulting dual potentials off-sample, entangling statistical, optimization,
  and smoothing errors. We study a learning-theoretic alternative based on a fixed-point
  characterization of a single \emph{transformed} Schrödinger potential $g^\star$,
  and we focus on quantitative approximation of $g^\star$ by a sample-based estimator
  $\widehat g$ that is continuous by construction. To address the intrinsic scaling
  ambiguity of Schrödinger potentials, we introduce a normalized, scale-invariant
  operator and analyze its local geometry around $g^\star$. Our main theoretical contribution
  is a stability result linking the error of the fixed-point residual to a distance
  to the solution $g^\star$ via analysis of spectral-gap property for the {Fréchet}
  derivative of the operator in a norm $\|\cdot\|$ being the sum of a localized {Hilbert}
  tangent seminorm and an $L^2$ distance. Combining this stability bound with the
  excess risk bounds and approximation error yields explicit non-asymptotic rates
  for $\|\widehat g-g^\star\|$. We illustrate performance of the suggested approach
  with numerical experiments.
openreview: H8OHD7o4tZ
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: belomestny26a
month: 0
tex_title: Approximation Rates for {Schrödinger} Bridge Potentials via Fixed-Point
  {ERM}
firstpage: 521
lastpage: 548
page: 521-548
order: 521
cycles: false
bibtex_author: Belomestny, Denis and Naumov, Alexey and Puchkin, Nikita and Suchkov,
  Denis
author:
- given: Denis
  family: Belomestny
- given: Alexey
  family: Naumov
- given: Nikita
  family: Puchkin
- given: Denis
  family: Suchkov
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
pdf: https://raw.githubusercontent.com/mlresearch/v337/main/assets/belomestny26a/belomestny26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
