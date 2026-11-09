---
title: "StaRPO: Stability-Augmented Reinforcement Policy Optimization"
subtitle: ''
summary: ''
authors:
- "Jinghan Zhang"
- "Fengran Mo"
- "Tharindu Cyril Weerasooriya"
- "Ruimin Dai"
- "X. Y. Han"
- "Yanjie Fu"
- "admin"
- "Kunpeng Liu"
tags: ["LLMs and AI Agents"]
categories: []
date: '2026-11-06'
publishDate: '2026-11-06'
featured: false
draft: false
publication_types:
- '1'
publication: "Conference on Neural Information Processing Systems (NeurIPS 2026)"
publication_short: "NeurIPS 2026"
abstract: "Reinforcement learning (RL) is effective in enhancing the accuracy of large language models in complex reasoning tasks. Existing RL policy optimization frameworks rely on final-answer correctness as feedback signals and rarely capture the internal logical structure of the reasoning process. Consequently, the models would generate fluent and semantically relevant responses but logically inconsistent, structurally erratic, or redundant. To this end, we propose StaRPO, a stability-augmented reinforcement learning framework that explicitly incorporates reasoning stability into the optimization objective. Our StaRPO decomposes stability into two computable lightweight metrics: the Autocorrelation Function (ACF) to evaluate local step-to-step coherence, and Path Efficiency (PE) to evaluate global goal-directedness of the reasoning trajectory. These stability rewards are combined with task rewards to provide complementary and process-aware feedback. We validate the effectiveness of using ACF and PE rewards by showing their correlation with logic errors on two backbone models. Experiments on four reasoning benchmarks show that StaRPO consistently outperforms compared baselines and can enhance both final-answer accuracy and logical stability."
url_pdf: ""
links:
- name: "arXiv"
  url: "https://arxiv.org/abs/2604.08905"
---
