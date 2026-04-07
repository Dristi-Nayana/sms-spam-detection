# SMS Spam Detection using NLP and Machine Learning

This project presents a machine learning-based system for detecting spam messages in SMS data using Natural Language Processing (NLP) techniques and real-time web deployment.

---

## 🚀 Overview

* Built an NLP-based SMS spam classification system
* Performed text preprocessing (tokenization, stopword removal, stemming)
* Evaluated multiple ML models and selected the best-performing classifier
* Achieved **100% precision** on the dataset
* Deployed the model using **Streamlit** for real-time prediction

---

## 🧠 Methodology

### 🔹 Data Preprocessing

* Converted text to lowercase
* Tokenization using NLTK
* Removed stopwords and punctuation
* Applied stemming using Porter Stemmer

### 🔹 Feature Engineering

* Text vectorization using TF-IDF

### 🔹 Model Training

* Evaluated multiple models:

  * Naive Bayes
  * Random Forest
  * KNN
  * SVM
  * Logistic Regression

* Selected best model based on precision

---

## 📂 Dataset

📊 SMS Spam Collection Dataset:
https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

* ~5,500 labeled SMS messages
* Classes: Spam / Ham

---

## 💻 Code Structure

* `app.py` → Streamlit web app for prediction
* `model.pkl` → Trained ML model
* `vectorizer.pkl` → TF-IDF vectorizer
* `sms-spam.csv` → Dataset

---

## ▶️ How to Run

### 1. Install dependencies

```bash
pip install -r requirements.txt
```

### 2. Run the app

```bash
streamlit run app.py
```

### 3. Open browser

Go to: http://localhost:8501

---

## 🌐 Web Application

* Input any SMS message
* Model predicts:

  * **Spam**
  * **Not Spam**

The system performs real-time classification using trained ML model.

---

## ⚙️ Key Features

* Real-time spam detection
* End-to-end NLP pipeline
* High precision classification
* Interactive web interface

---

## 🛠 Tech Stack

* Python
* Scikit-learn
* NLTK
* Pandas, NumPy
* Streamlit

---

## 📊 Results

* Achieved **100% precision** on test data
* Successfully classified spam and ham messages
* Demonstrated effectiveness of NLP-based filtering

---

## 📄 Project Report

📥 [View Full Report](Microsoft_Tecksaksham_Internship_Project_Paper.pdf)

---

## 🔗 Future Work

* Use deep learning models (LSTM, BERT)
* Add multilingual support
* Deploy as mobile application
* Improve robustness against evolving spam patterns

---

## 💡 Key Highlights

* NLP + ML + Web Deployment
* Real-world dataset
* Production-style project
* User-friendly interface

---
