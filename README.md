# MindState Detector
# 🧠 Emotion Insight Mental Health Classifier

**Emotion Insight** is a mental health text classifier that detects emotions from what you write such as **depression, anxiety, stress, bipolar disorder, personality disorder, suicidal thoughts**, or **neutral** state
and gives supportive advice based on your detected emotion.

## 💡 What It Does

-  Takes a sentence or message you type
-  Uses a BERT-based model (`all-MiniLM-L6-v2`) to understand the meaning
-  Predicts the emotional state (with ~90% accuracy )
-  Offers a piece of advice suited to that emotional state

##  Built using:

- **SentenceTransformer** (all-MiniLM-L6-v2) for BERT-based text embeddings.

- **Logistic Regression** for emotion classification.

- **PCA (Principal Component Analysis)** to reduce noise and speed up training .

- **kaggle data set [Sentiment Analysis for Mental Health](https://www.kaggle.com/datasets/suchintikasarkar/sentiment-analysis-for-mental-health/data)**


## Please take a look at my humble project (link is below)
[MindState Detector](https://colab.research.google.com/drive/1VpeDLYQq2uRs13gFtstvvoAq5ZDQtQmZ?usp=sharing)
