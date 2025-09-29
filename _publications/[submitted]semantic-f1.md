---
title: 'Semantic F1 Scores: Fair Evaluation Under Fuzzy Class Boundaries'
collection: publications
permalink: /publication/semantic-f1-score
excerpt: 'We propose Semantic F1 Scores, novel evaluation metrics for subjective or fuzzy multi-label classification that quantify semantic relatedness between predicted and gold labels. Unlike the conventional F1 metrics that treat semantically related predictions as complete failures, Semantic F1 incorporates a label similarity matrix to compute soft precision-like and recall-like scores, from which the Semantic F1 scores are derived. Unlike existing similarity-based metrics, our novel two-step precision-recall formulation enables the comparison of label sets of arbitrary sizes without discarding labels or forcing matches between dissimilar labels.'
date: 2025-09-28
venue: ''
published: 'review'
paperurl: https://arxiv.org/abs/2509.21633
citation: 'Chochlakis, Georgios, Jackson Trager, Vedant Jhaveri, Nikhil Ravichandran, Alexandros Potamianos, Shrikanth Narayanan. "Semantic F1 Scores: Fair Evaluation Under Fuzzy Class Boundaries." arXiv preprint arXiv:2509.21633'
---

<img src="https://gchochla.github.io/images/semantic-f1-thumbnail.png" style="display: block; margin-left: auto; margin-right:auto; width: 60%; height: auto;">
<br>
`pip install semantic-f1-score` or [[code](https://github.com/gchochla/semantic-f1-score)]
<br>
_Abstract_: We propose Semantic F1 Scores, novel evaluation metrics for subjective or fuzzy multi-label classification that quantify semantic relatedness between predicted and gold labels. Unlike the conventional F1 metrics that treat semantically related predictions as complete failures, Semantic F1 incorporates a label similarity matrix to compute soft precision-like and recall-like scores, from which the Semantic F1 scores are derived. Unlike existing similarity-based metrics, our novel two-step precision-recall formulation enables the comparison of label sets of arbitrary sizes without discarding labels or forcing matches between dissimilar labels. By granting partial credit for semantically related but nonidentical labels, Semantic F1 better reflects the realities of domains marked by human disagreement or fuzzy category boundaries. In this way, it provides fairer evaluations: it recognizes that categories overlap, that annotators disagree, and that downstream decisions based on similar predictions lead to similar outcomes. Through theoretical justification and extensive empirical validation on synthetic and real data, we show that Semantic F1 demonstrates greater interpretability and ecological validity. Because it requires only a domain-appropriate similarity matrix, which is robust to misspecification, and not a rigid ontology, it is applicable across tasks and modalities.

BibTex Citation
-

```bibtex
@article{chochlakis2025semanticf1score,
    title={Semantic F1 Scores: Fair Evaluation Under Fuzzy Class Boundaries}, 
    author={Georgios Chochlakis and Jackson Trager and Vedant Jhaveri and Nikhil Ravichandran and Alexandros Potamianos and Shrikanth Narayanan},
    year={2025},
    eprint={2509.21633},
    journal = {arXiv preprint arXiv:2509.21633},
    primaryClass={cs.AI},
    url={https://arxiv.org/abs/2509.21633},
    archiveprefix = {arXiv}
}
```
