---
title: "A Unifying Lens on Supervised Fine-Tuning Through Target Distribution Design"
authors:
- Tong Xie
- Yuanhao Ban
- Yunqi Hong
- Sohyun An
- Yihang Chen
- Cho-Jui Hsieh
date: '2026-06-09'
publishDate: '2026-06-09T13:06:13.819600Z'
publication_types:
- manuscript
publication: '*arXiv*'
# doi: 10.48550/arXiv.2305.16943
abstract: 'Supervised fine-tuning (SFT) typically maximizes the likelihood of every token in a demonstrated trajectory. However, an observed token can be non-unique, noisy, or misaligned with the model prior. Strictly fitting toward this one-hot target may be suboptimal, especially when the pretrained model encodes a rich knowledge prior. In this work, we reinterpret SFT as target distribution design: instead of studying only the loss objective, we analyze the token-level target that the loss drives the model to match. We introduce the Q-target framework, which decomposes SFT supervision into two explicit choices: (1) how strongly to rely on the observed token, and (2) how to allocate the remaining probability mass over alternatives. This perspective unifies many existing SFT variants as implicit choices of the target distribution Q. Building on this view, we propose Target-SFT which constructs the training objective directly from the desired target distribution. This method consistently outperforms across the ten reasoning dataset-model settings evaluated, showing the effectiveness of this target-based approach. Overall, our formulation reveals a more fundamental design principle for SFT training and opens a broader search space for SFT objectives.'
tags:
- Large Language Models
- SFT
links:
- name: Paper
  url: https://arxiv.org/abs/2606.11189
- name: Project
  url: https://txie1.github.io/Target-SFT/
- name: Code
  url: https://github.com/txie1/Target-SFT
---
