---
title: 'IDCR: Information-Directed Conformal Retrieval'
abstract: Retrieval-augmented prediction systems select documents by semantic similarity,
  ignoring their effect on downstream predictive uncertainty. In high-stakes domains
  such as clinical diagnosis, this can yield overconfident or needlessly imprecise
  predictions. We propose Information-Directed Conformal Retrieval, a framework that
  selects documents to minimize the volume of conformal prediction sets while preserving
  distribution-free coverage. Modeling each document as a {Bayesian} precision update,
  we show that minimizing conformal volume is exactly equivalent to maximizing a log-determinant
  objective, and prove this objective monotone submodular, so greedy selection inherits
  the constant-factor $(1-1/e)$ guarantee. A Document Interaction Tensor characterizes
  corpus-level interaction structure, and a lightweight marginal-gain-separation gate
  routes uncertain retrieval steps to lookahead search. On MIMIC-IV clinical diagnosis
  (275 admissions from 100 patients, 9273 PubMed abstracts), greedy retrieval attains
  a mean greedy-to-optimal ratio of 0.9999, produces conformal ellipsoids 4.8 times
  smaller than random retrieval and 5.8 times smaller than cosine retrieval while
  retaining the distribution-free coverage guarantee, and two-step lookahead closes
  77 percent of the remaining gap. Gains generalize to the SciQ and GoEmotions benchmarks,
  and on GoEmotions and LexGLUE the method yields tighter posterior uncertainty than
  learned and uncertainty-aware retrieval baselines. Complex multi-morbid patients
  benefit most, with twice the synergy-gap rate, precisely where prediction is hardest.
openreview: 4HAtvSTMHJ
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: nanivadekar26a
month: 0
tex_title: "{IDCR}: Information-Directed Conformal Retrieval"
firstpage: 4712
lastpage: 4732
page: 4712-4732
order: 4712
cycles: false
bibtex_author: Nanivadekar, Manas and Khanijoan, Jatin and Kothekar, Swayam and Khan,
  Mohd Amaan
author:
- given: Manas
  family: Nanivadekar
- given: Jatin
  family: Khanijoan
- given: Swayam
  family: Kothekar
- given: Mohd Amaan
  family: Khan
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
pdf: https://raw.githubusercontent.com/mlresearch/v337/main/assets/nanivadekar26a/nanivadekar26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
