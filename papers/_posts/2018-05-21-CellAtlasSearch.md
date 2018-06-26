---
layout: paper
title: "CellAtlasSearch: a scalable search engine for single cells"
year: "2018"
shortref: "Debarka et al. Nucleic Acids Research 2018"
nickname:
journal: "Nucleic Acids Research"
volume:
issue:
pages:
authors: "Divyanshu Srivastava, Arvind Iyer, Vibhor Kumar, Debarka Sengupta"
image: https://debarka.github.io/senguptalab/assets/images/papers/CellAtlasSearch.png
pdf:
pdflink: https://academic.oup.com/nar/advance-article/doi/10.1093/nar/gky421/5000022
github:
pmid: 29788498 
pmcid:
f1000:
figshare:
doi: 10.1093/nar/gky421.
category: paper
published: true
peerreview:
review: false
tags:
---
{% include JB/setup %}


# Abstract

Owing to the advent of high throughput single cell transcriptomics, past few years have seen exponential growth in production of gene expression data. Recently efforts have been made by various research groups to homogenize and store single cell expression from a large number of studies. The true value of this ever increasing data deluge can be unlocked by making it searchable. To this end, we propose CellAtlasSearch, a novel search architecture for high dimensional expression data, which is massively parallel as well as light-weight, thus infinitely scalable. In CellAtlasSearch, we use a Graphical Processing Unit (GPU) friendly version of Locality Sensitive Hashing (LSH) for unmatched speedup in data processing and query. Currently, CellAtlasSearch features over 300 000 reference expression profiles including both bulk and single-cell data. It enables the user query individual single cell transcriptomes and finds matching samples from the database along with necessary meta information. CellAtlasSearch aims to assist researchers and clinicians in characterizing unannotated single cells. It also facilitates noise free, low dimensional representation of single-cell expression profiles by projecting them on a wide variety of reference samples.
