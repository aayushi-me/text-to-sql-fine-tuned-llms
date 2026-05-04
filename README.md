# Text-to-SQL Generation with Fine-Tuned LLMs

Fine-tuning large language models on domain-specific SQL datasets to improve natural language to SQL query generation accuracy.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

## Overview

This project explores fine-tuning pre-trained LLMs on text-to-SQL datasets to generate accurate SQL queries from natural language input. The notebook covers data preparation, model fine-tuning, evaluation, and comparison against baseline models.

## What's Covered

- Dataset preparation and preprocessing for text-to-SQL fine-tuning
- Fine-tuning a pre-trained LLM using HuggingFace Transformers
- Evaluation using execution accuracy and exact match metrics
- Comparison of fine-tuned model performance against baseline

## Getting Started

### Prerequisites

- Python 3.9+
- GPU recommended for fine-tuning

### Installation

```bash
pip install transformers datasets torch accelerate
```

### Run

```bash
jupyter notebook text-to-sql-fine-tuned-llms.ipynb
```

## License

MIT License
