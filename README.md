# Bike Sharing Demand Prediction

This project aims to predict the number of bike-sharing users on a daily basis using various environmental and seasonal features.

## 🧠 Project Overview

This machine learning project was completed as part of an internship with **Fox Trading** in collaboration with **1Stop.ai**. The objective is to predict the daily count of total rental bikes (casual + registered) using regression techniques.

## 📁 Dataset

The dataset used is publicly available and includes features such as:

- Season  
- Year  
- Month  
- Holiday  
- Working day  
- Weather situation  
- Temperature (Normalized)  
- Feeling Temperature (Normalized)  
- Humidity  
- Windspeed  
- Casual users  
- Registered users  
- Total count of rental bikes (Target Variable)

## ⚙️ Tools & Libraries

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn

## 🧪 Workflow

### 1. Data Preprocessing

- Loaded the dataset and dropped irrelevant features.  
- Visualized correlations.  
- Checked for null values.  
- Split the dataset into input features and target variable.

### 2. Data Splitting

- Divided into training and testing sets (80/20 split).

### 3. Model Building

Implemented various regression models:

- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- K-Nearest Neighbors Regressor  
- XGBoost Regressor

### 4. Evaluation Metrics

Used the following metrics to evaluate model performance:

- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  
- Root Mean Squared Error (RMSE)  
- R² Score

### 5. Performance Comparison

Compared model performance using the above metrics to identify the best-fit model.

## 📊 Results

- The **XGBoost Regressor** performed best among the tested models in terms of accuracy and lower error metrics.

## 📌 Conclusion

This project demonstrates a regression-based approach to forecast bike rental demand, which can help optimize bike distribution and inventory planning for bike-sharing systems.
