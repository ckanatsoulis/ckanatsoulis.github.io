---
layout: page
title: KGGen — Knowledge Graphs from Text
description: Text-to-knowledge-graph extraction with LLMs. NeurIPS 2025. 1.1k+ GitHub stars.
img: assets/img/kggen.png
importance: 2
category: tools
giscus_comments: false
---

A Python package that generates **high-quality knowledge graphs from plain text** using LLMs, reducing sparsity through entity clustering. We also release **MINE**, the first benchmark for evaluating KG extraction.

🔗 **Code:** [github.com/stair-lab/kg-gen](https://github.com/stair-lab/kg-gen) · **1.1k+ stars**
📦 `pip install kg-gen`
📄 **Paper:** [Mo, Yu, Kazdan, et al. NeurIPS 2025](https://arxiv.org/abs/2502.09956)

## What it does

Given unstructured text, KGGen extracts an entity-relation graph suitable for downstream reasoning, retrieval, and agentic workflows. Designed for heterogeneous biomedical and scientific sources.

## Why it matters

Knowledge graphs grounded in structured scientific knowledge support agentic AI systems — hypothesis generation, evidence retrieval, and multi-step scientific reasoning. KGGen makes constructing such KGs from text tractable at scale.

## Related work

We are extending this to a **multimodal graph transformer** for knowledge and heterogeneous graphs to enable zero-shot reasoning over biomedical and scientific sources.
