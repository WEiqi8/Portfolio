
---

# 🧠 Machine Learning Projects Collection

This repository contains a collection of machine learning projects developed using Python and Jupyter Notebook. Each notebook explores a different domain, using data science and machine learning techniques to solve real-world problems.

## 📚 Table of Contents

1. [Car Price Predictions](#1-car-price-predictions)  
2. [Personality Prediction](#2-personality-prediction)  
3. [Fake News Detection](#3-fake-news-detection)  
4. [Sentiment Analysis](#4-sentiment-analysis)  
5. [Recommendation System](#5-recommendation-system)  
6. [Expense Tracker](#6-expense-tracker)  

---

## 1. 🚗 Car Price Predictions

**File:** `Car price predictions.ipynb`

### 📌 Objective
Predict the price of a car based on features like year, brand, mileage, and fuel type using regression models.

### 🔧 Tools Used
- Pandas, NumPy  
- Seaborn, Matplotlib  
- Scikit-learn (Linear Regression, Random Forest, etc.)

### 🧱 Key Steps
- Data preprocessing and visualization  
- Feature engineering  
- Regression model training and evaluation

## Best Model: XGBoost Regressor
Train R² Score: 0.8503
Test R² Score: 0.5486

- Achieved the best performance among tested models (Linear Regression, Ridge, Lasso, Random Forest, etc).
- Showed strong learning on training data while maintaining moderate generalization on unseen data.
- Used feature engineering and data preprocessing (e.g., encoding, scaling, missing value handling) for improved performance.
- Visualized feature importance to interpret which factors most influence price predictions.

---

## 2. 🧬 Personality Prediction

**File:** `Personality Prediction.ipynb`

### 📌 Objective
Predict a person’s MBTI (Myers–Briggs Type Indicator) personality type based on their writing/text data.

### 🔧 Tools Used
- Natural Language Processing (NLP)  
- TF-IDF, CountVectorizer  
- Logistic Regression, SVM, Naive Bayes

### 🧱 Key Steps
- Text preprocessing and vectorization  
- Multi-class classification modeling  
- Evaluation using accuracy and confusion matrix

---

## 3. 📰 Fake News Detection

**File:** `Fake news detection.ipynb`

### 📌 Objective
Classify whether a news article is fake or real using its title and content.

### 🔧 Tools Used
- NLP tools and techniques  
- TF-IDF for feature extraction  
- Machine learning models like Logistic Regression, Passive Aggressive Classifier

### 🧱 Key Steps
- Cleaning and tokenizing text  
- Feature extraction with TF-IDF  
- Binary classification and evaluation

## Model Used: Decision Tree Classifier
Accuracy Score: 99.54%
- Achieved the highest performance among models tested (e.g., Logistic Regression, Gradient Boosting and Random Forest).
- Applied text preprocessing techniques: lowercasing, punctuation removal, stopwords removal, and stemming.
- Converted text into numerical form using TF-IDF Vectorization.
- Trained and evaluated using stratified train-test split to ensure balanced representation.
- The model demonstrates excellent precision and recall, making it highly reliable for binary classification tasks.

---

## 4. 💬 Sentiment Analysis

**File:** `Sentiment Analysis.ipynb`

### 📌 Objective
Analyze the sentiment of text data (e.g., tweets, reviews) and classify it as positive, negative, or neutral.

### 🔧 Tools Used
- Pandas, Scikit-learn, NLTK  
- Logistic Regression / Naive Bayes  
- TF-IDF Vectorization

### 🧱 Key Steps
- Text cleaning and preprocessing  
- Feature extraction with TF-IDF  
- Model training and sentiment prediction

### 🧪 Example
```python
predict_sentiment("I love this app! It's amazing!")
# Output: Positive
```

---

## 5. 🔍 Recommendation System

**File:** `Recommendations.ipynb`

### 📌 Objective
Recommend items such as movies, books, or products based on user preferences using both content-based and collaborative filtering techniques.

### 🔧 Tools Used
- Pandas, Scikit-learn  
- Cosine similarity  
- Surprise (optional for collaborative filtering)

### 🧱 Key Steps
- Data analysis and preprocessing  
- Implementing content-based filtering  
- Implementing collaborative filtering

### 🧪 Example
```python
recommend("Avengers")
# Output: List of similar items
```

---

## 6. 💸 Expense Tracker

**File:** `Expense Tracker.ipynb`

### 📌 Objective
Track and visualize personal expenses by category and date.

### 🔧 Tools Used
- Pandas  
- Matplotlib, Seaborn

### 🧱 Key Steps
- Expense input and categorization  
- Monthly and category-wise summaries  
- Visualizations using charts

### 🧪 Example
```python
# Input
"Date: 2025-04-01, Category: Food, Amount: 10"

# Output
Pie chart: Food = 60%, Transport = 30%, Others = 10%
```

---

## ✅ Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Open any notebook using Jupyter:
   ```bash
   jupyter notebook
   ```

---
