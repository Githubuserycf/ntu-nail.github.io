---
title: Textual Manifold-based Defense Against Natural Language Adversarial Examples
publication_types:
  - "1"
authors:
  - Nguyen Minh Dang
  - Luu Anh Tuan
publication: "Empirical Methods in Natural Language Processing"
publication_short: EMNLP
abstract: Despite the recent success of large pretrained language models in NLP, they are susceptible to adversarial examples. Concurrently, several studies on adversarial images have observed an intriguing property:the adversarial images tend to leave the low-dimensional natural data manifold. In this study, we find a similar phenomenon occurs in the contextualized embedding space of natural sentences induced by pretrained language models in which textual adversarial examples tend to have their embeddings diverge off the manifold of natural sentence embeddings. Based on this finding, we propose Textual Manifold-based Defense (TMD), a defense mechanism that learns the embedding space manifold of the underlying language model and projects novel inputs back to the approximated structure before classification. Through extensive experiments, we find that our method consistently and significantly outperforms previous defenses under various attack settings while remaining unaffected to the clean accuracy. To the best of our knowledge, this is the first kind of manifold-based defense adapted to the NLP domain.
draft: false
featured: false
tags:
  - EMNLP
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2023-03-2T08:29:00.179Z
---
https://aclanthology.org/2022.emnlp-main.443/