---
title: "WEBSERV: A Browser-Server Environment for Efficient Training of Reinforcement Learning-based Web Agents at Scale"
subtitle: ''
summary: ''
authors:
- "Yuxuan Lu"
- "Jing Huang"
- "Hui Liu"
- "Jiri Gesi"
- "Yan Han"
- "Shihan Fu"
- "Tianqi Zheng"
- "admin"
tags: ["LLMs and AI Agents"]
categories: []
date: '2025-12-14'
publishDate: '2025-12-14'
featured: false
draft: false
publication_types:
- '1'
publication: "First Workshop on Multi-Turn Interactions in Large Language Models, NeurIPS 2025"
publication_short: "NeurIPS 2025 Workshop"
abstract: "Training and evaluation of Reinforcement Learning (RL) web agents have gained increasing attention, yet a scalable and efficient environment that couples realistic and robust browser-side interaction with controllable server-side state at scale is still missing. Existing environments tend to have one or more of the following issues: they overwhelm policy models with excessive and noisy context; they perform actions non-deterministically without waiting for the UI or network to stabilize; or they cannot scale isolated client-server containers effectively for parallel RL rollouts. We propose WEBSERV, an environment that includes 1) a compact, site-agnostic browser environment that balances context and action complexity, and 2) a scalable RL environment via efficient launching and resetting web-servers to enable scalable RL training and evaluation. We evaluate WEBSERV on the shopping CMS and Gitlab tasks in WebArena, achieving state-of-the-art single-prompt success rates while cutting launch latency by ~5x and storage need by ~240x, with a comparable memory footprint, enabling 200+ concurrent containers on a single host."
url_pdf: ""
---
