---
title: "Scoring with Large Language Models: A Study on Measuring Empathy of Responses in Dialogues"
collection: publications
category: conferences
permalink: /publication/2024-bigdata-llm-empathy-scoring
date: 2024-12-28
venue: "Proceedings of the 2024 IEEE International Conference on Big Data (BigData 2024)"
authors: "Henry J. Xie, Jinghan Zhang, Xinhao Zhang, Kunpeng Liu"
paperurl: "https://arxiv.org/abs/2412.20264"
excerpt: "This paper investigates how LLMs score empathy in dialogues, introducing a comprehensive framework that combines explicit features, embeddings, and the MITI code to approximate fine-tuned LLM performance."
---

In recent years, Large Language Models (LLMs) have become increasingly more powerful in their ability to complete complex tasks. One such task in which LLMs are often employed is scoring, i.e., assigning a numerical value from a certain scale to a subject. In this paper, we strive to understand how LLMs score, specifically in the context of empathy scoring. We develop a novel and comprehensive framework for investigating how effective LLMs are at measuring and scoring empathy of responses in dialogues, and what methods can be employed to deepen our understanding of LLM scoring. Our strategy is to approximate the performance of state-of-the-art and fine-tuned LLMs with explicit and explainable features. We train classifiers using various features of dialogues including embeddings, the Motivational Interviewing Treatment Integrity (MITI) Code, a set of explicit subfactors of empathy as proposed by LLMs, and a combination of the MITI Code and the explicit subfactors. Our results show that when only using embeddings, it is possible to achieve performance close to that of generic LLMs, and when utilizing the MITI Code and explicit subfactors scored by an LLM, the trained classifiers can closely match the performance of fine-tuned LLMs. We employ feature selection methods to derive the most crucial features in the process of empathy scoring. Our work provides a new perspective toward understanding LLM empathy scoring and helps the LLM community explore the potential of LLM scoring in social science studies.

📄 *In Proceedings of the 2024 IEEE International Conference on Big Data (BigData 2024).*  
🔗 [Paper Link (arXiv:2412.20264)](https://arxiv.org/abs/2412.20264)
