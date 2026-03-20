# customer_transaction_prediction
A machine learning project that predicts customer transaction behavior in the banking sector using data preprocessing, EDA, and models such as Logistic Regression and LightGBM.
# 📊 Customer Transaction Prediction in Banking

<p align="center">
  <b>Machine Learning Project to Predict Customer Transactions</b><br>
  Using Logistic Regression & LightGBM 🚀
</p>

---

## 🚀 Overview

This project predicts whether a customer will make a transaction based on historical banking data. It helps financial institutions improve customer targeting, marketing strategies, and decision-making.

---

## 🎯 Problem Statement

Banks need to identify potential customers who are likely to perform transactions. This project builds a classification model to solve this problem efficiently.

---

## 📁 Dataset

The dataset used is **Santander Customer Transaction Prediction**.

⚠️ Due to file size limitations, the dataset is not included in this repository.

👉 Download from Kaggle:
https://www.kaggle.com/competitions/santander-customer-transaction-prediction/data

---

## 🧠 Tech Stack

* Python 🐍
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn
* LightGBM

---

## ⚙️ Workflow

### 🔹 Data Preprocessing

* Removed unnecessary columns
* Feature scaling using StandardScaler
* Handled imbalanced data using SMOTE

### 🔹 Exploratory Data Analysis (EDA)

* Analyzed target distribution
* Identified patterns and trends

### 🔹 Model Building

* Logistic Regression (baseline model)
* LightGBM (advanced model)

### 🔹 Model Evaluation

* Accuracy Score
* Confusion Matrix
* ROC-AUC Score

---

## 📊 Results

| Model               | Performance                   |
| ------------------- | ----------------------------- |
| Logistic Regression | Good baseline accuracy        |
| LightGBM            | Better accuracy & performance |

---

## 🎯 Output

The model predicts:

* `0` → No Transaction
* `1` → Transaction

---

## 📂 Project Structure

```bash
Customer-Transaction-Prediction/
│── notebook.ipynb
│── README.md
```

---

## ▶️ How to Run

```bash
# Clone repository
git clone https://github.com/your-username/customer-transaction-prediction.git

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn lightgbm

# Run notebook
jupyter notebook
```

---

## 📌 Future Improvements

* Hyperparameter tuning
* Feature engineering
* Try XGBoost & Random Forest
* Deploy using Streamlit

---

## 🙌 Acknowledgement

Dataset provided by Kaggle.

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!

---

## 👩‍💻 Author
s.deepika
