# BlackFriday-Sales-Prediction


## 📌 Overview

This project focuses on analyzing and predicting customer purchase behavior during Black Friday sales using regression models. It covers the complete data science pipeline—from data cleaning and feature engineering to modeling and insights.

## 🎯 Objectives
Predict purchase amount using demographic and product features
Analyze spending patterns across age, gender, and city
Improve model performance using feature engineering and regression techniques


## 📊 Dataset
Train Dataset: ~550,000 rows
Test Dataset: ~233,000 rows
Features include:
User demographics (Age, Gender, Occupation, Marital Status)
City information
Product categories
Purchase amount (target variable)


## ⚙️ Project Pipeline
### 1️⃣ Data Cleaning
Handled missing values in product categories
Converted categorical variables to numeric
Transformed age groups into numerical values
### 2️⃣ Feature Engineering

Created meaningful features such as:

user_avg_purchase → Average spending per user
prod_avg_purchase → Average purchase per product
prod_purchase_count → Product popularity
age_gender → Interaction feature
city_age → Location-based interaction
total_categories → Number of categories per product
Category-level averages
### 3️⃣ Exploratory Data Analysis (EDA)

Key visualizations:

Purchase distribution
Gender vs Purchase
Age vs Spending
City category analysis
### 4️⃣ Modeling

Implemented the following models:

Linear Regression
Ridge Regression
Polynomial Regression (degree=2)
### 5️⃣ Model Optimization

Used:

StandardScaler for normalization
Polynomial Features for non-linearity
GridSearchCV for hyperparameter tuning


## 📈 Model Performance
Model	RMSE
Linear Regression	~2567
Ridge Regression	~2567
Polynomial Regression	~2537
Polynomial + Ridge (Tuned)	~2520–2535 ✅


## 🧠 Key Insights
💼 Age group 26–35 contributes the highest spending
👨 Male customers tend to spend more than female customers
🏙️ Customers from urban cities (B & C) spend more
🛍️ Certain product categories dominate revenue
🔁 Repeat buyers (high user_avg_purchase) are key revenue drivers


## 💡 Business Impact
Target high-spending age groups for marketing campaigns
Focus on popular product categories for promotions
Personalize recommendations based on user behavior
Optimize pricing strategies using product-level insights





