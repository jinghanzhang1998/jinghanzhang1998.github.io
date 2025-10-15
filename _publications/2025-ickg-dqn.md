---
title: "Dynamic Weight Adjusting Deep Q-Networks for Real-Time Environmental Adaptation"
collection: publications
category: conferences
permalink: /publication/2024-ickg-dwa-dqn
date: 2024-12-11
venue: "Proceedings of the 2024 IEEE International Conference on Knowledge Graph (ICKG 2024)"
authors: "Xinhao Zhang, Jinghan Zhang, Wujun Si, Kunpeng Liu"
paperurl: "https://ieeexplore.ieee.org/abstract/document/10884195"
excerpt: "This paper introduces IDEM-DQN, a Deep Q-Network framework with dynamic weight adjustment for real-time adaptation in changing environments."
---

Deep Reinforcement Learning has shown excellent performance in generating efficient solutions for complex tasks. However, its efficacy is often limited by static training modes and heavy reliance on vast data from stable environments. To address these shortcomings, this study explores integrating dynamic weight adjustments into Deep Q-Networks (DQN) to enhance their adaptability. We implement these adjustments by modifying the sampling probabilities in the experience replay to make the model focus more on pivotal transitions as indicated by real-time environmental feedback and performance metrics. We design a novel Interactive Dynamic Evaluation Method (IDEM) for DQN that successfully navigates dynamic environments by prioritizing significant transitions based on environmental feedback and learning progress. Additionally, when faced with rapid changes in environmental conditions, IDEM-DQN shows improved performance compared to baseline methods. Our results indicate that under circumstances requiring rapid adaptation, IDEM-DQN can more effectively generalize and stabilize learning. Extensive experiments across various settings confirm that IDEM-DQN outperforms standard DQN models, particularly in environments characterized by frequent and unpredictable changes.

📄 *In Proceedings of the 2024 IEEE International Conference on Knowledge Graph (ICKG 2024), pp. 500–507.*  
🔗 [Paper Link (IEEE Xplore)](https://ieeexplore.ieee.org/abstract/document/10884195)
