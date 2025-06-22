# 🧠 GPT from Scratch - A Minimal Transformer Language Model

This repository contains my personal implementation of a **GPT-style transformer model** built entirely from scratch using PyTorch. The project was created to deeply understand the internals of large language models (LLMs), including tokenization, attention mechanisms, positional embeddings, and text generation workflows.

> ⚠️ Disclaimer: This is a learning-focused project. Due to limited training data and lack of fine-tuning, the model **generates incoherent (gibberish) outputs**, which is expected. The goal is not to produce production-grade results, but to gain hands-on experience with the structure and training of generative models.

---

## 🔧 Features

- Manual implementation of:
  - Multi-head self-attention
  - Feedforward layers
  - Residual connections and layer normalization
  - Absolute positional embeddings
- Custom tokenizer (character-level & subword experiments)
- Full training loop with:
  - Cross-entropy loss
  - Gradient clipping
  - Learning rate scheduling
- Simple text generation using sampling (greedy, top-k, nucleus)
