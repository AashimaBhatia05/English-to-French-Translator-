# EN➡️FR English to French Translator

This project implements a Neural Machine Translation (NMT) model that translates English sentences to French using Recurrent Neural Networks (RNN) with attention mechanisms and teacher forcing.

## 📌 Problem Statement
Language translation is a complex task requiring understanding of both context and grammar. This project aims to build a model that can translate English sentences to French with high accuracy using deep learning.

## 🧠 Model Overview
- **Type**: Neural Machine Translation (NMT)
- **Architecture**: Sequence-to-Sequence with Attention
- **Core Techniques**:
  - Recurrent Neural Networks (RNN)
  - Word Embedding
  - Teacher Forcing
  - Attention Mechanism
- **Framework**: TensorFlow

## 📊 Dataset
- Source: English-French sentence pairs dataset (downloaded from Kaggle)
- Preprocessing:
  - Tokenization
  - Padding
  - Vocabulary creation for both languages

## 🚀 Accuracy & Results
- **Achieved Translation Accuracy**: **95.2%**
- Sample Outputs:
  - Input: `I love learning` → Output: `J'aime apprendre`
  - Input: `How are you?` → Output: `Comment ça va ?`

## 🛠️ Libraries & Tools
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

## 🔍 Key Components
1. **Data Preprocessing**
   - Cleaning, tokenizing, and padding sequences
2. **Model Design**
   - Encoder-Decoder architecture using RNN
   - Attention mechanism to improve translation quality
3. **Training**
   - Teacher forcing to improve learning speed
   - Cross-entropy loss function with Adam optimizer
4. **Evaluation**
   - BLEU score and sentence-level accuracy
- Jupyter Notebook

## 🌟 Future Improvements
-Use LSTM or GRU units instead of vanilla RNNs

-Implement beam search decoding for better translation output

-Train on larger datasets like the Europarl corpus

-Deploy the model using Streamlit or Flask as a web app

##  Author

Aashima Bhatia

**Gmail**: aashimabhatia2005@gmail.com

**LinkedIn**: https://www.linkedin.com/in/aashima-bhatia-a30919300/
