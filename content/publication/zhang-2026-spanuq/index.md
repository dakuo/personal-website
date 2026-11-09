---
title: "SpanUQ: Span-Level Uncertainty Quantification for Large Language Model Generation"
subtitle: ''
summary: ''
authors:
- "Yimeng Zhang"
- "Yingying Zhuang"
- "Ziyi Wang"
- "Ye Lu"
- "Pei Chen"
- "A. Gupta"
- "SU Zhe"
- "Ming Tan"
- "Zhilin Zhang"
- "Qun Liu"
- "Manikandarajan Ramanathan"
- "Rajashekar Maragoud"
- "Edward Vul"
- "Jing Huang"
- "admin"
tags: ["LLMs and AI Agents"]
categories: []
date: '2026-11-07'
publishDate: '2026-11-07'
featured: false
draft: false
publication_types:
- '1'
publication: "Conference on Neural Information Processing Systems (NeurIPS 2026)"
publication_short: "NeurIPS 2026"
abstract: "Uncertainty estimation is essential for the trustworthy deployment of LLMs: it underpins self-refinement and serves as a decision signal for downstream systems, from verifiers to collaborating agents. However, existing approaches operate at suboptimal granularities: token-level scores lack semantic coherence, while sequence-level scores fail to localize errors. We formalize Span-Level Uncertainty Estimation (SLUE), a new task that targets the natural granularity for uncertainty: semantically coherent text spans, each conveying a single assessable unit of meaning. To address this task, we introduce SPANUQ, a lightweight probe that distills the uncertainty knowledge from expensive multi-sample inference into a single forward pass over LLM hidden states. SPANUQ employs a DETR-style span decoder to simultaneously detect spans and estimate their uncertainty via a Mixture of Beta distribution, trained with a principled combination of Beta NLL regression and contrastive ranking objectives. We construct SPANUQ-BENCH, the first span-level uncertainty benchmark comprising 20K prompts, 293K annotated spans, and continuous soft labels derived from multi-sample claim verification. Experiments on five LLM backbones show that SPANUQ consistently achieves the best span-level uncertainty quality , outperforming the strongest probe baseline and all sampling-based methods while being 10~20x faster. Its DETR-based span detector attains 0.910 F1, surpassing the best heuristic by 39.4%, enabling precise error localization that sequence-level methods cannot provide. The same architecture ports to five LLMs spanning two model families, with one probe trained per backbone, and we additionally observe that sequence-level uncertainty is partially decomposable, suggesting that span-level estimation subsumes sequence-level as a special case. The project page is available damon-demon.github.io/SpanUQ."
url_pdf: ""
links:
- name: "arXiv"
  url: "https://arxiv.org/abs/2607.05721"
---
