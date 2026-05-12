---
layout: page
title: GREmLN — Biomedical Foundation Model
description: A transcriptomics foundation model that injects gene-regulatory-network structure as positional information. Collaboration with the Chan Zuckerberg Initiative.
img: assets/img/gremln.png
importance: 3
category: research
giscus_comments: false
---

**Collaborators:** Chan Zuckerberg Initiative.

GREmLN is a **multimodal graph transformer for single-cell transcriptomics** that uses gene-regulatory networks as positional information. The model captures long-range gene-token dependencies and improves single-cell embeddings over structure-blind baselines, accelerating research on diseases like cancer and Alzheimer's.

## Key idea

Standard transcriptomics foundation models treat genes as independent tokens. We inject **gene-regulatory-network (GRN) structure** as positional encoding, enabling the model to use biological priors during pretraining and downstream tasks.

## Impact

GREmLN can accelerate research on diseases like cancer and Alzheimer's by providing better-aligned representations of cell state, lineage, and perturbation response.

## Paper

Zhang, Swamy, Cassius, Dupire, **Kanatsoulis**, et al., Califano. **"GREmLN: A Cellular Regulatory Network-Aware Transcriptomics Foundation Model"** · ICLR 2026 Workshop on Machine Learning for Genomics Explorations. [[bioRxiv](https://www.biorxiv.org/content/10.1101/2025.07.03.663009v1.abstract)]
