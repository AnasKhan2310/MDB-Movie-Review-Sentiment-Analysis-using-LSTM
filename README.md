# MDB-Movie-Review-Sentiment-Analysis-using-LSTM
This project performs **Sentiment Analysis** on IMDB movie reviews using **LSTM (Long Short-Term Memory)** networks.  
We compare the performance of two embedding sizes: **32 vs 64** to analyze which provides better accuracy.

---
## 🧠 Model Overview
The project includes:
1. **Text Preprocessing:** Tokenization and padding of sequences  
2. **Model Building:** LSTM models with Embedding layers  
3. **Comparison:** Accuracy comparison between Embedding(32) and Embedding(64)  

---

## 🏗️ Architecture
```python
#Embedding(input_dim=10000, output_dim=32 or 64, input_length=200)
#LSTM(64)
#Dropout(0.5)
#Dense(1, activation='sigmoid')
#⚙️ Technologies Used
#Python

#TensorFlow / Keras

#Pandas, NumPy

#Matplotlib

Scikit-learn
📊 Results
Embedding Size	Validation Accuracy	Test Accuracy
32	~0.86	~0.85
64	~0.88	~0.86
Key Learnings

Text preprocessing is crucial for deep learning NLP tasks

Larger embedding size can improve performance, but increases training time

LSTM networks are effective for sequential sentiment classification
