# Credit Card Approval Prediction

A robust machine learning project for automating and improving credit card approval predictions using customer profile data.

---

## Table of Contents

* Introduction
* Dataset
* Approach
* Machine Learning Models Used
* Evaluation
* Results
* How to Run
* Author

---

## Introduction

Credit card approval is a crucial decision-making process for financial institutions. This project leverages machine learning to predict whether a customer’s credit card application should be approved or denied, based on a variety of demographic and financial features. The goal is to assist banks in automating approvals while minimizing risk and maximizing accuracy.

---

## Dataset

* **Source**: [UCI Machine Learning Repository - Credit Approval Dataset](https://archive.ics.uci.edu/ml/datasets/credit+approval)
* **Features**: Includes attributes such as `Age`, `Employment Status`, `Total Bill Amount`, `Annual Income`, and more.
* **Target Variable**: `default_payment` (1: defaulted, 0: non-defaulted).

---

## Approach

1. **Data Exploration and Visualization:**

   * Explored distributions and relationships among key features (age, gender, education, payment history).
   * Visualized correlations and feature importances to guide modeling.

2. **Data Preprocessing:**

   * Null value imputation
   * Categorical encoding (label mapping)
   * Feature scaling (StandardScaler)
   * Feature engineering (e.g., total bill, total payments)

3. **Model Building:**

   * Trained multiple classifiers to optimize predictive accuracy.

---

## Machine Learning Models Used

* **Logistic Regression:** Baseline linear model for binary classification.
* **Decision Tree Classifier:** Non-linear model for capturing complex patterns and feature interactions.
* **Random Forest Classifier:** Ensemble method for improved robustness and generalization.

Each model was tuned and evaluated on a hold-out test set.

---

## Evaluation

* **Performance Metrics:**

  * Accuracy
  * ROC-AUC Score
  * Confusion Matrix
  * Feature importance analysis
* **Visualization:**

  * ROC curves for model comparison
  * Feature importance bar plots
  * Exploratory data visualizations

---

## Results

* **Best Accuracy:** Up to \~88% on the test set.
* **Insights:** Random Forest and Logistic Regression models showed strong, consistent performance. Key features impacting approval included payment history, credit limit, and recent bill amounts.
* **Interpretability:** Feature importance plots provided clear business insights for decision-making.

---

## How to Run

1. **Clone this repository:**

   ```bash
   git clone https://github.com/yourusername/credit-card-approval-prediction.git
   cd credit-card-approval-prediction
   ```

2. **Launch Jupyter Notebook:**

   ```bash
   jupyter notebook credit_card_approval.ipynb
   ```

## Author

**Kandimalla Bruhadev**
Email: [devbruha@gmail.com](mailto:devbruha@gmail.com)

---

> *This project demonstrates best practices in data preprocessing, feature engineering, and interpretable machine learning for real-world financial decision automation.*
