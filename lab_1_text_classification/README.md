# Lab 1 - Text Classification

## Overview
This project explores several NLP classification approaches using Scikit-learn and classical machine learning techniques.

The objective was to perform sentiment analysis over movie reviews and compare different vectorization and classification strategies.

---

## Techniques Used

- CountVectorizer
- Bag of Words
- N-grams
- Logistic Regression
- Linear Support Vector Machines (LinearSVC)
- Hyperparameter tuning
- Validation/Test split

---

## Dataset

NLTK Movie Reviews Dataset

---

## Experiments

Several approaches were tested:

1. Logistic Regression baseline
2. Logistic Regression with preprocessing
3. Linear SVM
4. Linear SVM with bigrams
5. Linear SVM with feature limitation

---

## Best Model

- LinearSVC
- `ngram_range=(1,2)`
- `min_df=5`
- `max_df=0.7`

Test Accuracy:

```text
0.84167
