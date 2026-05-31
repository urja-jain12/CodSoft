# CodSoft Machine Learning Internship Tasks

This repository contains three machine learning projects developed using Python, Scikit-learn, Pandas, NumPy, and Jupyter Notebook. These projects demonstrate the application of machine learning techniques to solve real-world problems involving Natural Language Processing (NLP), Fraud Detection, and Customer Analytics.

---

## Task 1: Movie Genre Classification

### Overview

The objective of this project is to predict the genre of a movie based on its plot summary. Natural Language Processing (NLP) techniques are used to convert textual movie descriptions into numerical features, which are then used to train a machine learning model for genre prediction.

### Dataset

IMDb Genre Classification Dataset

### Techniques Used

* Text Preprocessing
* TF-IDF Vectorization
* Linear Support Vector Machine (Linear SVM)
* Natural Language Processing (NLP)

### Workflow

1. Load movie genre dataset.
2. Clean and preprocess movie descriptions.
3. Convert text into TF-IDF feature vectors.
4. Train a Linear SVM classifier.
5. Evaluate model performance on test data.
6. Predict genres for unseen movie descriptions.

### Result

The model achieved approximately **58% accuracy** in predicting movie genres using TF-IDF and Linear SVM.

---

## Task 2: Credit Card Fraud Detection

### Overview

The goal of this project is to identify fraudulent financial transactions using machine learning techniques. The model analyzes transaction details and classifies each transaction as either legitimate or fraudulent.

### Dataset

Credit Card Fraud Detection Dataset

### Techniques Used

* Data Cleaning and Preprocessing
* Label Encoding
* Feature Engineering
* Random Forest Classifier
* Performance Evaluation Metrics

### Workflow

1. Load training and testing datasets.
2. Remove irrelevant columns.
3. Encode categorical features.
4. Train a Random Forest classifier.
5. Evaluate model performance using classification metrics.
6. Predict fraudulent transactions.

### Result

The Random Forest model successfully identified fraudulent transactions and achieved high classification performance on the test dataset.

---

## Task 3: Customer Churn Prediction

### Overview

The objective of this project is to predict whether a customer is likely to leave a bank or continue using its services. The model uses customer demographic and account-related information to make predictions.

### Dataset

Customer Churn Prediction Dataset

### Techniques Used

* Data Preprocessing
* Label Encoding
* Feature Scaling
* Random Forest Classifier
* Classification Metrics

### Workflow

1. Load customer dataset.
2. Remove unnecessary columns.
3. Encode categorical features.
4. Scale numerical features.
5. Train a Random Forest classifier.
6. Predict customer churn.
7. Evaluate model performance.

### Result

The model achieved an accuracy of approximately **85%**, effectively identifying customers who are likely to leave the bank.

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## Repository Structure

```text
CodSoft/
│
├── Movie_Genre_Classification/
│   ├── movie_genre_classification.ipynb
│   └── dataset/
│
├── Credit_Card_Fraud_Detection/
│   ├── credit_card_fraud_detection.ipynb
│   └── dataset/
│
├── Customer_Churn_Prediction/
│   ├── customer_churn_prediction.ipynb
│   └── dataset/
│
└── README.md
```

---

## Skills Demonstrated

* Machine Learning
* Natural Language Processing
* Classification Models
* Feature Engineering
* Data Preprocessing
* Model Evaluation
* Predictive Analytics

---

## Author

**Urja Jain**
Artificial Intelligence & Machine Learning (AIML) Student
