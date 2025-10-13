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

Multi-step reasoning via large language models (LLMs) has proven effective for complex problem-solving.  
However, the *depth of exploration* in reasoning can critically affect performance.  
Existing methods that determine reasoning depth automatically often incur high computational cost and lack flexibility.

We propose **Entropy-based Exploration Depth Conduction (Entro-duction)**,  
a novel method that dynamically adjusts exploration depth during multi-step reasoning by monitoring LLM output **entropy** and **variance entropy**.  
These two metrics capture both the uncertainty at each reasoning step and the fluctuation of uncertainty across steps.

Based on the observed entropy dynamics, Entro-duction probabilistically decides whether to *deepen*, *expand*, or *stop* reasoning,  
achieving a balance between reasoning accuracy and exploration efficiency.  

Experimental results on four benchmark datasets demonstrate that Entro-duction significantly improves multi-step reasoning performance,  
achieving higher accuracy with reduced computation cost.

📄 *Findings of the Association for Computational Linguistics: ACL 2025, pp. 3895–3906, Vienna, Austria.*  
🔗 [Paper Link (ACL Anthology)](https://aclanthology.org/2025.findings-acl.201/)  
🔗 [DOI](https://doi.org/10.18653/v1/2025.findings-acl.201)
