---
title: Long term sequential decision making under risk
abstract: We study finite-horizon {MDP} planning under \emph{root-based} (resolute)
  risk objectives that apply a rank-dependent functional to the distribution of total
  returns. Such objectives are non-linear in the return distribution and generally
  break {Bellman} optimality, so direct optimization by scenario-tree enumeration
  is intractable. We propose \textbf{ERQDP}, an enumeration-free and sampling-free
  method that solves a rank–quantile surrogate via exact {DP} (Dynamic Programming),
  evaluates candidate policies exactly by {DP} over return Probability Mass Functions
  (PMFs) on a discretized return grid (with an explicit rounding bound), and refines
  the surrogate in an anytime loop that reports an explicit upper–lower gap (certificate)
  for the target objective up to discretization budgets. Across tested benchmarks,
  ERQDP returns certified solutions or explicit residual gaps, enables fast risk-parameter
  sweeps with substantial runtime gains, and supports both risk-averse and risk-seeking
  behaviors.
openreview: CzAn3U9kfw
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: mirzanejad26a
month: 0
tex_title: Long term sequential decision making under risk
firstpage: 4543
lastpage: 4560
page: 4543-4560
order: 4543
cycles: false
bibtex_author: Mirzanejad, Mohammad and Bourdache, Nadjet and Mouaddib, Abdel-illah
author:
- given: Mohammad
  family: Mirzanejad
- given: Nadjet
  family: Bourdache
- given: Abdel-illah
  family: Mouaddib
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
pdf: https://raw.githubusercontent.com/mlresearch/v337/main/assets/mirzanejad26a/mirzanejad26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
