# 📉 Customer Churn Prediction

![Customer Churn Prediction Thumbnail](churn_prediction.png)

This project focuses on predicting customer churn for a telecom provider using service usage and contract data.

---

## 🧠 Objective

To build a classification model that predicts whether a customer is likely to cancel their telecom service, enabling proactive retention strategies.

---

## 📂 Dataset

- **Source:** Telecom customer dataset (contract, personal, internet, and phone data)
- **Features:** Service types, contract length, payment method, monthly and total charges
- **Target:** Customer churn status (Yes/No)

---

## 🔧 Methods Used

- Data merging and preprocessing
- Encoding categorical variables
- Feature engineering (e.g., tenure, service combinations)
- Modeling: Logistic Regression, Random Forest, Gradient Boosting
- Evaluation: AUC-ROC, cross-validation

---

## 🚀 Key Results

- Final model: Gradient Boosting Classifier
- Achieved AUC-ROC score ≈ 0.844
- Identified key churn indicators: month-to-month contracts, fiber optic internet, electronic check payments

---

## 📌 Technologies Used

- Python, Pandas, NumPy
- Scikit-learn
- Jupyter Notebook
