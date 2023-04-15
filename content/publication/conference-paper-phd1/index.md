---
title: "D2D-Based Cellular-Connected UAV Swarm Control Optimization via Graph-Aware DRL"
authors:
- admin
- Hui Zhou
- Yansha Deng
date: "2023-01-11T00:00:00Z"
doi: "10.1109/GLOBECOM48099.2022.10001506"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-01-11T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: 2022 IEEE Global Communications Conference
publication_short: GLOBECOM 2022

abstract: Cellular-connected unmanned aerial vehicle (UAV) swarm is a promising solution for diverse applications, including cargo delivery and traffic control. However, it is still challenging to communicate with and control the UAV swarm with high reliability and low latency. In this paper, we propose a two-phase command and control (C&C) transmission scheme in cellular-connected UAV swarm network, where the ground base station (GBS) broadcasts the common C&C message in Phase I, the UAVs that have successfully decoded the C&C message will then relay the message to the rest of UAVs via device-to-device (D2D) communications under individual latency constraint. To maximize the number of UAVs that receive the message successfully within the latency constraint, we formulate the problem as a decentralized and partially observable Markov process for finding the optimal policies. To address this problem, we further develop a fully decentralized graph attention network (GAT)-based reinforcement learning algorithm to optimize the D2D pair selection, where the GAT is utilized to exploit the dynamic topology information of cellular-connected UAV swarm network. Simulation results show that our algorithm outperforms the other two baselines and could achieve a cooperative target under a mobile UAV swarm scenario.

# Summary. An optional shortened abstract.
summary: 

tags:
- Source Themes
featured: true

links:
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
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

