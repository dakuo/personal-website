---
title: "See, Think, Act: Online Shopper Behavior Simulation with VLM Agents"
subtitle: ''
summary: ''
authors:
- "Yimeng Zhang"
- "Jiri Gesi"
- "Ran Xue"
- "Tian Wang"
- "Ziyi Wang"
- "Yuxuan Lu"
- "Sinong Zhan"
- "Huimin Zeng"
- "Qingjun Cui"
- "Yufan Guo"
- "Jing Huang"
- "Mubarak Shah"
- "admin"
tags: ["LLMs and AI Agents", "Human-AI Collaboration"]
categories: []
date: '2025-12-10'
publishDate: '2025-12-10'
featured: false
draft: false
publication_types:
- '3'
publication: "Preprint"
publication_short: "Preprint"
abstract: "LLMs have recently demonstrated strong potential in simulating online shopper behavior. Prior work has improved action prediction by applying SFT on action traces with LLM-generated rationales, and by leveraging RL to further enhance reasoning capabilities. Despite these advances, current approaches rely on text-based inputs and overlook the essential role of visual perception in shaping human decision-making during web GUI interactions. In this paper, we investigate the integration of visual information, specifically webpage screenshots, into behavior simulation via VLMs, leveraging OPeRA dataset. By grounding agent decision-making in both textual and visual modalities, we aim to narrow the gap between synthetic agents and real-world users, thereby enabling more cognitively aligned simulations of online shopping behavior. Specifically, we employ SFT for joint action prediction and rationale generation, conditioning on the full interaction context, which comprises action history, past HTML observations, and the current webpage screenshot. To further enhance reasoning capabilities, we integrate RL with a hierarchical reward structure, scaled by a difficulty-aware factor that prioritizes challenging decision points. Empirically, our studies show that incorporating visual grounding yields substantial gains: the combination of text and image inputs improves exact match accuracy by more than 6% over text-only inputs. These results indicate that multi-modal grounding not only boosts predictive accuracy but also enhances simulation fidelity in visually complex environments, which captures nuances of human attention and decision-making that text-only agents often miss. Finally, we revisit the design space of behavior simulation frameworks, identify key methodological limitations, and propose future research directions toward building efficient and effective human behavior simulators."
url_pdf: ""
links:
- name: "arXiv"
  url: "https://arxiv.org/abs/2510.19245"
---
