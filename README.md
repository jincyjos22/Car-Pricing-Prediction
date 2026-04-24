# 🚗 Car Price Prediction using Machine Learning

## 📌 Project Overview

This project aims to analyze the factors affecting car prices in the US market and build machine learning models to predict car prices accurately.

A Chinese automobile company plans to enter the US market and wants to understand:

* Which variables significantly affect car prices
* How different features influence pricing
* How to optimize design and pricing strategy

---

## 🎯 Objectives

* Perform data preprocessing and feature engineering
* Explore the dataset using visualizations
* Build and compare multiple regression models
* Identify the most important features affecting price
* Improve model performance using hyperparameter tuning

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

* Removed unnecessary columns (`car_ID`)
* Extracted car brand from `CarName`
* Encoded categorical variables using Label Encoding
* Prepared dataset for modeling

---

### 2. Exploratory Data Analysis (EDA)

Visualizations were used to understand:

* Distribution of car prices
* Relationship between engine size and price
* Price variation across brands
* Correlation between features

---

### 3. Models Implemented

The following regression models were used:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor ⭐
* Gradient Boosting Regressor
* Support Vector Regressor (SVR)

---

### 4. Evaluation Metrics

Models were evaluated using:

* R² Score
* Mean Squared Error (MSE)
* Mean Absolute Error (MAE)

---

## 🏆 Best Model

The **Random Forest Regressor** performed the best.

### Why?

* Captures complex non-linear relationships
* Reduces overfitting using ensemble learning
* Provides reliable predictions on unseen data

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

* Models achieved strong predictive performance
* Ensemble models outperformed simple models
* Tuned model showed improved accuracy

---

## 💡 Key Insights

* Larger engine size and higher horsepower increase car price
* Premium brands have significantly higher pricing
* Heavier and wider cars tend to be more expensive

---

## 📁 Project Structure

```
car-price-prediction/
│
├── CarPrice_Assignment.csv
├── car_price_model.ipynb / .py
├── README.md
```

---

## 🏁 Conclusion

This project helps understand car pricing dynamics and supports data-driven decision-making for entering a new market.

---

