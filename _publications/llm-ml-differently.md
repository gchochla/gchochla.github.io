---
title: 'Large Language Models Do Multi-Label Classification Differently'
collection: publications
permalink: /publication/llm-ml-differently
excerpt: 'We investigate how autoregressive LLMs perform multi-label classification, with a focus on subjective tasks, by analyzing the output distributions of the models in each generation step. We find that their predictive behavior reflects the multiple steps in the underlying language modeling required to generate all relevant labels as they tend to suppress all but one label at each step.'
date: 2025-11-05
venue: 'Proceedings of EMNLP'
published: 'accepted'
paperurl: https://arxiv.org/abs/2505.17510
citation: 'Marcus Ma*, Georgios Chochlakis*, Niyantha Maruthu Pandiyan, Jesse Thomason, and Shrikanth Narayanan. "Large Language Models Do Multi-Label Classification Differently." arXiv preprint arXiv:2505.17510'
---

<img src="https://gchochla.github.io/images/multilabel-alignment.png" style="display: block; margin-left: auto; margin-right:auto; width: 90%; height: auto;">
<br>
[[code](https://github.com/gchochla/LLM-multilabel-differently)]
<br>
_Abstract_: Multi-label classification is prevalent in real-world settings, but the behavior of Large Language Models (LLMs) in this setting is understudied. We investigate how autoregressive LLMs perform multi-label classification, with a focus on subjective tasks, by analyzing the output distributions of the models in each generation step. We find that their predictive behavior reflects the multiple steps in the underlying language modeling required to generate all relevant labels as they tend to suppress all but one label at each step. We further observe that as model scale increases, their token distributions exhibit lower entropy, yet the internal ranking of the labels improves. Finetuning methods such as supervised finetuning and reinforcement learning amplify this phenomenon. To further study this issue, we introduce the task of distribution alignment for multi-label settings: aligning LLM-derived label distributions with empirical distributions estimated from annotator responses in subjective tasks. We propose both zero-shot and supervised methods which improve both alignment and predictive performance over existing approaches.

BibTex Citation
-

```bibtex
@misc{ma2025large,
      title={Large Language Models Do Multi-Label Classification Differently}, 
      author={Marcus Ma and Georgios Chochlakis and Niyantha Maruthu Pandiyan and Jesse Thomason and Shrikanth Narayanan},
      year={2025},
      journal={arXiv preprint arXiv:2505.17510},
      url={https://arxiv.org/abs/2505.17510}
}
```
