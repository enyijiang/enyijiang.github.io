---
title:          "CLEAR: Continuous Latent Adapter Routing for Utility-Preserving LLM Safety Alignment"
date:           2026-08-21 00:01:00 +0800
selected:       true
pub:            "arXiv preprint"
pub_date:       "2026"
research_question: "If latent risk can be detected, can we intervene only when necessary?"
summary: "CLEAR uses a hidden-state gate to adjust a safety adapter’s strength, reducing attack success while preserving useful capabilities."
abstract: >-
  CLEAR uses a lightweight hidden-state gate to continuously control the activation strength of a safety low-rank adapter, cutting HarmBench attack success on Llama-3-8B-Instruct from 32.3% to 0.5% while preserving utility -- up to 7.1 points higher GSM8K accuracy than standard safety fine-tuning or LoRA.
authors:
  - Chengxiao Wang*
  - Enyi Jiang*
  - Xiaojing Liao
  - Sanmi Koyejo
links:
  Arxiv: https://arxiv.org/abs/2608.21278
---
