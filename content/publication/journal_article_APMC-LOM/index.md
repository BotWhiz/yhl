---
title: "APMC-LOM: Accurate 3D LiDAR Odometry and Mapping based on Pyramid Warm-Up Registration and Multi-Constraint Optimization"
authors:
- admin
- Haiming Gao
- Jin Shi
- Chenglong Xu
- Daokui Qu
- Wei Hua
author_notes:
- "Lead author"
- ""
date: "2024-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Vehicular Technology*"
publication_short: "*IEEE TVT*"

abstract: Simultaneous localization and mapping (SLAM) based on LiDAR plays a pivotal role in many unmanned systems, but currently suffers from drift in trajectory estimation and lacks robustness, resulting in inconsistent global maps. This paper proposes an accurate and robust LiDAR SLAM system to achieve low-drift ego-motion estimation and globally consistent mapping for unmanned ground vehicles (UGVs) in diverse environments. Firstly, a pyramid warm-up registration method is proposed to directly match the current scan with the map without feature extraction. More importantly, it utilizes the original geometric information to improve the registration accuracy and adopts a fast covariance matrix calculation method to greatly enhance the registration speed. Secondly, a submap generation method is proposed by formulating an anti-slip strategy and a point cloud similarity metric. It effectively prevents the loss of critical information while establishing strong constraints between keyframes and the map. Finally, a local-to-global optimization factor graph is constructed by establishing multi-level constraint relationships to optimize the overall system accuracy. The proposed method is compared with the current state-of-the-art LiDAR SLAM methods on several challenging datasets, including the KITTI, NeBula, and Newer College datasets. Experimental results show that our method has higher trajectory estimation accuracy and map consistency, and performs robustly in disparate environments. The corresponding code can be accessed at [https://github.com/BotWhiz/APMC-LOM](https://github.com/BotWhiz/APMC-LOM).

# Summary. An optional shortened abstract.
summary: This paper proposes a robust LiDAR SLAM system for UGVs, improving trajectory estimation accuracy and mapping consistency across diverse environments, validated on challenging datasets like KITTI and NeBula.

tags:
- LiDAR SLAM
- Ego-motion Estimation
- UGV
- Mapping
- Multi-Constraint Optimization

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: ""
url_code: 'https://github.com/BotWhiz/APMC-LOM'
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

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
