---
title: "LEKA: LLM-Enhanced Knowledge Augmentation"
collection: publications
category: conferences
permalink: /publication/2025-ijcai-leka-knowledge-augmentation
date: 2025-01-29
venue: "Proceedings of the 34th International Joint Conference on Artificial Intelligence (IJCAI 2025)"
authors: "Xinhao Zhang, Jinghan Zhang, Fengran Mo, Dongjie Wang, Yanjie Fu, Kunpeng Liu"
paperurl: "https://arxiv.org/abs/2501.17802"
excerpt: "This paper proposes LEKA, a Large Language Model–Enhanced Knowledge Augmentation framework that actively retrieves and aligns transferable knowledge across domains for improved data efficiency and transfer learning performance."
---

Humans excel at **analogical learning** and **knowledge transfer**, intuitively identifying which knowledge sources are appropriate for new problems.  
Emulating this capability in models remains a challenge: while it is straightforward to feed more data or train on larger corpora, enabling models to **select and analogize useful knowledge** is far more complex.

We propose **LEKA (LLM-Enhanced Knowledge Augmentation)**, a framework that enables models to autonomously **retrieve**, **align**, and **integrate** knowledge from external sources to improve transfer learning.  
LEKA extracts key information from target-domain text, retrieves semantically related data from large external libraries, and harmonizes the retrieved knowledge with the target domain in both **feature space** and **marginal probability measures**.

Extensive experiments across multiple domains demonstrate that LEKA significantly reduces computational cost, automates data alignment, and improves transfer learning outcomes—showcasing a step toward **self-directed knowledge utilization** in LLMs.

📄 *In Proceedings of the 34th International Joint Conference on Artificial Intelligence (IJCAI 2025).*  
🔗 [Paper Link (arXiv:2501.17802)](https://arxiv.org/abs/2501.17802)
