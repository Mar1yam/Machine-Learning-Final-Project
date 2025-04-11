# 📊 Telecom Customer Churn Prediction (INFR 3700U Project)

This project uses machine learning and deep learning models to predict customer churn in the telecom industry. The goal is to help telecom providers identify customers who are likely to leave, so they can take proactive steps to retain them.

---

## 📁 Dataset

The dataset used is the [Telco Customer Churn dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) from Kaggle.

- 7,043 customer records
- 21 features including demographics, contract types, and service usage
- Binary classification: Churn (`Yes`) or Not Churn (`No`)

---

## 🧠 Models Used

This project compares five models:
- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)
- XGBoost
- Deep Learning (Keras Neural Network)

---

## ⚙️ Preprocessing Steps

- Removed missing values
- Label-encoded categorical features
- Scaled numerical features (`tenure`, `MonthlyCharges`, `TotalCharges`)
- Split dataset into 80% training and 20% testing

---

## 📈 Evaluation Metrics

Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

📌 **Best Model:**  
The Deep Learning model achieved the highest performance:
- Accuracy: `80.2%`
- Recall: `50.3%`
- F1-Score: `57.5%`

---

## 📊 Feature Importance

Based on Random Forest and XGBoost analysis, the most important features were:
- `tenure`
- `contract type`
- `monthly charges`

These features helped identify patterns in churn behavior and informed the model predictions.

---

## 🛠️ Technologies

- Python 3.10+
- Scikit-learn
- XGBoost
- Keras (TensorFlow backend)
- Pandas, NumPy, Matplotlib

---

## 📌 Project Report

This project was submitted as part of the INFR 3700U course at Ontario Tech University.  
[📄 View Final Report](./Project_Report_ML_100867858.pdf)


