---
title: "Real-time and Efficient Collision Avoidance Planning Approach for Safe Human-Robot Interaction"
authors:
- admin
- Daokui Qu
- Fang Xu
- Zhenjun Du
- Kai Jia
- Jilai Song
- Mingmin Liu
author_notes:
- "Lead author"
- ""
date: "2022-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-04-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Intelligent & Robotic Systems, 105*(4)"
publication_short: "*J. Intell. Robot. Syst.*"

abstract: |
  With the rapid development of robot perception and planning technology, robots are gradually getting rid of fixed fences and working closely with humans in a shared workspace. The safety of human-robot coexistence becomes critical. Although various safety-related motion planning methods have been proposed to prevent robots from colliding with obstacles, collision avoidance planning in highly dynamic environments is still an open problem. In this paper, we propose a robust and efficient collision avoidance planning method that generates a collision-free trajectory in real-time by leveraging the complementary strengths of the potential field and optimization. Our approach starts with a new repulsive force generation method that quickly generates collision avoidance actions even if obstacles are moving faster than the robot. To ensure that the robot avoids collisions while converging toward the goal, an optimization method based on quadratic programming is designed to minimize the deviation of the post-optimized trajectory from the reference trajectory by fusing the whole body collision avoidance constraints and constraints dimensionality reduction. Finally, a closed-loop safety protection framework is presented, including obstacle perception, collision avoidance planning, and multi-task optimization. Compared with the existing state-of-the-art collision avoidance planners as well as advanced trajectory optimization methods, our method can generate a shorter collision-free trajectory in less time with a higher success rate. Detailed simulation comparison experiments, as well as real-world comparison experiments, are reported to verify the effectiveness of our method.

# Summary. An optional shortened abstract.
summary: This paper presents a real-time, efficient collision avoidance planning method for safe human-robot interaction, offering faster, more successful collision-free trajectory generation compared to existing methods.

tags:
- Collision Avoidance
- Human-Robot Interaction
- Robot Planning
- Trajectory Optimization
- Real-Time Systems

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: "https://link.springer.com/article/10.1007/s10846-022-01687-0"
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/nUuXCuCmhkQ'

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
