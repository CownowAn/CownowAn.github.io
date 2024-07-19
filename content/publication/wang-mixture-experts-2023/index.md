---
title: "One Prompt is not Enough: Automated Construction of a Mixture-of-Expert Prompts"
authors:
- Ruochen Wang*
- Sohyun An*
- Minhao Cheng
- Tianyi Zhou
- Sung Ju Hwang
- Cho-Jui Hsieh
date: '2024-02-01'
publishDate: '2024-02-27T13:06:13.827525Z'
publication_types:
- manuscript
publication: '*ICML 2024*'
abstract: 'Large Language Models (LLMs) exhibit strong generalization capabilities to novel tasks when prompted with language instructions and in-context demos. Since this ability sensitively depends on the quality of prompts, various methods have been explored to automate the instruction design. While these methods demonstrated promising results, they also restricted the searched prompt to one instruction. Such simplification significantly limits their capacity, as a single demo-free instruction might not be able to cover the entire complex problem space of the targeted task. To alleviate this issue, we adopt the Mixture-of-Expert paradigm and divide the problem space into a set of sub-regions; Each sub-region is governed by a specialized expert, equipped with both an instruction and a set of demos. A two-phase process is developed to construct the specialized expert for each region: (1) demo assignment: Inspired by the theoretical connection between in-context learning and kernel regression, we group demos into experts based on their semantic similarity; (2) instruction assignment: A region-based joint search of an instruction per expert complements the demos assigned to it, yielding a synergistic effect. The resulting method, codenamed Mixture-of-Prompts (MoP), achieves an average win rate of 81% against prior arts across several major benchmarks.'
tags:
- Large Language Models
- Prompt Optimization
- Multiple-of-Experts
links:
- name: PDF
  url: https://arxiv.org/abs/2407.00256
---
