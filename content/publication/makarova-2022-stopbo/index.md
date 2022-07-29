---
title: "Automatic Termination for Hyperparameter Optimization"
date: 2022-02-05
publishDate: 2022-02-05
authors: ["Anastasiia Makarova", "Huibin Shen", "Valerio Perrone", "Aaron Klein", "Jean Baptiste Faddoul", "Andreas Krause", "Matthias Seeger", "Cedric Archambeau"]
publication_types: ["1"]
featured: false
publication: "\ **Best Paper Award** and **Contributed Talk** at *International Conference on Automated Machine Learning (AutoML-Conf)*"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

abstract:
  "Bayesian optimization (BO) is a widely popular approach for the hyperparameter optimization (HPO) 
in machine learning. 
At its core, BO iteratively evaluates promising configurations until a user-defined budget, such as wall-clock time or number of iterations, is exhausted. While the final performance after tuning heavily depends on the provided budget, it is hard to pre-specify an optimal value in advance. In this work, we propose an effective and intuitive termination criterion for BO that automatically stops 
the procedure if it is 
sufficiently close to the global optimum. Our key insight is that the discrepancy between the true objective (predictive performance on test data) and the computable target (validation performance) suggests stopping once the suboptimality in optimizing the target is dominated by the statistical estimation error.
Across an extensive range of real-world HPO problems and baselines, we show that our termination criterion achieves a better trade-off between the test performance and optimization time.
Additionally, we find that overfitting may occur in the context of HPO, which is arguably an overlooked problem in the literature, and show how our termination criterion helps to mitigate this phenomenon on both small and large datasets. "
# Summary. An optional shortened abstract.
summary: ""

links:
- name: PDF
  url: https://arxiv.org/abs/2104.08166
- icon: github
  icon_pack: fab
  name: Code
  url: https://github.com/amazon-research/bo-early-stopping
- name: Video
  url: https://www.youtube.com/watch?v=7ilqNzxLp2g&feature=youtu.be
- name: Slides
  url: https://docs.google.com/presentation/d/1KatZbfDyjydqYhKUDNw5vywqtKUz0wJCGyJBmZqzbwU/edit?usp=sharing
 

 # Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
---
