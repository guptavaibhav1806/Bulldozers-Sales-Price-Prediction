# 🏗️ Bulldozer Price Prediction

This project predicts the sale price of used bulldozers using historical auction data from the **Blue Book for Bulldozers** dataset (Kaggle). The goal is to build a regression model that can estimate future prices based on machine features.

## 📦 Dataset

- Dataset: [Kaggle - Blue Book for Bulldozers](https://www.kaggle.com/competitions/bluebook-for-bulldozers)
- Features include:
  - Sale date, machine model, usage hours, product group, and more.
  - Target variable: `SalePrice` (adjusted for inflation).

## 📊 Workflow Overview

1. **Data Exploration**  
   - Understanding dataset structure  
   - Visualizing missing values and feature types

2. **Data Cleaning & Feature Engineering**  
   - Parsing date features  
   - Handling missing values  
   - Converting categorical variables  
   - Feature selection

3. **Model Training**  
   - Used `RandomForestRegressor`  
   - Model trained with time-based validation split

4. **Evaluation Metrics**  
   - R² Score  
   - Mean Absolute Error (MAE)  
   - Root Mean Squared Log Error (RMSLE)



