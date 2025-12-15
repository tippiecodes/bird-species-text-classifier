# Bird Species Text Classifier (NLP)

This project builds a supervised text classification pipeline to predict bird species from written descriptions.

It covers end-to-end NLP workflow: data cleaning, feature extraction with TF-IDF, model training, evaluation, and interpretation of key features driving predictions.

---

## What this project includes
- Text preprocessing (cleaning, stopword handling, tokenization, lemmatization)
- Exploratory text analysis (length distributions, n-grams, word clouds)
- TF-IDF feature extraction
- Supervised model training and comparison:
  - Logistic Regression
  - Multinomial Naive Bayes
  - Random Forest
- Evaluation using accuracy, precision, recall, F1-score, and classification reports
- Feature importance review (Random Forest)

---

## Tools & Libraries
- Python (Google Colab)
- pandas, numpy
- nltk, spaCy
- scikit-learn
- matplotlib / seaborn

---

## Files
- `notebook.ipynb` (or `.py`) – Full workflow and model results
- `cleaned_text_output.csv` – Preprocessed dataset used for training/testing
