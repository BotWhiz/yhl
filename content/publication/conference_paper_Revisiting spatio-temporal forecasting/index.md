---
title: 'Revisiting Spatio-Temporal Forecasting: Feature Propagation Carry More Weights Than How They Do'
authors:
  - Shen Fang
  - admin
  - Chengcheng Yu
  - Tian Xie
  - Wei Hua

date: '2024-01-01T00:00:00Z'
doi: ''

publishDate: '2024-01-01T00:00:00Z'

publication_types: ['paper-conference']

publication: In *IEEE 27th International Conference on Intelligent Transportation Systems (ITSC)*
publication_short: In *ITSC 2024*

abstract: Spatio-temporal forecasting, a prominent research focus for understanding the dynamics of data flow in various domains, has recently extended its significance to traffic prediction as a notable application. Considering topology of data flow, existing methods mainly utilize Graph Convolutional Networks (GCNs), where graph construction is the basic concern and generally determines how data features are propagated. However, through extensive investigations and theoretical evidence, it is revealed that graph construction strategy, which is usually regarded as the key step to success, has actually provided very little benefit, while the presence of feature propagation itself on spatio-temporal domain is more significant, i.e., feature propagation carry more weights than how they do. Thus, by making slight refinements of a feature normalization method, we propose a Spatio-Temporal Propagation (STP) module, which does not require intervention of a specific graph structure, yet simple and effective. Various experiments on public datasets verify that the proposed STP module is an on-the-shelf tool that can be accessed to the end of current models or even replace GCNs as an alternative for capturing spatio-temporal features, while achieving better predictions. All the source codes are open accessed on GitHub.

summary: This paper revisits spatio-temporal forecasting, showing that feature propagation in data flow is more significant than the method of graph construction. The proposed Spatio-Temporal Propagation (STP) module outperforms GCNs in traffic prediction without the need for specific graph structures.

tags:
  - Spatio-Temporal Forecasting
  - Feature Propagation
  - Intelligent Transportation Systems
  - Graph Convolutional Networks

keywords: 
  - Data Mining and Data Analysis
  - Network Modeling
  - Off-line and Online Data Processing Techniques

featured: true

url_pdf: 'https://its.papercept.net/conferences/scripts/abstract.pl?ConfID=87&Number=201'
url_code: 'https://github.com/YourRepo/STP_module'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

projects: []
slides: ""
---
