---
title: 'MeshGPT: Generating Triangle Meshes with Decoder-Only Transformers'
date: '2023-11-27'
draft: false
publishDate: '2023-11-30T12:28:41.532436Z'
authors:
- Yawar Siddiqui
- Antonio Alliegro
- Alexey Artemov
- Tatiana Tommasi
- Daniele Sirigatti
- Vladislav Rosov
- Angela Dai
- Matthias Nießner
publication_types:
- '2'
abstract: 'We introduce MeshGPT, a new approach for generating triangle meshes that reflects the compactness typical of artist-created meshes, in contrast to dense triangle meshes extracted by iso-surfacing methods from neural fields. Inspired by recent advances in powerful large language models, we adopt a sequence-based approach to autoregressively generate triangle meshes as sequences of triangles. We first learn a vocabulary of latent quantized embeddings, using graph convolutions, which inform these embeddings of the local mesh geometry and topology. These embeddings are sequenced and decoded into triangles by a decoder, ensuring that they can effectively reconstruct the mesh. A transformer is then trained on this learned vocabulary to predict the index of the next embedding given previous embeddings. Once trained, our model can be autoregressively sampled to generate new triangle meshes, directly generating compact meshes with sharp edges, more closely imitating the efficient triangulation patterns of human-crafted meshes. MeshGPT demonstrates a notable improvement over state of the art mesh generation methods, with a 9% increase in shape coverage and a 30-point enhancement in FID scores across various categories.'

featured: false
publication: 'Accepted to CVPR 2024'
url_pdf: https://arxiv.org/pdf/2311.15475
url_bibtex: /publications/2024-meshgpt/cite.bib
url_code: https://github.com/nihalsid/mesh-gpt
url_video: https://www.youtube.com/watch?v=UV90O1_69_o
url_project: https://nihalsid.github.io/mesh-gpt/
youtube: UV90O1_69_o
---

