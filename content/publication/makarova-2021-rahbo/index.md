---
title: "Risk-averse Heteroscedastic Bayesian Optimization"
date: 2021-11-05
publishDate: 2021-11-05
authors: ["Anastasiia Makarova", "Ilnura Usmanova", "Ilija Bogunovic", "Andreas Krause"]
publication_types: ["1"]
featured: false
publication: "*Conference on Neural Information Processing Systems (NeurIPS)*"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

abstract:
  "Many black-box optimization tasks arising in high-stakes applications require risk-averse decisions. The standard Bayesian optimization (BO) paradigm, however, optimizes the expected value only. We generalize BO to trade mean and input-dependent variance of the objective, both of which we assume to be unknown a priori. In particular, we propose a novel risk-averse heteroscedastic Bayesian optimization algorithm (RAHBO) that aims to identify a solution with high return and low noise variance, while learning the noise distribution on the fly. To this end, we model both expectation and variance as (unknown) RKHS functions, and propose a novel risk-aware acquisition function. We bound the regret for our approach and provide a robust rule to report the final decision point for applications where only a single solution must be identified. We demonstrate the effectiveness of RAHBO on synthetic benchmark functions and hyperparameter tuning tasks."
# Summary. An optional shortened abstract.
summary: ""

links:
- name: PDF
  url: https://arxiv.org/pdf/2111.03637.pdf
- name: Video
  url: https://neurips.cc/virtual/2021/poster/26309
- name: Slides
  url: https://docs.google.com/presentation/d/1XYURj0pa6afc_shsdTJfJ0oKJRIu59FIuDYdfdCVazY/edit?usp=sharing

 # Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
---
