---
layout: paper
title: "Structure-Aware Principal Component Analysis for Single-Cell RNA-seq Data"
year: "2018"
shortref: "Lall et al. Journal of Computational Biology 2018"
nickname:
journal: "Journal of Computational Biology"
volume: 46
issue: 6
pages:
authors: "Snehalika Lall, Debajyoti Sinha, Sanghamitra Bandyopadhyay, and Debarka Sengupta"
image: 
pdf:
pdflink: https://www.liebertpub.com/doi/10.1089/cmb.2018.0027
github: 
pmid: 29361178
pmcid:
f1000:
figshare:
doi: 10.1089/cmb.2018.0027
category: paper
published: true
peerreview:
review: false
tags:
---
{% include JB/setup %}


# Abstract

With the emergence of droplet-based technologies, it has now become possible to profile transcriptomes of several thousands of cells in a day. Although such a large single-cell cohort may favor the discovery of cellular heterogeneity, it also brings new challenges in the prediction of minority cell types. Identification of any minority cell type holds a special significance in knowledge discovery. In the analysis of single-cell expression data, the use of principal component analysis (PCA) is surprisingly frequent for dimension reduction. The principal directions obtained from PCA are usually dominated by the major cell types in the concerned tissue. Thus, it is very likely that using a traditional PCA may endanger the discovery of minority populations. To this end, we propose locality-sensitive PCA (LSPCA), a scalable variant of PCA equipped with structure-aware data sampling at its core. Structure-aware sampling provides PCA with a neutral spread of the data, thereby reducing the bias in its principal directions arising from the redundant samples in a data set. We benchmarked the performance of the proposed method on ten publicly available single-cell expression data sets including one very large annotated data set. Results have been compared with traditional PCA and PCA with random sampling. Clustering results on the annotated data sets also show that LSPCA can detect the minority populations with a higher accuracy.
