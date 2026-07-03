# 🤗 Hugging Face LLM Course Portfolio

A collection of practical implementations completed while following the **Hugging Face Large Language Model (LLM) Course**. This repository has been reorganized into a structured portfolio that demonstrates modern Natural Language Processing (NLP), Transformer models, and Large Language Model (LLM) workflows using the Hugging Face ecosystem.

![Transformer Architecture](01-transformers/transformers_architecture.png)

---

## 🚀 Repository Overview

This repository documents my hands-on implementation of the Hugging Face LLM Course. Each notebook has been reorganized, documented, and expanded with additional explanations, comments, and examples to create a professional learning portfolio.

---

## 📚 Topics Covered


- Transformer architectures
- Hugging Face pipelines
- Transformer model training
- Fast tokenizers
- WordPiece, Byte-Pair Encoding (BPE), and Unigram tokenization
- Dataset preprocessing
- Question Answering (QA)
- Named Entity Recognition (NER)
- Machine Translation
- Text Summarization
- Masked Language Modeling
- Causal Language Modeling
- Chat Templates
- Supervised Fine-Tuning (SFT)
- Parameter-Efficient Fine-Tuning (LoRA)
- Reasoning Models
- Group Relative Policy Optimization (GRPO)
- Reward Functions
- Reinforcement Learning for LLMs
---

## 🛠️ Technologies

- Python
- PyTorch
- Hugging Face Transformers
- Hugging Face Datasets
- Hugging Face Tokenizers
- Hugging Face Evaluate
- Hugging Face Hub
- Accelerate
- TRL
- PEFT
---

## 📂 Repository Structure

```text
huggingface-llm-course/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── 01-transformers/
├── 02-transformer-workflow/
├── 03-model-training/
├── 04-tokenizers/
├── 05-nlp-applications/
│   ├── token-classification
│   ├── masked-language-modeling
│   ├── machine-translation
│   ├── text-summarization
│   └── causal-language-modeling
├── 06-fine-tuningLLMs/
│   ├── chat-templates/
│   ├── supervised-fine-tuning
│   └── lora-fine-tuning
│
└── 07-reasoning-models/
    └── grpo-finetuning
```

---

## 📖 Modules

| Module | Description | Status |
|---------|-------------|:------:|
| **01 – Transformers** | Introduction to Transformer models and the Hugging Face `pipeline` API | ✅ |
| **02 – Transformer Workflow** | Understanding the internal workflow of tokenizers, models, and inference pipelines | ✅ |
| **03 – Model Training** | Dataset preprocessing and supervised fine-tuning using the Hugging Face `Trainer` API | ✅ |
| **04 – Tokenization** | Fast tokenizers, normalization, WordPiece, BPE, Unigram, and custom tokenizer construction | ✅ |
| **05 – NLP Tasks** | Question Answering, Named Entity Recognition, Translation, and Summarization | ✅ |
| **06 – LLM Fine-Tuning** | Chat templates, Supervised Fine-Tuning (SFT), and LoRA | ✅ |
| **07 – Reasoning Models** | Fine-tuning reasoning models using GRPO, custom reward functions, and reinforcement learning for LLMs| ✅ |
---

## 🎯 Learning Objectives

Throughout this repository, I explore how to:

- Understand the architecture of Transformer models.
- Build NLP applications using pretrained models.
- Process and tokenize text efficiently.
- Train and fine-tune Transformer models.
- Build custom tokenizers from scratch.
- Evaluate NLP models using standard benchmarks.
- Work effectively with the Hugging Face ecosystem.
- Understand conversational data formatting using chat templates.
- Apply parameter-efficient fine-tuning techniques such as LoRA.
- Understand post-training techniques for reasoning language models.
- Fine-tune LLMs using Group Relative Policy Optimization (GRPO).

---

## 📚 References

- Hugging Face Large Language Model Course
- Hugging Face Transformers
- Hugging Face Datasets
- Hugging Face Tokenizers
- Hugging Face Hub

---


## ⭐ About This Repository

This repository is part of my continuous learning journey in **Large Language Models (LLMs)**, **Generative AI**, and **Natural Language Processing (NLP)**. Rather than simply reproducing the Hugging Face course notebooks, I reorganized each module into a structured technical portfolio with improved documentation, code comments, and practical implementations. The repository now spans the complete LLM workflow—from Transformer fundamentals and NLP applications to supervised fine-tuning, parameter-efficient adaptation, and reinforcement learning techniques for reasoning models.