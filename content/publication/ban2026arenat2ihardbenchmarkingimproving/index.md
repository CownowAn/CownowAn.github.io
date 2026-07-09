---
title: 'Arena-T2I Hard: Benchmarking and Improving Faithfulness with Dependency-Aware Checklist'
authors:
- Yuanhao Ban
- Tong Xie
- Sohyun An
- Yunqi Hong
- Evan Frick
- I-Hung Hsu
- Wei-Lin Chiang
- Ion Stoica
- Cho-Jui Hsieh
date: '2026-06-30'
publishDate: '2026-06-30T13:06:13.819600Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: 'Faithfulness -- how precisely a generated image aligns with its prompt -- is increasingly central to the real-world utility of text-to-image (T2I) models. Existing faithfulness benchmarks, however, rely on simple atomic instructions, on which top-tier systems already achieve near-perfect scores. As T2I models enter creative workflows, users issue multi-faceted requests combining intricate spatial relationships, stylistic constraints, and complex text rendering. In this setting, a single binary VLM-judge score no longer captures which specific constraints the model fails to satisfy. We introduce Arena-T2I Hard, a 310-prompt stress benchmark drawn from real arena T2I logs, with approximately 30 decomposed yes/no constraints per prompt spanning six categories, including text rendering. The strongest closed-source system we evaluate reaches 0.855 with a 33~pp performance gap across 11 systems, demonstrating substantial discriminative power. Moreover, high public-arena rankings fail to predict faithfulness, confirming that holistic Bradley-Terry (BT) preference scores prioritize aesthetics over fine-grained prompt adherence. We propose a dependency-aware checklist reward that decomposes each prompt into a DAG of yes/no questions and zeroes descendants of failed parents, turning faithfulness into a per-constraint training signal. Combined with a BT aesthetic reward via group-decoupled normalization (GDPO), which standardizes each reward within its rollout group so neither collapses, the recipe attains a strictly better faithfulness-aesthetics trade-off on SD3.5-Medium and FLUX.1-dev under MMRB2 pairwise comparisons than every single-reward, naive weighted-sum, or 4-reward BT-ensemble baseline.
tags:
- Text-to-Image
- Reward Modeling
- Reinforcement Learning
- Benchmark
links:
- name: Paper
  url: https://arxiv.org/abs/2606.31711
- name: Project
  url: https://banyuanhao.github.io/Arena-T2I-Hard-Page/
- name: Code
  url: https://github.com/banyuanhao/Arena-T2I-Hard
- name: Dataset
  url: https://huggingface.co/datasets/lmarena-ai/Arena-T2I-Hard
---
