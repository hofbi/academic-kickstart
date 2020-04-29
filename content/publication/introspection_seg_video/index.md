---
title: "Pixel-Wise Failure Prediction for Semantic Video Segmentation"
authors:
- Christopher Kuhn
- admin
- Ziqin Xu
- Goran Petrovic
- Eckehard Steinbach
date: "2021-09-19T00:00:00Z"
doi: "10.1109/ICIP42928.2021.9506552"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-05-08T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *28th IEEE International Conference on Image Processing*
publication_short: In *ICIP2021*

abstract: "We propose a pixel-accurate failure prediction approach for semantic video segmentation. The proposed scheme improves previously proposed failure prediction methods which so far disregarded the temporal information in videos. Our approach consists of two main steps: First, we train an LSTM-based model to detect spatio-temporal patterns that indicate pixel-wise misclassifications in the current video frame. Second, we use sequences of failure predictions to train a denoising autoencoder that both refines the current failure prediction and predicts future misclassifications. Since public data sets for this scenario are limited, we introduce the large-scale densely annotated video driving (DAVID) data set generated using the CARLA simulator. We evaluate our approach on the real-world Cityscapes data set and the simulator-based DAVID data set. Our experimental results show that spatio-temporal failure prediction outperforms single-image failure prediction by up to 8.8%. Refining the prediction using a sequence of previous failure predictions further improves the performance by a significant 15.2% and allows to accurately predict misclassifications for future frames. While we focus our study on driving videos, the proposed approach is general and can be easily used in other scenarios as well."

# Summary. An optional shortened abstract.
summary: ""

tags:
- Teleoperated Driving
- Failure Prediction
featured: false

links:
- name: Conference
  url: https://www.2021.ieeeicip.org/
- name: Proceedings
  url: https://doi.org/10.1109/ICIP42928.2021
url_pdf: "https://www.researchgate.net/publication/352743076_Pixel-Wise_Failure_Prediction_for_Semantic_Video_Segmentation"
url_code: ''
url_dataset: 'https://mediatum.ub.tum.de/1596437'
url_poster: ''
url_project: 'https://www.researchgate.net/project/Failure-Prediction-in-Autonomous-Driving'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- research

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
