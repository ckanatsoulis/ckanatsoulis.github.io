---
layout: page
title: LoRTA — Low-Rank Tensor Adaptation
description: Parameter-efficient adaptation of generative LLMs via tensor decomposition. Reduces trainable parameters by up to two orders of magnitude vs. LoRA.
img: assets/img/lorta.png
importance: 4
category: research
giscus_comments: false
---

**Collaborators:** Microsoft Research.

LoRTA is a **low-rank tensor adaptation** framework for parameter-efficient fine-tuning of large language, vision, and protein models. It generalizes LoRA from matrix factorization to **tensor decomposition**, achieving matched performance with up to **two orders of magnitude fewer trainable parameters** on DPO, instruction tuning, and protein folding.

## Why tensor adaptation

LoRA decomposes weight updates as the product of two low-rank matrices. LoRTA decomposes them as low-rank tensors, exploiting structure across multiple parameter axes (attention heads, layers, modalities). The result: drastically fewer parameters per task at matched downstream accuracy.

## Applications shown in the paper

- DPO and instruction tuning of LLMs
- Vision-model adaptation
- Protein-folding model fine-tuning

We are extending the framework to **multi-head latent attention** for inference-time efficiency.

## Paper

Hounie, **Kanatsoulis**, Tandon, Ribeiro. **"LoRTA: Low Rank Tensor Adaptation of Large Language Models."** [arXiv:2410.04060](https://arxiv.org/abs/2410.04060). *Under review.*
