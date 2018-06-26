---
layout: paper
title: "Reformulated Kemeny Optimal Aggregation with Application in Consensus Ranking of microRNA Targets"
year: "2013"
shortref: "Debarka et al. IEEE/ACM transactions 2013"
nickname:
journal: "IEEE/ACM transactions on computational biology and bioinformatics"
volume: 10
issue: 3
pages: 742-751
authors: "Debarka Sengupta, Aroonalok Pyne, Ujjwal Maulik, Sanghamitra Bandyopadhyay"
image: /assets/images/papers/KemenyAggr.png
pdf:
pdflink: https://ieeexplore.ieee.org/abstract/document/6547149/
github:
pmid:
pmcid:
f1000:
figshare:
doi: 10.1109/TCBB.2013.74.
category: paper
published: true
peerreview:
review: false
tags:
---
{% include JB/setup %}


# Abstract

MicroRNAs are very recently discovered small noncoding RNAs, responsible for negative regulation of gene expression. Members of this endogenous family of small RNA molecules have been found implicated in many genetic disorders. Each microRNA targets tens to hundreds of genes. Experimental validation of target genes is a time- and cost-intensive procedure. Therefore, prediction of microRNA targets is a very important problem in computational biology. Though, dozens of target prediction algorithms have been reported in the past decade, they disagree significantly in terms of target gene ranking (based on predicted scores). Rank aggregation is often used to combine multiple target orderings suggested by different algorithms. This technique has been used in diverse fields including social choice theory, meta search in web, and most recently, in bioinformatics. Kemeny optimal aggregation (KOA) is considered the more profound objective for rank aggregation. The consensus ordering obtained through Kemeny optimal aggregation incurs minimum pairwise disagreement with the input orderings. Because of its computational intractability, heuristics are often formulated to obtain a near optimal consensus ranking. Unlike its real time use in meta search, there are a number of scenarios in bioinformatics (e.g., combining microRNA target rankings, combining disease-related gene rankings obtained from microarray experiments) where evolutionary approaches can be afforded with the ambition of better optimization. We conjecture that an ideal consensus ordering should have its total disagreement shared, as equally as possible, with the input orderings. This is also important to refrain the evolutionary processes from getting stuck to local extremes. In the current work, we reformulate Kemeny optimal aggregation while introducing a trade-off between the total pairwise disagreement and its distribution. A simulated annealing-based implementation of the proposed objective has been found effective in context of microRNA target ranking.
