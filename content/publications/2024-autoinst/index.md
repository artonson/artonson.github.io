---
title: 'AutoInst: Automatic Instance-Based Segmentation of LiDAR 3D Scans'
date: '2024-01-01'
draft: false
publishDate: '2024-03-19T18:01:42.524897Z'
authors:
- Cedric Perauer
- Laurenz Heidrich
- Haifan Zhang
- Matthias Nießner
- Anastasiia Kornilova
- Alexey Artemov
publication_types:
- '2'
abstract: 'Recently, progress in acquisition equipment such as LiDAR sensors has enabled sensing increasingly spacious outdoor 3D environments. Making sense of such 3D acquisitions requires fine-grained scene understanding, such as constructing instance-based 3D scene segmentations. Commonly, a neural network is trained for this task; however, this requires access to a large, densely annotated dataset, which is widely known to be challenging to obtain. To address this issue, in this work we propose to predict instance segmentations for 3D scenes in an unsupervised way, without relying on ground-truth annotations. To this end, we construct a learning framework consisting of two components: (1) a pseudo-annotation scheme for generating initial unsupervised pseudo-labels; and (2) a self-training algorithm for instance segmentation to fit robust, accurate instances from initial noisy proposals. To enable generating 3D instance mask proposals, we construct a weighted proxy-graph by connecting 3D points with edges integrating multi-modal image- and point-based self-supervised features, and perform graph-cuts to isolate individual pseudo-instances. We then build on a state-of-the-art point-based architecture and train a 3D instance segmentation model, resulting in significant refinement of initial proposals. To scale to arbitrary complexity 3D scenes, we design our algorithm to operate on local 3D point chunks and construct a merging step to generate scene- level instance segmentations. Experiments on the challenging SemanticKITTI benchmark demonstrate the potential of our approach, where it attains 13.3% higher Average Precision and 9.1% higher F1 score compared to the best-performing baseline. The code will be made publicly available.'
featured: false
publication: 'ArXiv'
url_video: https://www.youtube.com/watch?v=ioKJWY8L6xk
youtube: ioKJWY8L6xk
---


## Visual Results on KITTI

| **3DUIS** | **HDBSCAN** |
|-|-|
| {{< video id="3duis" src="videos/3duis_800x450_20s_compressed.mp4" width="400" height="225" mute="true" autoplay="true" loop="true" >}} | {{< video id="hdbscan" src="videos/hdbscan_800x450_20s_compressed.mp4" width="400" height="225" mute="true" autoplay="true" loop="true" >}} |
{.video-gallery}

| **OURS (NCut)** | **Ours (NCut + Refined)** |
|-|-|
| {{< video id="ours" src="videos/ours_800x450_20s_compressed.mp4" width="400" height="225" mute="true" autoplay="true" loop="true" >}} | {{< video id="ours_refined" src="videos/ours_refined_800x450_20s_compressed.mp4" width="400" height="225" mute="true" autoplay="true" loop="true" >}} |
{.video-gallery}

