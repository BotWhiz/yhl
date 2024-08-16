---
title: "Approach for Accurate Calibration of RGB-D Cameras Using Spheres"
authors:
- admin
- Daokui Qu
- Fang Xu
- Fengshan Zou
- Jilai Song
- Kai Jia
author_notes:
- "Lead author"
- ""
date: "2022-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-06-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Optics Express, 28*(13)"
publication_short: "*Opt. Express (JCR Q1, 中科院TOP期刊)*"

abstract: |
  RGB-D cameras (or color-depth cameras) play key roles in many vision applications. A typical RGB-D camera has only rough intrinsic and extrinsic calibrations that cannot provide the accuracy required in many vision applications. In this paper, we propose a novel and accurate sphere-based calibration framework for estimating the intrinsic and extrinsic parameters of color-depth sensor pair. Additionally, a method of depth error correction is suggested, and the principle of error correction is analyzed in detail. In our method, the feature extraction module can automatically and reliably detect the center and edges of the sphere projection, while excluding noise data and outliers, and the projection of the sphere center on RGB and depth images is used to obtain a closed solution of the initial parameters. Finally, all the parameters are accurately estimated within the framework of nonlinear global minimization. Compared to other state-of-the-art methods, our calibration method is easy to use and provides higher calibration accuracy. Detailed experimental analysis is performed to support our conclusions.

# Summary. An optional shortened abstract.
summary: This paper presents a novel sphere-based calibration framework for RGB-D cameras, improving intrinsic and extrinsic parameter accuracy as well as depth error correction, with experimental results demonstrating superior calibration performance.

tags:
- RGB-D Cameras
- Camera Calibration
- 3D Reconstruction
- Machine Vision
- Point Clouds
- Structured Light

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: "https://opg.optica.org/oe/fulltext.cfm?uri=oe-28-13-19058&id=432581"
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
