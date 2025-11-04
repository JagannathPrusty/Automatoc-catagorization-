# 🧠 Software Requirement Classification using Machine Learning

This project focuses on classifying software requirement statements into specific quality attributes such as **Performance**, **Usability**, **Reliability**, **Security**, etc., using **Natural Language Processing (NLP)** and **Machine Learning** techniques.

---

## 🎯 Objective

The main goal of this project is to build a classification model that can automatically analyze and categorize software requirements, helping teams improve requirement management and traceability in software engineering.

---

## 🧰 Technologies Used

- **Programming Language:** Python 3.x  
- **Libraries & Frameworks:**
  - Pandas  
  - NumPy  
  - NLTK  
  - Scikit-learn  
  - Matplotlib / Seaborn  

---

## 🧠 Methodology

1. **Data Collection** – Software requirement dataset (e.g., PURE Dataset).  
2. **Text Preprocessing** – Cleaning, tokenization, stopword removal, and vectorization using **TF-IDF**.  
3. **Model Training** – Applying ML algorithms such as:
   - Random Forest  
   - Logistic Regression  
   - Support Vector Machine (SVM)  
4. **Model Evaluation** – Using **Confusion Matrix** and **Accuracy Score** for performance analysis.  
5. **Visualization** – Displaying accuracy and confusion matrix for each classifier.  
6. **Testing** – Predicting category for new input requirement statements.  

---

## ⚙️ System Requirements

- **Python:** 3.8 or above  
- **OS:** Windows / macOS / Linux  
- **IDE:** VS Code / Jupyter Notebook / PyCharm  
- **Dependencies:** Listed in `requirements.txt`

---

## 🚀 Steps to Execute

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/software-requirement-classification.git
   cd software-requirement-classification
