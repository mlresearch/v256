---
title: Confidence Interval Estimation of Predictive Performance in the Context of
  AutoML
openreview: f4BAvKsVmT
abstract: Any supervised machine learning analysis is required to provide an estimate
  of the out-of-sample predictive performance. However, it is imperative to also provide
  a quantification of the uncertainty of this performance in the form of a confidence
  or credible interval (CI) and not just a point estimate. In an AutoML setting, estimating
  the CI is challenging due to the “winner’s curse”, i.e., the bias of estimation
  due to cross-validating several machine learning pipelines and selecting the winning
  one. In this work, we perform a comparative evaluation of 9 state-of-the-art methods
  and variants in CI estimation in an AutoML setting on a corpus of real and simulated
  datasets. The methods are compared in terms of inclusion percentage (does a 95%
  CI interval include the true performance at least 95% of the time), CI tightness
  (tighter CIs are preferable as being more informative), and execution time. The
  evaluation is the first one that covers most, if not all, such methods and extends
  previous work to multi-class, imbalanced, and small-sample tasks. In addition, we
  present a variant, called BBC-F, of an existing method (the Bootstrap Bias Correction,
  or BBC) that maintains the statistical properties of the BBC but is more computationally
  efficient. The results support that BBC-F and BBC dominate the other methods in
  all metrics measured. However, the results also point to open problems and challenges
  in producing accurate CIs of performance, particularly in the case of multi-class
  tasks.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: paraschakis24a
month: 0
tex_title: Confidence Interval Estimation of Predictive Performance in the Context
  of AutoML
firstpage: 4/1
lastpage: 14
page: 4/1-14
order: 4
cycles: false
bibtex_author: Paraschakis, Konstantinos and Castellani, Andrea and Borboudakis, Giorgos
  and Tsamardinos, Ioannis
author:
- given: Konstantinos
  family: Paraschakis
- given: Andrea
  family: Castellani
- given: Giorgos
  family: Borboudakis
- given: Ioannis
  family: Tsamardinos
date: 2024-10-09
address:
container-title: Proceedings of the Third International Conference on Automated Machine
  Learning
volume: '256'
genre: inproceedings
issued:
  date-parts:
  - 2024
  - 10
  - 9
pdf: https://raw.githubusercontent.com/mlresearch/v256/main/assets/paraschakis24a/paraschakis24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
