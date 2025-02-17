---
title: Learning to Attend via Word-Aspect Associative Fusion for Aspect-based Sentiment Analysis
publication_types:
  - "1"
authors:
  - Yi Tay
  - Luu Anh Tuan
  - Siu Cheung Hui
publication: " AAAI Conference on Artificial Intelligence"
publication_short: AAAI
abstract: Aspect-based sentiment analysis (ABSA) tries to predict the polarity of a given document with respect to a given aspect entity. While neural network architectures have been successful in predicting the overall polarity of sentences, aspect-specific sentiment analysis still remains as an open problem. In this paper, we propose a novel method for integrating aspect information into the neural model. More specifically, we incorporate aspect information into the neural model by modeling word-aspect relationships. Our novel model, \textit{Aspect Fusion LSTM} (AF-LSTM) learns to attend based on associative relationships between sentence words and aspect which allows our model to adaptively focus on the correct words given an aspect term. This ameliorates the flaws of other state-of-the-art models that utilize naive concatenations to model word-aspect similarity. Instead, our model adopts circular convolution and circular correlation to model the similarity between aspect and words and elegantly incorporates this within a differentiable neural attention framework. Finally, our model is end-to-end differentiable and highly related to convolution-correlation (holographic like) memories. Our proposed neural model achieves state-of-the-art performance on benchmark datasets, outperforming ATAE-LSTM by 4%−5% on average across multiple datasets.
draft: false
featured: false
tags:
  - AAAI
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2023-03-2T08:29:00.179Z
---
https://arxiv.org/abs/1712.05403