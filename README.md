# Emotion Analysis using BERT and SVM

This project performs emotion classification from text using BERT embeddings and a Support Vector Machine (SVM) classifier.

## 💡 Overview

We use a pre-trained BERT model (`bert-base-uncased`) to extract deep contextual embeddings from input text. These embeddings are then used to train a linear SVM to classify emotions into:

- Joy
- Sadness
- Neutral
- Anger
- Fear

## 📁 Dataset

The dataset should be in a CSV file named `data_test.csv` with the following columns:

- `Text`: The input sentence.
- `Emotion`: The corresponding emotion label (one of: sadness, neutral, anger, fear, joy).

## ⚙️ Requirements

Install dependencies using:

```bash
pip install torch transformers pandas scikit-learn matplotlib seaborn


