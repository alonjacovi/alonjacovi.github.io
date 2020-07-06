---
layout: archive
title: " "
permalink: /publications/
author_profile: true
---

<!---  {% if author.googlescholar %}
  <u><a href="{{author.googlescholar}}">My Google Scholar profile</a> will </u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->

# Preprints


### *Aligning Faithful Interpretations with their Social Attribution.*
<ins>Alon Jacovi</ins>, Yoav Goldberg.  
[ArXiv](https://arxiv.org/abs/2006.01067)

An exciting (to me!) new formalization on explanations of artificial model decisions, with highlight explanations as a motivating case-study.
 
### *When Bert Forgets How To POS: Amnesic Probing of Linguistic Properties and MLM Predictions*
Yanai Elazar, Shauli Ravfogel, <ins>Alon Jacovi</ins>, Yoav Goldberg.  
[ArXiv](https://arxiv.org/abs/2006.00995)

A behavioral, causality-inspired analysis of the linguistic knowledge utilized by masked language models, using nullspace projection to remove the information from the representation and then observe the change in output. 

### *Scalable Evaluation and Improvement of Document Set Expansion via Neural Positive-Unlabeled Learning*
<ins>Alon Jacovi</ins>, Gang Niu, Yoav Goldberg, Masashi Sugiyama.  
[ArXiv](https://arxiv.org/abs/1910.13339)

We apply state-of-the-art PU learning solutions to large neural models for the document set expansion (DSE) task, finding that they fail - so we propose modifications to PU learning to perform well on large models and small quantity of labeled data, with strong results. We also propose a new method of evaluation DSE models, which is scalable to a large amount of topics. 


# Publications
 
### *Towards Faithfully Interpretable NLP Systems: How should we define and evaluate faithfulness?*
<ins>Alon Jacovi</ins>, Yoav Goldberg.  
In ACL 2020.  
[ArXiv](https://arxiv.org/abs/2004.03685) [Slides](https://alonjacovi.github.io/files/Faithfulness_ACL2020.pdf)

We survey the available literature, and present a position, on the faithfulness attribute of artificial model interpretations. This involves guidelines on faithfulness evaluation, a survey and meta-analysis of works in the area, and an opinion on what is missing in current work and how to move forward.

### *Improving Task-Oriented Dialogue Systems In Production with Conversation Logs*
<ins>Alon Jacovi</ins>*, Ori Bar El*, Ofer Lavi, David Boaz, David Amid, Inbal Ronen and Ateret Anaby-Tavor 
In the KDD Converse workshop at KDD 2020.  
[PDF](https://alonjacovi.github.io/files/Updating_Bots_from_Logs__KDD_Converse_2020_.pdf)

When dialogue agents are deployed in production, their failure cases are escalated to a human agent to handle the issue. This escalated conversation log is often recorded to help the system developer to improve the system. We propose a way of using these logs, often available "for free" during production, to automatically generate system improvement recommendations to the developer.

### *Neural network gradient-based learning of black-box function interfaces*
<ins>Alon Jacovi</ins>, Guy Hadash, Einat Kermany, Boaz Carmeli, Ofer Lavi, George Kour, Jonathan Berant.    
In ICLR 2019 and in AI Week 2019.  
[ArXiv](https://arxiv.org/abs/1901.03995)

We propose a modular neural framework for integrating black-box (non-differentiable) oracle functions into the neural model, such that the new model can interface directly with the black-box function during inference.

### *Understanding Convolutional Neural Networks for Text Classification*
<ins>Alon Jacovi</ins>, Oren Sar Shalom, Yoav Goldberg.  
In the BlackboxNLP workshop at EMNLP 2018 (oral presentation). Also in ISCOL 2018 (oral presentation).  
[ArXiv](https://arxiv.org/abs/1809.08037) [Slides](https://alonjacovi.github.io/files/Understanding-CNNs-Text-BlackboxNLP2018.pdf)

We analyze CNNs trained to classify text, arriving at various conclusions on the learned behavior of each of the filters in the network. This allows us to propose model interpretation and prediction interpretation techniques for such models.

<!--- 
## Extended Abstracts

\textit{(Extended Abstract)} \textbf{Learning and Understanding Different Categories of Sexism Using Convolutional Neural Network Filters} \\ Sima Sharifirad, \underline{Alon Jacovi}, Stan Matwin. \\ In the Widening NLP workshop at ACL 2019.

 -->
