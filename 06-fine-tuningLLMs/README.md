# Module 6 – Fine-Tuning Large Language Models

This module explores modern techniques for adapting pretrained Large Language Models (LLMs) to downstream tasks using the Hugging Face ecosystem. It covers chat templates, supervised fine-tuning (SFT), and parameter-efficient fine-tuning with Low-Rank Adaptation (LoRA).

## Learning Objectives

- Understand chat templates for conversational LLMs
- Prepare datasets for supervised fine-tuning
- Fine-tune pretrained language models using TRL
- Apply LoRA for parameter-efficient fine-tuning
- Compare full fine-tuning and LoRA-based approaches
- Publish fine-tuned models to the Hugging Face Hub

---

## Topics Covered

- Chat Templates
- Conversational datasets
- Supervised Fine-Tuning (SFT)
- TRL SFTTrainer
- PEFT
- LoRA
- Model inference
- Hugging Face Hub

---

## Notebooks

| Notebook | Description |
|----------|-------------|
| `01-chat-templates.ipynb` | Formatting conversational data using chat templates |
| `02-supervised-fine-tuning.ipynb` | Fine-tuning LLMs using the TRL `SFTTrainer` |
| `03-lora-fine-tuning.ipynb` | Parameter-efficient fine-tuning using LoRA adapters |

---

## Skills Demonstrated

- Hugging Face Transformers
- TRL
- PEFT
- LoRA
- Chat Templates
- Supervised Fine-Tuning
- Large Language Models
- Hugging Face Hub

---

## Requirements

```bash
pip install -r ../requirements.txt
```