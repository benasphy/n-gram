# N-Gram Language Model with Neural Network Enhancement

## Overview
This repository contains an implementation of an N-Gram language model using Python and NLTK, with additional enhancements through neural networks (LSTM) for text generation. The project focuses on Amharic text processing, including stopword removal, probability calculations, and evaluation using perplexity and extrinsic methods.

## Features
### N-Gram Model
- Generates **unigrams, bigrams, trigrams, and fourgrams**.
- Computes **probabilities** of n-grams.
- Calculates **conditional probabilities** using bigrams.
- Implements **stopword removal** to refine results.
- Visualizes **word clouds** before and after stopword removal.
- Computes **sentence probabilities** based on the trained model.
- Generates **random sentences** using n-grams.
- Evaluates **model performance** using **perplexity**.

### Neural Network Model (LSTM-Based)
- Tokenizes the corpus and prepares sequences.
- Uses an **LSTM-based model** to predict and generate text.
- Trains on sentence structures for **better fluency**.
- Implements an **embedding layer** for efficient text representation.
- Generates text dynamically based on seed words.

## Installation
Ensure you have Python installed, then install the required dependencies:
```sh
pip install nltk wordcloud tensorflow keras matplotlib
```

## Usage
1. **Prepare your corpus**
   - Replace `path_to_corpus.txt` with your actual dataset.
2. **Run the N-Gram Model**
   ```python
   python ngram_model.py
   ```
3. **Train the Neural Network Model**
   - The LSTM model will be trained using tokenized sequences.
4. **Generate New Text**
   ```python
   generate_text("ኢትዮጵያ")
   ```

## Evaluation
- **Intrinsic Evaluation**: Perplexity score calculation.
- **Extrinsic Evaluation**: Evaluate the model by applying it to NLP tasks like translation or classification.

## Contributions
Feel free to contribute by improving stopword removal, adding new evaluation techniques, or optimizing LSTM training.

## License
MIT License

## Author
Your Name

