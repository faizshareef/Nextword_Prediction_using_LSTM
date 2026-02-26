# 🧠 Next Word Prediction using LSTM

## 📌 Project Overview
This project implements a **Next Word Prediction model** using Deep Learning techniques.  
The model is trained on TMDB movie titles to learn sequential text patterns and predict the most probable next word given an input phrase.

It demonstrates the practical application of:
- Natural Language Processing (NLP)
- Sequence Modeling
- Recurrent Neural Networks (LSTM)
- Text Generation

---

## 🚀 Features
- Text preprocessing and tokenization using Keras Tokenizer
- Sliding window sequence generation
- Sequence padding for uniform input length
- Stacked LSTM architecture
- Softmax-based next word prediction
- Model saving and inference support

---

## 🛠 Tech Stack
- Python
- NumPy
- Pandas
- TensorFlow
- Keras

---

## 🏗 Model Architecture
- **Embedding Layer**
- **LSTM Layer (100 units, return_sequences=True)**
- **LSTM Layer (100 units)**
- **Dense Layer (ReLU activation)**
- **Output Layer (Softmax activation)**

The stacked LSTM layers help capture sequential dependencies and contextual relationships between words.

---

## 📊 Dataset
- TMDB 5000 Movie Titles Dataset
- Used the `original_title` column for training

---
