# IMDB-reviews---Sentiment-Analysis
#  DL Project 5: IMDB Reviews - Sentiment Analysis

This project applies Deep Learning techniques to perform **Sentiment Analysis** on IMDB movie reviews.
The goal is to classify each review as **positive** or **negative**, helping machines understand human sentiment from natural language.

##  Project Overview

Sentiment Analysis is a fundamental task in Natural Language Processing (NLP). Using a labeled dataset of IMDB movie reviews, 
we built and trained deep learning models to automatically classify the sentiment of each review.

This project demonstrates:
- Text preprocessing and tokenization
- Word embedding techniques.
- Deep learning architectures like LSTM
- Evaluation using accuracy, confusion matrix, and loss plots

---

## Dataset
- Dataset URL: https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews
- **Content**: 50,000 movie reviews (40,000 for training, 10,000 for testing).

---

##  Preprocessing Steps

- Lowercasing and punctuation removal
- Tokenization
- Padding sequences to a fixed length
- Word embedding initialization (Random/GloVe)

---
Accuracy on training data is 90.80%.
Accuracy on test data is 87.7%.
