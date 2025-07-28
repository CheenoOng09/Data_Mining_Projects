# Week 13 – Text Mining (SMSSpamCollection)

This project demonstrates a basic NLP (Natural Language Processing) pipeline for text preprocessing and feature extraction using the **SMSSpamCollection** dataset.

---

## Objective

To preprocess SMS text data and apply a full NLP pipeline including:

- Tokenization  
- Stopword Removal  
- Stemming or Lemmatization  
- TF-IDF Vectorization

---

## Dataset

- Source: [UCI Machine Learning Repository – SMSSpamCollection](https://archive.ics.uci.edu/dataset/228/sms+spam+collection)
- A collection of 5,574 real SMS messages, tagged as "spam" or "ham" (not spam).

---

## Implementation Summary

The notebook demonstrates the following:

- Loaded and previewed a sample of 5 SMS messages
- Tokenized each sentence into words
- Removed common stopwords
- Applied stemming or lemmatization
- Converted text to numerical vectors using **TF-IDF**

---

## Files

- `Text Mining.ipynb` – Main Jupyter notebook for the assignment
- `Instructions.txt` – Task requirements and dataset source

---

## Bonus Note

This assignment is optional, but completing it as a group with a job breakdown description earns extra credit in class performance.

---

## Requirements

Install dependencies:

```bash
pip install nltk scikit-learn pandas
```

Make sure to download necessary NLTK resources:

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
```

---
