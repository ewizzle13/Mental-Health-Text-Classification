#  Mental Health Text Classification using NLP

##  Project Overview

This project focuses on building a **machine learning-based text classifier** to analyze mental health-related statements and predict psychological status. The goal is to explore how **unique word patterns** and linguistic features can assist in identifying potential mental health conditions.

We investigate multiple machine learning approaches to determine which models perform best for this task, with a focus on **Natural Language Processing (NLP)** techniques.

---

## Objectives

* Classify text data related to mental health into appropriate categories
* Analyze the role of **unique words** in distinguishing mental health conditions
* Compare performance across different machine learning models
* Evaluate models using metrics such as:

  * Accuracy
  * Precision
  * Recall
  * F1 Score

---

##  Models Used

We are experimenting with multiple models to compare performance:

* **LSTM (Long Short-Term Memory)** – Deep learning model for sequential data *(Eniya Madden)*
* **Random Forest Classifier** – Ensemble-based machine learning model *(Sania Ali)*
* **LinearSVC (Linear Support Vector Classifier)** - A supervised learning model that finds a hyperplane to separate categories *(Maryum Ahmad)*
* Additional models (TBD)

---

## Methodology

### 1. Data Preprocessing

* Removed missing values
* Tokenized text (lowercasing, splitting)
* Extracted **unique words** per statement

### 2. Feature Engineering

* Created custom word embeddings (300-dimensional vectors)
* Generated feature vectors by averaging word embeddings
* Focus on **unique vocabulary patterns** in each statement

### 3. Model Training

* Split dataset into training and testing sets (70/30)
* Trained models using labeled mental health status data
* Used validation split to monitor performance

### 4. Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

## Results (Placeholder)

| Model         | Accuracy | F1 Score | Precision | Recall |
| ------------- | -------- | -------- | --------- | ------ |
| LSTM          | TBD      | TBD      | TBD       | TBD    |
| Random Forest | TBD      | TBD      | TBD       | TBD    |

---

##  Project Structure

```
├── data/
│   └── CombinedData.csv
├── notebooks/
│   └── model_training.ipynb
├── src/
│   ├── preprocessing.py
│   ├── feature_engineering.py
│   └── models/
│       ├── lstm_model.py
│       └── random_forest.py
├── results/
│   ├── plots/
│   └── metrics/
└── README.md
```

---

## Team Members

* **Eniya Madden**
* **Sania Ali**
* **Andrew Allison**
* **Maryum Ahmad**

---

## Course Information

* Course: Natural Language Processing (NLP)
* Project Type: Group Course Project
* Focus: Text Classification in Mental Health

