---
title: 'Collision-Free Motion Planning Method Based on Online Trajectory Generation in High Dimensional Dynamic Workspace  (** Best Paper Finalist ** )'
authors:
  - admin
  - Daokui Qu
  - Fang Xu
  - Zhenjun Du
  - Kai Jia
  - Mingmin Liu

date: '2022-01-01T00:00:00Z'
doi: ''

publishDate: '2022-07-01T00:00:00Z'

publication_types: ['paper-conference']

publication: In *2022 IEEE International Conference on Real-time Computing and Robotics (RCAR)*
publication_short: In *RCAR 2022*

abstract: This paper proposes a novel and effective online trajectory generation method to help 6 DOF non-redundant manipulators avoid dynamic obstacles. The proposed method decouples the robot motion planning in the task space into front-end path search and back-end trajectory optimization modules. The path planning module uses the constraint-based kinodynamic path search approach to generate a safe and feasible initial trajectory. In the following stage, the cubic B-spline-based trajectory optimization method is adopted to minimize the penalty of collision cost, smoothness, and dynamical feasibility. The optimization method of the links collision avoidance based on constraint relaxation is integrated into the online trajectory planning task. The task space trajectory is converted to the joint space based on the robot inverse kinematics. Detailed simulations and real-world experiments are reported to demonstrate the effectiveness of our approach.

summary: This paper introduces an online trajectory generation method to help 6 DOF manipulators avoid dynamic obstacles, incorporating path planning, trajectory optimization, and inverse kinematics to ensure smooth and collision-free motion.

tags:
  - Online Trajectory Generation
  - Robot Motion Planning
  - Dynamic Workspace
  - 6 DOF Manipulators
  - Collision Avoidance

featured: true

url_pdf: 'https://ieeexplore.ieee.org/document/9872205'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

projects: []
slides: ""
---

### Video
<video width="640" height="360" controls>
  <source src="{{< relURL "videos/cf.mp4" >}}" type="video/mp4">
  Your browser does not support the video tag.
</video>
