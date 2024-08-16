---
title: "An Efficient Online Trajectory Generation Method Based on Kinodynamic Path Search and Trajectory Optimization for Human-Robot Interaction Safety"
authors:
- admin
- Daokui Qu
- Fang Xu
- Zhenjun Du
- Kai Jia
- Mingmin Liu
author_notes:
- "Lead author"
- ""
date: "2022-04-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-04-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Entropy, 24*(5)"
publication_short: "*Entropy*"

abstract: |
  With the rapid development of robot perception and planning technology, robots are gradually getting rid of fixed fences and working closely with humans in shared workspaces. The safety of human-robot coexistence has become critical. Traditional motion planning methods perform poorly in dynamic environments where obstacle motion is highly uncertain. In this paper, we propose an efficient online trajectory generation method to help manipulator autonomous planning in dynamic environments. Our approach starts with an efficient kinodynamic path search algorithm that considers the links constraints and finds a safe and feasible initial trajectory with minimal control effort and time. To increase the clearance between the trajectory and obstacles and improve the smoothness, a trajectory optimization method using the B-spline convex hull property is adopted to minimize the penalty of collision cost, smoothness, and dynamical feasibility. To avoid collisions between the links and obstacles and the collisions of the links themselves, a constraint-relaxed links collision avoidance method is developed by solving a quadratic programming problem. Compared with the existing state-of-the-art planning method for dynamic environments and advanced trajectory optimization method, our method can generate a smoother, collision-free trajectory in less time with a higher success rate. Detailed simulation comparison experiments, as well as real-world experiments, are reported to verify the effectiveness of our method.

# Summary. An optional shortened abstract.
summary: This paper presents an efficient online trajectory generation method for manipulators in dynamic environments, focusing on safety in human-robot interaction through kinodynamic path search and trajectory optimization.

tags:
- Online Trajectory Generation
- Kinodynamic Path Search
- Human-Robot Interaction
- Collision Avoidance
- Trajectory Optimization

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: "https://www.mdpi.com/1099-4300/24/5/653"
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
