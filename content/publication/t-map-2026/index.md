---
title: 'T-MAP: Red-Teaming LLM Agents with Trajectory-aware Evolutionary Search'
authors:
- Hyomin Lee
- Sangwoo Park
- Yumin Choi
- Sohyun An
- Seanie Lee
- Sung Ju Hwang
date: '2026-03-21'
publishDate: '2026-03-21T00:00:00.000000Z'
publication_types:
- manuscript
publication: '*EMNLP 2026*'
# doi: 10.48550/arXiv.2305.16943
abstract: 'While prior red-teaming efforts have focused on eliciting harmful text outputs from large language models (LLMs), such approaches fail to capture agent-specific vulnerabilities that emerge through multi-step tool execution, particularly in rapidly growing ecosystems such as the Model Context Protocol (MCP). To address this gap, we propose a trajectory-aware evolutionary search method, T-MAP, which leverages execution trajectories to guide the discovery of adversarial prompts. Our approach enables the automatic generation of attacks that not only bypass safety guardrails but also reliably realize harmful objectives through actual tool interactions. Empirical evaluations across diverse MCP environments demonstrate that T-MAP substantially outperforms baselines in attack realization rate (ARR) and remains effective against frontier models, including GPT-5.2, Gemini-3-Pro, Qwen3.5, and GLM-5, thereby revealing previously underexplored vulnerabilities in autonomous LLM agents.'
tags:
- LLM
- Agents
- Red-Teaming
- Search
links:
- name: Paper
  url: https://arxiv.org/abs/2603.22341
- name: Code
  url: https://github.com/pwnhyo/T-MAP
---
