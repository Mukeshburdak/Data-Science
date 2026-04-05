# 📊 Quality of Life Prediction using Machine Learning
## 🚀 Project Overview

This project analyzes how daily lifestyle habits such as work hours, sleep, rest, and exercise impact human lifespan. Using regression-based machine learning models, we predict age at death and evaluate how different models handle overfitting and underfitting.

## 🎯 Objectives
- Analyze lifestyle factors affecting lifespan
- Build multiple regression models
- Compare model performance
- Detect overfitting and underfitting
- Visualize results using graphs
## 📁 Dataset Description

The dataset contains information about individuals and their daily habits:

| Feature                      | Description                     |
| ---------------------------- | ------------------------------- |
| `gender`                     | Male/Female                     |
| `occupation_type`            | Type of work (Active/Sedentary) |
| `avg_work_hours_per_day`     | Daily working hours             |
| `avg_rest_hours_per_day`     | Daily rest hours                |
| `avg_sleep_hours_per_day`    | Daily sleep duration            |
| `avg_exercise_hours_per_day` | Daily exercise time             |
| `age_at_death`               | Target variable (lifespan)      |

## 🧠 Machine Learning Models Used
🔹 Linear Regression (Baseline model)

🔹 Ridge Regression (L2 Regularization)

🔹 Lasso Regression (L1 Regularization)

🔹 ElasticNet (Combination of L1 + L2)
## ⚙️ Workflow
- Data Loading & Preprocessing
- Handling Categorical Variables (One-Hot Encoding)
- Feature Scaling (StandardScaler)
- Train-Test Split
- Model Training
- Performance Evaluation
- Visualization
## 📊 Performance Metrics

We evaluate models using:

✅ R² Score → Measures accuracy of regression

📉 RMSE (Root Mean Squared Error) → Penalizes large errors

📉 MAE (Mean Absolute Error) → Average prediction error

📈 Visualizations

- Train vs Test R² comparison
- RMSE comparison across models
- MAE comparison across models

These graphs help identify:

- Overfitting (High train, low test performance)
- Underfitting (Low train and test performance)

## 🔍 Key Insights
- Balanced sleep and exercise positively impact lifespan
- Excessive work hours may reduce lifespan
- Regularization models reduce overfitting
- ElasticNet provides the best balance between bias and variance
## 🧪 Overfitting vs Underfitting
- Scenario	Observation
- Overfitting	High Train R², Low Test R²
- Underfitting	Low Train R², Low Test R²
- Good Fit	Train ≈ Test R²
## 🛠️ Tech Stack
- Python 🐍
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn
  
---
