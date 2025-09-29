---
title: "semantic-f1-score"
collection: software
permalink: /software/semantic-f1-score
excerpt: "The Semantic F1 scores are novel evaluation metrics for subjective or fuzzy multi-label classification that quantify semantic relatedness between predicted and gold labels."
date: 2025-09-28
codelink: https://github.com/gchochla/semantic-f1-score
---

<img src="https://gchochla.github.io/images/semantic-f1-thumbnail.png" style="display: block; margin-left: auto; margin-right:auto; width: 40%; height: auto;">
<br>

Semantic F1 [`semantic-f1-score`](https://github.com/gchochla/semantic-f1-score) is a drop-in replacement for `sklearn`'s conventional `f1_score` in subjective or fuzzy multi-label classification. It keeps the familiar precision-recall framing while using a domain similarity matrix to acknowledge when wrong labels are still semantically close. The package is the reference implementation accompanying the paper: 'Semantic F1 Scores: Fair Evaluation Under Fuzzy Class Boundaries'.

To install: `pip install semantic-f1-score`
