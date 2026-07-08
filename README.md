
# 🛡️ Phishing Email Text Classifier

An end-to-end Machine Learning project that detects phishing emails using Natural Language Processing (NLP).

The project preprocesses email text, extracts TF-IDF features, trains multiple machine learning models, and predicts whether an email is phishing or legitimate.

---

## 🚀 Features

- Email text preprocessing
- URL removal
- HTML tag removal
- Email address removal
- Lowercase conversion
- TF-IDF Vectorization
- Machine Learning Classification
- Performance Evaluation
- Save & Load trained model

---

## 📊 Dataset

The dataset contains labeled email messages.

Classes:

- Legitimate Email (Ham)
- Phishing Email (Spam)

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Joblib
- Regex
- TF-IDF
- Google Colab

---

## Machine Learning Pipeline

Email Text
↓

Text Cleaning

↓

TF-IDF Vectorizer

↓

Machine Learning Model

↓

Prediction

---

## Models Used

- Logistic Regression
- Multinomial Naive Bayes
- Random Forest
- Linear SVM
- Stacking Classifier

---

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

---

## Repository Structure

```
Phishing-Email-Text-Classifier
│
├── README.md
├── requirements.txt
├── app.py
├── final_phishingdetection.ipynb
├── phishing_model.pkl
├── vectorizer.pkl
├── images
└── LICENSE
```

---

## Installation

```bash
git clone https://github.com/Yehmeg/Phishing-Email-Text-Classifier.git
```

```bash
cd Phishing-Email-Text-Classifier
```

```bash
pip install -r requirements.txt
```

---

## Run

```bash
python app.py
```

or open

```
final_phishingdetection.ipynb
```

---

## Future Improvements

- Deep Learning (LSTM)
- BERT Classifier
- Explainable AI (SHAP)
- Streamlit Deployment
- Real-time Email Scanner

---

## Author

**Gomti Kumari**

B.Tech CSE (AI)

IGDTUW

Machine Learning | Data Science | AI

GitHub:
https://github.com/Yehmeg

LinkedIn:
https://www.linkedin.com/in/gomti-kumari-05bab4214/
