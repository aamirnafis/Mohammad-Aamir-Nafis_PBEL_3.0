<h1 align="center">📰 Fake News Detection using Machine Learning</h1>

<p align="center">
A Machine Learning project that detects whether a news article is <b>Fake</b> or <b>Real</b> using Natural Language Processing (NLP) and classification algorithms.
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![NLP](https://img.shields.io/badge/NLP-TF--IDF-success?style=for-the-badge)

</p>

---

# 📌 About the Project

Fake news spreads rapidly across social media and online platforms, making it difficult to distinguish between genuine and misleading information.

This project aims to build a Machine Learning model capable of automatically classifying news articles as **Fake** or **Real** by applying text preprocessing techniques, TF-IDF feature extraction, and supervised learning algorithms.

The final model achieved an accuracy of **99.70%** using the **Random Forest Classifier**.

---

# 🚀 Features

✔ Data Cleaning & Text Preprocessing

✔ Exploratory Data Analysis (EDA)

✔ TF-IDF Vectorization

✔ Multiple Machine Learning Models

✔ Model Performance Comparison

✔ Fake/Real News Prediction

✔ Trained Model Serialization using Pickle

---

# 📂 Dataset

**Dataset Used**

ISOT Fake News Dataset

Dataset Files

```
Fake.csv
True.csv
```

Each record contains:

- Title
- News Text
- Subject
- Date

Target Labels

| Label | Meaning |
|-------:|---------|
| 0 | Fake News |
| 1 | Real News |

---

# ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- NLTK
- Pickle
- Google Colab

---

# 🤖 Machine Learning Models

The following classification algorithms were implemented and compared:

- Multinomial Naive Bayes
- Logistic Regression
- Random Forest

### 🏆 Best Performing Model

| Model | Accuracy |
|--------|----------|
| **Random Forest** | **99.70%** |

---

# 🔄 Project Workflow

```text
Dataset
    │
    ▼
Data Cleaning
    │
    ▼
Text Preprocessing
    │
    ▼
Exploratory Data Analysis
    │
    ▼
TF-IDF Vectorization
    │
    ▼
Train-Test Split
    │
    ▼
Model Training
    │
    ▼
Model Evaluation
    │
    ▼
Prediction
```

---

# 📁 Project Structure

```
Fake-News-Detection/
│
├── Fake_News_Detection_using_ML.ipynb
├── fake_news_model.pkl
├── tfidf_vectorizer.pkl
├── README.md
```

---

# 🎯 Prediction

The trained model classifies an input news article as:

✅ Real News

❌ Fake News

---

# 📈 Future Improvements

- Develop a Flask-based web application
- Deploy the project on Render
- Support real-time news prediction
- Improve accuracy using Deep Learning (LSTM/BERT)

---

# 👨‍💻 Author

**Mohammad Aamir Nafis**

B.Tech Computer Science & Engineering (Data Science)


---

⭐ If you found this project useful, consider giving it a star.
