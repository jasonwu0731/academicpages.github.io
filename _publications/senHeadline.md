---
title: "Clickbait? Sensational Headline Generation with Auto-tuned Reinforcement Learning"
collection: publications
permalink: /publications/senHeadline
excerpt: 
date: 2019-09-01
venue: 'The Conference on Empirical Methods in Natural Language Processing (EMNLP)'
paperurl: 
citation: 
---

[[PDF]](https://arxiv.org/abs/1909.03582)

<pre style="background-color: rgb(230,230,230);white-space: pre-wrap;">
<font size="1">
@article{xu2019clickbait,
  title={Clickbait? Sensational Headline Generation with Auto-tuned Reinforcement Learning},
  author={Xu, Peng and Wu, Chien-Sheng and Madotto, Andrea and Fung, Pascale},
  journal={arXiv preprint arXiv:1909.03582},
  year={2019}
}
</font>
</pre>

## Abstract
Sensational headlines are headlines that capture people’s attention and generate reader interest. Conventional abstractive headline generation methods, unlike human writers, do not optimize for maximal reader attention. In this paper, we propose a model that generates sensational headlines without labeled data. We first train a sensationalism scorer by classifying online headlines with many comments (“clickbait”) against a baseline of headlines generated from a summarization model. The score from the sensationalism scorer is used as the reward for a reinforcement learner. However, maximizing the noisy sensationalism reward will generate unnatural phrases instead of sensational headlines. To effectively leverage this noisy reward, we propose a novel loss function, Auto-tuned Reinforcement Learning (ARL), to dynamically balance reinforcement learning (RL) with maximum likelihood estimation (MLE). Human evaluation shows that 60.8% of samples generated by our model are sensational, which is significantly better than the Pointer-Gen baseline (See et al., 2017) and other RL models.
