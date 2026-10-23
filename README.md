# 🚗 Fuel Efficiency Prediction and Analysis for Automotive Insights

## 📌 Project Overview

This project develops a machine learning solution to predict vehicle fuel efficiency (MPG) using automotive characteristics such as engine specifications, vehicle weight, acceleration, manufacturing year, and country of origin.

The objective is to help automotive manufacturers identify the key factors affecting fuel efficiency and support data-driven vehicle design decisions that improve performance, reduce costs, and enhance competitiveness.

---

## 🎯 Business Problem

Fuel efficiency is a critical factor influencing:

- Vehicle operating costs
- Environmental compliance
- Customer satisfaction
- Product competitiveness

By accurately predicting fuel efficiency, manufacturers can optimize vehicle designs early in the development process and reduce reliance on costly trial-and-error testing.

---

## 🛠️ Project Workflow

### Data Preparation
- Handled missing values
- Corrected data types
- Prevented data leakage using ML pipelines
- Performed train-test split and cross-validation

### Exploratory Data Analysis
- Fuel efficiency distribution
- MPG vs Weight analysis
- MPG vs Horsepower analysis
- Regional comparisons
- Model year trend analysis

### Feature Engineering
- Origin encoding
- Vehicle segmentation
- Pipeline-based preprocessing

### Model Development
- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

### Model Optimization
- K-Fold Cross Validation
- RandomizedSearchCV Hyperparameter Tuning

### Model Interpretability
- Feature Importance Analysis
- Business Insight Generation

---

## 📊 Model Performance

| Model | MAE | RMSE | R² Score |
|---------|---------:|---------:|---------:|
| Linear Regression | 2.29 | 2.89 | 0.845 |
| XGBoost (Tuned) | 1.77 | 2.45 | 0.888 |
| Random Forest (Tuned) | **1.59** | **2.15** | **0.914** |

### 🏆 Best Model

**Random Forest Regressor (Tuned)**

- R² Score: **91.4%**
- MAE: **1.59 MPG**
- RMSE: **2.15 MPG**

The model explains over **91% of the variation in fuel efficiency**, demonstrating strong predictive performance.

---

## 🔍 Key Findings

- Vehicle **weight** is the most influential factor affecting fuel efficiency.
- Higher **horsepower** and **engine displacement** typically reduce MPG.
- Fuel efficiency improved significantly in newer model years.
- Japanese vehicles generally achieve higher fuel efficiency than their counterparts.

---

## 📈 Power BI Dashboard

A stakeholder-focused Power BI dashboard was developed to:

- Monitor fuel efficiency trends
- Identify key MPG drivers
- Compare regional performance
- Evaluate model accuracy
- Support strategic design decisions

### Dashboard Highlights

✅ Executive KPI Cards

✅ Feature Importance Analysis

✅ MPG vs Weight Relationship

✅ Fuel Efficiency by Region

✅ MPG Trend Over Time

✅ Model Performance Metrics

✅ Business Recommendations

---

## 💼 Business Impact

The solution enables manufacturers to predict fuel efficiency before production, understand design trade-offs, and make evidence-based engineering decisions.

Key benefits include:

- Reduced design and development costs
- Improved fuel economy
- Better regulatory compliance
- Enhanced customer satisfaction
- Stronger competitive advantage

---

## 🛠️ Tech Stack

**Languages & Tools**
- Python
- Power BI

**Libraries**
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- SHAP
- Matplotlib
- Seaborn

---

## 📂 Project Structure

```text
Fuel-Efficiency-Prediction/
│
├── data/
├── notebook/
├── dashboard/
├── report/
├── images/
├── requirements.txt
└── README.md
```

---

## 🚀 Future Improvements

- SHAP Explainability Dashboard
- Streamlit Web Application
- Real-Time Prediction API
- Additional Automotive Datasets
- Advanced Ensemble Models

---

## 👨‍💻 Author

**Rahit Saha**

Data Science & AI Enthusiast
