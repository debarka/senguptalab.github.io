---
layout: paper
title: "Weighted Markov Chain Based Aggregation of Biomolecule Orderings"
year: "2012"
shortref: "Sengupta et al. IEEE/ACM Transactions 2012"
nickname:
journal: "IEEE/ACM Transactions on Computational Biology and Bioinformatics (TCBB)"
volume: 9
issue: 3
pages: 924-933
authors: "Debarka Sengupta, Ujjwal Maulik, Sanghamitra Bandyopadhyay"
image: https://debarka.github.io/senguptalab/assets/images/papers/WeightedMarkovChain.png
pdf:
pdflink: https://dl.acm.org/citation.cfm?id=2189830
github:
pmid:
pmcid:
f1000:
figshare:
doi: 10.1109/TCBB.2012.28.
category: paper
published: true
peerreview:
review: false
tags:
---
{% include JB/setup %}


# Abstract

The scope and effectiveness of Rank Aggregation (RA) have already been established in contemporary bioinformatics research. Rank aggregation helps in meta-analysis of putative results collected from different analytic or experimental sources. For example, we often receive considerably differing ranked lists of genes or microRNAs from various target prediction algorithms or microarray studies. Sometimes combining them all, in some sense, yields more effective ordering of the set of objects. Also, assigning a certain level of confidence to each source of ranking is a natural demand of aggregation. Assignment of weights to the sources of orderings can be performed by experts. Several rank aggregation approaches like those based on Markov Chains (MCs), evolutionary algorithms, etc., exist in the literature. Markov chains, in general, are faster than the evolutionary approaches. Unlike the evolutionary computing approaches Markov chains have not been used for weighted aggregation scenarios. This is because of the absence of a formal framework of Weighted Markov Chain (WMC). In this paper, we propose the use of a modified version of MC4 (one of the Markov chains proposed by Dwork et al., 2001), followed by the weighted analog of local Kemenization for performing rank aggregation, where the sources of rankings can be prioritized by an expert. Effectiveness of the weighted Markov chain approach over the very recently proposed Genetic Algorithm (GA) and Cross-Entropy Monte Carlo (MC) algorithm-based techniques, has been established for gene orderings from microarray analysis and orderings of predicted microRNA targets.
