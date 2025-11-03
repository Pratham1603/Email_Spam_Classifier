# 📧 Email Spam Classifier

## 🧠 Overview
This project is an **Email Spam Classifier** that uses machine learning techniques to detect whether a given email message is *Spam* or *Not Spam*.  
The model learns from historical email data and predicts the category based on the content of new messages.

---

## ✨ Features
- Text preprocessing and cleaning  
- Tokenization and stopword removal  
- Feature extraction using **TF-IDF Vectorization**  
- Model training using **Naive Bayes Classifier**  
- Evaluation using accuracy and confusion matrix  
- Real-time prediction for custom inputs  

---

## 🛠️ Tech Stack
- **Python 3.x**
- **scikit-learn**
- **pandas**
- **numpy**
- **nltk**
- (Optional) **Streamlit / Flask** for UI

---

## 📁 Project Structure
Email_Spam_Classifier/
│
├── data/
│ ├── spam.csv
│
├── model/
│ └── spam_model.pkl
│
├── notebooks/
│ └── spam_classifier.ipynb
│
├── src/
│ ├── preprocess.py
│ ├── train_model.py
│ └── predict.py
│
├── app.py
├── requirements.txt
└── README.md
