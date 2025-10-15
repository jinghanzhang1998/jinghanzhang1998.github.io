---
title: "Entropy-based Exploration Conduction for Multi-step Reasoning"
collection: publications
category: conferences
permalink: /publication/2025-acl-entro
date: 2025-07-01
venue: "Findings of the Association for Computational Linguistics: ACL 2025"
authors: "Jinghan Zhang, Xiting Wang, Fengran Mo, Yeyang Zhou, Wanfu Gao, Kunpeng Liu"
paperurl: "https://aclanthology.org/2025.findings-acl.201/"
doi: "10.18653/v1/2025.findings-acl.201"
excerpt: "Entro-duction dynamically adjusts reasoning depth in LLMs by monitoring entropy and variance entropy, improving reasoning accuracy and efficiency."
---

Multi-step processes via large language models (LLMs) have proven effective for solving complex reasoning tasks. However, the depth of exploration of the reasoning procedure can significantly affect the task performance. Existing methods to automatically decide the depth often lead to high cost and a lack of flexibility. To address these issues, we propose Entropy-based Exploration Depth Conduction (Entro-duction), a novel method that dynamically adjusts the exploration depth during multi-step reasoning by monitoring LLM's output entropy and variance entropy. We employ these two features to capture the model's uncertainty of the current step and the fluctuation of uncertainty across consecutive reasoning steps. Based on the observed entropy changes, the LLM selects whether to deepen, expand, or stop exploration according to the probability, which facilitates the trade-off between the reasoning accuracy and exploration effectiveness. Experimental results across four benchmark datasets demonstrate the efficacy of Entro-duction.


📄 *Findings of the Association for Computational Linguistics: ACL 2025, pp. 3895–3906, Vienna, Austria.*  
🔗 [Paper Link (ACL Anthology)](https://aclanthology.org/2025.findings-acl.201/)  
🔗 [DOI](https://doi.org/10.18653/v1/2025.findings-acl.201)
