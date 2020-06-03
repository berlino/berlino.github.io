---
title: "Neural Segmental Hypergraphs for Overlapping Mention Recognition"
collection: publications
permalink: /publication/2018-11-01-overlapping
excerpt: ''
date: 2018-11-01
venue: 'EMNLP'
paperurl: 'https://www.aclweb.org/anthology/D18-1019/'
# citation: ''
---
In this work, we propose a novel segmental hypergraph representation to model overlapping entity mentions that are prevalent in many practical datasets. We show that our model built on top of such a new representation is able to capture features and interactions that cannot be captured by previous models while maintaining a low time complexity for inference. We also present a theoretical analysis to formally assess how our representation is better than alternative representations reported in the literature in terms of representational power. Coupled with neural networks for feature learning, our model achieves the state-of-the-art performance in three benchmark datasets annotated with overlapping mentions.

[Paper](https://www.aclweb.org/anthology/D18-1019/)

[Video](https://vimeo.com/306356485)

[Slides](https://berlino.github.io/files/emnlp2018_overlapping.pdf)


[Code](https://github.com/berlino/overlapping-ner-em18)

BibTex:

    @inproceedings{wang-lu-2018-neural,
        title = "Neural Segmental Hypergraphs for Overlapping Mention Recognition",
        author = "Wang, Bailin  and
        Lu, Wei",
        booktitle = "Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing",
        month = oct # "-" # nov,
        year = "2018",
        address = "Brussels, Belgium",
        publisher = "Association for Computational Linguistics",
        url = "https://www.aclweb.org/anthology/D18-1019",
        doi = "10.18653/v1/D18-1019",
        pages = "204--214",
        abstract = "In this work, we propose a novel segmental hypergraph representation to model overlapping entity mentions that are prevalent in many practical datasets. We show that our model built on top of such a new representation is able to capture features and interactions that cannot be captured by previous models while maintaining a low time complexity for inference. We also present a theoretical analysis to formally assess how our representation is better than alternative representations reported in the literature in terms of representational power. Coupled with neural networks for feature learning, our model achieves the state-of-the-art performance in three benchmark datasets annotated with overlapping mentions.",
    }