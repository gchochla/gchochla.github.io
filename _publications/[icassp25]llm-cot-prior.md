---
title: 'Larger Language Models Dont Care How You Think: Why Chain-of-Thought Prompting Fails in Subjective Tasks'
collection: publications
permalink: /publication/llm-cot-prior
excerpt: 'In this work, we examine whether "enabling" reasoning also retrieves reasoning priors that remain relatively unchanged despite the evidence in the prompt. We find that, surprisingly, CoT indeed suffers from the same posterior collapse as ICL for larger language models.'
date: 2025-04-06
venue: 'ICASSP'
published: 'true'
paperurl: https://arxiv.org/abs/2409.06173
citation: 'Chochlakis, Georgios, Niyantha Maruthu Pandiyan, Kristina Lerman, and Shrikanth Narayanan. "Larger Language Models Dont Care How You Think: Why Chain-of-Thought Prompting Fails in Subjective Tasks." In ICASSP 2025-2025 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), pp. 1-5. IEEE, 2025.'
---

<img src="https://gchochla.github.io/images/pull-thumbnail.png" style="display: block; margin-left: auto; margin-right:auto; width: 90%; height: auto;">
<br>
[[code](https://github.com/gchochla/cot-priors)]
<br>
_Abstract_: In-Context Learning (ICL) in Large Language Models (LLM) has emerged as the dominant technique for performing natural language tasks, as it does not require updating the model parameters with gradient-based methods. ICL promises to "adapt" the LLM to perform the present task at a competitive or state-of-the-art level at a fraction of the computational cost. ICL can be augmented by incorporating the reasoning process to arrive at the final label explicitly in the prompt, a technique called Chain-of-Thought (CoT) prompting. However, recent work has found that ICL relies mostly on the retrieval of task priors and less so on "learning" to perform tasks, especially for complex subjective domains like emotion and morality, where priors ossify posterior predictions. In this work, we examine whether "enabling" reasoning also creates the same behavior in LLMs, wherein the format of CoT retrieves reasoning priors that remain relatively unchanged despite the evidence in the prompt. We find that, surprisingly, CoT indeed suffers from the same posterior collapse as ICL for larger language models.

BibTex Citation
-

```bibtex
@inproceedings{chochlakis2025larger,
  author    = {Chochlakis, Georgios and
               Pandiyan, Niyantha Maruthu and
               Lerman, Kristina and
               Narayanan, Shrikanth},
  title     = {Larger Language Models Don't Care How You Think: 
               Why Chain-of-Thought Prompting Fails in Subjective Tasks},
  booktitle = {2025 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)},
  year      = {2025},
  publisher = {IEEE},
}
```
