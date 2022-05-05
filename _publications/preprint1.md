---
title: "BABD: A Bitcoin Address Behavior Dataset for Pattern Analysis"
collection: publications
permalink: /publication/preprint1
excerpt: '**<u>Yuexin Xiang</u>**, Yuchen Lei, Ding Bao, Wei Ren, Tiantian Li, Qingqing Yang, Wenmao Liu, Tianqing Zhu, and Kim-Kwang Raymond Choo'
date: 2022-05-06
venue: 'arXiv'

---

Cryptocurrencies are no longer just the preferred option for cybercriminal activities on darknets, due to the increasing adoption in mainstream applications. This is partly due to the transparency associated with the underpinning ledgers, where any individual can access the record of a transaction record on the public ledger. In this paper, we build a dataset comprising Bitcoin transactions between 12 July 2019 and 26 May 2021. This dataset (hereafter referred to as BABD-13) contains 13 types of Bitcoin addresses, 5 categories of indicators with 148 features, and 544,462 labeled data, which is the largest labeled Bitcoin address behavior dataset publicly available to our knowledge. We then use our proposed dataset on common machine learning models, namely: k-nearest neighbors algorithm, decision tree, random forest, multilayer perceptron, and XGBoost. The results show that the accuracy rates of these machine learning models for the multi-classification task on our proposed dataset are between 93.24% and 97.13%. We also analyze the proposed features and their relationships from the experiments, and propose a k-hop subgraph generation algorithm to extract a k-hop subgraph from the entire Bitcoin transaction graph constructed by the directed heterogeneous multigraph starting from a specific Bitcoin address node (e.g., a known transaction associated with a criminal investigation). Besides, we initially analyze the behavior patterns of different types of Bitcoin addresses according to the extracted features.

[Preprint](https://arxiv.org/abs/2204.05746)  [Dataset](https://www.kaggle.com/datasets/lemonx/babd13)




