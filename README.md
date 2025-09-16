# Fake News Detection and Evaluation with Confusion Matrix 

This repository contains a complete project on **Fake News Detection** using machine learning algorithms.  
The goal is to classify news articles as **real or fake** using supervised learning methods, and evaluate the results with standard metrics and a confusion matrix.  

---

## Technologies & Libraries Used  

- **Python 3**  
- **Pandas, NumPy** → Data preprocessing & cleaning  
- **Matplotlib** → Data visualization & EDA  
- **Scikit-learn** → Train-test split, Logistic Regression, Random Forest, evaluation metrics  
- **Word2Vec (gensim)** → Text vectorization  
- **Pickle** → Model serialization  

---

## Workflow  

1. **Data Collection**  
   - Real news scraped from [Reuters.com](https://www.reuters.com/)  
   - Fake news collected from unreliable sources identified by Politifact & Wikipedia  
   - Dataset also available on Kaggle: [Fake News Detection Dataset](https://www.kaggle.com/datasets/emineyetm/fake-news-detection-datasets)  

2. **Data Preprocessing**  
   - Cleaning text, removing punctuation & special symbols  
   - Lowercasing, tokenizing, removing duplicates  
   - Merging datasets and shuffling  

3. **Exploratory Data Analysis (EDA)**  
   - Bar chart of top 5 subjects  
   - Pie chart of subject-wise distribution  
   - Word frequency checks  

4. **Text Vectorization**  
   - Word2Vec embeddings trained on BBC dataset for semantic representation  

5. **Model Building & Evaluation**  
   - Logistic Regression → Accuracy: **0.943**  
   - Random Forest → Accuracy: **0.938**  
   - Evaluation metrics: Accuracy, Precision, Recall, F1-score  
   - Confusion matrix visualization  

6. **Model Saving**  
   - Models serialized using Pickle for reuse  

---

## Demonstration  

A short demo video of the project workflow and results is included in the **Dependencies** folder.  

---

## Future Work  

- Experiment with **boosting algorithms** (AdaBoost, XGBoost, etc.) to improve accuracy.  
- Use **TF-IDF vectorizer** and compare with Word2Vec embeddings.  
- Explore **deep learning methods** (e.g., LSTMs, GRUs, BERT).  

---

## Author  

Developed as part of an academic project for **IDEAS-TIH ISI Kolkata - Foundation Autumn Internship** on **Data Science**.  
- Contact: *adityachakraborty153@gmail.com*  
- GitHub: *https://github.com/Adiborty-Code/*  

---
