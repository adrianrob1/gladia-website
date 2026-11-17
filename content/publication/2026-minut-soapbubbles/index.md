---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "SOAP-Bubbles: Structured Weight Uncertainty for Neural Networks"
subtitle: ''
summary: ''
authors:
- minut
- Nico Daheim
- Marco Miani
- Mohammad Emtiyaz Khan
- Wu Lin
- Thomas Möllenhoff


tags: []
categories: []
date: '2026-06-22'
lastmod: 2026-11-17T00:00:00
featured: false
draft: false
publication_short: "NeurIPS 2026"

image:
  caption: ''
  focal_point: 'Center'
  preview_only: false

projects: []
publishDate: '2026-11-17T00:00:00'
publication_types:
- '1'
abstract: "Structured weight-uncertainty can improve many aspects of deep learning, but it remains costly to estimate and difficult to implement. Here, we show that these issues can be addressed by adapting the SOAP optimizer. Our key idea is to run IVON, an existing diagonal-covariance variational method, in the eigenspace of SOAP's preconditioner and then use the preconditioner to transform the diagonal estimate into a non-diagonal covariance. The resulting method has costs similar to those of SOAP and requires no drastic changes to training pipelines. We call the posteriors obtained in this way SOAP-Bubbles and our new optimizer Eigenspace-VON (EVON). We show that, for logistic regression, EVON can match the full Gaussian covariance and that, for language model pretraining, it yields significantly better results than existing diagonal-covariance methods. Our work makes it easier to estimate more expressive posterior distributions for deep learning at scale."

links:
- name: arXiv
  url : https://arxiv.org/abs/2606.23357
- name: Code
  url : https://github.com/team-approx-bayes/evon
- name: Experiments
  url : https://github.com/team-approx-bayes/evon-experiments

publication: '*Conference on Neural Information Processing Systems (NeurIPS 2026)*'
---
