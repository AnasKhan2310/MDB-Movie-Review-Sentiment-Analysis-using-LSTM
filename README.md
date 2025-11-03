# 🎬 IMDB Movie Review Sentiment Analysis using LSTM

This project performs Sentiment Analysis on IMDB movie reviews using a Long-Short-Term Memory (LSTM) neural network.  
We compare two different **embedding sizes (32 vs 64)** to see which provides better accuracy for text classification.

---

## 📚 Project Overview

This project aims to build a deep learning model to classify movie reviews as **Positive 😊** or **Negative 😞** based on their textual content.

The dataset used is the **IMDB 50K Movie Reviews Dataset** from Kaggle.  
Each review is labeled with a sentiment (positive/negative), making it ideal for binary sentiment classification tasks.

---

## 🧠 Objectives

- Load and preprocess text data (tokenization, padding)  
- Build an LSTM model for sentiment classification  
- Experiment with **different embedding sizes (32 vs 64)**  
- Compare validation and test accuracy between the two models  

---

**Columns:**
- `review` → Movie review text  
- `sentiment` → Target label (`positive` / `negative`)



