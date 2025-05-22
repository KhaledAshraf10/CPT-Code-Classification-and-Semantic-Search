# 🏷️ Medical Code Classification using NLP

## 📋 Project Overview
This project focuses on classifying medical CPT codes based on textual descriptions using Natural Language Processing (NLP) techniques. It compares traditional ML pipelines with modern deep learning models to identify the most efficient solution.

The classification task is critical for medical billing and insurance workflows, where accuracy and semantic understanding are essential.

---

## 🔧 Features

- Built and evaluated **25+ ML models** using various embeddings: TF-IDF, Word2Vec, FastText, and BERT
- Achieved **91% accuracy** using TF-IDF + SVM — outperforming more complex models like BERT and LSTM
- Conducted detailed **data preprocessing**, **feature engineering**, and **error analysis**
- Proposed improvements including **class balancing** and **model ensembling**
- Explored **semantic search** using vector-based similarity techniques

---

## 🛠️ Technologies Used

- Python  
- scikit-learn  
- TF-IDF, Word2Vec, FastText, BERT  
- SVM, LSTM, ensemble models  
- NLP preprocessing techniques  

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/khaledashrafn0/medical-code-classification-nlp.git
   cd medical-code-classification-nlp
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the model training pipeline**
   ```bash
   python train.py
   ```

4. **Test classification and semantic search**
   ```bash
   python evaluate.py
   ```

---

## 📈 Results

- Best model: **TF-IDF + SVM** with **91% accuracy**
- Deep learning models such as **BERT and LSTM** underperformed due to dataset characteristics and limited size
- Traditional models with thoughtful preprocessing outperformed transformer-based approaches

---


