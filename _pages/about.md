---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

:man_technologist:  I am a final-year PhD student at the University of Edinburgh, advised by [Ivan Titov](http://ivan-titov.org/) and [Mirella Lapata](http://homepages.inf.ed.ac.uk/mlap/index.php).

During my PhD, I primarily focus on addressing several generalization challenges that arise in executable semantic parsing (e.g., text-to-SQL parsing), namely *domain generalization*, *learning from weak supervision* and *systematic generalization*, based on methodologies of **latent discrete structure learning** and **specialized learning objectives** (e.g., meta-learning). 

Currently, I am interested in exploring similar challenges in related tasks such as machine translation, and extending the methodologies to them. Prior to my PhD, I worked on structured prediction such as nested entity recognition.

:wave: Free feel to reach out if you'd like to chat!

:clipboard: **I'm looking for a job where I can still do interesting research.**

## Publications

You can also find them on <a href="https://scholar.google.com/citations?user=IlgMpNoAAAAJ&hl=en">my Google Scholar profile</a>.

* [Structured Reordering for Modeling Latent Alignments in Sequence Transduction](https://arxiv.org/abs/2106.03257) <br/>
**Bailin Wang**, Mirella Lapata and Ivan Titov <br/>
To appear in *NeurIPS 2021*

* [Meta-Learning to Compositionally Generalize](https://arxiv.org/abs/2106.04252) <br/>
Henry Conklin<sup>\*</sup>, **Bailin Wang**<sup>\*</sup>, Kenny Smith and Ivan Titov (\* equal contribution) <br/>
In *ACL 2021*,
[[code](https://github.com/berlino/tensor2struct-public)]
[[slides](https://berlino.github.io/files/acl2021-comp-maml.pdf)]
[[video (via Underline)](https://underline.io/events/167/sessions/5543/lecture/25594-meta-learning-to-compositionally-generalize)]

* [Learning from Executions for Semantic Parsing](https://arxiv.org/abs/2104.05819) <br/>
**Bailin Wang**, Mirella Lapata and Ivan Titov <br/>
In *NAACL 2021*,
[[code](https://github.com/berlino/tensor2struct-public)]
[[slides](https://berlino.github.io/files/naacl2021-semisup.pdf)]
[[video (via Underline)](https://underline.io/lecture/20036-learning-from-executions-for-semantic-parsing)]

* [Meta-Learning for Domain Generalization in Semantic Parsing](https://arxiv.org/abs/2010.11988) <br/>
**Bailin Wang**, Mirella Lapata and Ivan Titov <br/>
In *NAACL 2021*,
[[code](https://github.com/berlino/tensor2struct-public)]
[[slides](https://berlino.github.io/files/naacl2021-dg-maml.pdf)]
[[video (via Underline)](https://underline.io/lecture/19816-meta-learning-for-domain-generalization-in-semantic-parsing)]

* [Learning to Synthesize Data for Semantic Parsing](https://arxiv.org/abs/2104.05827)<br/>
**Bailin Wang**, Wenpeng Yin, Victoria Lin and Caiming Xiong <br/>
In *NAACL 2021*,
[[code](https://github.com/berlino/tensor2struct-public)]
[[video (via Underline)](https://underline.io/lecture/20041-learning-to-synthesize-data-for-semantic-parsing)]

* [GraPPa: Grammar-Augmented Pre-Training for Table Semantic Parsing](https://arxiv.org/abs/2009.13845) <br/>
Tao Yu, Chien-Sheng Wu, Xi Victoria Lin, **Bailin Wang**, Yi Chern Tan, Xinyi Yang, Dragomir Radev, Richard Socher and Caiming Xiong <br/>
In *ICLR 2021*,
[[video](https://iclr.cc/virtual/2021/poster/3307)]

* [RAT-SQL: Relation-Aware Schema Encoding and Linking for Text-to-SQL Parsers](https://arxiv.org/abs/1911.04942)  <br/>
**Bailin Wang**<sup>\*</sup>, Richard Shin<sup>\*</sup>, Xiaodong Liu, Oleksandr Polozov and Matthew Richardson (\* equal contribution) <br/>
In *ACL 2020*,
[[code](https://github.com/Microsoft/rat-sql)]
[[slides](https://berlino.github.io/files/ratsql-acl2020.pdf)]
[[video](https://virtual.acl2020.org/paper_main.677.html)]

* [Learning Semantic Parsers from Denotations with Latent Structured Alignments and Abstract Programs](https://www.aclweb.org/anthology/D19-1391/) <br/>
**Bailin Wang**, Mirella Lapata and Ivan Titov <br/>
 In *EMNLP 2019*,
[[code](https://github.com/berlino/weaksp_em19)]
[[slides](https://berlino.github.io/files/emnlp2019_weaksp.pdf)]
[[video](https://crossminds.ai/video/learning-semantic-parsers-from-denotations-with-latent-structured-alignments-and-abstract-programs-601de6e3ecbeebc970a2f524/)]

* [Combining Spans into Entities: A Neural Two-Stage Approach for Recognizing Discontiguous Entities](https://www.aclweb.org/anthology/D19-1644/) <br/>
**Bailin Wang** and Wei Lu <br/>
In *EMNLP 2019*,
[[code](https://github.com/berlino/disco_em19)]

* [A Neural Transition-based Model for Nested Mention Recognition](https://www.aclweb.org/anthology/D18-1124) <br/>
**Bailin Wang**, Wei Lu, Yu Wang and Hongxia Jin <br/>
In *EMNLP 2018*,
[[code](https://github.com/berlino/nest-trans-em18)]

* [Neural Segmental Hypergraphs for Overlapping Mention Recognition](https://www.aclweb.org/anthology/D18-1019/) <br/>
**Bailin Wang** and Wei Lu <br/>
In *EMNLP 2018*,
[[code](https://github.com/berlino/overlapping-ner-em18)]
[[slides](https://berlino.github.io/files/emnlp2018_overlapping.pdf)]
[[video](https://vimeo.com/306356485)]

* [Learning latent opinions for aspect-level sentiment classification](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/17327) <br/>
**Bailin Wang** and Wei Lu.  <br/>
In *AAAI 2018*,
[[code](https://github.com/berlino/SA-Sent)]
[[slides](https://berlino.github.io/files/aaai2018_absa.pdf)]


## Log of Parsing Papers

**Epoch 5**: :thinking: In 2021, I'm convinced that Transformers are indeed powerful, but we also need specialized objectives to regularize the training of them. <br/>
**Epoch 4**: :confused: In 2020, Transformers are everywhere, wondering how latent structures can still be useful somehow. <br/>
**Epoch 3**: :thinking: During 2018-2019,  maybe structured prediction is not required as we already have good end-to-end systems? But latent structures can help! <br/>
**Epoch 2**: :smile_cat:  During 2017-2018, structured prediction is interesting, I can play with DL and fancy structures! <br/>
**Epoch 1**: :expressionless: 	In 2017, it seems that everyone is doing DL for NLP, so I should follow though I do not understand why they work so well. <br/>
**Epoch 0**: :grimacing: During 2016-2017, I was intrigued by rule/grammar-based parsing systems (and their usage in SMT), and I wish I could do something related. <br/>


## Work Experience

* Research Intern at Salesforce Research, Summer 2020 
* Research Intern at Microsoft Research Redmond, Summer 2019
* Research Intern at Samsung Research America, Summer 2018
* Research Intern at [StatNLP](http://statnlp.org) Singapore, Summer 2017
* NLP Intern/Engineer at Mobvoi. Beijing, 2016

## Education

* Ph.D in ILCC, University of Edinburgh, 2021 (expected) 
* M.S. in CICS, University of Massachusetts Amherst, 2018
* B.S. in Xidian University, 2015


