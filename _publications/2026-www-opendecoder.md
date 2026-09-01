---
title: "OpenDecoder: Open Large Language Model Decoding to Incorporate Document Quality in RAG"
collection: publications
category: conferences
permalink: /publication/2026-www-opendecoder
date: 2026-04-12
venue: "Proceedings of the ACM Web Conference 2026 (TheWebConf 2026)"
authors: "Fengran Mo, Zhan Su, Yuchen Hui, Jinghan Zhang, Jia Ao Sun, Zheyuan Liu, Chao Zhang, Tetsuya Sakai, Jian-Yun Nie"
paperurl: "https://doi.org/10.1145/3774904.3792524"
excerpt: "OpenDecoder incorporates explicit document-quality indicators into large language model decoding to make retrieval-augmented generation more robust to noisy and variably useful context."
---

Retrieval-augmented generation typically assumes that retrieved passages are sufficiently relevant and useful, even though real retrieval results vary considerably in quality. OpenDecoder exposes the large language model decoding process to explicit document-quality indicators, including relevance scores, ranking scores, and query performance prediction signals. This design allows generation to respond directly to the reliability of the retrieved context and can be integrated flexibly with different post-training objectives and external indicators. Experiments on five benchmarks demonstrate stronger effectiveness and robustness than existing approaches under varying levels of retrieval noise.

📄 *In Proceedings of the ACM Web Conference 2026 (TheWebConf 2026), pp. 2252–2262.*  
🔗 [Paper Link (ACM Digital Library)](https://doi.org/10.1145/3774904.3792524)
