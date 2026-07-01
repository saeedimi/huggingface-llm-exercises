# Module 3 – Fine-Tuning Transformer Models

This module demonstrates how to prepare datasets and fine-tune pretrained Transformer models using the Hugging Face Transformers library and the `Trainer` API.

Unlike the later LLM-specific modules (e.g., SFT, LoRA, and GRPO), this notebook focuses on the standard supervised fine-tuning workflow for Transformer models on downstream NLP tasks.

---

## Learning Objectives

- Load and inspect NLP datasets
- Tokenize and preprocess text
- Perform a single optimization step
- Configure training with `TrainingArguments`
- Fine-tune pretrained Transformer models using the `Trainer` API
- Evaluate model performance

---

## Topics Covered

- Dataset loading
- Dataset preprocessing
- Tokenization
- Dynamic padding with data collators
- Single-batch training
- Hugging Face Trainer API
- Training configuration
- Model evaluation

---

## Notebook

| Notebook | Description |
|----------|-------------|
| `03_model_training.ipynb` | End-to-end supervised fine-tuning of a pretrained Transformer model using the Hugging Face Trainer API. |

---

## Skills Demonstrated

- PyTorch
- Hugging Face Transformers
- Hugging Face Datasets
- Hugging Face Evaluate
- Hugging Face Trainer API
- Dataset preprocessing
- Tokenization
- Model fine-tuning
- Model evaluation

---

## Requirements

Install the required packages from the repository root:

```bash
pip install -r ../requirements.txt
```

---

## Repository Structure

```
03-model-training/
│
├── README.md
└── 03_model_training.ipynb
```

---

## Key Takeaways

- Prepare datasets for Transformer training.
- Build an end-to-end supervised fine-tuning pipeline.
- Configure and train models using the Hugging Face `Trainer`.
- Evaluate fine-tuned models on downstream NLP tasks.
