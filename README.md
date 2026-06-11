# Symptom Classification NLP Project

An NLP-based text classification project that classifies medical symptom descriptions into categories using natural language processing techniques and machine learning.

---

## 📌 Project Overview

This project processes and classifies symptom-related text data. It covers the full NLP pipeline — from raw text cleaning all the way to training a classification model and generating predictions.

---

## 🛠️ Techniques Used

### Text Preprocessing
- Contraction fixing
- Lowercasing
- Punctuation removal
- Whitespace normalization
- Special case handling (URLs, emails, hashtags, user handles)
- Tokenization
- Stopword removal
- Lemmatization

### Exploratory Data Analysis (EDA)
- POS (Part-of-Speech) tagging using spaCy
- Unigram, Bigram, and Trigram word clouds
- Frequency distribution analysis

### Text Classification
- TF-IDF Vectorization (top 5000 features)
- Logistic Regression classifier
- Evaluation using Macro Recall score

---

## 📁 Files

| File | Description |
|------|-------------|
| `Codies_AI_Project.ipynb` | Main Jupyter notebook with full code |
| `Final_Formatted_NLP_Project_Report_2.docx` | Full project report |

---

## 📦 Libraries & Dependencies

```
pandas
nltk
spacy
textacy
contractions
scikit-learn
wordcloud
matplotlib
```

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/mehkshabir/Symptom-classification-nlp.git
   ```
2. Install dependencies:
   ```bash
   pip install pandas nltk spacy textacy contractions scikit-learn wordcloud matplotlib
   python -m spacy download en_core_web_sm
   ```
3. Open the notebook in Google Colab or Jupyter and run all cells.

> **Note:** The dataset files (Train, Validation, Test `.xlsx` files) are not included in this repo. Add them to your `/content/` directory if running on Google Colab.

---

## 📊 Output

The model generates predictions on the test set and saves them as `LogReg_test_predictions.csv`.

---

## 📄 License

This project is licensed under the MIT License.
