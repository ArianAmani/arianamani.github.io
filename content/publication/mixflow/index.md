---
title: "Shortest-Path Flow Matching with Mixture-Conditioned Bases for OOD Generalization to Unseen Conditions"
authors:
- Andrea Rubbi
- Amir Akbarnejad
- Mohammad Vali Sanian
- Aryan Yazdan Parast
- Hesam Asadollahzadeh
- Arian Amani
- Naveed Akhtar
- Sarah Cooper
- Andrew Bassett
- Pietro Liò
- Lassi Paavolainen
- Sattar Vakili
- Mo Lotfollahi

author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
date: "2026-02-11T00:00:00Z"
doi: "10.48550/arXiv.2601.11827"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-01-16T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "arXiv"
publication_short: "arXiv"

abstract: "Robust generalization under distribution shift remains a key challenge for conditional generative modeling: conditional flow-based methods often fit the training conditions well but fail to extrapolate to unseen ones. We introduce SP-FM, a shortest-path flow-matching framework that improves out-of-distribution (OOD) generalization by conditioning both the base distribution and the flow field on the condition. Specifically, SP-FM learns a condition-dependent base distribution parameterized as a flexible, learnable mixture, together with a condition-dependent vector field trained via shortest-path flow matching. Conditioning the base allows the model to adapt its starting distribution across conditions, enabling smooth interpolation and more reliable extrapolation beyond the observed training range. We provide theoretical insights into the resulting conditional transport and show how mixture-conditioned bases enhance robustness under shift. Empirically, SP-FM is effective across heterogeneous domains, including predicting responses to unseen perturbations in single-cell transcriptomics and modeling treatment effects in high-content microscopy--based drug screening. Overall, SP-FM provides a simple yet effective plug-in strategy for improving conditional generative modeling and OOD generalization across diverse domains."

# Summary. An optional shortened abstract.
summary: "SP-FM introduces a shortest-path flow-matching framework with mixture-conditioned bases to improve out-of-distribution generalization in conditional generative modeling, enabling better extrapolation to unseen conditions."

tags:
- Machine Learning
- Flow Matching
- Generative Models
- Out-of-Distribution Generalization
- Conditional Generative Modeling
featured: true

links:
- name: "arXiv"
  url: "https://arxiv.org/abs/2601.11827"
url_pdf: 'https://arxiv.org/pdf/2601.11827.pdf'
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
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
projects:
- sp-fm

---
