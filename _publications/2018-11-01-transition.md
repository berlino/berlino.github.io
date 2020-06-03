---
title: "A Neural Transition-based Model for Nested Mention Recognition"
collection: publications
permalink: /publication/2018-11-01-transition
excerpt: ''
date: 2018-11-01
venue: 'EMNLP'
paperulr: 'https://www.aclweb.org/anthology/D18-1124/'
# citation: ''
---

It is common that entity mentions can contain other mentions recursively. This paper introduces a scalable transition-based method to model the nested structure of mentions. We first map a sentence with nested mentions to a designated forest where each mention corresponds to a constituent of the forest. Our shift-reduce based system then learns to construct the forest structure in a bottom-up manner through an action sequence whose maximal length is guaranteed to be three times of the sentence length. Based on Stack-LSTM which is employed to efficiently and effectively represent the states of the system in a continuous space, our system is further incorporated with a character-based component to capture letter-level patterns. Our model gets the state-of-the-art performances in ACE datasets, showing its effectiveness in detecting nested mentions.


[Paper](https://www.aclweb.org/anthology/D18-1124.pdf)

[Code](https://github.com/berlino/nest-trans-em18)