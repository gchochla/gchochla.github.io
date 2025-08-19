---
title: 'Aggregation Artifacts in Subjective Tasks Collapse Large Language Models Posteriors'
collection: publications
permalink: /publication/subjective-aggregation-artifacts
excerpt: 'Our results indicate that aggregation is a confounding factor in the modeling of subjective tasks, and advocate focusing on modeling individuals instead. However, aggregation does not explain the entire gap between ICL and the state of the art, meaning other factors in such tasks also account for the observed phenomena. Finally, by rigorously studying annotator-level labels, we find that it is possible for minority annotators to both better align with LLMs and have their perspectives further amplified.'
date: 2025-04-29
venue: 'Proceedings of NAACL'
published: 'true'
paperurl: https://aclanthology.org/2025.naacl-long.284/#
citation: 'Chochlakis, Georgios, Alexandros Potamianos, Kristina Lerman, and Shrikanth Narayanan. "Aggregation Artifacts in Subjective Tasks Collapse Large Language Models Posteriors." In Proceedings of the 2025 Conference of the Nations of the Americas Chapter of the Association for Computational Linguistics (NAACL).'
---

<img src="https://gchochla.github.io/images/aggregate-artifacts.png" style="display: block; margin-left: auto; margin-right:auto; width: 90%; height: auto;">
<br>
[[code](https://github.com/gchochla/aggregation-artifacts-llms)]
<br>
_Abstract_: In-context Learning (ICL) has become the primary method for performing natural language tasks with Large Language Models (LLMs). The knowledge acquired during pre-training is crucial for this few-shot capability, providing the model with task priors. However, recent studies have shown that ICL predominantly relies on retrieving task priors rather than "learning" to perform tasks. This limitation is particularly evident in complex subjective domains such as emotion and morality, where priors significantly influence posterior predictions. In this work, we examine whether this is the result of the aggregation used in corresponding datasets, where trying to combine low-agreement, disparate annotations might lead to annotation artifacts that create detrimental noise in the prompt. Moreover, we evaluate the posterior bias towards certain annotators by grounding our study in appropriate, quantitative measures of LLM priors. Our results indicate that aggregation is a confounding factor in the modeling of subjective tasks, and advocate focusing on modeling individuals instead. However, aggregation does not explain the entire gap between ICL and the state of the art, meaning other factors in such tasks also account for the observed phenomena. Finally, by rigorously studying annotator-level labels, we find that it is possible for minority annotators to both better align with LLMs and have their perspectives further amplified.

BibTex Citation
-

```bibtex
@inproceedings{chochlakis2025aggregation,
    title = "Aggregation Artifacts in Subjective Tasks Collapse Large Language Models' Posteriors",
    author = "Chochlakis, Georgios  and
      Potamianos, Alexandros  and
      Lerman, Kristina  and
      Narayanan, Shrikanth",
    editor = "Chiruzzo, Luis  and
      Ritter, Alan  and
      Wang, Lu",
    booktitle = "Proceedings of the 2025 Conference of the Nations of the Americas Chapter of the Association for Computational Linguistics: Human Language Technologies (Volume 1: Long Papers)",
    month = apr,
    year = "2025",
    address = "Albuquerque, New Mexico",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.naacl-long.284/",
    pages = "5513--5528",
    ISBN = "979-8-89176-189-6",
}
```
