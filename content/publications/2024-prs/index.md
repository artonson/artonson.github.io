---
title: 'PRS: Sharp Feature Priors for Resolution-Free Surface Remeshing'
date: '2023-01-01'
draft: false
publishDate: '2023-11-30T12:28:41.532436Z'
authors:
- Natalia Soboleva
- Olga Gorbunova
- Maria Ivanova
- Evgeny Burnaev
- Matthias Nießner
- Denis Zorin
- Alexey Artemov
publication_types:
- '2'
abstract: Surface reconstruction with preservation of geometric features is a challenging computer vision task. 
  Despite significant progress in implicit shape reconstruction, state-of-the-art mesh extraction methods often 
  produce aliased, perceptually distorted surfaces and lack scalability to high-resolution 3D shapes. 
  We present a data-driven approach for automatic feature detection and remeshing that requires only a coarse, 
  aliased mesh as input and scales to arbitrary resolution reconstructions. 
  We define and learn a collection of surface-based fields to (1) capture sharp geometric features 
  in the shape with an implicit vertexwise model and (2) approximate improvements in normals alignment 
  obtained by applying edge-flips with an edgewise model. 
  To support scaling to arbitrary complexity shapes, we learn our fields using local triangulated patches, 
  fusing estimates on complete surface meshes.
  Our feature remeshing algorithm integrates the learned fields as sharp feature priors and optimizes 
  vertex placement and mesh connectivity for maximum expected surface improvement.
  On a challenging collection of high-resolution shape reconstructions in the ABC dataset, our algorithm 
  improves over state-of-the-art by 26% normals F-score and 42% perceptual RMSEv. 
featured: false
publication: 'Arxiv'
url_pdf: https://artonson.github.io/publications/2024-prs/
url_bibtex: /publications/2024-prs/cite.bib
url_code: https://github.com/artonson/prs
url_video: https://www.youtube.com/watch?v=tm2NqXfcP4I
youtube: tm2NqXfcP4I
---

