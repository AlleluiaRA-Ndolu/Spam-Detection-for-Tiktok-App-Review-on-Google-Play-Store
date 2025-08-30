# Spam-Detection-for-Tiktok-App-Review-on-Google-Play-Store
_IEEE IAICT Publication (2025)_  

## 📖 Publication  
- **IEEE IAICT 2025** – *Two Stage Framework of Spam Detection for TikTok Reviews on Google Play Store*  
- 📄 [Read on IEEE Xplore](https://ieeexplore.ieee.org/document/11101496)  

---

## 📌 Project Overview  
This project presents a **two-stage spam detection framework** for reviews of the TikTok application on the Google Play Store.  
The research was published in **IEEE IAICT 2025**, co-authored as part of an academic collaboration.  

The framework works in two steps:  
1. **Stage 1:** Classify reviews into **Spam** vs **Non-Spam**.  
2. **Stage 2:** Further classify spam reviews into **Sensitive Spam** vs **Insensitive Spam**.  

---

## ⚙️ Tech Stack  
- Python  
- Scikit-learn  
- TensorFlow / Keras  
- Gensim  
- Pandas & NumPy  
- Matplotlib & Seaborn  

---

## 🗂️ Dataset  
- Reviews collected from **Google Play Store (TikTok app)**.  
- Preprocessing steps included:  
  - Text cleansing  
  - Tokenization  
  - Stopword removal  
  - Vectorization using **TF-IDF** and **Word2Vec**  

---

## 🔬 Methodology  
1. **Data Preprocessing** → Cleansing, tokenization, stopword removal, feature extraction.  
2. **Stage 1 Classification** → Trained ML/DL models to classify **Spam vs Non-Spam**.  
3. **Stage 2 Classification** → For detected spam, trained additional models to classify **Sensitive vs Insensitive Spam**.  
4. **Models Implemented:**  
   - Machine Learning: Random Forest, SVM, Logistic Regression  
   - Deep Learning: CNN, LSTM, MLP  

---

## 📊 Results  
- The **MLP (Multi-Layer Perceptron)** with **TF-IDF features** achieved the highest performance.  
- Final accuracy: **96%**.  
- Results demonstrate the effectiveness of combining traditional ML with deep learning for spam detection.  
