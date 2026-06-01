# Customer-Churn-Prediction

## 📌 Project Overview

Customer churn is one of the most critical challenges for subscription-based businesses. This project focuses on predicting whether a customer is likely to leave a telecom service provider based on demographic information, account details, and service usage patterns.

Using machine learning techniques, the model identifies high-risk customers, enabling businesses to take proactive retention measures and reduce revenue loss.

---

## 🎯 Business Problem

Customer acquisition is significantly more expensive than customer retention. Telecom companies lose substantial revenue when customers discontinue their services.

The objective of this project is to:

- Predict customer churn accurately.
- Identify key factors contributing to customer attrition.
- Generate actionable business insights for customer retention strategies.

---

## 📊 Dataset Information

The dataset contains **7,043 customer records** with **21 features**.

### Features Included

| Category | Features |
|-----------|-----------|
| Customer Demographics | Gender, SeniorCitizen, Partner, Dependents |
| Account Information | Tenure, Contract Type, Payment Method, Paperless Billing |
| Services | Phone Service, Multiple Lines, Internet Service |
| Additional Services | Online Security, Online Backup, Device Protection, Tech Support |
| Entertainment Services | Streaming TV, Streaming Movies |
| Billing Information | Monthly Charges, Total Charges |
| Target Variable | Churn |

### Target Variable

- **Churn = Yes** → Customer left the company
- **Churn = No** → Customer stayed

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🔍 Project Workflow

### 1. Data Collection
- Imported telecom customer churn dataset.
- Inspected data structure and feature types.

### 2. Data Cleaning
- Handled missing values.
- Converted categorical variables into numerical format.
- Removed inconsistencies in data types.

### 3. Exploratory Data Analysis (EDA)
- Analyzed churn distribution.
- Investigated customer behavior patterns.
- Visualized relationships between churn and various features.

### 4. Feature Engineering
- Label Encoding / One-Hot Encoding.
- Feature scaling where necessary.
- Created machine-learning-ready dataset.

### 5. Model Building
Implemented and compared multiple machine learning algorithms:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost (Optional)
- Gradient Boosting Classifier

### 6. Model Evaluation
Evaluation metrics used:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

---

## 📈 Key Insights

Some common churn indicators discovered during analysis:

- Customers with **Month-to-Month contracts** show higher churn rates.
- Customers using **Electronic Check** payment methods are more likely to churn.
- Customers with **Fiber Optic Internet** exhibit relatively higher churn.
- Lack of **Online Security** and **Tech Support** services increases churn probability.
- Customers with shorter tenure are more likely to leave.

---

## 🚀 Results

The final machine learning model successfully predicts customer churn and helps identify customers at risk of leaving.

Example business applications:

- Targeted retention campaigns
- Personalized customer offers
- Improved customer support strategies
- Revenue protection initiatives

---

## 🎓 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Machine Learning
- Classification Modeling
- Model Evaluation
- Business Insight Generation
- Data Visualization

---

## Contact

**Danish Butt**  
📧 Email: buttdanix@gmail.com  
🔗 LinkedIn: linkedin.com/in/idanishbutt
