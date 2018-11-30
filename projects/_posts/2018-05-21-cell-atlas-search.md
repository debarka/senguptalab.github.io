---
layout: post
title: "GPU accelerated single cell search"
description: ""
author: "Debarka Sengupta"
author_handle: DS
category: project
published: true
theme: lab
tags: []
---
{% include JB/setup %}

An explosion in production of single-cell expression data has triggered the need for a search engine. To cater to the need of the hour, we developed CellAtlasSearch, a novel search architecture for high dimensional expression data, which is massively parallel as well as light-weight, thus infinitely scalable. In CellAtlasSearch, we use a Graphical Processing Unit (GPU) friendly version of Locality Sensitive Hashing (LSH) for unmatched speedup in data processing and query. Currently, CellAtlasSearch features over 300 000 reference expression profiles including both bulk and single-cell data. The web-server is accessible at the [this link][1].


<!--![CellAtlasSearch](https://debarka.github.io/senguptalab/assets/images/CellAtlasSearch.jpeg){:height="400px width="400px" style=".center"}-->


### Publication

Srivastava, D., Iyer, A., Kumar, V., and Sengupta, D., 2018. [CellAtlasSearch:][1] A scalable search engine for single cells.


[1]: https://www.debarka.com/papers/paper/CellAtlasSearch
