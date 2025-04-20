
---

## 🧠 Project Overview

- **Objective**: To develop a predictive model that automates credit card approval using machine learning techniques.
- **Scope**: The system uses demographic and financial data to classify applications into approved or rejected categories.

---

## 📊 Dataset

- **Source**: [UCI Machine Learning Repository - Credit Approval Dataset](https://archive.ics.uci.edu/ml/datasets/credit+approval)
- **Features**: Includes attributes such as `Age`, `Employment Status`, `Total Bill Amount`, `Annual Income`, and more.
- **Preprocessing**:
  - Handled missing values
  - Encoded categorical variables
  - Normalized numerical features
  - Feature selection based on correlation and domain logic

---

## ⚙️ Machine Learning Models

The following models were trained and evaluated:

| Model                  | Accuracy | Precision | Recall | F1-Score |
|------------------------|----------|-----------|--------|----------|
| Random Forest          | 87.86%   | 0.88      | 0.88   | 0.88     |
| Logistic Regression    | 86.88%   | 0.86      | 0.86   | 0.86     |
| Decision Tree          | 83.61%   | 0.83      | 0.84   | 0.83     |
| K-Nearest Neighbors    | 85.25%   | 0.85      | 0.85   | 0.85     |

> **Best Performer**: Random Forest showed the highest accuracy and generalization.

---

## 📈 Visualizations

- Confusion Matrix
- Feature Importance Plot
- Model Comparison Graphs
- Correlation Heatmaps

These visuals provide insights into model performance, influential features, and error patterns.

---

## ✅ Evaluation Metrics

- **Accuracy**
- **Precision**
- **Recall**
- **F1-score**
- **Confusion Matrix**

---

## 🔬 Results & Insights

- Random Forest achieved the best overall performance.
- Feature importance showed variables like `pay_day_range`, `employment_status`, and `total_bill_value` played key roles.
- Logistic Regression offered good performance with high interpretability.
- Confusion matrices helped identify false positives and negatives for each model.

---

## 🚀 Future Improvements

- Apply cross-validation for more robust evaluation
- Integrate SHAP/LIME for model interpretability
- Try deep learning models (e.g., MLP)
- Use AutoML tools like TPOT or H2O.ai for optimization
- Perform fairness and bias audits
- Deploy the model using Flask or FastAPI for real-time prediction

---

## 📚 References

- [UCI Credit Approval Dataset](https://archive.ics.uci.edu/ml/datasets/credit+approval)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [LIME for Model Interpretability](https://github.com/marcotcr/lime)
- [SHAP for Explainable AI](https://shap.readthedocs.io/en/latest/)
- [SMOTE - Imbalanced Learning](https://imbalanced-learn.org/stable/)

---


