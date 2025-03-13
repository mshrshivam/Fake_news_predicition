# 📰 Fake News Prediction

## 📌 Introduction
This repository contains a **Flask-based web application** that utilizes **Machine Learning** techniques to classify news articles as **Fake** or **Real**. It leverages **TF-IDF Vectorization** and **Logistic Regression** for text classification, ensuring reliable and efficient results.

---

## ⚙️ Features
- Detects fake news articles using **Logistic Regression**.
- Implements **TF-IDF Vectorization** for text preprocessing.
- Handles **class imbalance** with **SMOTE**.
- Provides a **Flask-based web interface** for easy interaction.
- Simple and lightweight UI using **HTML, CSS**.

---

## 🚀 Getting Started
### Prerequisites
Ensure you have the following installed:
- **Python 3.x**
- **Flask**
- **Scikit-learn**
- **NLTK**
- **Pandas**
- **Numpy**
- **Imbalanced-learn**

Install dependencies using:
```sh
pip install -r requirements.txt
```

---

## 📂 Project Structure
The repository consists of the following key files:

### **Application Files**
- `app.py` → Main **Flask application** for serving the web interface.
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

## 🏃‍♂️ Running the Application
### Steps to run the project locally:

1️⃣ **Clone the Repository**  
```sh
git clone https://github.com/mshrshivam/Fake_news_prediction.git
cd Fake_news_prediction
```

2️⃣ **Install Dependencies**  
```sh
pip install -r requirements.txt
```

3️⃣ **Run the Flask App**  
```sh
python app.py
```

4️⃣ **Open in Browser**  
Navigate to `http://127.0.0.1:5000/` in your web browser to access the application.

---

## 📜 Usage
- Enter a news article in the text box.
- Click on the **Predict** button.
- The model will classify the news as **Fake** or **Real** and display the result.

---

## 🔍 Model Details
The model utilizes **TF-IDF Vectorization** for text transformation and **Logistic Regression** for classification.
- **TF-IDF (Term Frequency-Inverse Document Frequency)** helps convert text into numerical features.
- **Logistic Regression** is a simple yet effective classification algorithm.
- **SMOTE (Synthetic Minority Over-sampling Technique)** is used to handle class imbalance in the dataset.

---

## 📢 Contributing
Contributions are welcome! Feel free to **fork**, create a **pull request**, or open an **issue** if you have suggestions.

---

## 📜 License
This project is licensed under the **MIT License**.

---

## 🤝 Connect
- **LinkedIn**: [Shivam Kumar Mishra](https://www.linkedin.com/in/shivam-kumar-mishra-586b02291/)
- **GitHub**: [mshrshivam](https://github.com/mshrshivam)
- **Email**: [shivam200419mishra@gmail.com](mailto:shivam200419mishra@gmail.com)

