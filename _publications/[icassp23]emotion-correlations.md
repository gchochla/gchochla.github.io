---
title: 'Leveraging Label Correlations in a Multi-label Setting: A Case Study in Emotion'
collection: publications
permalink: /publication/label-correlations
excerpt: 'We develop two modeling approaches to emotion recognition in order to capture word associations of the emotion words themselves, by either including the emotions in the input, or by leveraging Masked Language Modeling (MLM). Second, we integrate pairwise constraints of emotion representations as regularization terms alongside the classification loss of the models.'
date: 2023-06-04
venue: 'ICASSP'
published: 'true'
paperurl: https://arxiv.org/abs/2210.15842
citation: 'Chochlakis, Georgios, Gireesh Mahajan, Sabyasachee Baruah, Keith Burghardt, Kristina Lerman, and Shrikanth Narayanan. "Leveraging label correlations in a multi-label setting: A case study in emotion." In ICASSP 2023-2023 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), pp. 1-5. IEEE, 2023.'
---

<img src="https://gchochla.github.io/images/correlations.png" style="display: block; margin-left: auto; margin-right:auto; width: 90%; height: auto;">
<br>
[[code](https://github.com/gchochla/Demux-MEmo)]
<br>
_Abstract_: Detecting emotions expressed in text has become critical to a range of fields. In this work, we investigate ways to exploit label correlations in multi-label emotion recognition models to improve emotion detection. First, we develop two modeling approaches to the problem in order to capture word associations of the emotion words themselves, by either including the emotions in the input, or by leveraging Masked Language Modeling (MLM). Second, we integrate pairwise constraints of emotion representations as regularization terms alongside the classification loss of the models. We split these terms into two categories, local and global. The former dynamically change based on the gold labels, while the latter remain static during training. We demonstrate state-of-the-art performance across Spanish, English, and Arabic in SemEval 2018 Task 1 E-c using monolingual BERT-based models. On top of better performance, we also demonstrate improved robustness.
<br>
<img src="https://gchochla.github.io/images/demux.png" style="display: block; margin-left: auto; margin-right:auto; width: 90%; height: auto;">
<img src="https://gchochla.github.io/images/memo.png" style="display: block; margin-left: auto; margin-right:auto; width: 90%; height: auto;">
<br>

BibTex Citation
-

```bibtex
@INPROCEEDINGS{chochlakis2023leveraging,
  author={Chochlakis, Georgios and Mahajan, Gireesh and Baruah, Sabyasachee and Burghardt, Keith and Lerman, Kristina and Narayanan, Shrikanth},
  booktitle={ICASSP 2023 - 2023 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)}, 
  title={Leveraging Label Correlations in a Multi-Label Setting: a Case Study in Emotion}, 
  year={2023},
  volume={},
  number={},
  pages={1-5},
  doi={10.1109/ICASSP49357.2023.10096864}
}
```
