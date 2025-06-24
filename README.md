# Customer-Churn-Prediction
This project focuses on predicting *customer churn—whether a customer is likely to leave a service—using **Logistic Regression, **Random Forest, and **Artificial Neural Networks (ANN)*. By analyzing historical customer data, we aim to identify key factors that influence customer retention and help businesses reduce churn rates.

---

## 📌 Objective

To develop and compare multiple machine learning models that can accurately classify whether a customer will churn, using features such as credit score, geography, age, tenure, and more.

---

## 📊 Dataset Overview

*Source*: [Kaggle – Churn Modelling Dataset](https://www.kaggle.com/datasets/shrutimechlearn/churn-modelling)

The dataset contains 10,000 customer records from a bank, including:

- CustomerId, Surname
- CreditScore
- Geography, Gender
- Age, Tenure, Balance
- NumOfProducts, HasCrCard, IsActiveMember
- EstimatedSalary
- Exited – Target variable (1 = churned, 0 = retained)

---

## ⚙ Technologies Used

- Python 3.x  
- Jupyter Notebook  
- Pandas, NumPy  
- Matplotlib, Seaborn (EDA & Visualization)  
- Scikit-learn (Logistic Regression, Random Forest)  
- TensorFlow / Keras (ANN)

---

## 🔍 Workflow

1. *Data Preprocessing*
   - Handle missing values, encode categorical data
   - Feature scaling (StandardScaler)

2. *Exploratory Data Analysis (EDA)*
   - Visualize churn patterns with respect to age, geography, account balance, etc.

3. *Model Building*
   - Logistic Regression (baseline model)
   - Random Forest Classifier (ensemble technique)
   - ANN (deep learning model using Keras)

4. *Model Evaluation*
   - Accuracy, Precision, Recall, F1-score
   - Confusion Matrix, ROC-AUC Curve

5. *Prediction*
   - Predict churn for new customer inputs

---

## 📈 Results

| Model              | Accuracy | ROC-AUC |
|-------------------|----------|---------|
| Logistic Regression | 80.2%    | 0.76    |
| Random Forest       | 86.1%    | 0.84    |
| ANN                 | 86.5%    | 0.85    |

> ✅ ANN provided the highest performance and captured complex patterns better than traditional models.
