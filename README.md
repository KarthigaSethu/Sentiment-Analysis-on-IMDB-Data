# Sentiment Classification with BERT and RoBERTa

This repository contains implementations of text sentiment classification using BERT and RoBERTa models. The models were trained and evaluated on a sentiment classification dataset. Below are the details of the setup and results.

## Models

### BERT
BERT (Bidirectional Encoder Representations from Transformers) is a pre-trained language model developed by Google. It is designed to understand the context of a word in search queries, providing better search results. In this repository, we fine-tuned a BERT model for the task of sentiment classification.

- **Test Accuracy:** 93%

### RoBERTa
RoBERTa (A Robustly Optimized BERT Pretraining Approach) is an optimized version of BERT developed by Facebook AI. It improves upon BERT by training with more data, larger batch sizes, and longer sequences.

- **Test Accuracy:** 95%
- **Note:** The RoBERTa model was trained for a single epoch due to GPU memory limitations on Google Colab.
