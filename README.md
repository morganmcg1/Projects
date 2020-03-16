<a href="https://explosion.ai"><img src="https://explosion.ai/assets/img/logo.svg" width="125" height="125" align="right" /></a>

# Example projects

This repo contains example projects for various NLP tasks, including scripts, benchmarks, results and datasets created with [Prodigy](https://prodi.gy).

## 💝 Projects

| Name                                           | Description                                                                                                                                                                                                                                                                                                                                                                                                                          |
| ---------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [`ner-food-ingredients`](ner-food-ingredients) | Use [`sense2vec`](https://github.com/explosion/sense2vec) and [Prodigy](https://prodi.gy) to boostrap an NER model to detect ingredients [Reddit comments](https://files.pushshift.io/reddit/comments/) and to calculate how mentions change over time. Includes an **end-to-end [video tutorial](https://www.youtube.com/watch?v=59BKHO_xBPA)**, raw pre-processed data, **949 annotated examples** and pretrained tok2vec weights. |
| [`ner-fashion-brands`](ner-fashion-brands)     | Use [`sense2vec`](https://github.com/explosion/sense2vec) to boostrap an NER model to detect fashion brands in Reddit comments. Includes **1735 annotated examples**, a data visualizer, training and evaluation scripts for spaCy and pretrained tok2vec weights.                                                                                                                                                                   |
| [`ner-drugs`](ner-drugs)                       | Use word vectors to boostrap an NER model to detect drug names in Reddit comments. Includes **1977 annotated examples**, a data visualizer, training and evaluation scripts for spaCy and pretrained tok2vec weights.                                                                                                                                                                                                                |
| [`textcat-docs-issues`](textcat-docs-issues)   | Train a binary text classifier with exclusive classes to predict whether a GitHub issue title is about documentation. Includes **1161 annotated examples**, a live demo and downloadable model and training and evaluation scripts for spaCy.                                                                                                                                                                                        |
