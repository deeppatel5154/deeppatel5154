# 🐦 Twitter Sentiment Classification

> NLP-based model for tweet sentiment analysis and sales outcome prediction

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-NLTK-green?style=flat)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

---

## 📌 Overview

This project develops an **NLP-based statistical model** that classifies tweet sentiment into positive, negative, and neutral categories — enabling better sales outcome prediction for business decision-making.

- ✅ Achieved **85%+ accuracy** in tweet sentiment categorization
- ✅ Improved sales outcome prediction by **20%**

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core development |
| NLTK / TextBlob | Natural language processing |
| Scikit-learn | Classification models |
| Pandas / NumPy | Data manipulation |
| Matplotlib | Visualization |
| Jupyter Notebook | Analysis & reporting |

---

## 📂 Project Structure

```
twitter-sentiment-classification/
│
├── data/
│   ├── raw/                  # Raw tweet dataset
│   └── processed/            # Cleaned & tokenized data
│
├── notebooks/
│   ├── 01_data_preprocessing.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_model_training.ipynb
│   └── 04_evaluation.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── feature_engineering.py
│   └── classifier.py
│
├── results/
│   └── confusion_matrix.png
│
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/deeppatel5154/twitter-sentiment-classification.git
cd twitter-sentiment-classification

# Install dependencies
pip install -r requirements.txt

# Run notebooks
jupyter notebook notebooks/
```

---

## 📊 Model Performance

| Model | Accuracy | Precision | Recall |
|---|---|---|---|
| Naive Bayes | 79% | 0.77 | 0.80 |
| SVM | 83% | 0.82 | 0.83 |
| Random Forest | 85% | 0.84 | 0.86 |

---

## 📬 Contact

**Deep Patel** — [deeppatel5154@gmail.com](mailto:deeppatel5154@gmail.com) | [LinkedIn](https://www.linkedin.com/in/deeppatel5154)
