# 📰 Fake News Classifier

### **Authors:** Vyom Mangtani, Taitil Chheda, Zafir Khanchey  
### **Dataset Source:** [Fake News Dataset on Kaggle](https://www.kaggle.com/competitions/fake-news/data)

---

## 📘 Project Overview

This project focuses on detecting **fake news** articles using **Natural Language Processing (NLP)** and **Machine Learning** techniques.  
The goal is to build a model that can accurately classify news as *real* or *fake* based on textual features such as headlines, authors, and article body.  

By using text preprocessing, TF-IDF vectorization, and classification algorithms, the project aims to contribute to the growing need for automated fake news detection tools in today’s information-driven world.

---

## 🧠 Objective

To develop and compare different machine learning models to classify news articles as *real* or *fake* based on their content and metadata.

---

## ⚙️ Methodology

1. **Data Collection**  
   The dataset was sourced from the Kaggle Fake News Detection Competition.

2. **Data Preprocessing**  
   - Removal of null values and duplicates  
   - Text normalization: lowercase conversion, punctuation removal, and stopword elimination  
   - Tokenization and stemming  
   - TF-IDF vectorization for numerical feature extraction

3. **Model Training**  
   The following models were implemented and trained:
   - **Naive Bayes Classifier (MultinomialNB)**  
   - **Logistic Regression**  
   - **Passive Aggressive Classifier**

4. **Model Evaluation**  
   Models were assessed using:
   - Accuracy Score  
   - Confusion Matrix  
   - ROC-AUC Curve

---

## 📊 Visualization and Analysis

The notebook includes the following visualizations:
- Most common words in fake vs. real news articles  
- Distribution of article lengths  
- ROC-AUC curve comparing model performance  

*(Graphs can be reinserted manually from the notebook when preparing the report.)*

---

## 🧩 Results

- **Naive Bayes** provided a strong baseline accuracy but struggled with more complex textual dependencies.  
- **Logistic Regression** showed consistent results across balanced datasets.  
- **Passive Aggressive Classifier** achieved the highest accuracy and F1-score, making it the most effective among the models tested.

---

## 🏁 Conclusion

This project demonstrates the potential of combining NLP techniques with machine learning models for effective **fake news detection**.  
While traditional classifiers such as Naive Bayes and Logistic Regression perform well, the **Passive Aggressive Classifier** proved to be more robust in identifying deceptive news patterns.  

Future enhancements could include:
- Integrating deep learning models such as **LSTM** or **BERT** for contextual text analysis  
- Expanding the dataset to include multilingual or multimedia sources  
- Developing a web-based or real-time fake news detection tool

---

## 💾 Requirements

To install the dependencies:

```bash
pip install -r requirements.txt
