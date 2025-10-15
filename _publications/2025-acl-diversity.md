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

Data augmentation is an essential technique in natural language processing (NLP) for enriching training datasets by generating diverse samples. This process is crucial for improving the robustness and generalization capabilities of NLP models. However, a significant challenge remains: Insufficient Attention to Sample Distribution Diversity. Most existing methods focus on increasing the sample numbers while neglecting the sample distribution diversity, which can lead to model overfitting. In response, we explore data augmentation's impact on dataset diversity and propose a Diversity-oriented data Augmentation framework (DoAug). Specifically, we utilize a diversity-oriented fine-tuning approach to train an LLM as a diverse paraphraser, which is capable of augmenting textual datasets by generating diversified paraphrases. Then, we apply the LLM paraphraser to a selected coreset of highly informative samples and integrate the paraphrases with the original data to create a more diverse augmented dataset. Finally, we conduct extensive experiments on 12 real-world textual datasets. The results show that our fine-tuned LLM augmenter improves diversity while preserving label consistency, thereby enhancing the robustness and performance of downstream tasks. Specifically, it achieves an average performance gain of 10.52, surpassing the runner-up baseline with more than three percentage points.

📄 *In Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (ACL 2025).*  
🔗 [Paper Link (arXiv:2502.11671)](https://arxiv.org/abs/2502.11671)
