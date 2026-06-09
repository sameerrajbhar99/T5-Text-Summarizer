# T5-Text-Summarizer
A Transformer-based NLP project that fine-tunes the T5-small model for abstractive text summarization using Hugging Face Transformers and PyTorch. The model generates concise and meaningful summaries while preserving key information from the original text.


# T5 Text Summarizer

## Overview

T5 Text Summarizer is a Natural Language Processing (NLP) project that fine-tunes the T5-small transformer model for abstractive text summarization. The model learns to generate concise and meaningful summaries from lengthy text while retaining the most important information.

This project demonstrates the complete NLP pipeline, including data preprocessing, tokenization, model training, evaluation, and summary generation using Hugging Face Transformers and PyTorch.

---

## Features

- Text preprocessing and cleaning
- Tokenization using T5 Tokenizer
- Fine-tuning T5-small Transformer model
- Abstractive text summarization
- Summary generation for unseen text
- Model saving and loading
- Evaluation on validation data

---

## Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- Datasets
- Pandas
- NumPy
- Google Colab

---

## Model Information

**Base Model:** T5-small

**Task:** Abstractive Text Summarization

**Architecture:** Transformer Encoder-Decoder

---

## Project Workflow

1. Load dataset
2. Preprocess text data
3. Tokenize inputs and summaries
4. Fine-tune T5-small model
5. Evaluate model performance
6. Generate summaries
7. Save trained model
