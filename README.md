###🧠 Software Requirement Classification

This project classifies software requirement statements into different quality attributes (like Performance, Usability, Security, etc.) using Machine Learning.

##🎯 Objective

To automatically categorize software requirement text using ML models trained on labeled datasets such as the PURE Dataset.

##🧰 Technologies Used

Python 3.x

Pandas, NumPy

NLTK – for text preprocessing

Scikit-learn – for TF-IDF and ML models

Matplotlib / Seaborn – for visualization

##⚙️ Steps to Run

Clone this repository

git clone https://github.com/<your-username>/software-requirement-classifier.git
cd software-requirement-classifier


Install dependencies

pip install -r requirements.txt


Run the model

python model_training.py


Test with new input

test_text = ["The system must be easy to navigate."]
test_tfidf = vectorizer.transform(test_text)
prediction = models["Random Forest"].predict(test_tfidf)
print("Predicted Category:", prediction[0])

##📊 Output Example
Accuracy: 0.75
Predicted Category: Usability
