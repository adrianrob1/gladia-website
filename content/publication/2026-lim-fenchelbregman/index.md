---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Train for Many, Update with One: Improving Multi-Sample Reasoning via Fenchel-Bregman Posterior Learning"
subtitle: ''
summary: ''
authors:
- Sungjun Lim
- minut
- Nico Carlsen Daheim
- Mohammad Emtiyaz Khan
- Kyungwoo Song
- Thomas Möllenhoff


tags: []
categories: []
date: '2026-10-13'
lastmod: 2026-11-17T00:00:00
featured: false
draft: false
publication_short: "arXiv preprint"

image:
  caption: ''
  focal_point: 'Center'
  preview_only: false

projects: []
publishDate: '2026-11-17T00:00:00'
publication_types:
- '3'
abstract: "Multi-sample reasoning measures candidate coverage, the probability that at least one of *K* candidates is correct. However, minimizing the average loss of individual attempts does not directly optimize candidate coverage. We therefore formulate finite-*K* posterior learning, which trains a distribution over solver parameters to reduce the probability that all *K* independently generated candidates fail. To optimize this objective efficiently, we propose a Fenchel-Bregman (FB) approach that requires only one posterior draw per update, rather than the *K* used by direct Monte Carlo optimization. FB first uses an exact Fenchel reformulation to separate problem-specific weights from the posterior update, enabling one-draw posterior updates. It then applies a closed-form Bregman update to track these weights through an exponential running average of observed failures, reusing the same draw. We instantiate FB with IVON, a variational optimizer for Gaussian posteriors over solver parameters, yielding Fenchel-Bregman IVON (FBI). Across diverse recursive and autoregressive reasoning tasks, FBI improves candidate coverage. In a matched comparison, it achieves comparable Pass@10 using 12.3% of the direct Monte Carlo baseline's measured training time per update."

links:
- name: arXiv
  url : https://arxiv.org/abs/2610.17735

publication: '*arXiv preprint*'
---
