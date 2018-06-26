---
layout: post
title: "LSH for clustering ultra-large Drop-seq data"
description: ""
author: "Debarka Sengupta"
author_handle: Debarka Sengupta
category: project
published: true
theme: lab
tags: []
---
{% include JB/setup %}

Droplet-based single-cell transcriptomics has recently enabled parallel screening of tens of thousands of single cells. Clustering methods that scale for such high dimensional data without compromising accuracy are scarce. We exploit Locality Sensitive Hashing, an approximate nearest neighbor search technique to develop a de novo clustering algorithm for large-scale single-cell data. On a number of real datasets, dropClust outperformed the existing best practice methods including Seurat in terms of speed, clustering accuracy and detectability of minor cell sub-types. Moreover, dropClust, for the first time, helps discerning transcriptomic signature of the regulatory T cell population in blood.


![dropClust](https://debarka.github.io/senguptalab/assets/images/dropClust.jpeg){:height="700px" width="700px" style=".center"}

### Publication

Sinha, D., Kumar, A., Kumar, H., Bandyopadhyay, S., and Sengupta, D., 2018. [dropClust:][1] Efficient clustering of ultra-large scRNA-seq data.


[1]: https://academic.oup.com/nar/article/46/6/e36/4816215
