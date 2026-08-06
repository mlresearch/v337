---
title: 'APIC: Amortized Physics-Informed Calibration using Neural Processes'
abstract: Physics models are inherently imperfect due to misspecified or missing mechanisms,
  resulting in systematic discrepancies between model predictions and real-world observations.
  The Kennedy–O’Hagan (KOH) framework addresses this issue through explicit discrepancy
  modeling. However, its non-amortized, per-instance formulation limits scalability
  across families of related systems. We introduce Amortized Physics-Informed Calibration
  ({APIC}), a population-level extension of KOH that leverages Neural Processes to
  perform scalable {Bayesian} inference across realizations. Our framework employs
  a two-branch latent architecture to disentangle instance-specific physical parameters
  from shared, state-dependent structural discrepancies. By integrating differentiable
  physics into an amortized inference backbone, {APIC} enables rapid calibration of
  unseen realizations from sparse observations while quantifying uncertainty. Experiments
  on the damped spring oscillator, the Lotka–Volterra system, and the advection–diffusion
  {PDE} with misspecified physics demonstrate improved parameter recovery and consistent
  identification of the systemic discrepancy structure compared to other calibration
  approaches.
openreview: YrYl9QgVBV
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: venkataramanan26a
month: 0
tex_title: "{APIC}: Amortized Physics-Informed Calibration using Neural Processes"
firstpage: 6900
lastpage: 6916
page: 6900-6916
order: 6900
cycles: false
bibtex_author: Venkataramanan, Aishwarya and Vemuri, Sai Karthikeya and Denzler, Joachim
author:
- given: Aishwarya
  family: Venkataramanan
- given: Sai Karthikeya
  family: Vemuri
- given: Joachim
  family: Denzler
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
pdf: https://raw.githubusercontent.com/mlresearch/v337/main/assets/venkataramanan26a/venkataramanan26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
