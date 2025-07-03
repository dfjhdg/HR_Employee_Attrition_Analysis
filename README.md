# 💼 HR Employee Attrition Analysis & Prediction using Machine Learning

This project focuses on predicting employee attrition and uncovering key drivers behind workforce turnover using advanced machine learning techniques. It empowers HR departments to take data-driven, proactive steps to reduce employee churn and improve retention.

---

## 🎯 Project Objectives

- ✅ Predict whether an employee is likely to leave the organization (Attrition = Yes/No).
- ✅ Identify key features influencing attrition such as OverTime, Monthly Income, Job Role, and Age.
- ✅ Deliver actionable insights and HR recommendations to reduce turnover.
- ✅ Compare machine learning models to find the best attrition predictor.

---

## 📊 Dataset Overview

- 📁 Source: IBM HR Analytics Employee Attrition Dataset  
- 👥 Records: 2,940 employees  
- 🔢 Features: 35 attributes including:
  - Demographics: `Age`, `Gender`, `MaritalStatus`
  - Job Information: `JobRole`, `Department`, `JobLevel`
  - Compensation: `MonthlyIncome`, `PercentSalaryHike`
  - Engagement: `OverTime`, `YearsAtCompany`, `JobSatisfaction`
  - Target: `Attrition` (Yes/No)

---

## 🔍 Exploratory Data Analysis (EDA)

The EDA section includes detailed visualizations to understand attrition patterns across:

- 📌 Departments and Job Roles
- 📌 OverTime vs Attrition
- 📌 Gender and Age Distribution
- 📌 Income and Work-Life Balance

📊 Key Finding: Employees with high OverTime, lower income, and fewer years at the company are more likely to leave.

---

## 🧠 Machine Learning Models Used

| Model                 | Purpose                        |
|----------------------|--------------------------------|
| 🎯 Random Forest      | Main classifier + feature importance |
| 📈 Logistic Regression| Simple baseline model          |
| 🚀 XGBoost            | Gradient boosting for high accuracy |

- ✔️ Handled class imbalance using `class_weight` and `scale_pos_weight`
- ✔️ Compared using metrics: **Accuracy**, **Precision**, **Recall**, **F1-Score**, **ROC-AUC**

📈 Best ROC-AUC: **0.87** with **XGBoost**

---

## 📌 Top Features Identified

1. `OverTime`
2. `MonthlyIncome`
3. `JobRole`
4. `DistanceFromHome`
5. `Age`

---

## 💡 HR Insights & Recommendations

- 🕒 **OverTime**: Reduce excessive overtime to lower burnout.
- 💰 **Compensation**: Review salary bands for high-risk roles.
- 🧑‍🎓 **Engage Young Employees**: Provide career pathing and recognition.
- 🎯 **Focus on Roles with High Churn**: Like Sales Reps and Lab Technicians.

---

## 🛠️ Tools & Technologies Used

- 🐍 Python
- 📊 Pandas, NumPy
- 📈 Matplotlib, Seaborn
- 🧪 Scikit-learn
- 🚀 XGBoost
- 💻 Jupyter Notebook
- 🧠 Machine Learning
- ⚖️ Imbalanced Data Handling
- 📁 CSV File Processing

---


