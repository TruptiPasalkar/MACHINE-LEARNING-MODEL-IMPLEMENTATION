# 📧 Spam Email Classification using Machine Learning

## 📌 Project Overview

This project demonstrates the implementation of a machine learning model to classify messages as **Spam** or **Ham (Not Spam)**.

The model is built using Scikit-learn and applies text feature extraction and a Naive Bayes classifier to predict whether a message is spam.

---

## 🚀 Technologies Used

- Python
- Pandas (Data Handling)
- Scikit-learn (Machine Learning)
- CountVectorizer (Text Feature Extraction)
- Multinomial Naive Bayes (Classification Algorithm)

---

## 📂 Project Structure

Task4/
│── spam_classifier.py (or SpamClassifier.ipynb)  
│── README.md  

---

## 🔍 Features

- Text preprocessing using CountVectorizer
- Train-test data splitting
- Machine learning model training
- Model evaluation using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report
- Real-time user input prediction

---

## 🛠 How It Works

1. A dataset of spam and ham messages is created.
2. Text data is converted into numerical features using CountVectorizer.
3. The dataset is split into training and testing data.
4. A Multinomial Naive Bayes model is trained on the training data.
5. The model is evaluated using accuracy and confusion matrix.
6. Users can enter a custom message to check whether it is spam or not.

