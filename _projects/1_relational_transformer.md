---
layout: page
title: Relational Transformer & RelBench
description: Foundation models for relational databases. Architectures for forecasting and generation over multi-table relational data, plus the community-standard benchmark.
img: assets/img/relbench.png
importance: 1
category: research
giscus_comments: false
---

**Collaborators:** NVIDIA, SAP, Kumo.AI · Stanford SNAP Group.

We design foundation-model and generative architectures for **relational databases** — the most widespread form of structured enterprise data. Our goal is to enable zero-shot transfer across schemas and tables, the way LLMs transfer across text.

## Architectures

- **PEARL** *(ICLR 2025, first author)* — efficient positional encodings for graph transformers over relational data.
- **RelGNN** *(ICML 2025)* — composite message passing for relational deep learning, with up to 25% improvement over prior baselines.
- **Relational Transformer** *(ICLR 2026; Oral at EurIPS AI for Tabular Data Workshop)* — foundation model architecture for forecasting over relational databases, enabling large-scale pretraining and zero-shot generalization.
- **Relational Graph Transformer** *(ICLR 2026; Best Paper Award, KDD Temporal Graph Learning Workshop 2025)* — multi-modal graph transformer architecture for relational data.

## RelBench v2

A community-standard benchmark and data repository for relational deep learning. **350+ GitHub stars.** Adopted across NVIDIA, SAP, and Kumo.AI teams.

🔗 [relbench.stanford.edu](https://relbench.stanford.edu/)

## Papers

- Ranjan et al., "Relational Transformer," **ICLR 2026** · [arXiv](https://arxiv.org/abs/2510.06377)
- Dwivedi et al., "Relational Graph Transformer," **ICLR 2026** · [arXiv](https://arxiv.org/abs/2505.10960) · **Best Paper Award (KDD TGL Workshop 2025)**
- Chen, Kanatsoulis, Leskovec, "RelGNN," **ICML 2025** · [arXiv](https://arxiv.org/abs/2502.06784)
- Kanatsoulis et al., "PEARL," **ICLR 2025** · [arXiv](https://arxiv.org/abs/2502.01122)
- Dwivedi, Kanatsoulis, Huang, Leskovec, "Relational Deep Learning: Challenges, Foundations and Next-Generation Architectures," **KDD 2025** · [arXiv](https://arxiv.org/abs/2506.16654)
