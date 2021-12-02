---
title: Making DensePose Fast and Light
date: '2021-01-01'
draft: false
publishDate: '2021-12-02T18:20:12.978136Z'
authors:
- Ruslan Rakhimov
- Emil Bogomolov
- Alexandr Notchenko
- Fung Mao
- Alexey Artemov
- Denis Zorin
- Evgeny Burnaev
publication_types:
- '1'
abstract: DensePose estimation task is a significant step forward for enhancing user experience computer vision applications ranging from augmented reality to cloth fitting. Existing neural network models capable of solving this task are heavily parameterized and a long way from being transferred to an embedded or mobile device. To enable Dense Pose inference on the end device with current models, one needs to support an expensive server-side infrastructure and have a stable internet connection. To make things worse, mobile and embedded devices do not always have a powerful GPU inside. In this work, we target the problem of redesigning the DensePose R-CNN model's architecture so that the final network retains most of its accuracy but becomes more light-weight and fast. To achieve that, we tested and incorporated many deep learning innovations from recent years, specifically performing an ablation study on 23 efficient backbone architectures, multiple two-stage detection pipeline modifications, and custom model quantization methods. As a result, we achieved 17 times model size reduction and 2 times latency improvement compared to the baseline model.
featured: false
publication: WACV
url_pdf: https://openaccess.thecvf.com/content/WACV2021/papers/Rakhimov_Making_DensePose_Fast_and_Light_WACV_2021_paper.pdf
url_bibtex: /publications/2021-dense-pose/cite.bib
url_code: https://github.com/zetyquickly/DensePoseFnL
url_slides: https://www.dropbox.com/s/89jx45uibpqjx8p/2021-dense-pose.key.zip?dl=0
---

