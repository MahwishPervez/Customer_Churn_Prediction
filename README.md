# 📉 Customer Churn Prediction using Machine Learning

## 👩‍💻 Author

**Mahwish Pervez**
B.Tech Computer Science Student | Machine Learning & Data Science Enthusiast

---

## 📌 Project Overview

Customer churn is one of the biggest challenges faced by subscription-based businesses. This project uses Machine Learning techniques to predict whether a customer is likely to leave a telecom service provider based on demographic, account, and service-related information.

The objective is to help organizations identify high-risk customers and take proactive retention measures.

---

## 🎯 Objectives

* Analyze customer behavior and churn patterns
* Perform Exploratory Data Analysis (EDA)
* Build and compare Machine Learning models
* Identify key factors influencing churn
* Generate business recommendations based on insights

---

## 📊 Dataset

**Dataset:** Telco Customer Churn Dataset

### Features Include:

* Customer demographics
* Contract details
* Payment methods
* Internet services
* Account information
* Monthly and total charges

### Target Variable:

* **Churn**

  * Yes
  * No

Dataset Size:

* 7043 Records
* 21 Features

---

## 🔍 Exploratory Data Analysis

EDA was performed using Pandas, Matplotlib, and Seaborn to understand customer behavior.

### Key Findings

* Customers with shorter tenure show higher churn rates.
* Month-to-month contracts have significantly higher churn.
* Electronic check users are more likely to churn.
* Customers with higher monthly charges tend to leave more frequently.
* Long-term contract customers are comparatively loyal.

---

## 🤖 Machine Learning Models

The following models were trained and evaluated:

| Model                  | Accuracy |
| ---------------------- | -------- |
| Logistic Regression    | 80%      |
| Random Forest          | 82%      |
| Support Vector Machine | 78%      |
| K-Nearest Neighbors    | 75%      |
| Naive Bayes            | 72%      |

### Best Performing Model

🏆 Random Forest Classifier

Evaluation Metrics:

* Accuracy Score
* Confusion Matrix
* Precision
* Recall
* F1-Score
* Classification Report

---

## 📈 Visualizations

The project includes:

* Churn Distribution Analysis
* Customer Tenure Distribution
* Monthly Charges Distribution
* Contract Type vs Churn
* Payment Method vs Churn
* Correlation Heatmap
* Model Performance Comparison

---

## 💡 Business Insights

* Approximately 27% of customers churn.
* Month-to-month contract customers have the highest churn probability.
* Short-tenure customers require targeted onboarding strategies.
* Electronic check payment users represent a high-risk segment.
* Predictive analytics can significantly improve customer retention efforts.

---

## 🚀 Business Recommendations

### 1. Improve Customer Onboarding

Provide personalized support during the first year of service.

### 2. Promote Long-Term Contracts

Offer discounts and incentives for annual subscriptions.

### 3. Encourage Automated Payments

Reduce churn risk by promoting credit card and auto-payment methods.

### 4. Deploy Predictive Monitoring

Use churn predictions to identify at-risk customers early.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## 📂 Project Structure

```text
Customer_Churn_Prediction/
│
├── data/
├── notebooks/
├── visuals/
├── models/
├── README.md
└── requirements.txt
```

---

## 🔮 Future Improvements

* Hyperparameter Tuning using GridSearchCV
* XGBoost and CatBoost Models
* SHAP Explainability Analysis
* Streamlit Dashboard Deployment
* Real-Time Churn Prediction System

---

## 📚 Learning Outcomes

Through this project I gained practical experience in:

* Data Cleaning
* Exploratory Data Analysis
* Feature Engineering
* Classification Algorithms
* Model Evaluation
* Business-Oriented Data Interpretation

---

## 🙋‍♀️ About Me

I am **Mahwish Pervez**, a Computer Science student passionate about Machine Learning, Data Science, and Software Development.

I enjoy building data-driven solutions that transform raw data into actionable insights and business value.

---

## ⭐ Support

If you find this project useful, consider giving it a star on GitHub.
