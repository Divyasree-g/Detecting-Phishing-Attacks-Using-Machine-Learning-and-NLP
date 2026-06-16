# Detecting-Phishing-Attacks-Using-Machine-Learning-and-NLP
This project presents a machine learning–based system designed to detect phishing emails using Natural Language Processing (NLP) techniques and text classification models. The system analyzes email content and accurately classifies it as phishing or legitimate, helping to protect users from cyber threats.

![Python](https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-NLP-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---

## 📌 Project Overview

This project presents a machine learning–based system designed to detect phishing emails using Natural Language Processing (NLP) techniques and text classification models. The system analyzes email content and accurately classifies it as **phishing** or **legitimate**, helping to protect users from cyber threats.

---

## 🎯 Objectives

- Build an automated system to identify phishing emails
- Apply NLP preprocessing techniques for feature extraction
- Train and evaluate multiple ML classification models
- Compare model performance to identify the most effective approach

---

## 🛠️ Tech Stack

| Category | Tools / Libraries |
|---|---|
| Language | Python |
| NLP | NLTK, Scikit-learn |
| ML Models | Naive Bayes, Logistic Regression, Random Forest, SVM |
| Feature Engineering | TF-IDF, N-grams, Tokenization |
| Evaluation | Precision, Recall, F1-Score, Confusion Matrix |
| Environment | Jupyter Notebook / VS Code |

---

## 🔄 Project Workflow

```
Raw Email Data
      ↓
Data Preprocessing
(Tokenization, Stop-word Removal, N-grams)
      ↓
Feature Engineering
(TF-IDF Vectorization)
      ↓
Model Training
(Naive Bayes, Logistic Regression, Random Forest, SVM)
      ↓
Model Evaluation
(Precision, Recall, F1-Score)
      ↓
Results & Analysis
```

---

## ⚙️ Key Steps

### 1. Data Preprocessing
- Cleaned raw email text by removing HTML tags, special characters, and stopwords
- Applied **tokenization** to break text into meaningful units
- Used **n-gram analysis** to capture word sequences and context

### 2. Feature Engineering
- Applied **TF-IDF (Term Frequency–Inverse Document Frequency)** to convert text into numerical features
- Extracted key features that distinguish phishing emails from legitimate ones

### 3. Model Training
Trained and compared the following classification models:
- Naive Bayes
- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)

### 4. Model Evaluation
Evaluated each model using:
- **Precision** – How many predicted phishing emails were actually phishing
- **Recall** – How many actual phishing emails were correctly identified
- **F1-Score** – Harmonic mean of precision and recall

---

## 📊 Results

| Model | Precision | Recall | F1-Score |
|---|---|---|---|
| Naive Bayes | - | - | - |
| Logistic Regression | - | - | - |
| Random Forest | - | - | - |
| SVM | - | - | - |



 📁 Project Structure

📦 phishing-detection-ml-nlp
 ┣ 📂 data/
 ┃ ┗ 📄 emails.csv
 ┣ 📂 notebooks/
 ┃ ┗ 📄 phishing_detection.ipynb
 ┣ 📂 models/
 ┃ ┗ 📄 trained_model.pkl
 ┣ 📂 src/
 ┃ ┣ 📄 preprocessing.py
 ┃ ┣ 📄 feature_engineering.py
 ┃ ┗ 📄 model_training.py
 ┣ 📄 requirements.txt
 ┗ 📄 README.md
```

---
 🚀 How to Run

bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/phishing-detection-ml-nlp.git

# 2. Navigate to the project folder
cd phishing-detection-ml-nlp

# 3. Install required libraries
pip install -r requirements.txt

# 4. Run the notebook
jupyter notebook notebooks/phishing_detection.ipynb
```

📚 Key Learnings

- End-to-end ML pipeline from raw data to model evaluation
- Importance of text preprocessing in NLP tasks
- Comparative analysis of multiple classification algorithms
- Handling class imbalance in security-related datasets

👩‍💻 Author

**Divyasree Guttha**  
M.S. Information Systems — University of Maryland, Baltimore County (UMBC)  
📧 gutthadivyasree2003@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/divyasree-guttha)

---

📄 License

This project is for academic purposes only.
