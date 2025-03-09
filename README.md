# Markov Chain Text Generation

This project implements text generation using advanced Markov chain models and NLP techniques, trained specifically on the Sherlock Holmes stories dataset from [Kaggle](https://www.kaggle.com/datasets/idevji1/sherlock-holmes-stories/data).

## Project Overview
This pipeline leverages advanced Markov chain modeling techniques, including part-of-speech (POS) tagging, backoff mechanisms, and extensive evaluation metrics to produce coherent, stylistically accurate generated texts based on Sherlock Holmes stories.

## Features
- **Text Processing:** Preprocessing steps including tokenization, cleaning, and normalization.
- **Advanced Markov Chain Model:** Supports variable-order n-grams, POS tagging, and employs backoff mechanisms for robust text generation.
- **Model Evaluation:** Comprehensive evaluation using perplexity, BLEU, and ROUGE metrics.
- **Text Generation:** Flexible text generation with configurable seed words and adjustable length.

## Dataset
The Sherlock Holmes stories dataset sourced from [Kaggle](https://www.kaggle.com/datasets/idevji1/sherlock-holmes-stories/data).

## Evaluation Metrics
- **Perplexity:** Measures how well the model predicts a sample.
- **BLEU Score:** Assesses the overlap of generated text with reference texts.
- **ROUGE Score:** Evaluates the quality of generated summaries against reference texts.

## Technologies
- Python
- NLTK (for tokenization, POS tagging)
- NumPy, Pandas
- Libraries: rouge, nltk.tokenize, nltk.corpus

## Usage
1. Clone the repository
2. Install required dependencies (`nltk`, `numpy`, `pandas`, `rouge`)
3. Execute `MarkovChain_Text_generation.ipynb` to train and generate Sherlock Holmes-style texts.

## Example Outputs
Generated narratives demonstrating realistic text construction in the style of Sherlock Holmes, showcasing narrative coherence and stylistic fidelity.

## Author
- **Vishal Nair** | [GitHub](https://github.com/VishalNair129) | Email: v1292002@gmail.com

Explore further by adjusting model parameters and examining detailed evaluation results included within the notebook.

