---
title: 'DEF: Deep Estimation of Sharp Geometric Features in 3D Shapes'
date: '2020-11-30'
draft: false
publishDate: '2022-07-28T17:57:13.557457Z'
authors:
- Albert Matveev
- Ruslan Rakhimov
- Alexey Artemov
- Gleb Bobrovskikh
- Vage Egiazarian
- Emil Bogomolov
- Daniele Panozzo
- Denis Zorin
- Evgeny Burnaev
publication_types:
- '2'
abstract: We propose Deep Estimators of Features (DEFs), a learning-based framework
  for predicting sharp geometric features in sampled 3D shapes. Differently from existing
  data-driven methods, which reduce this problem to feature classification, we propose
  to regress a scalar field representing the distance from point samples to the closest
  feature line on local patches. Our approach is the first that scales to massive
  point clouds by fusing distance-to-feature estimates obtained on individual patches.We
  extensively evaluate our approach against related state-of-the-art methods on newly
  proposed synthetic and real-world 3D CAD model benchmarks. Our approach not only
  outperforms these (with improvements in Recall and False Positives Rates), but generalizes
  to real-world scans after training our model on synthetic data and fine-tuning it
  on a small dataset of scanned data.We demonstrate a downstream application, where
  we reconstruct an explicit representation of straight and curved sharp feature lines
  from range scan data.We make code, pre-trained models, and our training and evaluation
  datasets available at https://github.com/artonson/def.
featured: false
publication: 'ACM Transaction on Graphics (SIGGRAPH) 2022'
tags:
- '"curve extraction"'
- '"sharp geometric features"'
- '"deep learning"'
url_pdf: https://doi.org/10.1145/3528223.3530140
doi: 10.1145/3528223.3530140
url_pdf: https://dl.acm.org/doi/pdf/10.1145/3528223.3530140
url_supp: https://www.dropbox.com/s/weqxi9nzknpxbra/2022-def-supp.pdf
url_bibtex: /publications/2022-def/cite.bib
url_code: https://github.com/artonson/def
url_video: https://www.youtube.com/watch?v=roiqmlBXn_k
youtube: roiqmlBXn_k
---

