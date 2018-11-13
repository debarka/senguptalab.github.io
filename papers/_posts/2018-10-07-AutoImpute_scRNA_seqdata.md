---
layout: paper
title: "AutoImpute : Autoencoder based imputation of single-cell RNA-seq data"
year: "2018"
shortref: "Talwar et al. Scientific Reports 2018"
nickname:
journal: “Scientific Reports"
volume:
issue:
pages:
authors: "Divyanshu Talwar, Aanchal Mongia, Angshul Majumdar, and Debarka Sengupta"
image: https://debarka.github.io/senguptalab/assets/images/papers/AutoImpute.png
pdf:
pdflink: https://www.nature.com/articles/s41598-018-34688-x
github: divyanshu-talwar/AutoImpute
pmid: 30397240
pmcid: PMC6218547
f1000:
figshare:
doi: 10.1038/s41598-018-34688-x 
category: paper
published: true
peerreview:
review: false
tags:
---
{% include JB/setup %}


# Abstract

The emergence of single-cell RNA sequencing (scRNA-seq) technologies has enabled us to measure the expression levels of thousands of genes at single-cell resolution. However, insufficient quantities of starting RNA in the individual cells cause significant dropout events, introducing a large number of zero counts in the expression matrix. To circumvent this, we developed an autoencoder-based sparse gene expression matrix imputation method. AutoImpute, which learns the inherent distribution of the input scRNA-seq data and imputes the missing values accordingly with minimal modification to the biologically silent genes. When tested on real scRNA-seq datasets, AutoImpute performed competitively wrt., the existing single-cell imputation methods, on the grounds of expression recovery from subsampled data, cell-clustering accuracy, variance stabilization and cell-type separability.

