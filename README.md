# Advanced Markov Text Generator

This project implements an advanced Markov chain model for generating text using the Sherlock Holmes stories dataset from [Kaggle](https://www.kaggle.com/datasets/idevji1/sherlock-holmes-stories/data). It includes features like POS tagging, backoff mechanisms, and evaluation using perplexity, BLEU, and ROUGE scores.

## Features

- **Variable-Order Markov Models**: Supports n-gram orders up to a specified maximum.
- **POS Tagging**: Generates grammatically plausible text using part-of-speech tagging.
- **Backoff Mechanism**: Handles unseen n-grams by falling back to lower-order models.
- **Evaluation Metrics**: Includes perplexity, BLEU, and ROUGE scores for model evaluation.
- **Text Generation**: Generates text with customizable length and optional seed words.


