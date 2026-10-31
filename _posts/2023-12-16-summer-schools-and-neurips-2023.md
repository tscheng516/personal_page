---
title: 'Summer schools and NeurIPS 2023: notes from the road'
date: 2023-12-16
permalink: /posts/2023/12/summer-schools-and-neurips-2023/
comments: false
share: false
redirect_from:
  - /posts/2023/07/genova/
  - /posts/2023/07/oxford/
  - /posts/2023/07/princeton/
  - /posts/2023/12/new_orleans_0/
  - /posts/2023/12/new_orleans_1/
  - /posts/2023/12/new_orleans_2/
  - /posts/2023/12/new_orleans_3/
  - /posts/2023/12/new_orleans_5/
  - /posts/2023/12/new_orleans_6/
tags:
  - summer school
  - conference
  - machine learning theory
---

A compact record of three summer schools and one conference in 2023, merged from my original blog posts.

Summer schools (June to July 2023)
======

* **[Princeton Machine Learning Theory](https://mlschool.princeton.edu), 26-30 June.** Dynamical mean field theory, Wasserstein gradient flow, high-dimensional deep learning, neural tangent kernel and feature learning, the replica method. Theory-heavy, with strong poster sessions and a research-focused atmosphere. *Theory 5/5, practice 1/5.*
* **[Topics in Modern Machine Learning, Genova](https://malga.unige.it/education/schools/modml), 19-23 June.** Implicit regularization, sketching and random features, reinforcement learning, inverse problems, optimal transport, fairness, and the interpolation regime and double descent. A good mix of lectures and hands-on exercises. *Theory 3/5, practice 4/5.*
* **[Oxford Machine Learning Summer School](https://www.oxfordml.school), 8-11 July (online).** Generative market simulators, financial time series, factor investing, robustness of NLP models, automated trading, quantum NLP. Broad and applied; many talks still used RNN/LSTM/GAN models rather than transformers and diffusion. *Theory 2/5, practice 2/5.*

NeurIPS 2023, New Orleans (10-16 December)
======

I presented [A Theoretical Analysis of the Test Error of Finite-Rank Kernel Ridge Regression]({{ site.baseurl }}/publication/neurips2023) at the poster session. Highlights of my week:

* **Smaller models can pack a punch.** With quantization and multi-LoRA, small fine-tuned models can beat generic pre-trained ones on downstream tasks. It pulls attention back from over-parametrization to the regularized, under-parametrized regime, where the open question is what pre-training and fine-tuning actually learn.
* **LLM inference from first principles.** A clear walk-through of why transformer inference is slow and how careful implementation speeds it up. Inference cost is a real bottleneck before scaling models further.
* **Reconsidering overfitting in the age of overparameterized models (tutorial).** Harmless overfitting seen through over-parametrized linear regression, close to my own research.
* **Randomized numerical linear algebra for ML (tutorial).** A call for user-friendly packages; I had run into the need to build such experiments from scratch myself.
* **Why babies learn so fast (invited talk).** Biased, structured learning rather than i.i.d. or Gaussian data assumptions may be the key to fast feature learning.
* **Workshops.** Diffusion models: different models trained on the same data map the same noise to nearly the same image, hinting at reproducibility in generative models. Mathematics of Modern ML: using group symmetries refines generalization bounds.
