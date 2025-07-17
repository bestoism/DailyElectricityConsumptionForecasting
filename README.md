# ⚡ Daily Electricity Consumption Forecasting

## 📝 Project Overview
This repository contains a comprehensive data science project focused on forecasting daily electricity consumption. The primary goal is to build a robust machine learning model that predicts energy demand based on historical weather data and temporal features.

This project was developed as part of the **Data Science Academy COMPFEST 17 Selection Process**.

The solution includes:
- Deep exploratory data analysis (EDA)
- Systematic feature engineering
- Model training with **LightGBM Regressor**
- Rigorous validation

The final model demonstrates high accuracy, supporting efficient grid management, cost optimization, and long-term capacity planning.

---

## ✨ Key Features
- **In-depth Exploratory Data Analysis (EDA):** Visual exploration to uncover temporal patterns, seasonal trends, and the influence of weather on energy consumption.
- **Advanced Feature Engineering:** Extraction of time-based features (year, month, day of week, week of year) to capture cyclical behavior.
- **High-Performance Modeling:** Leveraging **LightGBM Regressor**, a fast and accurate gradient boosting model for tabular data.
- **Rigorous Validation:** Using a hold-out validation set and calculating **Root Mean Squared Error (RMSE)** to ensure generalization.
- **Clear & Structured Code:** Organized in a Jupyter Notebook with a logical workflow from data loading to final prediction.

---

## 📊 Business & Technical Insights
1. **Urgency of Forecasting:** Daily forecasting is crucial for real-time grid balancing, reducing operational costs by minimizing reliance on expensive peaker plants, and informing long-term capacity planning.
2. **Climate Identification:** Seasonal consumption patterns (with dual peaks in winter and summer) suggest the dataset originates from a **4-season climate region**, not a tropical region.
3. **Model Performance:** The model achieves a **Validation RMSE of 23.5088**, reflecting strong predictive accuracy without overfitting.
4. **Feature Importance:** Time-based features and cluster identifiers significantly boost model performance.
5. **Cross-Cluster Analysis:** Reveals substantial disparities in energy consumption across clusters, with `cluster_4` consuming over 3 times more than `cluster_1`. This indicates the necessity of a cluster-aware modeling approach.

---

## 🚀 How to Run This Project

### ✅ Prerequisites
- Python 3.8+
- Jupyter Notebook or Google Colab
- Required libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `lightgbm`
  - `matplotlib`
  - `seaborn`
