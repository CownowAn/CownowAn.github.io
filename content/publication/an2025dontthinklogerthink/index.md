---
title: Don't Think Longer, Think Wisely: Optimizing Thinking Dynamics for Large Reasoning Models
authors:
- Sohyun An
- Ruochen Wang
- Tianyi Zhou
- Cho-Jui Hsieh
date: '2025-05-27'
publishDate: '2025-05-27T20:59:29Z'
publication_types:
- manuscript
publication: '*Under Review*'
# doi: 10.48550/arXiv.2305.16943
abstract: While recent success of large reasoning models (LRMs) significantly advanced LLMs' reasoning capability by optimizing the final answer accuracy using reinforcement learning, they may also drastically increase the output length due to overthinking, characterized by unnecessarily complex reasoning paths that waste computation and potentially degrade the performance. We hypothesize that such inefficiencies stem from LRMs' limited capability to dynamically select the proper modular reasoning strategies, termed thinking patterns at the right position. To investigate this hypothesis, we propose a dynamic optimization framework that segments model-generated reasoning paths into distinct thinking patterns, systematically identifying and promoting beneficial patterns that improve the answer while removing detrimental ones. Empirical analysis confirms that our optimized thinking paths yield more concise yet sufficiently informative trajectories, enhancing reasoning efficiency by reducing attention FLOPs by up to 47% while maintaining accuracy for originally correct responses. Moreover, a non-trivial portion of originally incorrect responses are transformed into correct ones, achieving a 15.6% accuracy improvement with reduced length. Motivated by the improvement brought by the optimized thinking paths, we apply a preference optimization technique supported by a pairwise dataset contrasting suboptimal and optimal reasoning paths. Experimental evaluations across multiple mathematical reasoning benchmarks reveal that our method notably reduces computational overhead while simultaneously improving reasoning accuracy, achieving up to a 12% accuracy improvement and reducing token usage from approximately 5,000 to 3,000 tokens.
tags:
- Large Language Models
- Preference Learning
- Reasoning
- Large Reasoning Models
- Overthinking
links:
- name: PDF
  url: https://arxiv.org/abs/2505.21765
---
