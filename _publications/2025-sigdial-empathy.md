---
title: "Distilling Empathy from Large Language Models"
collection: publications
category: conferences
permalink: /publication/2025-sigdial-empathy-distillation
date: 2025-07-10
venue: "Proceedings of the 26th Annual Meeting of the Special Interest Group on Discourse and Dialogue (SIGDIAL 2025)"
authors: "Henry J. Xie, Jinghan Zhang, Xinhao Zhang, Kunpeng Liu"
paperurl: "https://arxiv.org/abs/2507.08151"
excerpt: "This paper presents a two-step fine-tuning framework for distilling empathy from Large Language Models (LLMs) into Smaller Language Models (SLMs), achieving a 90% win rate in empathetic response generation."
---

**Knowledge distillation** from Large Language Models (LLMs) to Smaller Language Models (SLMs) has been instrumental in making advanced language capabilities accessible to resource-constrained environments such as mobile devices.  
However, beyond preserving general task performance, ensuring the transfer of **empathy**—a cornerstone of positive human interaction—remains a largely unexplored challenge.

We propose a comprehensive framework for **Empathy Distillation**, transferring the empathetic behaviors of LLMs into smaller models through a **two-step fine-tuning process**.  
Our method leverages dialogue datasets distilled from empathetic LLM responses and introduces **targeted empathy improvement prompts** to guide the SLM during training.

The proposed framework explores multiple distillation strategies beyond direct prompting, demonstrating that models fine-tuned with targeted prompts achieve substantially higher empathy quality.  
Experimental results show that our empathy-enhanced SLM attains a **90% win rate** in human evaluations, outperforming baseline distillation approaches by over **10%**.

📄 *In Proceedings of the 26th Annual Meeting of the Special Interest Group on Discourse and Dialogue (SIGDIAL 2025).*  
🔗 [Paper Link (arXiv:2507.08151)](https://arxiv.org/abs/2507.08151)
