---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Spilled Energy in Large Language Models"
subtitle: ''
summary: ''
authors:
- minut
- dewidar
- Iacopo Masi


tags: []
categories: []
date: '2026-02-21'
lastmod: 2026-11-17T00:00:00
featured: false
draft: false
publication_short: "ICLR 2026"

image:
  caption: ''
  focal_point: 'Center'
  preview_only: false

projects: []
publishDate: '2026-11-17T00:00:00'
publication_types:
- '1'
abstract: "We reinterpret the final Large Language Model (LLM) softmax classifier as an Energy-Based Model (EBM), decomposing the sequence-to-sequence probability chain into multiple interacting EBMs at inference. This principled approach allows us to track \"energy spills\" during decoding, which we empirically show correlate with factual errors, biases, and failures. Similar to Orgad et al. (2025), our method localizes the exact answer token and subsequently tests for hallucinations. Crucially, however, we achieve this without requiring trained probe classifiers or activation ablations. Instead, we introduce two completely training-free metrics derived directly from output logits: spilled energy, which captures the discrepancy between energy values across consecutive generation steps that should theoretically match, and marginalized energy, which is measurable at a single step. Evaluated on nine benchmarks across state-of-the-art LLMs (including LLaMA, Mistral, and Gemma) and on synthetic algebraic operations (Qwen3), our approach demonstrates robust, competitive hallucination detection and cross-task generalization. Notably, these results hold for both pretrained and instruction-tuned variants without introducing any training overhead."

links:
- name: arXiv
  url : https://arxiv.org/abs/2602.18671
- name: OpenReview
  url : https://openreview.net/forum?id=EXFKk4Y3yc
- name: Code
  url : https://github.com/OmnAI-Lab/spilled-energy

publication: '*International Conference on Learning Representations (ICLR 2026)*'
---
