# Module 4 – Tokenization

This module explores how Hugging Face tokenizers transform raw text into numerical representations that can be processed by Transformer models. It covers the complete tokenization pipeline, from text normalization and pre-tokenization to building custom tokenizers using different tokenization algorithms.

## Learning Objectives

- Understand the architecture of modern tokenizers
- Explore fast tokenizer capabilities
- Learn token alignment for Question Answering and Named Entity Recognition
- Understand text normalization and pre-tokenization
- Build custom tokenizers from scratch
- Compare WordPiece, Byte-Pair Encoding (BPE), and Unigram tokenization

## Topics Covered

- Fast tokenizers
- Token-to-word and character offset mappings
- Question Answering tokenization
- Named Entity Recognition tokenization
- Text normalization
- Pre-tokenization
- WordPiece tokenization
- Byte-Pair Encoding (BPE)
- Byte-Level BPE
- Unigram tokenization
- Training tokenizer vocabularies
- Tokenizer post-processing
- Saving and reloading custom tokenizers

## Notebook

| Notebook | Description |
|----------|-------------|
| `04_tokenizers.ipynb` | Exploring Hugging Face fast tokenizers and building custom tokenizers from scratch. |

## Skills Demonstrated

- Hugging Face Tokenizers
- Hugging Face Transformers
- Text preprocessing
- Offset mappings
- Question Answering preprocessing
- Named Entity Recognition preprocessing
- Tokenization pipelines
- Vocabulary training
- Custom tokenizer development

## Requirements

Install the required dependencies from the repository root:

```bash
pip install -r ../requirements.txt
```

## Key Takeaways

After completing this module, you will understand how to:

- Transform raw text into model-ready token IDs.
- Use fast tokenizers for NLP tasks such as Question Answering and Named Entity Recognition.
- Build and train custom tokenizers using WordPiece, Byte-Pair Encoding (BPE), Byte-Level BPE, and Unigram algorithms.
- Understand each stage of the tokenization pipeline, from normalization to post-processing.