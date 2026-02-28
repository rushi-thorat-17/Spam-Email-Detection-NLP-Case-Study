# 📧 Spam Email Detection – NLP Case Study

## 📌 Project Overview

This project is an end-to-end Natural Language Processing (NLP) case study to classify emails as Spam or Ham (Not Spam).

The objective is to build a machine learning model that can automatically detect unwanted spam emails using text processing techniques.

---

## 📊 Business Problem

Organizations receive thousands of emails daily.  
Manual filtering is inefficient and error-prone.

Can we automatically classify emails into:
- Spam
- Ham (Not Spam)

---

## 📁 Dataset Information

The dataset contains:
- Email text
- Label (Spam / Ham)

---

## 🛠️ Tools & Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- TF-IDF Vectorizer
- Jupyter Notebook

---

## 🔍 Project Workflow

### 1️⃣ Data Loading
- Loaded dataset using Pandas
- Checked shape, null values, duplicates

### 2️⃣ Data Cleaning
- Lowercasing text
- Removing punctuation
- Removing stopwords
- Tokenization

### 3️⃣ Feature Engineering
- Applied CountVectorizer / TF-IDF
- Converted text into numerical format

### 4️⃣ Model Building
Applied classification models:
- Naive Bayes
- Logistic Regression
- Random Forest

### 5️⃣ Model Evaluation
- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1 Score

---

## 📈 Results

The model achieved high accuracy in classifying spam and ham emails.

Key Insights:
- Spam emails contain promotional and urgent keywords.
- TF-IDF significantly improved model performance.
- Naive Bayes performed very efficiently for text classification.

---

## 📷 Visualizations

Example:

<img width="727" height="554" alt="image" src="https://github.com/user-attachments/assets/ecc3c124-e1f8-46b9-a424-b9228d2f95b7" />


---

## 🚀 How to Run This Project

1. Clone this repository
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open Jupyter Notebook
4. Run `spam_ham_detection.ipynb`

---

## 📌 Future Improvements

- Hyperparameter tuning
- Use Deep Learning (LSTM / BERT)
- Deploy model using Streamlit
- Build email spam API

---

## 👨‍💻 Author

Rushi Thorat  
Data Science Enthusiast  
Pune, Maharashtra  

---

⭐ If you found this project helpful, feel free to give it a star!
