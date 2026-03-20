# customer_transaction_prediction
A machine learning project that predicts customer transaction behavior in the banking sector using data preprocessing, EDA, and models such as Logistic Regression and LightGBM.
# 📊 Customer Transaction Prediction in Banking

## 🚀 Overview

This project aims to predict whether a customer will make a transaction using machine learning techniques. It helps banks improve marketing strategies, customer targeting, and decision-making.

---

## 📁 Dataset

The dataset used is **Santander Customer Transaction Prediction** from Kaggle.

* `train.csv` → Contains features + target variable
* `test.csv` → Contains features only for prediction

---

## 🧠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* LightGBM

---

## ⚙️ Workflow

### 1. Data Loading

* Load dataset using Pandas

### 2. Data Preprocessing

* Remove unnecessary columns
* Feature scaling
* Handle imbalanced data using SMOTE

### 3. Exploratory Data Analysis (EDA)

* Visualize target distribution
* Understand feature behavior

### 4. Model Building

* Logistic Regression
* LightGBM

### 5. Model Evaluation

* Accuracy Score
* Confusion Matrix
* ROC-AUC Score

---

## 📊 Results

* Logistic Regression provides a good baseline
* LightGBM improves performance and accuracy

---

## 🎯 Output

The model predicts:

* `0` → No Transaction
* `1` → Transaction

---


## ▶️ How to Run

1. Clone the repository:

```
git clone https://github.com/your-username/customer-transaction-prediction.git
```

2. Install dependencies:

```
pip install pandas numpy matplotlib seaborn scikit-learn lightgbm
```

3. Run the notebook:

```
jupyter notebook
```

---

## 📌 Future Improvements

* Hyperparameter tuning
* Feature engineering
* Try advanced models like XGBoost
* Deploy using Streamlit

---
## 📁 Dataset
The dataset is not included due to size limitations.

You can download it from Kaggle:
https://www.kaggle.com/competitions/santander-customer-transaction-prediction/data

## 🙌 Acknowledgement

Dataset provided by Kaggle.

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
