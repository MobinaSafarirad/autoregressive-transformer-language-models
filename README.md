# Autoregressive Transformer Language Models

A technical study of how modern language models turn next-token prediction into text generation.

This project started from studying the fundamentals of language models and gradually expanded into the Transformer architecture, causal self-attention, autoregressive generation, scaling, and instruction tuning.

## What this covers

- What a language model actually predicts
- Tokens and next-token probability distributions
- How autoregressive generation works
- Transformer architecture
- Causal self-attention and masking
- Logits, softmax, and token probabilities
- Training with next-token prediction and cross-entropy
- Scaling of language models
- Instruction tuning and RLHF
- Some limitations and practical considerations

## Report

The main result of this project is the technical report:

**Autoregressive Transformer Language Models: From Next-Token Prediction to Text Generation**

You can find the report in the `report/` directory.

## Why I made this

I wanted to understand what really happens inside a language model beyond simply using an API or chatbot.

The goal was to study the underlying ideas, read the original research behind them, and organize what I learned into a technical document that I could refer back to later.

## Sources

The report is based on academic papers, technical documentation, and NLP/ML learning material.

Some of the main references include:

- Vaswani et al. — *Attention Is All You Need*
- Radford et al. — *Improving Language Understanding by Generative Pre-Training*
- Radford et al. — *Language Models are Unsupervised Multitask Learners*
- Brown et al. — *Language Models are Few-Shot Learners*
- Kaplan et al. — *Scaling Laws for Neural Language Models*
- Ouyang et al. — *Training Language Models to Follow Instructions with Human Feedback*

Full references are included with the report.

## Status

This is an ongoing learning project. I plan to extend it with implementations and experiments as I continue studying language models and deep learning.

## Author

Mobina Safarirad

Interested in AI, machine learning, software engineering, and understanding how things work under the hood.
