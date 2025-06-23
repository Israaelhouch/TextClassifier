# 🗂️ News Classification with Logistic Regression

A text classification project that categorizes news articles into fields like sports, politics, and tech using logistic regression.

---

## 📊 Dataset

This project uses the [News Category Dataset](https://www.kaggle.com/datasets/rmisra/news-category-dataset) from Kaggle.

- 📁 Contains over **200,000** news headlines from HuffPost, published between 2012 and 2018.
- 🏷️ Each headline is labeled with one of several categories (e.g., POLITICS, ENTERTAINMENT, TECH, SPORTS, etc.)
- 📄 Format: JSON with fields like `headline`, `category`, `authors`, and `date`.

The dataset was used to train and evaluate a multi-class text classification model.

---

## ✨ Features

- 📑 Preprocessing of raw text data (cleaning, tokenization, vectorization)
- 🔍 Multi-class classification with Logistic Regression
- 📊 Evaluation using accuracy, precision, recall, and confusion matrix
- 🧪 Supports `.ipynb` notebook for interactive experimentation
- ✅ Easily customizable for other text datasets or classification tasks

---

## 🛠️ Tech Stack

- Python  
- Scikit-learn  
- Pandas, NumPy  
- Jupyter Notebook  

---

## 📁 Use Case

Automatically classify news content into predefined categories to streamline organization, filtering, and content discovery in news platforms or educational datasets.

---

## 🚀 How to Run

1. Clone the repo  
2. Set up a virtual environment  
3. Install dependencies:  
   ```bash
   pip install -r requirements.txt
