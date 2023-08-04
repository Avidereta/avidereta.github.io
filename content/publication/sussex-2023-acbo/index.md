---
title: "Adversarial Causal Bayesian Optimization"
date: 2023-07-31
publishDate: 2023-07-31
authors: ["Scott Sussex", "Pier Giuseppe Sessa", "Anastasiia Makarova", "Andreas Krause"]
publication_types: ["1"]
featured: false
# publication: "*International Conference on Learning Representations (ICLR) 2023*"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

abstract:
  "In Causal Bayesian Optimization (CBO), an agent intervenes on an unknown structural causal model to maximize a downstream reward variable. In this paper, we
consider the generalization where other agents or external events also intervene
on the system, which is key for enabling adaptiveness to non-stationarities such as
weather changes, market forces, or adversaries. We formalize this generalization
of CBO as Adversarial Causal Bayesian Optimization (ACBO) and introduce the
first algorithm for ACBO with bounded regret: Causal Bayesian Optimization with
Multiplicative Weights (CBO-MW). Our approach combines a classical online
learning strategy with causal modeling of the rewards. To achieve this, it computes
optimistic counterfactual reward estimates by propagating uncertainty through the
causal graph. We derive regret bounds for CBO-MW that naturally depend on
graph-related quantities. We further propose a scalable implementation for the case
of combinatorial interventions and submodular rewards. Empirically, CBO-MW
outperforms non-causal and non-adversarial Bayesian optimization methods on synthetic environments and environments based on real-word data. Our experiments
include a realistic demonstration of how CBO-MW can be used to learn users’ demand patterns in a shared mobility system and reposition vehicles in strategic areas."
# Summary. An optional shortened abstract.
summary: "A principled algorithm for causal bayesian optimization in non-stationary systems."

links:
- name: PDF
  url: https://arxiv.org/pdf/2307.16625.pdf


 # Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
---
