# restaurant-analytics-sentiment-analysis

# 🍽️ Restaurant Analytics & Sentiment Analysis using Machine Learning and NLP

## 📌 Project Overview

This project focuses on analyzing restaurant information and customer reviews using **Exploratory Data Analysis (EDA), Natural Language Processing (NLP), Machine Learning, and Unsupervised Learning (Clustering)**.

The project extracts meaningful business insights from restaurant data, predicts customer sentiment from review text, and segments restaurants into similar groups using K-Means clustering.

---

# 🎯 Objectives

- Perform data cleaning and preprocessing.
- Analyze restaurant and review datasets using EDA.
- Apply NLP techniques to preprocess customer reviews.
- Build sentiment classification models.
- Compare multiple machine learning models.
- Segment restaurants using K-Means clustering.
- Generate business insights for restaurant owners.

---

# 📂 Dataset

The project uses two datasets:

### Restaurant Dataset

Contains restaurant information such as:

- Restaurant Name
- Cost
- Cuisines
- Collections
- Timings
- Rating

### Customer Reviews Dataset

Contains:

- Review
- Rating
- Pictures
- Reviewer
- Restaurant

---

# 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK
- TF-IDF Vectorizer
- K-Means Clustering
- Google Colab

---

# 📊 Project Workflow

```
Data Collection
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Feature Engineering
        │
        ▼
NLP Preprocessing
        │
        ▼
TF-IDF Vectorization
        │
        ▼
Sentiment Classification
        │
        ├──────────────┐
        ▼              ▼
Logistic Regression   Multinomial Naive Bayes
        │
        ▼
Random Forest Classifier
        │
        ▼
Model Comparison
        │
        ▼
Best Model Selection
        │
        ▼
Restaurant Segmentation
(K-Means Clustering)
```

---

# 🧹 Data Preprocessing

- Missing Value Treatment
- Duplicate Removal
- Data Type Conversion
- Outlier Detection & Treatment
- Feature Engineering
- Feature Selection
- Feature Scaling
- Text Cleaning

---

# 📝 NLP Pipeline

- Lowercase Conversion
- Remove Punctuation
- Remove Numbers
- Remove URLs
- Remove Stopwords
- Tokenization
- Lemmatization
- POS Tagging
- TF-IDF Vectorization

---

# 🤖 Machine Learning Models

### Model 1

- Logistic Regression

### Model 2

- Multinomial Naive Bayes

### Model 3

- Random Forest Classifier

---

# 📈 Model Performance

| Model | Accuracy | Precision | Recall | F1 Score |
|--------|----------|-----------|--------|----------|
| Logistic Regression | **82.87%** | 80.40% | **82.87%** | **80.29%** |
| Multinomial Naive Bayes | 79.56% | **82.71%** | 79.56% | 74.17% |
| Random Forest Classifier | 81.27% | 77.05% | 81.27% | 76.65% |

🏆 **Best Model:** Logistic Regression

---

# 📊 Clustering

Restaurant segmentation was performed using **K-Means Clustering** to group restaurants based on their characteristics.

Benefits:

- Customer Segmentation
- Pricing Analysis
- Restaurant Grouping
- Business Strategy
- Market Analysis

---

# 📌 Key Insights

- Customer reviews provide valuable business intelligence.
- Logistic Regression achieved the best overall sentiment classification performance.
- TF-IDF significantly improved text representation.
- Restaurant segmentation helps identify similar restaurant categories.
- NLP can automatically classify customer reviews into Positive, Neutral, and Negative sentiments.

---

# 🚀 Future Scope

- Deep Learning (LSTM / BERT)
- Restaurant Recommendation System
- Real-Time Review Analysis
- Streamlit Web Application
- Deployment using Flask or FastAPI

---

# 📁 Project Structure

```
Restaurant-Analytics-Sentiment-Analysis/
│
├── Dataset/
│   ├── restaurant_data.csv
│   └── restaurant_reviews.csv
│
├── Notebook/
│   └── Restaurant_Analytics_and_Sentiment_Analysis.ipynb
│
├── Images/
│
├── README.md
│
└── requirements.txt
```

---

# 👨‍💻 Author

**Piyush Madhukar**

PG-Diploma in Big Data Analytics (CDAC Noida)

GitHub: https://github.com/byte-piyush16

LinkedIn: https://www.linkedin.com/in/piyushmadhukar45/

---

## ⭐ If you found this project useful, don't forget to Star this repository.
