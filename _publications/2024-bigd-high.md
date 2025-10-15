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

Recent advances in **Large Language Models (LLMs)** have expanded their capabilities to a variety of evaluative tasks, including **automated scoring** — assigning numerical values to subjective attributes.  
In this study, we explore how effectively LLMs can **measure and score empathy** in dialogues.

We introduce a **comprehensive scoring framework** that analyzes LLM-based empathy evaluation through explicit and explainable features.  
Our approach incorporates multiple dialogue representations, including:
- **Embeddings**, capturing contextual semantics;  
- The **Motivational Interviewing Treatment Integrity (MITI) Code**, representing human-defined empathy factors;  
- A set of **explicit subfactors** derived from LLM interpretations of empathy.

We further train classifiers on combinations of these features to approximate the scoring behavior of **fine-tuned LLMs**.  
Results demonstrate that models using only embeddings can approach generic LLM scoring performance, while combining MITI codes and explicit subfactors yields results comparable to fine-tuned models.

Our findings offer new insights into **LLM-based empathy assessment** and contribute to understanding how LLMs can support **social science research** involving affective and behavioral evaluation.

📄 *In Proceedings of the 2024 IEEE International Conference on Big Data (BigData 2024).*  
🔗 [Paper Link (arXiv:2412.20264)](https://arxiv.org/abs/2412.20264)
