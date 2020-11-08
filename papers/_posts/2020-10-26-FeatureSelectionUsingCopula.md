---
layout: paper
title: "Stable Feature Selection using Copula based Mutual Information"
year: "2020"
shortref: "Lall et al. Pattern Recognition 2020"
nickname:
journal: "Pattern Recognition"
volume: 
issue:
pages: 107697
authors: "Snehalika Lall, Debajyoti Sinha, Abhik Ghosh, Debarka Sengupta, Sanghamitra Bandyopadhyay"
image: https://debarka.github.io/senguptalab/assets/images/papers/FeatureSelectionUsingCopula.png
pdf:
pdflink: https://www.sciencedirect.com/science/article/abs/pii/S0031320320305008
pmid: 
pmcid: 
f1000:
figshare:
doi: 10.1016/j.patcog.2020.107697
category: paper
published: true
peerreview:
review: false
tags:
---
{% include JB/setup %}


# Abstract

Feature selection is a key step in many machine learning tasks. A majority of the existing methods of feature selection address the problem by devising some scoring function while treating the features independently, thereby overlooking their interdependencies. We leverage the scale invariance property of copula to construct a greedy, supervised feature selection algorithm that maximizes the feature relevance while minimizing the redundant information content. Multivariate copula is used in the proposed copula Based Feature Selection (CBFS) to discover the dependence structure between features. The incorporation of copula-based multivariate dependency in the formulation of mutual information helps avoid averaging over multiple instances of bivariate dependencies, thus eliminating the average estimation error introduced when bivariate dependency is used between a pair of feature variables. Under a controlled setting, our algorithm outperformed the existing best practice methods in warding off the noise in data. On several real and synthetic datasets, the proposed algorithm performed competitively in maximizing classification accuracy. CBFS also outperforms the other methods in terms of its noise tolerance property.
