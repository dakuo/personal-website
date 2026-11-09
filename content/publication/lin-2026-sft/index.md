---
title: "SFT Doesn’t Always Hurt General Capabilities: Revisiting Domain-Specific Fine-Tuning in LLMs"
subtitle: ''
summary: ''
authors:
- "Jiacheng Lin"
- "Zhongruo Wang"
- "Kun Qian"
- "Tian Wang"
- "Arvind Srinivasan"
- "Hansi Zeng"
- "Ruochen Jiao"
- "Xie Zhou"
- "Jiri Gesi"
- "admin"
- "Yufan Guo"
- "Kai Zhong"
- "Weiqi Zhang"
- "Sujay Sanghavi"
- "Changyou Chen"
- "Hyokun Yun"
- "Lihong Li"
tags: ["LLMs and AI Agents"]
categories: []
date: '2026-10-21'
publishDate: '2026-10-21'
featured: false
draft: false
publication_types:
- '1'
publication: "ICLR 2026"
publication_short: "ICLR 2026"
abstract: "Supervised Fine-Tuning (SFT) on domain-specific datasets is a common approach to adapt Large Language Models (LLMs) to specialized tasks but is often believed to degrade their general capabilities. In this work, we revisit this trade-off and present both empirical and theoretical insights. First, we show that SFT does not always hurt: using a smaller learning rate can substantially mitigate general performance degradation while preserving comparable target-domain performance. We then provide a theoretical analysis that explains these phenomena and further motivates a new method, Token-Adaptive Loss Reweighting (TALR). Building on this, and recognizing that smaller learning rates alone do not fully eliminate general-performance degradation in all cases, we evaluate a range of strategies for reducing general capability loss, including L2 regularization, LoRA, model averaging, FLOW, and our proposed TALR. Experimental results demonstrate that while no method completely eliminates the trade-off, TALR consistently outperforms these baselines in balancing domain-specific gains and general capabilities. Finally, we distill our findings into practical guidelines for adapting LLMs to new domains: (i) using a small learning rate to achieve a favorable trade-off, and (ii) when a stronger balance is further desired, adopt TALR as an effective strategy."
url_pdf: ""
links:
- name: "OpenReview"
  url: "https://openreview.net/forum?id=ru93xpQFi1"
---
