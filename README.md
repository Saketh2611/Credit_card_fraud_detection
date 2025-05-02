# 💳 Credit Card Fraud Detection using Machine Learning

This project uses a machine learning model (Random Forest Classifier) to detect fraudulent credit card transactions based on a dataset of anonymized transactions.

## 🔍 Dataset

- The dataset contains 284,807 transactions.
- Each transaction is labeled as fraud (`Class = 1`) or valid (`Class = 0`).
- Features V1 to V28 are anonymized using PCA.

## 📈 Model

- Random Forest Classifier is used.
- Accuracy: ~99.95%
- Evaluation: Precision, Recall, F1-Score, Confusion Matrix

## 📂 Project Files

- `credit_card_fraud_detection.py` – main Python code
- `credit.csv` – dataset
- `README.md` – project documentation

## 🛠️ Future Work

- Add SMOTE to handle class imbalance
- Try other models (XGBoost, SVM, Logistic Regression)
- Add ROC and PR curves

## 📌 Requirements

Install using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
