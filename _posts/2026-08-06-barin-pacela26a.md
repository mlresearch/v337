---
title: 'Stop Probing, Start Coding: Why Linear Probes and Sparse Autoencoders Fail
  at Compositional Generalization'
abstract: 'Foundational to interpreting pretrained representations of deep generative
  models, the linear representation hypothesis states that neural network activations
  encode high-level concepts as linear mixtures. However, linear representation does
  not imply linear accessibility of such concepts: under superposition, when the number
  of concepts exceeds the activation dimension, recovering the underlying latent factors
  requires sparse nonlinear inference, making methods such as linear probes insufficient.
  Sparse autoencoders ({SAEs}) perform nonlinear inference but amortize it into a
  fixed encoder, introducing a systematic amortization gap. We show this gap dominates
  all other error sources and persists as the number of training samples is increased,
  causing {SAEs} to fail under out-of-distribution ({OOD}) compositional shifts. In
  contrast, classical sparse coding with per-sample iterative inference leverages
  compressed sensing guarantees to recover latent factors robustly, maintaining near-zero
  gaps in the accuracy between in and out of distribution. Our results demonstrate
  that the recent {OOD} failures of {SAEs} can be attributed to amortization failures:
  per-sample inference at test time substantially improves {OOD} performance, even
  when using a dictionary learned by an {SAE}. This is observed along a spectrum of
  hybrid approaches that progressively undo amortization and recover {OOD} performance.'
openreview: eOJ8JaMRTK
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: barin-pacela26a
month: 0
tex_title: 'Stop Probing, Start Coding: Why Linear Probes and Sparse Autoencoders
  Fail at Compositional Generalization'
firstpage: 364
lastpage: 412
page: 364-412
order: 364
cycles: false
bibtex_author: Barin-Pacela, Vit\'{o}ria and Joshi, Shruti and Camacho, Isabela and
  Lacoste-Julien, Simon and Klindt, David
author:
- given: Vitória
  family: Barin-Pacela
- given: Shruti
  family: Joshi
- given: Isabela
  family: Camacho
- given: Simon
  family: Lacoste-Julien
- given: David
  family: Klindt
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
pdf: https://raw.githubusercontent.com/mlresearch/v337/main/assets/barin-pacela26a/barin-pacela26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
