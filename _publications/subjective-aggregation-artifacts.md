---
title: 'Aggregation Artifacts in Subjective Tasks Collapse Large Language Models Posteriors'
collection: publications
permalink: /publication/subjective-aggregation-artifacts
excerpt: 'Our results indicate that aggregation is a confounding factor in the modeling of subjective tasks, and advocate focusing on modeling individuals instead. However, aggregation does not explain the entire gap between ICL and the state of the art, meaning other factors in such tasks also account for the observed phenomena. Finally, by rigorously studying annotator-level labels, we find that it is possible for minority annotators to both better align with LLMs and have their perspectives further amplified.'
date: 2024-10-17
venue: ''
published: 'review'
paperurl: https://arxiv.org/abs/2410.13776
citation: 'Chochlakis, Georgios, Alexandros Potamianos, Kristina Lerman, and Shrikanth Narayanan. "Aggregation Artifacts in Subjective Tasks Collapse Large Language Models Posteriors." arXiv preprint arXiv:2410.13776 (2024).'
---

<img src="https://gchochla.github.io/images/aggregate-artifacts.png" style="display: block; margin-left: auto; margin-right:auto; width: 90%; height: auto;">
<br>
_Abstract_: In-context Learning (ICL) has become the primary method for performing natural language tasks with Large Language Models (LLMs). The knowledge acquired during pre-training is crucial for this few-shot capability, providing the model with task priors. However, recent studies have shown that ICL predominantly relies on retrieving task priors rather than "learning" to perform tasks. This limitation is particularly evident in complex subjective domains such as emotion and morality, where priors significantly influence posterior predictions. In this work, we examine whether this is the result of the aggregation used in corresponding datasets, where trying to combine low-agreement, disparate annotations might lead to annotation artifacts that create detrimental noise in the prompt. Moreover, we evaluate the posterior bias towards certain annotators by grounding our study in appropriate, quantitative measures of LLM priors. Our results indicate that aggregation is a confounding factor in the modeling of subjective tasks, and advocate focusing on modeling individuals instead. However, aggregation does not explain the entire gap between ICL and the state of the art, meaning other factors in such tasks also account for the observed phenomena. Finally, by rigorously studying annotator-level labels, we find that it is possible for minority annotators to both better align with LLMs and have their perspectives further amplified.

BibTex Citation
-
```
@article{chochlakis2024larger,
  title={Larger Language Models Don't Care How You Think: Why Chain-of-Thought Prompting Fails in Subjective Tasks},
  author={Chochlakis, Georgios and Pandiyan, Niyantha Maruthu and Lerman, Kristina and Narayanan, Shrikanth},
  journal={arXiv preprint arXiv:2409.06173},
  year={2024}
}
```