# 🚗 Car Price Prediction

## 📌 Problem Statement

The car market is dynamic, and accurately estimating a car's price is essential for both buyers and sellers. Various features such as brand, engine capacity, mileage, and fuel type impact the pricing of a car. Incorrect pricing can lead to poor customer satisfaction and revenue losses.

This project aims to predict the selling price of used cars based on multiple input features using machine learning algorithms.

---

## 🎯 Objectives

- Perform Exploratory Data Analysis (EDA) to understand the distribution of variables.
- Preprocess the dataset to handle missing values and encode categorical features.
- Build regression models to predict car prices based on various input features.
- Evaluate model performance using suitable regression metrics.
- Identify the most influential features impacting the price.

---

## 🎯 Aim

To build a robust machine learning model that can predict the price of a car based on features such as age, brand, fuel type, kilometers driven, and other specifications.

---

## 📚 Dataset Description

The dataset includes the following features:

- **Car_Name**: Name of the car
- **Year**: Year of manufacture
- **Selling_Price**: Price at which the car is being sold (target)
- **Present_Price**: Current price of the car (in lakhs)
- **Kms_Driven**: Total kilometers driven
- **Fuel_Type**: Fuel type of the car (Petrol, Diesel, CNG)
- **Seller_Type**: Dealer or Individual
- **Transmission**: Manual or Automatic
- **Owner**: Number of previous owners

---

## 🧪 Exploratory Data Analysis (EDA)

- Analyzed correlations between features and target variable
- Visualized distributions using histograms, scatter plots, and box plots
- Compared prices across fuel types, transmission types, and seller types

---

## 🧼 Data Preprocessing

- Converted year to car age
- Dropped irrelevant columns like `Car_Name`
- Label encoded categorical features (`Fuel_Type`, `Seller_Type`, `Transmission`)
- Scaled numerical features where necessary
- Split data into training and testing sets (typically 80-20)

---

## 🤖 Machine Learning Models Used

- **Linear Regression**
- **Lasso Regression**
- **Ridge Regression**
- **Random Forest Regressor**
- **Decision Tree Regressor**
- **XGBoost Regressor** (if included)

---

## ✅ Model Evaluation

Evaluation metrics used:

- **R² Score**
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**

| Model                | R² Score |
|---------------------|----------|
| Linear Regression   | ~84%     |
| Decision Tree       | ~89%     |
| Random Forest       | **~92%** ✅ |
| XGBoost             | ~91%     |

🏆 **Best Model**: **Random Forest Regressor** with approximately **92% R² Score**

---

## 📈 Visualizations

- Feature importance from tree-based models
- Price trends by age, fuel type, and transmission
- Error residual plots

---

## 🔧 Tools & Libraries

- Python (Jupyter Notebook)
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- XGBoost (optional)

---

## 📁 Project Structure

