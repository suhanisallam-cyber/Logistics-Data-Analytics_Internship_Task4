# Predictive Modeling & Logistics Optimization

## 📌 Project Overview

This project focuses on building a predictive machine learning framework for forecasting last-mile delivery delays
and supporting operational decision-making in logistics.

The project uses supervised regression models to predict continuous delivery delay in hours and demonstrates how machine 
learning predictions can be converted into practical logistics optimization strategies.

This project was completed as the **Week 4 Internship Assignment – Predictive Modeling**.

## 🎯 Project Objectives

- Build a machine learning model to predict delivery delays.
- Identify the major factors influencing shipment delays.
- Compare multiple regression algorithms.
- Evaluate model performance using RMSE, MAE, and R².
- Perform hyperparameter tuning using GridSearchCV.
- Identify important operational features.
- Convert model predictions into logistics optimization strategies.
- Develop an implementation roadmap for predictive logistics systems.

## 🛠️ Technologies & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn

### Machine Learning Techniques

- Multiple Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- StandardScaler
- GridSearchCV
- Train-Test Split
- 5-Fold Cross-Validation


## 🔍 Data & Target Generation

The synthetic dataset was designed to represent real-world logistics conditions including:

- Traffic congestion
- Weather disturbances
- Driver experience
- Warehouse processing constraints
- Shipment distance
- Order volume

## 🤖 Model Development

Three regression algorithms were evaluated:

### 1. Multiple Linear Regression

Used as the baseline model because of its interpretability and simple linear relationship between features and delivery delay.

### 2. Random Forest Regressor

An ensemble learning algorithm capable of capturing interactions and non-linear relationships between variables.

### 3. Gradient Boosting Regressor

A boosting-based model that sequentially improves predictions by minimizing residual errors.

Hyperparameter tuning was performed for the Gradient Boosting model using `GridSearchCV` with 5-fold cross-validation. 

Traffic density and warehouse processing lag together contributed more than 65% of the overall feature importance. 

## ⚙️ Logistics Optimization Strategies

The predictive model can be connected to a Transportation Management System (TMS) to trigger automated operational actions.

When predicted delay exceeds **1.5 hours**, the proposed framework triggers optimization responses:

### 1. Dynamic Corridor Re-Routing

High traffic conditions can trigger alternative routes to help avoid congestion before dispatch.

### 2. Priority Pre-Staging

High predicted warehouse staging delays can trigger warehouse alerts and prioritize cross-docking activities.

### 3. Risk-Based Driver Allocation

Shipments affected by severe weather can be assigned to more experienced drivers.

### 4. Automated SLA Notification

Customers can receive updated estimated arrival times when predicted delays change.



##  Skills Demonstrated
- Python
- Pandas
- NumPy
- Machine Learning
- Predictive Modeling
- Regression
- Feature Engineering
- Model Evaluation
- Hyperparameter Tuning
- GridSearchCV
- Cross-Validation
- Feature Importance Analysis
- Logistics Analytics
- Supply Chain Analytics
- Operational Optimization

## 📄 Project Report

[View Detailed Project Report](Week%204%20Task_%20Predictive%20Modeling%20and%20Optimization%20in%20Logistics%20Systems.pdf)

## 👩‍💻 Author

**Suhani Sallam**

B.Tech IT | Aspiring Data Analyst & SQL Developer
