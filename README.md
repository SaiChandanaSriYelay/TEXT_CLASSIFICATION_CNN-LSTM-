#  Fake News Detection using NLP and CNN-LSTM

##  Project Overview
This project implements a Fake News Detection system using Natural Language Processing (NLP).  
The goal is to classify news articles as **Fake** or **Real** by analyzing their textual content.  
Both classical machine learning models and a deep learning CNN-LSTM model are implemented and compared.

---

##  Objectives
- Clean and preprocess news article text  
- Extract meaningful features using TF-IDF  
- Train and evaluate classical machine learning models  
- Build a CNN-LSTM deep learning model  
- Compare the performance of all models  

---

##  Dataset
- **Source:** Kaggle – Fake and Real News Dataset  
- **Files Used:**
  - `Fake.csv` – Fake news articles  
  - `True.csv` – Real news articles  

Each article contains textual content used for classification.

---

##  Technologies Used
- **Programming Language:** Python  
- **Libraries:**  
  - NumPy  
  - Pandas  
  - NLTK  
  - Scikit-learn  
  - TensorFlow / Keras  
  - Matplotlib  
  - Seaborn  

---

## Methodology

###  Text Preprocessing
- Convert text to lowercase  
- Remove punctuation and special characters  
- Tokenization  
- Stopword removal  

###  Feature Extraction
- TF-IDF vectorization for classical machine learning models  
- Tokenization and padding for CNN-LSTM model  

###  Models Implemented
#### Classical Machine Learning Models
- Naive Bayes  
- Logistic Regression  
- Support Vector Machine (SVM)  

#### Deep Learning Model
- CNN-LSTM (Convolutional Neural Network + Long Short-Term Memory)

---

##  Model Comparison

| Model | Accuracy |
|------|---------|
| Naive Bayes | ~95% |
| Logistic Regression | ~98% |
| SVM | ~99% |
| CNN-LSTM | **~99.7%** |

---

##  Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

---

## How to Run the Project

1. Install required libraries:
```bash
pip install numpy pandas nltk scikit-learn tensorflow matplotlib seaborn
