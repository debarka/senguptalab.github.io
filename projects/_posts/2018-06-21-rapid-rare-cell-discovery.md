---
layout: post
title: "Rapid rare cell discovery"
description: ""
author: "Debarka Sengupta"
author_handle: DS
category: project
published: true
theme: lab
tags: []
---
{% include JB/setup %}

Development of the in-drop barcoding technique for single cells has opened the floodgate for production of large-scale scRNA-seq data. With the growing popularity of the assay and availability of affordable commercial platforms (ChromiumTM by 10x Genomics, ICELL8 by WaferGen Biosystems etc.) a sharp increase has been observed in the average sample sizes of the recent single-cell studies. A typical Drop-seq experiment involves profiling of several tens of thousands of cells on a single run.
Existing rare cell finding algorithms including GiniClust[PMID: 27368803] and RaceID [PMID: 26287467]) are computationally demanding and in practice, do not scale beyond 5-15K transcriptomes. We have developed FiRE, a patent-pending, linear-time, monolithic algorithm for rareness scoring of a massive number of cell transcriptomes in a matter of a few seconds.


<!--![RapidRareCellDiscovery](https://debarka.github.io/senguptalab/assets/images/RapidRareCellDiscovery.png){:width="400px" style=".center"}-->



### Publication

Jindal, A., Gupta, P., Jayadeva, and Sengupta, D., 2018. [Discovery of rare cells from voluminous single cell expression data][1].


[1]: https://www.debarka.com/papers/paper/FiRE
