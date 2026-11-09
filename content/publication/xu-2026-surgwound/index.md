---
title: "SurgWound-Bench: A Benchmark for Surgical Wound Diagnosis"
subtitle: ''
summary: ''
authors:
- "Jiahao Xu"
- "Changchang Yin"
- "Odysseas Chatzipanagiotou"
- "Diamantis Tsilimigras"
- "Kevin Clear"
- "Bingsheng Yao"
- "admin"
- "Timothy Pawlik"
- "Ping Zhang"
tags: ["AI for Healthcare", "LLMs and AI Agents"]
categories: []
date: '2026-10-13'
publishDate: '2026-10-13'
featured: false
draft: false
publication_types:
- '1'
publication: "npj Digital Medicine"
publication_short: "npj Digit. Med. 2026"
abstract: "Surgical site infection (SSI) is one of the most common and costly healthcare-associated infections and and surgical wound care remains a significant clinical challenge in preventing SSIs and improving patient outcomes. While recent studies have explored the use of deep learning for preliminary surgical wound screening, progress has been hindered by concerns over data privacy and the high costs associated with expert annotation. Currently, no publicly available dataset or benchmark encompasses various types of surgical wounds, resulting in the absence of an open-source Surgical-Wound screening tool. To address this gap: (1) we present SurgWound, the first open-source dataset featuring a diverse array of surgical wound types. It contains 697 surgical wound images annotated by 3 professional surgeons with eight fine-grained clinical attributes. (2) Based on SurgWound, we introduce the first benchmark for surgical wound diagnosis, which includes visual question answering (VQA) and report generation tasks to comprehensively evaluate model performance. (3) Furthermore, we propose a three-stage learning framework, WoundQwen, for surgical wound diagnosis. In the first stage, we employ five independent MLLMs to accurately predict specific surgical wound characteristics. In the second stage, these predictions serve as additional knowledge inputs to two MLLMs responsible for diagnosing outcomes, which assess infection risk and guide subsequent interventions. In the third stage, we train a MLLM that integrates the diagnostic results from the previous two stages to produce a comprehensive report. This three-stage framework can analyze detailed surgical wound characteristics and provide subsequent instructions to patients based on surgical images, paving the way for personalized wound care, timely intervention, and improved patient outcomes."
url_pdf: ""
links:
- name: "Nature"
  url: "https://doi.org/10.1038/s41746-026-02791-3"
- name: "arXiv"
  url: "https://arxiv.org/abs/2508.15189"
---
