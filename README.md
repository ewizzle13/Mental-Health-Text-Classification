# Mental Health Text Classification using NLP

## Project Overview

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

## Models Used

We are experimenting with multiple models to compare performance:

* **LSTM (Long Short-Term Memory)** – Deep learning model for sequential text data *(Eniya Madden)*
* **Linear SVM** – Finding the maximum margin hyperplane to separate classes *(Maryum Ahmad)*
* **XGBoost Classifier** – Gradient boosting model for high-performance classification *(Sania Ali)*
* **Custom Neural Network (Dense NN)** – Feedforward neural network for classification *(Andrew Allison)*
---

## Methodology

### 1. Data Preprocessing

* Removed missing values
* Tokenized text using Keras Tokenizer (with vocabulary size of 10,000)
* Converted text into padded sequences (fixed length of 64 tokens)

### 2. Feature Engineering

* Transformed text into numerical representations using tokenization and sequencing
* Applied padding to ensure consistent input length across all samples
* Focused on preserving important word patterns within each statement

### 3. Model Training

* Split dataset into training and testing sets (70/30)
* Trained models using labeled mental health status data
* Used validation split and early stopping (for neural networks) to monitor performance and prevent overfitting

### 4. Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

## Results (Placeholder)

| Model             | Accuracy | F1 Score | Precision | Recall |
| ----------------- | -------- | -------- | --------- | ------ |
| LSTM              | 0.73     | 0.73     | 0.73      | 0.73   |
| Linear SVM        | 0.78     | 0.77     | 0.78      | 0.78   |
| XGBoost           | 0.72     | 0.72     | 0.72      | 0.73   |
| Custom Neural Net | 0.72     | 0.72     | 0.75      | 0.72   |

---

## Project Structure

```
.
├── data
│   └── CombinedData.csv
├── notebooks
│   ├── lstm_model.ipynb
│   ├── SVM_Model.ipynb
│   ├── custom_nn.ipynb
│   ├── xgboost_model.ipynb
│   └── xgboost_updated.ipynb
├── README.md
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
