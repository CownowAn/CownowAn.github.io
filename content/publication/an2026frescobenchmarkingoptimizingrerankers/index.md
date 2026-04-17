---
title: 'FRESCO: Benchmarking and Optimizing Re-rankers for Evolving Semantic Conflict in Retrieval-Augmented Generation'
authors:
- Sohyun An
- Hayeon Lee
- Shuibenyang Yuan
- Chun-cheng Jason Chen
- Vijai Mohan
- Cho-Jui Hsieh
- Alexander Min
date: '2026-03-21'
publishDate: '2026-03-21T00:00:00.000000Z'
publication_types:
- manuscript
publication: '*arXiv*'
# doi: 10.48550/arXiv.2305.16943
abstract: 'Retrieval-Augmented Generation (RAG) is a key approach to mitigating the temporal staleness of large language models (LLMs) by grounding responses in up-to-date evidence. Within the RAG pipeline, re-rankers play a pivotal role in selecting the most useful documents from retrieved candidates. However, existing benchmarks predominantly evaluate re-rankers in static settings and do not adequately assess performance under evolving information -- a critical gap, as real-world systems often must choose among temporally different pieces of evidence. To address this limitation, we introduce FRESCO (Factual Recency and Evolving Semantic COnflict), a benchmark for evaluating re-rankers in temporally dynamic contexts. By pairing recency-seeking queries with historical Wikipedia revisions, FRESCO tests whether re-rankers can prioritize factually recent evidence while maintaining semantic relevance. Our evaluation reveals a consistent failure mode across existing re-rankers: a strong bias toward older, semantically rich documents, even when they are factually obsolete. We further investigate an instruction optimization framework to mitigate this issue. By identifying Pareto-optimal instructions that balance Evolving and Non-Evolving Knowledge tasks, we obtain gains of up to 27% on Evolving Knowledge tasks while maintaining competitive performance on Non-Evolving Knowledge tasks.'
tags:
- RAG
- Reranker
- Prompt Optimization
- Benchmarking
links:
- name: Paper
  url: https://arxiv.org/abs/2604.14227
- name: Code
  url: https://github.com/facebookresearch/fresco
---
