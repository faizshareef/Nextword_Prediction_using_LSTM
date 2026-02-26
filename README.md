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


## Output Screenshots

<img width="755" height="598" alt="model_accuracy" src="https://github.com/user-attachments/assets/d25ed65d-dc35-45fb-ab44-447494a93627" />


<img width="850" height="514" alt="image" src="https://github.com/user-attachments/assets/6f2e32ad-013e-4772-869b-91c6d7c62e4b" />


<img width="773" height="681" alt="image" src="https://github.com/user-attachments/assets/4097f945-df7a-4439-be7c-a77b7c0a6905" />


<img width="681" height="266" alt="image" src="https://github.com/user-attachments/assets/2b04fb59-ddbf-4d1d-95fe-245e8733c021" />


---
