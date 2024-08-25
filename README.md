# Sentiment_Analysis

This project measures the average sentiment of Amazon Reviews using various sentiment analysis techniques.

## Overview

The objective of this project is to analyze the sentiment of Amazon reviews by leveraging multiple sentiment analysis tools. The analysis is performed using the following approaches:

1. **VADER (Valence Aware Dictionary and sEntiment Reasoner):**
   - A lexicon and rule-based sentiment analysis tool that is specifically attuned to sentiments expressed in social media. It is capable of detecting both positive and negative sentiment, as well as intensity.

2. **roBERTa Pre-trained Sentiment Analyzer:**
   - An advanced deep learning model that builds on the BERT architecture. This model is fine-tuned for sentiment analysis tasks and provides more nuanced and context-aware sentiment classification.

3. **HuggingFace Pipeline:**
   - A powerful tool from the HuggingFace library that simplifies the implementation of state-of-the-art natural language processing models. It supports multiple sentiment analysis models, including both VADER and roBERTa.

## Dataset

The dataset used in this project is sourced from Kaggle and contains Amazon reviews. You can find the dataset [here](https://www.kaggle.com/datasets/tarkkaanko/amazon).

