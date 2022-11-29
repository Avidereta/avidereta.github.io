---
title: "Model-based Causal Bayesian Optimization"
date: 2022-11-18
publishDate: 2022-11-18
authors: ["Scott Sussex", "Anastasiia Makarova", "Andreas Krause"]
publication_types: ["1"]
featured: false
publication: 

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

abstract:
  "How should we intervene on an unknown structural equation model to maximize a downstream variable of interest? 
  This setting, also known as causal Bayesian optimization (CBO), has important applications in medicine, ecology, and manufacturing. 
  Standard Bayesian optimization algorithms fail to effectively leverage the underlying causal structure. 
  Existing CBO approaches assume noiseless measurements and do not come with guarantees. 
  We propose the *model-based causal Bayesian optimization algorithm (MCBO)* that learns a full system model instead of only modeling intervention-reward pairs. 
  MCBO propagates epistemic uncertainty about the causal mechanisms through the graph and trades off exploration and exploitation via the optimism principle. 
  We bound its cumulative regret, and obtain the first non-asymptotic bounds for CBO. Unlike in standard Bayesian optimization, our acquisition function cannot be evaluated in closed form, 
  so we show how the reparameterization trick can be used to apply gradient-based optimizers. 
  The resulting practical implementation of MCBO compares favorably with state-of-the-art approaches empirically."
# Summary. An optional shortened abstract.
summary: "A principled algorithm for causal bayesian optimization."

links:
- name: PDF
  url: https://arxiv.org/pdf/2211.10257.pdf
- icon: github
  icon_pack: fab
  name: Code
  url: https://github.com/ssethz/mcbo


 # Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
---
