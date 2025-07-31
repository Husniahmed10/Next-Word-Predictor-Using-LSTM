# ✨ Next-Word Prediction with LSTM — Streamlit App

Predict the **next word** in a sentence using a characterful dataset: Shakespeare’s *Hamlet*. This repo includes a trained **TensorFlow LSTM** model and a sleek **Streamlit** UI for instant, on-device inference.

<p align="left">
  <a href="#"><img alt="Python" src="https://img.shields.io/badge/Python-3.10+-3776AB.svg?logo=python&logoColor=white"></a>
  <a href="#"><img alt="TensorFlow" src="https://img.shields.io/badge/TensorFlow-2.x-FF6F00.svg?logo=tensorflow&logoColor=white"></a>
  <a href="#"><img alt="Streamlit" src="https://img.shields.io/badge/Streamlit-1.x-FF4B4B.svg?logo=streamlit&logoColor=white"></a>
</p>

---

## 🌟 Highlights

- 📚 **Corpus:** NLTK Gutenberg — *shakespeare-hamlet.txt*  
- 🧠 **Model:** Embedding → LSTM(150) → Dropout(0.2) → LSTM(100) → Dense(softmax)  
- ⚙️ **Inference:** Real-time predictions in a minimal Streamlit UI  
- 💾 **Artifacts:** `next_word_lstm.h5` (model) & `tokenizer.pickle` (vocab)  
- 🧪 **Preprocessing:** Tokenization, n-gram sequence building, sequence padding

---
