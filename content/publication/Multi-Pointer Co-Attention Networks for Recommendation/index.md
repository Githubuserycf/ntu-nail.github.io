---
title: Multi-Pointer Co-Attention Networks for Recommendation
publication_types:
  - "1"
authors:
  - Yi Tay
  - Luu Anh Tuan
  - Siu Cheung Hui
publication: "Knowledge Discovery and Data Mining"
publication_short: KDD
abstract: Many recent state-of-the-art recommender systems such as D-ATT, TransNet and DeepCoNN exploit reviews for representation learning. This paper proposes a new neural architecture for recommendation with reviews. Our model operates on a multi-hierarchical paradigm and is based on the intuition that not all reviews are created equal, i.e., only a select few are important. The importance, however, should be dynamically inferred depending on the current target. To this end, we propose a review-by-review pointer-based learning scheme that extracts important reviews, subsequently matching them in a word-by-word fashion. This enables not only the most informative reviews to be utilized for prediction but also a deeper word-level interaction. Our pointer-based method operates with a novel gumbel-softmax based pointer mechanism that enables the incorporation of discrete vectors within differentiable neural architectures. Our pointer mechanism is co-attentive in nature, learning pointers which are co-dependent on user-item relationships. Finally, we propose a multi-pointer learning scheme that learns to combine multiple views of interactions between user and item. Overall, we demonstrate the effectiveness of our proposed model via extensive experiments on \textbf{24} benchmark datasets from Amazon and Yelp. Empirical results show that our approach significantly outperforms existing state-of-the-art, with up to 19% and 71% relative improvement when compared to TransNet and DeepCoNN respectively. We study the behavior of our multi-pointer learning mechanism, shedding light on evidence aggregation patterns in review-based recommender systems.
draft: false
featured: false
tags:
  - KDD
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2023-03-2T08:29:00.179Z
---
https://arxiv.org/abs/1801.09251