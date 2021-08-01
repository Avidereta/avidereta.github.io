---
title: "Overfitting in Bayesian Optimization: an empirical
study and early-stopping solution"
date: 2021-04-16
publishDate: 2021-06-11
authors: ["Anastasiia Makarova", "Huibin Shen", "Valerio Perrone", "Aaron Klein", "Jean Baptiste Faddoul", "Andreas Krause", "Matthias Seeger", "Cedric Archambeau"]
publication_types: ["1"]
featured: false
publication: "*ICLR Workshop on Neural Architecture Search*"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

abstract:
  "Tuning machine learning models with Bayesian optimization (BO) is a successful
strategy to find good hyperparameters. BO defines an iterative procedure where
a cross-validated metric is evaluated on promising hyperparameters. In practice,
however, an improvement of the validation metric may not translate in better predictive performance on a test set, especially when tuning models trained on small
datasets. In other words, unlike conventional wisdom dictates, BO can overfit.
In this paper, we carry out the first systematic investigation of overfitting in BO
and demonstrate that this issue is serious, yet often overlooked in practice. We propose a novel criterion to early stop BO, which aims to maintain the solution quality
while saving the unnecessary iterations that can lead to overfitting. Experiments
on real-world hyperparameter optimization problems show that our approach effectively meets these goals and is more adaptive comparing to baselines."
# Summary. An optional shortened abstract.
summary: ""

links:
- name: PDF
  url: https://arxiv.org/pdf/2104.08166.pdf
- name: Video
  url: https://slideslive.com/38955387/overfitting-in-bayesian-optimization-an-empirical-study-and-earlystopping-solution?ref=search


 # Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
---
