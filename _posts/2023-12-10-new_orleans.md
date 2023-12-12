---
title: 'Blog Post: Neurips2023'
date: 2023-12-10
permalink: /posts/2023/12/new_orleans/
tags:
  - neurips
  - conference
---

Conference blog.

I am attending [Thirty-seventh Conference on Neural Information Processing Systems](https://neurips.cc/virtual/2023/calendar) (Neurips2023) now and I am happy to share my experience with you all. I will write a short summary every day.

# LLM is the word of the year?
The word LLM(large language models) appears talk I have attended today and it is really a hit this year due to the emergence of powerful chatbots. Many empirical and theoretical understandings are still missing and I am fascinated to find ourselves in this age of exploration!


Talks I have attended
======
* [Smaller models can pack a punch in the era of Large Language Models](https://neurips.cc/Expo/Conferences/2023/talk%20panel/78244)

TLDR: Yes, smaller models can beat generic pre-trained models in downstream task. Popular techniques are quantization (forcing the weight to be 8-bits in training instead of 16-bits) and multi-LoRA (low rank adaptation for multi-task learning).

Comment: While deep neural networks, over-parametrization and benign overfitting were the hit in recent years, the emergence of pre-trained LLM together with fine-tuning drags the focus back to the under-parametrized and regularized regime, where both the datasets (in few-shot learning, or in-context learning) and the model (LoRA, for example) are small but the task space is enorm (for example, any downstream classification tasks). What are the difference between the traditional method of regularized regression and fine-tunging after the (auto-regressive) pre-training? What is indeed happening in pre-training? How does the dataset itself play a role in the training? What is the feature learned in the pre-training and fine tuning phase? How can one formally conceptualize and define them?

* [Optimizing and Reasoning about LLM Inference: from First Principles to SOTA Techniques](https://neurips.cc/Expo/Conferences/2023/talk%20panel/78245) (Highlight of my day)

TLDR: LLM like ChatGPT-4 is slow in inference (the time needed to read the prompt and output a response). There are some ways to speed the inference time by careful implementations on transformers. 

Comment: Very good talk which brings the audience into the details of inference of transformer network. Simple math and clear explanation on how the improvement can speed up the inference. Slow inference is really a bottleneck for LLM, for example ChatGPT-4 is way larger than 3.5, but it suffers from a much slower inference. This is a practical problem which one has to solve before scaling-up the models.

* [Understanding the Effectiveness of Large Language Models in Code Translation](https://neurips.cc/Expo/Conferences/2023/talk%20panel/78249)

TLDR: LLM fails in real-world code translation, despite its super-human performance in natural language translation. The errors are marked and categorized by expert coders and computer scientists and one can have to look on where the machine fails.

Comment: A good exploration step. Coders can relieve for now as it still takes time for AI to take over the job. :p  

* [Reinforcement Learning: Trends, Applications, and Challenges](https://neurips.cc/Expo/Conferences/2023/talk%20panel/78250)

TLDR: Brief summary of what is on the field. The application of RL (reinforcement learning) in robotics, finance and industry is ubiquitous.

Comment: My favorite part is the application on RL on solving constrained optimization problem:
$ \min \{  f(x):g(x)\leq 0  \}  $
where the objective and the constraint functions $f,g$ are hard to compute and only accessible by simulations. RL helps approximating the functions as well as run the optimization at the same time.

Extras
======
* The melons and berries offered in the break sessions are very sweet. :)
