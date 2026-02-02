# Week 3 – Text Classification with RNNs and LSTMs

## Overview
This project compares a baseline SimpleRNN model with an LSTM model for binary sentiment classification using the IMDB movie reviews dataset. The goal is to evaluate how architectural differences impact performance on sequence-based text data.

## Dataset
- IMDB Movie Reviews Dataset (TensorFlow Keras)
- 50,000 labeled reviews (positive / negative)

## Methods
- Text preprocessing: tokenization and padding to fixed sequence length
- Models:
  - Embedding + SimpleRNN
  - Embedding + LSTM
- Hyperparameter tuning:
  - Sequence length
  - Batch size
  - Learning rate
  - Gradient clipping
- Evaluation metrics:
  - Accuracy
  - Loss (training and validation)

## Results Summary
- SimpleRNN Test Accuracy: ~0.50
- LSTM Test Accuracy: ~0.82
- LSTM demonstrated stronger generalization and training stability

## Files
- `Week3_IMDB_RNN_LSTM.ipynb` – main notebook containing model implementation, training, and evaluation
- `.gitignore` – excludes virtual environment and cache files

## How to Run
1. Open the notebook
2. Run cells top-to-bottom in order

## References
- TensorFlow. Text classification with an RNN  
  https://www.tensorflow.org/text/tutorials/text_classification_rnn
