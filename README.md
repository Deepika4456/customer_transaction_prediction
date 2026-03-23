# 💳 Customer Transaction Prediction using Machine Learning

## 📌 Project Overview

This project aims to predict whether a customer will make a transaction using machine learning techniques.
The dataset is from the Santander Kaggle competition and contains **200 anonymized features** representing customer behavior.

---

## 📊 Dataset Description

* **Train Dataset**: Includes features (`var_0` to `var_199`) and target variable
* **Test Dataset**: Includes only features (used for prediction)

### 🎯 Target Variable:

* `0` → No transaction
* `1` → Transaction

---

## ⚙️ Project Workflow

1. **Data Loading**
   Importing train and test datasets

2. **Data Preprocessing**
   Handling missing values and feature scaling

3. **Exploratory Data Analysis (EDA)**
   Understanding feature distribution and patterns

4. **Feature Selection**
   Identifying important variables

5. **Model Training**
   Training classification models

6. **Prediction**
   Predicting customer transactions on test data

---

## 🤖 Models Used

* **Logistic Regression**
  → Simple and interpretable baseline model

* **Random Forest**
  → Handles non-linearity and improves accuracy

---

## 📈 Results & Performance

* **Accuracy**: 0.785675
* The model achieved 0.785675 accuracy, indicating good generalization on unseen data.
* **ROC-AUC Score**: 0.8580798936379652

📌 The model demonstrates strong ability to distinguish between customers who will and will not make transactions.

---

## 💼 Business Use Case

This model can help banks:

* Identify potential customers likely to make transactions
* Improve targeted marketing strategies
* Enhance customer engagement

---

## 📁 Project Structure

```
customer_transaction_prediction/
│── notebook.ipynb
│── README.md
```

---

## 📸 Output Visualization

<img width="1097" height="724" alt="Screenshot 2026-03-20 145848" src="https://github.com/user-attachments/assets/c93415e3-fd0e-4a4a-9384-748ff69f920d" />
<img width="979" height="903" alt="Screenshot 2026-03-20 145920" src="https://github.com/user-attachments/assets/07d2c40f-030d-4878-9e48-f7955b2322aa" />
<img width="1437" height="850" alt="Screenshot 2026-03-20 150533" src="https://github.com/user-attachments/assets/22971b3b-1b8b-41e6-894a-cb1bf6197b18" />


---

## 🚀 Future Improvements

Hyperparameter tuning (GridSearch / RandomSearch)

Advanced model (XGBoost)

Deep learning approaches

Deployment using Streamlit

---

## ✅ Conclusion

This project demonstrates the application of machine learning techniques to solve a real-world banking problem.
The model achieves strong predictive performance and can be further enhanced for production-level deployment.
---


## 👩‍💻 Author
s.deepika
