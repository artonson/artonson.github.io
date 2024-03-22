---
title: 'DeepMIF: Deep Monotonic Implicit Fields for Large-Scale LiDAR 3D Mapping'
date: '2024-01-01'
draft: false
publishDate: '2024-03-19T12:43:09.121255Z'
authors:
- Kutay Yılmaz
- Matthias Nießner
- Anastasiia Kornilova
- Alexey Artemov
authors_roles:
- role_name: Researcher
  role_members:
  - name: Kutay Yılmaz
    url: https://github.com/kutipense
publication_types:
- '2'
abstract: 'Recently, significant progress has been achieved in sensing real large-scale outdoor 3D environments, particularly by using modern acquisition equipment such as LiDAR sensors. Unfortunately, they are fundamentally limited in their ability to produce dense, complete 3D scenes. To address this issue, recent learning-based methods integrate neural implicit representations and optimizable feature grids to approximate surfaces of 3D scenes. However, naively fitting samples along raw LiDAR rays leads to noisy 3D mapping results due to the nature of sparse, conflicting LiDAR measurements. Instead, in this work we depart from fitting LiDAR data exactly, instead letting the network optimize a non-metric monotonic implicit field defined in 3D space. To fit our field, we design a learning system integrating a monotonicity loss that enables optimizing neural monotonic fields and leverages recent progress in large- scale 3D mapping. Our algorithm achieves high-quality dense 3D mapping performance as captured by multiple quantitative and perceptual measures and visual results obtained for Mai City, Newer College, and KITTI benchmarks. The code of our approach will be made publicly available.'
featured: false
publication: 'ArXiv'
url_code: https://github.com/artonson/deepmif
url_video: https://youtu.be/WC-pcaf94N4
youtube: WC-pcaf94N4
---

## Sample Reconstruction Results

We have tested our approach vs. [NeRF-LOAM](https://github.com/JunyuanDeng/NeRF-LOAM), 
[Make it Dense](https://github.com/PRBonn/make_it_dense),
[SHINE-Mapping](https://github.com/PRBonn/SHINE_mapping),
[PUMA](https://github.com/PRBonn/puma),
and [VDBFusion](https://github.com/PRBonn/vdbfusion).

### Mai City
Mai City is a simulated environment commonly used for benchmarking scene reconstruction algorithms.

| | |
|-|-|
| {{< video id="mai_city_shaded" src="mai_city_shaded.mp4" width="400" height="225" mute="true" autoplay="true" loop="true" >}} | {{< video id="newer_college_color" src="newer_college_color.mp4" width="400" height="225" mute="true" autoplay="true" loop="true" >}} |
{.video-gallery}



### Newer College
Newer College is a building belonging to Oxford University. It was scanned using a hand-held LiDAR (common input data for reconstruction) and a terrestrial industrial LiDAR (common reference data for evaluation).



### KITTI
KITTI is the best known, and the most commonly used benchmark for autonomous driving algorithms. 
The data used was a Velodyne LiDAR scanned mounted on a Volkswagen. 



