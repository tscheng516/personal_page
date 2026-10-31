---
permalink: /
title: "Tin Sum Cheng"
excerpt: "Postdoctoral researcher in machine learning: multimodal foundation models, AI for healthcare and AI for science."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a postdoctoral researcher at the [University of Basel](https://dbe.unibas.ch/en/aich/) in the *Analytics & Informatics for Child Health* (AICH) group, working on **uncertainty quantification for multimodal foundation models in pediatric healthcare**.
I completed my PhD in Machine Learning in 2026 under [Aurelien Lucchi](https://omls.dmi.unibas.ch/en/persons/aurelien-lucchi/), with a thesis on the spectral analysis of feature embeddings in deep learning.

I work across the full stack of foundation models, from the theory of why they generalize down to the GPU kernels that train them, and I enjoy working with domain experts such as clinicians, chemists and engineers.

News
======

{% for item in site.data.news limit: 5 -%}
* **{{ item.date }}:** {{ item.text }}
{% endfor %}

What I work on
======

* **Multimodal & foundation models**: pre-training and fine-tuning of language transformers (OLMo, nanochat), vision transformers (ViT, DeiT) and vision-language models (CLIP).
* **AI for healthcare**: uncertainty quantification and reliable multimodal models for pediatric medicine.
* **AI for science**: kernels, GNNs and pretrained embeddings for molecular property prediction, in collaboration with chemists.
* **AI engineering**: custom Triton/C kernels (MatMul, BMM) at the Huawei Hong Kong Research Center, and reproducible multi-GPU SLURM pipelines with Weights & Biases.
* **Theory behind the practice**: generalization of kernel methods, neural collapse, optimizer behaviour and transformer training instability.

Selected publications
======

* **Optimizer Choice Matters for the Emergence of Neural Collapse**. ICLR 2026. [arXiv](https://arxiv.org/abs/2602.16642)
* **Spectral Analysis of Molecular Features: When Richer Features Do Not Guarantee Better Generalization**. TMLR. [arXiv](https://arxiv.org/abs/2510.14217) · [OpenReview](https://openreview.net/forum?id=teXV1OiQCo)
* **A Comprehensive Analysis on the Learning Curve in Kernel Ridge Regression**. NeurIPS 2024. [arXiv](https://arxiv.org/abs/2410.17796)
* **Characterizing Overfitting in Kernel Ridgeless Regression Through the Eigenspectrum**. ICML 2024. [arXiv](https://arxiv.org/abs/2402.01297)
* **A Theoretical Analysis of the Test Error of Finite-Rank Kernel Ridge Regression**. NeurIPS 2023.

[All publications]({{ site.baseurl }}/publications/) · [Google Scholar](https://scholar.google.com/citations?user=5wfAh9kAAAAJ) · [Download CV]({{ site.baseurl }}/files/Tin_Sum_Cheng_CV.pdf)

Get in touch
======

I am happy to talk about collaborations, and about research or applied-science roles in multimodal learning, AI for healthcare and AI for science. Reach me by [email](mailto:tinsum.cheng@unibas.ch), on [LinkedIn](https://www.linkedin.com/in/tinsumcheng/) or [GitHub](https://github.com/tscheng516).
