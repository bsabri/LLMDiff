# Beyond the Leaderboard: Understanding Performance Disparities in Large Language Models via Model Diffing

This repository contains code and artifacts for the EMNLP 2025 paper: "Beyond the Leaderboard: Understanding Performance Disparities in Large Language Models via Model Diffing"

## Abstract

Traditional benchmarking often fails to explain why one language model outperforms another. This work introduces **model diffing**, a mechanistic interpretability approach using crosscoders to analyze specific capability differences between closely related LLMs. We demonstrate this methodology by comparing Gemma-2-9b-it with its SimPO-enhanced variant, revealing that performance improvements stem from targeted capability shifts rather than uniform enhancements.

## Key Findings

- SimPO enhances safety mechanisms (+32.8%), multilingual capabilities (+43.8%), and instruction-following (+151.7%)
- Trade-offs include reduced emphasis on hallucination detection (-68.5%) and model self-reference (-44.1%)
- Model diffing reveals fine-grained insights invisible to benchmark scores and leaderboard metrics

## Repository Contents

- `crosscoder/` - Crosscoder training and analysis code
- `analysis/` - Scripts for capability categorization and latent interpretation
- `experiments/` - Replication code for Gemma-2-9b experiments
- `data/` - Capability taxonomy and processed results

## Citation
```bibtex
[Citation will be added upon publication]
