---
title: 'The Strong Pull of Prior Knowledge in Large Language Models and Its Impact on Emotion Recognition'
collection: publications
permalink: /publication/llm-prior-pull
excerpt: 'In this work, we design experiments and propose measurements to explicitly quantify the consistency of proxies of LLM priors and their pull on the posteriors. We show that LLMs have strong yet inconsistent priors in emotion recognition that ossify their predictions. We also find that the larger the model, the stronger these effects become. Our results suggest that caution is needed when using ICL with larger LLMs for affect-centered tasks outside their pre-training domain and when interpreting ICL results.'
date: 2024-09-16
venue: 'ACII'
published: 'true'
paperurl: https://arxiv.org/abs/2403.17125
citation: 'Chochlakis, Georgios, Alexandros Potamianos, Kristina Lerman and Shrikanth Narayanan. “The Strong Pull of Prior Knowledge in Large Language Models and Its Impact on Emotion Recognition.” In 2024 12th International Conference on Affective Computing and Intelligent Interaction (ACII).'
---

<img src="https://gchochla.github.io/images/pull-thumbnail.png" style="display: block; margin-left: auto; margin-right:auto; width: 90%; height: auto;">
[[code](https://github.com/gchochla/llm-prior-pull)]
<br>
_Abstract_: In-context Learning (ICL) has emerged as a powerful paradigm for performing natural language tasks with Large Language Models (LLM) without updating the models' parameters, in contrast to the traditional gradient-based finetuning. The promise of ICL is that the LLM can adapt to perform the present task at a competitive or state-of-the-art level at a fraction of the cost. The ability of LLMs to perform tasks in this few-shot manner relies on their background knowledge of the task (or task priors). However, recent work has found that, unlike traditional learning, LLMs are unable to fully integrate information from demonstrations that contrast task priors. This can lead to performance saturation at suboptimal levels, especially for subjective tasks such as emotion recognition, where the mapping from text to emotions can differ widely due to variability in human annotations. In this work, we design experiments and propose measurements to explicitly quantify the consistency of proxies of LLM priors and their pull on the posteriors. We show that LLMs have strong yet inconsistent priors in emotion recognition that ossify their predictions. We also find that the larger the model, the stronger these effects become. Our results suggest that caution is needed when using ICL with larger LLMs for affect-centered tasks outside their pre-training domain and when interpreting ICL results.

BibTex Citation
-

```bibtex
@inproceedings{chochlakis2024strong,
  author    = {Chochlakis, Georgios and Potamianos, Alexandros and 
               Lerman, Kristina and Narayanan, Shrikanth},
  title     = {The Strong Pull of Prior Knowledge in Large Language Models 
               and Its Impact on Emotion Recognition},
  booktitle = {Proceedings of the 12th International Conference on Affective 
               Computing and Intelligent Interaction (ACII)},
  year      = {2024},
  publisher = {IEEE},
}
```
