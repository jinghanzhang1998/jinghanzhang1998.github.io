---
title: "Prototypical Reward Network for Data-Efficient RLHF"
collection: publications
category: conferences
permalink: /publication/2024-acl-proto-rm
date: 2024-08-01
venue: "Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics (ACL 2024)"
authors: "Jinghan Zhang, Xiting Wang, Yiqiao Jin, Changyu Chen, Xinhao Zhang, Kunpeng Liu"
paperurl: "https://aclanthology.org/2024.acl-long.771"
excerpt: "Proto-RM introduces prototypical networks into reward modeling to enhance data efficiency in RLHF, achieving robust preference learning with limited human feedback."
---

The reward model for **Reinforcement Learning from Human Feedback (RLHF)** has proven effective in fine-tuning Large Language Models (LLMs).  
However, collecting human feedback for RLHF can be resource-intensive and limit scalability for large models and complex tasks.

We propose **Proto-RM**, a *Prototypical Reward Network* that leverages prototypical representations to enhance reward models under limited human feedback.  
By enabling stable and reliable structural learning from fewer samples, Proto-RM significantly enhances LLMs’ adaptability and accuracy in interpreting human preferences.

Extensive experiments on various datasets demonstrate that Proto-RM improves both reward model and LLM performance in human feedback tasks,  
achieving comparable or better results than traditional methods while requiring substantially less annotated data.

📄 *In Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics (ACL 2024), pp. 13871–13884.*  
🔗 [Paper Link (ACL Anthology)](https://aclanthology.org/2024.acl-long.771)
