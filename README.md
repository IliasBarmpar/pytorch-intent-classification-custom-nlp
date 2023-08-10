# Natural Language Processing with LSTM and Transformers 
This repository contains code for performing natural language processing tasks using LSTM and Transformers models. The code demonstrates how to preprocess text data, build LSTM models, and fine-tune Transformers models for sequence classification tasks.

## Introduction

This notebook showcases the implementation of LSTM and Transformers models for text classification tasks. The notebook covers the following key steps:

1. Data preprocessing: The notebook demonstrates how to preprocess text data, including tokenization, removing stopwords, and converting text into integer sequences for input to the models.

2. LSTM model implementation: The notebook presents the implementation of an LSTM-based model for sequence classification. It covers model architecture, training, and evaluation using F1 score.

3. LSTM with GloVe embeddings: The notebook includes an example of initializing the LSTM model with pre-trained GloVe word embeddings.

4. Transformers model implementation: The notebook shows how to fine-tune a pre-trained Transformers model (such as ALBERT, Roberta, or BERT) for sequence classification.

5. Evaluation and visualization: The notebook evaluates the trained models using F1 score and displays a confusion matrix to assess classification performance.

6. Answering user queries: The notebook includes helper functions to input a user query and get a response using the trained LSTM and Transformers models.

## Prerequisites
- Python 3.x
- Jupyter Notebook environment
- PyTorch, TensorFlow, nltk, Transformers, pandas, numpy, matplotlib libraries
- Pre-trained GloVe word embeddings (glove.6B.100d.txt)