---
title: "CT-BSO: Accurate LiDAR Odometry and Mapping System for Ground Vehicles Based on Continuous-Time Trajectory Modeling and B-Spline Optimization"
authors:
- admin
- Shen Fang
- Haiming Gao
- Wei Hua
author_notes:
- "Lead author"
- ""
date: "2023-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Automotive Innovation*"
publication_short: ""

abstract: |
  Simultaneous Localization and Mapping (SLAM) methods play a crucial role in robotics and autonomous driving. However, existing methods still face challenges in achieving accurate pose estimation and consistent map construction for unmanned ground vehicles (UGVs) in complex environments. In this paper, we propose a two-stage continuous-time trajectory modeling and optimization method using only LiDAR data to improve trajectory accuracy and help UGVs achieve low-drift ego-motion estimation. Our approach combines B-splines and linear interpolation to represent LiDAR motion with a continuous-time trajectory model and introduces sparse Levenberg-Marquardt optimization and a new marginalization strategy during the optimization process. By integrating fine geometric information from LiDAR points with dynamic constraints in trajectory modeling, our method ensures high accuracy and coherence in motion estimation. Comprehensive evaluations on several public datasets, including the KITTI odometry dataset and NeBula dataset, demonstrate that our proposed method outperforms existing state-of-the-art LiDAR SLAM methods in trajectory estimation accuracy, significantly enhancing both trajectory estimation precision and map construction consistency.

# Summary. An optional shortened abstract.
summary: This paper introduces CT-BSO, a LiDAR odometry and mapping system that improves trajectory accuracy and consistency for unmanned ground vehicles using continuous-time trajectory modeling and B-spline optimization.

tags:
- LiDAR Odometry
- SLAM
- UGV
- B-Spline Optimization
- Continuous-Time Trajectory

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   Otherwise, set `slides: ""`.
slides: ""
---
