---
layout: paper
title: "dropClust: Efficient clustering of ultra-large scRNA-seq data"
year: "2018"
shortref: "Debarka et al. Nucleic Acids Research 2018"
nickname:
journal: "Nucleic Acids Research"
volume: 46
issue: 6
pages:
authors: "Debajyoti Sinha, Akhilesh Kumar, Himanshu Kumar, Sanghamitra Bandyopadhyay, Debarka Sengupta"
image: https://debarka.github.io/senguptalab/assets/images/papers/dropClust.png
pdf:
pdflink: https://watermark.silverchair.com/gky007.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAAZ0wggGZBgkqhkiG9w0BBwagggGKMIIBhgIBADCCAX8GCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQMETHAOet9bYlJ2aUKAgEQgIIBUJLEiGitAMo1FL92wDvfaupvyRf8sU5_escgoTXWKDRM80HMzS0ZpNU_YZDg9fKDpljyqcxZTPwE9Fhs3m5VE16L8-ySBCgi3RvxxN8g_S6sAWqrwXsrRtzNkY1hgYyZ1suGxIZ6QOquBvb2XM7TO4gHUcZzvIq6JKWOogTRBJqDhBZlUgTe-rce_Sx8GvobClUNg_ya4v1mzzUX63fh7jmqKASDGhXRbJ8_6bbMCu7i70jo6qBs2Dt3yb9WvXWVKTScIy_N4X9ET7M3GP6wO0uS-pvyzwhTdcGlMmOjiNIRTajMwkClD8avyX3KLIjCSRF8sRZ9pDeScubbxtjwtpmVphtq_RIELtVuOs-Ax5tfgEKOSkYjJcOPZofSTYtmaJ3eYlTCnuesacAHClglTyEAKEocNxPmQs5ywgHyUAnWGk7BSvJzCkRi8-39oJ4EnQ
github: debsin/dropClust
pmid: 29361178
pmcid:
f1000:
figshare:
doi: 10.1093/nar/gky007.
category: paper
published: true
peerreview:
review: false
tags:
---
{% include JB/setup %}


# Abstract

Droplet based single cell transcriptomics has recently enabled parallel screening of tens of thousands of single cells. Clustering methods that scale for such high dimensional data without compromising accuracy are scarce. We exploit Locality Sensitive Hashing, an approximate nearest neighbour search technique to develop a de novo clustering algorithm for large-scale single cell data. On a number of real datasets, dropClust outperformed the existing best practice methods in terms of execution time, clustering accuracy and detectability of minor cell sub-types.
