# OIBSIP_Data_analysis_taskno6

# 🔍 Fraud Detection with Machine Learning

This project aims to identify fraudulent transactions using supervised machine learning techniques. The notebook outlines a complete pipeline from data preparation to model evaluation and interpretation.

---

## 🎯 Objective

To build a machine learning model that can detect fraudulent financial transactions with high accuracy and minimal false positives.

---

## 🔍 Steps Performed

1. **Data Exploration**
   - Loaded the dataset using `pandas`
   - Analyzed class distribution (fraud vs. non-fraud)
   - Reviewed feature statistics and correlations

2. **Data Preprocessing**
   - Handled class imbalance using techniques like:
     - Undersampling / Oversampling
     - SMOTE (Synthetic Minority Oversampling)
   - Normalized or scaled features if necessary

3. **Model Building**
   - Applied machine learning models such as:
     - Logistic Regression
     - Decision Tree / Random Forest
     - XGBoost or other ensemble methods
   - Used train-test split for evaluation

4. **Evaluation Metrics**
   - Evaluated models using:
     - Confusion Matrix
     - Precision, Recall, F1-score
     - ROC-AUC Curve

5. **Interpretation**
   - Analyzed feature importance
   - Addressed trade-offs between false positives and false negatives

---

## 🛠️ Tools & Libraries Used

- **Python 3.x**
- **Jupyter Notebook**
- **pandas** – Data handling  
- **numpy** – Numerical operations  
- **matplotlib / seaborn** – Visualization  
- **scikit-learn** – Modeling and evaluation  
- **imbalanced-learn** – Handling imbalanced datasets

**✅ Outcome**


Developed classification models capable of identifying fraudulent activity

Handled class imbalance for better real-world performance

Achieved balanced performance using precision-recall trade-offs

Gained insights into which features most influence fraudulent behavior
