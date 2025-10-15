---
title: "Diversity-Oriented Data Augmentation with Large Language Models"
collection: publications
category: conferences
permalink: /publication/2025-acl-doaug-llm
date: 2025-02-17
venue: "Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (ACL 2025)"
authors: "Zaitian Wang, Jinghan Zhang, Xinhao Zhang, Kunpeng Liu, Pengfei Wang, Yuanchun Zhou"
paperurl: "https://arxiv.org/abs/2502.11671"
excerpt: "This paper proposes DoAug, a Diversity-Oriented Data Augmentation framework that leverages LLMs as diverse paraphrasers to enhance dataset diversity and robustness in NLP tasks."
---

**Data augmentation** plays a vital role in Natural Language Processing (NLP) by enriching training datasets and improving model robustness.  
However, most existing approaches primarily focus on increasing the **quantity** of samples while overlooking **distributional diversity**, which can lead to model overfitting and poor generalization.

We propose **DoAug** — a **Diversity-Oriented Data Augmentation** framework that addresses this issue by fine-tuning a Large Language Model (LLM) as a **diverse paraphraser**.  
DoAug generates semantically consistent yet distributionally diverse samples, augmenting datasets with higher information richness and reduced redundancy.

The method involves selecting a **coreset of informative samples**, applying the LLM-based paraphraser for diversity-oriented generation, and integrating the augmented data with the original dataset.  
Comprehensive experiments across **12 real-world NLP datasets** demonstrate that DoAug consistently improves **diversity**, **label consistency**, and **downstream task performance**, outperforming existing baselines by over three percentage points on average.

📄 *In Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (ACL 2025).*  
🔗 [Paper Link (arXiv:2502.11671)](https://arxiv.org/abs/2502.11671)
