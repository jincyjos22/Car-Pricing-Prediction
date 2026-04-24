# 🚗 Car Price Prediction using Machine Learning

## 📌 Problem Statement

A Chinese automobile company plans to enter the US market and wants to understand the factors affecting car prices. The goal is to identify key variables influencing pricing and build a model to predict car prices accurately.

---

## 🎯 Business Goal

The objective is to model car prices based on various features so that the company can understand pricing dynamics and make informed decisions regarding product design and market strategy.

---

## 📊 Dataset

The dataset contains various features of cars such as:

* Engine size
* Horsepower
* Fuel type
* Car body type
* Brand
* Price (Target variable)

---

## ⚙️ Project Workflow

### 1. Data Preprocessing

* Removed unnecessary column (`car_ID`)
* Extracted car brand from `CarName`
* Encoded categorical variables using Label Encoding
* Prepared the dataset for machine learning models

---

### 2. Exploratory Data Analysis (EDA)

Visualizations were used to understand:

* Distribution of car prices
* Relationship between engine size and price
* Price variation across brands
* Correlation between features

---

### 3. Models Implemented

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor ⭐
* Gradient Boosting Regressor
* Support Vector Regressor (SVR)

---

### 4. Model Evaluation

Models were evaluated using:

* R² Score
* Mean Squared Error (MSE)
* Mean Absolute Error (MAE)

---

## 🏆 Best Model

The **Random Forest Regressor** performed the best based on evaluation metrics.

### Why?

* Captures complex non-linear relationships
* Reduces overfitting using ensemble learning
* Provides better generalization on unseen data

---

## 🔍 Feature Importance

Top factors affecting car price:

* Engine Size
* Horsepower
* Curb Weight
* Car Width

These features have the strongest influence on pricing.

---

## ⚙️ Hyperparameter Tuning

* Used GridSearchCV to optimize Random Forest parameters
* Improved model performance and generalization

---

## 📈 Results

* Ensemble models outperformed simpler models
* The tuned model achieved improved performance
* The model effectively predicts car prices

---

## 💡 Key Insights

* Engine size and horsepower strongly influence car price
* Premium brands have higher average prices
* Heavier vehicles tend to be more expensive

---

## 📁 Project Structure

car-price-prediction/
├── CarPrice_Assignment.csv


├── car_price_model.ipynb / .py


├── README.md

---


## 🏁 Conclusion

This project helps understand the key factors influencing car prices and provides a reliable model for predicting prices in a new market.

---
