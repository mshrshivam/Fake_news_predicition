# 📰 Fake News Prediction

## Introduction
This repository contains a **Flask-based web application** that utilizes **Machine Learning** techniques to classify news articles as **Fake** or **Real**. It leverages **TF-IDF Vectorization** and **Logistic Regression** for text classification.  

---

## Getting Started
To run this repository, ensure that you have the following environment and dependencies installed:

- **Python 3.x**
- **Flask**
- **Scikit-learn**
- **NLTK**
- **Pandas**
- **Numpy**
- **Imbalanced-learn**

---

## File Illustration
The repository consists of the following key files:

### **Application Files**
- `app.py` → The main **Flask application** for serving the web interface.
- `requirements.txt` → List of dependencies required to run the application.

### **Dataset Files**
- `data/Fake.csv` → Contains fake news articles.
- `data/True.csv` → Contains real news articles.

### **Preprocessing & Model**
- `preprocessing.py` → Text preprocessing using **NLTK** (stopword removal, stemming, TF-IDF transformation).
- `model.py` → Implements **Logistic Regression** for classification.

### **Templates (Frontend)**
- `templates/index.html` → Web interface for user input.
- `templates/result.html` → Displays the classification result.

### **Static Files**
- `static/style.css` → Stylesheet for UI design.

---

## Run
To run the Fake News Prediction application, follow these steps:

1️⃣ **Clone the Repository**  
```sh
git clone https://github.com/mshrshivam/Fake_news_predicition.git
cd Fake_news_predicition





