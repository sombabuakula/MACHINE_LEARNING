#  Credit Card Fraud Detection using Logistic Regression

A Machine Learning project that detects fraudulent credit card transactions using **Logistic Regression**. This project addresses the challenge of **highly imbalanced data** by applying **SMOTE (Synthetic Minority Over-sampling Technique)** and evaluates the model using appropriate classification metrics rather than relying only on accuracy.

---

##  Project Overview

Credit card fraud detection is a critical application of machine learning in the financial industry. Since fraudulent transactions represent only a tiny fraction of all transactions, building an effective model requires handling class imbalance and evaluating performance with suitable metrics.

This project demonstrates an end-to-end machine learning workflow, including:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Handling class imbalance using SMOTE
- Feature scaling
- Logistic Regression model training
- Model evaluation using multiple metrics

---

##  Objectives

- Detect fraudulent credit card transactions.
- Handle severe class imbalance using SMOTE.
- Train a Logistic Regression classifier.
- Evaluate the model using Precision, Recall, F1-Score and ROC-AUC.
- Understand the trade-off between Precision and Recall in fraud detection.

---

##  Dataset

**Dataset:** Credit Card Fraud Detection Dataset

- Total Transactions: **284,807**
- Fraudulent Transactions: **492**
- Legitimate Transactions: **284,315**

**Download the dataset from Kaggle:**

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

> **Note:** The dataset is not included in this repository because it exceeds GitHub's file size limit.

Place the downloaded file in the project directory as:

```text
creditcard.csv
```

---

##  Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Jupyter Notebook

---

##  Machine Learning Workflow

1. Load Dataset
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Train-Test Split (Stratified)
6. Feature Scaling
7. Handle Class Imbalance using SMOTE
8. Train Logistic Regression Model
9. Evaluate Model Performance
10. Interpret Results

---

##  Model Performance

| Metric | Score |
|---------|-------|
| Accuracy | **97.28%** |
| Precision | **5.14%** |
| Recall | **87.37%** |
| F1-Score | **9.71%** |
| ROC-AUC Score | **96.63%** |

### Key Insight

The model achieved a **high Recall (87.37%)**, meaning it successfully detected most fraudulent transactions. Although the Precision is relatively low due to false positives, this trade-off is often acceptable in fraud detection because missing fraudulent transactions can result in significant financial losses.

---

##  Project Structure

```text
CreditCard_Fraud_Detection/
│
├── Fraud_Detection.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

##  Installation

Clone the repository:

```bash
git clone https://github.com/sombabuakula/MACHINE_LEARNING.git
```

Navigate to the project directory:

```bash
cd CreditCard_Fraud_Detection
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Download the dataset from Kaggle and place it in the project folder.

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
Fraud_Detection.ipynb
```
---
##  Future Improvements
- Train and compare Random Forest and XGBoost models.
- Perform hyperparameter tuning.
- Optimize the decision threshold.
- Deploy the model using Flask or FastAPI.
- Build a real-time fraud detection API.
---
##  Author

**Sombabu Akula**

B.Tech – Computer Science and Business Systems (CSBS)

Passionate about Data Analytics, Machine Learning and AI.