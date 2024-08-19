---
title: Optimal Neural Architecture Generation with Diffusion Models
authors:
- Sohyun An
date: '2024-06-10'
publishDate: '2024-02-27T13:06:13.794546Z'
publication_types:
- manuscript
publication: '*KAIST Master's Thesis 2024*'
abstract: "Existing NAS methods suffer from either an excessive amount of time for repetitive sampling and training of many task-irrelevant architectures. To tackle such limitations of existing NAS methods, we propose a paradigm shift from NAS to a novel conditional Neural Architecture Generation (NAG) framework based on diffusion models, dubbed DiffusionNAG. Specifically, we consider the neural architectures as directed graphs and propose a graph diffusion model for generating them. Moreover, with the guidance of parameterized predictors, DiffusionNAG can flexibly generate task-optimal architectures with the desired properties for diverse tasks, by sampling from a region that is more likely to satisfy the properties. This conditional NAG scheme is significantly more efficient than previous NAS schemes which sample the architectures and filter them using the property predictors. We validate the effectiveness of DiffusionNAG through extensive experiments in two predictor-based NAS scenarios: Transferable NAS and Bayesian Optimization (BO)-based NAS. DiffusionNAG achieves superior performance with speedups of up to 35x when compared to the baselines on Transferable NAS benchmarks. Furthermore, when integrated into a BO-based algorithm, DiffusionNAG outperforms existing BO-based NAS approaches, particularly in the large MobileNetV3 search space on the ImageNet 1K dataset."
tags:
- Neural Architectures
- Generative Models
- Diffusion Models
- Graphs
links:
- name: PDF
  url: https://o365kaist-my.sharepoint.com/:b:/g/personal/thgus4425_office_kaist_ac_kr/EZKqmT5niMlBstvliRl19zcB8z6joEQpdgAcIxwj3YwInw?e=18e7P1
---
