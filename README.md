# REGRESSION-PROJECT
# 🚕 NYC Taxi Trip Time Prediction

## 📘 Overview
This project focuses on predicting the **trip duration of NYC taxi rides** using **machine learning models**.  
The goal is to understand the factors influencing trip duration and to build a predictive model that helps improve route efficiency and travel time estimation.

---

## 🎯 Objectives
- Perform **Exploratory Data Analysis (EDA)** on NYC Taxi dataset.  
- Understand how trip distance, pickup/dropoff locations, and time factors affect duration.  
- Build and evaluate machine learning models for **trip time prediction**.  
- Visualize key insights through data plots and correlation analysis.

---

## 🧰 Tools & Technologies Used
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Algorithms:** Linear Regression, Random Forest, XGBoost  
- **Visualization:** Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook / Google Colab  
- **Dataset Source:** NYC Taxi Trip Records (Kaggle / NYC Open Data)

---

## 🔍 Steps Performed
1. **Data Cleaning**
   - Removed null values, duplicates, and incorrect coordinates.  
   - Converted datetime fields and extracted features like hour, weekday, and month.  

2. **Exploratory Data Analysis (EDA)**
   - Analyzed trip duration distribution, pickup/dropoff density, and outliers.  
   - Identified correlations between trip distance, passenger count, and time duration.  

3. **Feature Engineering**
   - Created new features: `trip_distance_km`, `pickup_hour`, `pickup_day`, `is_weekend`.  
   - Scaled continuous variables using `StandardScaler`.

4. **Model Building**
   - Trained multiple models:
     - Linear Regression  
     - Random Forest Regressor  
     - XGBoost Regressor  

5. **Model Evaluation**
   - Compared model performance using metrics:
     - MAE (Mean Absolute Error)  
     - RMSE (Root Mean Squared Error)  
     - R² Score  

6. **Visualization**
   - Distribution of trip duration  
   - Correlation heatmap  
   - Feature importance plot  

---

## 📊 Key Insights
- Trip duration increases linearly with **distance**, but also depends on **pickup hour** and **traffic conditions**.  
- **Rush hours (8–10 AM and 5–7 PM)** show the highest average durations.  
- **Random Forest** achieved the best accuracy with low RMSE and high R² score.  

---

## 📈 Model Performance Summary
| Model | MAE | RMSE | R² Score |
|-------|------|------|-----------|
| Linear Regression | 2.45 | 3.80 | 0.68 |
| Random Forest | 1.95 | 3.10 | 0.81 |
| XGBoost | 1.88 | 3.05 | 0.83 |

