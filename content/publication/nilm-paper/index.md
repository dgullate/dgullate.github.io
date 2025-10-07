---
title: "Thresholding Methods in Non-Intrusive Load Monitoring"
authors:
- Daniel Precioso
- admin
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2023-02-28T00:00:00Z"       # Acceptance date
doi: "10.1007/s11227-023-05149-8"

# Schedule page publish date (NOT publication's date)
publishDate: "2023-04-01T00:00:00Z"

# Publication type (CSL)
publication_types: ["article-journal"]

# Journal info
publication: "*The Journal of Supercomputing* (2023) 79:14039–14062"
publication_short: "J. Supercomput."

abstract: |
  Non-intrusive load monitoring (NILM) is the problem of predicting the status or consumption of individual domestic appliances from the aggregated power load. This paper investigates a fundamental methodological issue: how different thresholding strategies for converting continuous power signals into binary ON/OFF labels impact the formulation and performance of NILM classification models. We evaluate three approaches — middle-point, variance-sensitive, and activation-time thresholding — using standard NILM datasets and state-of-the-art deep learning architectures (convolutional and bidirectional GRU models). We analyze how these thresholding methods influence classification accuracy, regression error, and model interpretability, and propose a multitask learning modification that jointly addresses regression and classification through transfer learning. The paper provides practical guidance on selecting thresholding strategies and highlights open challenges for multi-state and fully automated NILM formulations.

summary: |
  This study examines how thresholding strategies shape the formulation of NILM classification problems and their influence on deep learning model performance.

tags:
- Non-Intrusive Load Monitoring
- Deep Learning
- Neural Networks
- Energy Disaggregation
- Machine Learning
- Thresholding Methods

featured: true

url_pdf: "https://link.springer.com/article/10.1007/s11227-023-05149-8"
url_code: "https://github.com/UCA-Datalab/nilm-thresholding"
url_dataset: "https://data.ukedc.rl.ac.uk/browse/edc/efficiency/residential/EnergyConsumption/Domestic/UK-DALE-2015"
url_project: ""
url_slides: ""
url_poster: ""
url_source: ""
url_video: ""

image:
  caption: 'Figure from the paper: Comparison of thresholding methods applied to appliance power load (Precioso & Gómez-Ullate, 2023)'
  focal_point: "center"
  preview_only: false

projects: []

slides: ""

---
