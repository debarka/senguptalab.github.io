---
layout: paper
title: "A scoring scheme for online feature selection: simulating model performance without retraining"
year: "2017"
shortref: "Sengupta et al. IEEE TNNLS 2017"
nickname:
journal: "IEEE transactions on neural networks and learning systems"
volume: 28
issue: 2
pages: 405-414
authors: "Debarka Sengupta, Sanghamitra Bandyopadhyay, Debajyoti Sinha"
image: https://debarka.github.io/senguptalab/assets/images/papers/ScoringScheme.png
pdf:
pdflink: https://ieeexplore.ieee.org/abstract/document/7389431/
github: debsin
pmid:
pmcid:
f1000:
figshare:
doi: 10.1109/TNNLS.2016.2514270.
category: paper
published: true
peerreview:
review: false
tags:
---
{% include JB/setup %}


# Abstract

Increasing the number of features increases the complexity of a model even if the additional feature does not improve its decision-making capacity. Irrelevant features may also cause overfitting and reduce interpretability of the concerned model. It is, therefore, important that the features are optimally selected before a model is built. In the case of online learning, new instances are periodically discovered, and the respective model is tactically retrained as required. Similarly, there are many real-life situations where hundreds of new features are discovered periodically, and the existing model needs to be retrained or tested for its performance improvement. Supervised selection of feature subset usually requires creation of multiple suboptimal models, thus incurring time-intensive computations. Unsupervised selections, although faster, largely rely on some subjective definition of feature relevance. In this paper, we introduce a score that accurately determines the importance of the features. The proposed score is appropriate for online feature selection scenarios for its low time complexity and ability to interpret performance improvement of the current model after the addition of a new feature, without invoking a retraining.
