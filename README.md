# E-Commerce Customer Churn Prediction

End-to-end data analysis and predictive modeling project to identify and predict customer churn in an e-commerce environment.


## 📌 Project Overview

Customer churn is one of the most critical challenges in e-commerce, directly impacting revenue and long-term growth. 

This project analyzes customer behavioral and transactional data to:

- Identify the key drivers of churn
- Extract actionable business insights
- Build a predictive model to detect at-risk customers

The goal is to transform raw customer data into strategic business decisions.



## 📂 Dataset

The dataset was sourced from Kaggle and contains 50,000 customer records including:

- Session duration
- Login frequency
- Cart abandonment rate
- Lifetime value (LTV)
- Days since last purchase
- Churn status (target variable)

 Dataset Source: Kaggle (Customer Churn Dataset)



## 🎯 Objectives

- Perform structured exploratory data analysis (EDA)
- Identify behavioral patterns associated with churn
- Engineer and prepare features for modeling
- Train and evaluate a Logistic Regression model
- Translate model outputs into business recommendations


## 🛠 Methodology

### 1️⃣ Data Cleaning & Preparation
- Handled missing values
- Feature selection
- Train-test split
- Feature scaling using StandardScaler

### 2️⃣ Exploratory Data Analysis
- Compared behavioral metrics across churned vs retained customers
- Identified inactivity and engagement-related patterns
- Summarized key behavioral differences

### 3️⃣ Predictive Modeling
- Logistic Regression classifier
- Evaluated using Accuracy, Recall, ROC AUC, and Confusion Matrix
- Focused on recall to prioritize churn detection



## 📊 Model Performance

- **ROC AUC:** 0.745  
![alt text](image.png)

- **Accuracy:** 67.4%  
- **Churn Recall:** 70%

The model demonstrates strong ability to distinguish between churned and retained customers. 

Given the business objective of preventing revenue loss, the model prioritizes recall to ensure high-risk customers are identified early.



## 🔎 Model Interpretation

Below is the feature importance derived from the Logistic Regression model:

![alt text](Feature_importance-1.png)


### Key Predictive Drivers:
- **High cart abandonment rate** → Increased churn risk 
- **Longer inactivity (days since last purchase)** → Higher churn probability. !
- **Lower lifetime value** → Associated with churned customers  

These features highlight that disengagement and reduced purchasing activity are strong churn signals.



## 💡 Key Business Insights

- Customers with prolonged inactivity are significantly more likely to churn.
- Cart abandonment is a strong behavioral indicator of dissatisfaction or friction.
- Engagement-based metrics outperform pure revenue metrics in predicting churn.



## 🚀 Business Recommendations

- Implement automated retention campaigns targeting high-risk customers.
- Optimize checkout flow to reduce cart abandonment.
- Re-engage inactive users with personalized incentives.
- Monitor churn probability as an early warning system.



## 🔮 Future Work


- Experiment with tree-based models (Random Forest)
- Hyperparameter tuning
- Class imbalance handling improvements
- Deploy model as a real-time churn scoring API



## 🧰 Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Jupyter Notebook



## 👤 Author

**Meriem Aznag**
Aspiring Data Scientist
Focused on Data Analysis & Machine Learning






