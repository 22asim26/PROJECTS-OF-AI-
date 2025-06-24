# 🎯 Project Title: Text Emotion Detection using NLP

## 🧠 Overview
This project aims to detect emotions (such as joy, anger, sadness, etc.) from short English texts using Natural Language Processing (NLP) and Machine Learning techniques. It is useful for analyzing customer reviews, tweets, or chat messages.

---

## 📂 Dataset
- **Name**: Emotion Dataset (manually labeled)
- **Size**: ~3,000 text samples
- **Features**: `Text`, `Emotion`
- Source: [Kaggle Dataset](https://www.kaggle.com/datasets/praveengovi/emotions-dataset-for-nlp) (or mention your own if local)

---

## 🤖 Model Used
- Text preprocessing: Lowercasing, tokenization, stopword removal
- Feature extraction: **TF-IDF Vectorization**
- Machine Learning Models tried:
  - Logistic Regression ✅ (Best Accuracy: **82.5%**)
  - Random Forest
  - Naive Bayes

---

## 📈 Results
| Model | Accuracy |
|-------|----------|
| Logistic Regression | **82.5%** |
| Naive Bayes | 78.2% |
| Random Forest | 80.1% |

> Final model saved as `emotion_model.pkl`

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/text-emotion-detector.git
   cd text-emotion-detector


pip install -r requirements.txt

jupyter notebook Text_Emotion_Detection.ipynb
