---
title: Unlabeled Data Improves Fine-Grained Image Zero-shot Classification with Multimodal LLMs
authors:
- Yunqi Hong
- Sohyun An
- Andrew Bai
- Neil Y.C. Lin
- Cho-Jui Hsieh
date: '2025-06-01'
publishDate: '2025-06-01T09:04:07Z'
publication_types:
- manuscript
publication: '*Under Review*'
# doi: 10.48550/arXiv.2305.16943
abstract: Despite Multimodal Large Language Models (MLLMs) showing promising results on general zero-shot image classification tasks, fine-grained image classification remains challenging. It demands precise attention to subtle visual details to distinguish between visually similar subcategories--details that MLLMs may easily overlook without explicit guidance. To address this, we introduce AutoSEP, an iterative self-supervised prompt learning framework designed to enhance MLLM fine-grained classification capabilities in a fully unsupervised manner. Our core idea is to leverage unlabeled data to learn a description prompt that guides MLLMs in identifying crucial discriminative features within an image, and boosts classification accuracy. We developed an automatic self-enhancing prompt learning framework called AutoSEP to iteratively improve the description prompt using unlabeled data, based on instance-level classification scoring function. AutoSEP only requires black-box access to MLLMs, eliminating the need for any training or fine-tuning. We evaluate our approach on multiple fine-grained classification datasets. It consistently outperforms other unsupervised baselines, demonstrating the effectiveness of our self-supervised optimization framework. Notably, AutoSEP on average improves 13 percent over standard zero-shot classification and 5 percent over the best-performing baselines.
tags:
- Multimodal Large Language Models
- Prompt Optimization
- Fine-grained Classificatoin
links:
- name: PDF
  url: https://arxiv.org/abs/2506.03195
- name: Code
  url: https://github.com/yq-hong/AutoSEP
---
