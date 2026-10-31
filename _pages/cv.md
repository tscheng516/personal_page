---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download as PDF]({{ base_path }}/files/Tin_Sum_Cheng_CV.pdf)

Summary
======
Postdoctoral researcher and machine learning scientist working across the full stack of foundation models, from model design to kernel optimization in large-scale training. Publications at NeurIPS (×2), ICML, ICLR and TMLR. Industry experience at Huawei's Research Center. Regularly the bridge between ML and non-ML stakeholders, having worked alongside chemists and engineers on cross-disciplinary problems.

Experience
======
**Postdoctoral Researcher**, University of Basel, Switzerland (AICH group), Oct 2026 – present
* Uncertainty quantification for multimodal foundation models in pediatric healthcare

**PhD in Computer Science (Machine Learning)**, University of Basel, Switzerland, Feb 2022 – Sep 2026
* Pre-training and fine-tuning of large-scale foundation models on text (nanochat), image (ViT), molecules (GNN) and multimodal data (CLIP)
* Designed reproducible ML experiment pipelines on HPC GPU clusters with Weights & Biases tracking and GitHub documentation

**Research Intern**, Huawei Hong Kong Research Center, Aug 2025 – Jan 2026
* Optimized core matrix operators (MatMul, BMM) for next-generation hardware using C and Triton, improving computational efficiency by up to 60% in large-scale environments
* Prototyped and integrated a neural network module into a legacy industrial system, improving prediction accuracy by 75%

Education
======
* **PhD in Computer Science (Machine Learning)**, University of Basel, Feb 2022 – Sep 2026. Thesis: *Spectral Analysis of Feature Embeddings in Modern Deep Learning: Theory of Optimization and Generalization*. Supervisor: Prof. Dr. Aurelien Lucchi
* **MSc in Mathematics**, University of Bonn, Mar 2019 – Sep 2021
* **BSc in Mathematics**, The Chinese University of Hong Kong, Sep 2014 – Sep 2018

Core competences
======
* **Programming & frameworks:** Python, PyTorch, Triton (custom kernels)
* **Models:** kernel methods, language transformers (OLMo, nanochat), vision transformers (ViT, DeiT), multimodal models (CLIP)
* **Infrastructure & tools:** SLURM, multi-GPU training, Linux, Docker, Git, Weights & Biases

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Summer schools
======
* [Oxford Machine Learning Summer School](https://www.oxfordml.school/program), July 2023
* [Princeton Machine Learning Theory Summer School](https://mlschool.princeton.edu/#courses), June 2023
* [Topics in Modern Machine Learning, University of Genova](https://malga.unige.it/education/schools/modml), June 2023

Languages
======
English (fluent, C1) · German (fluent, C1) · Chinese (native)
