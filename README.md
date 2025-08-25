# 🏡 House Price Prediction using Linear Regression

This project implements a *Linear Regression Model* to predict house prices based on their *square footage, **number of bedrooms, and **bathrooms*.  
It is part of Task-01 for the ML internship/project.

---

## 📂 Dataset
We are using the *House Prices - Advanced Regression Techniques* dataset from Kaggle:  
🔗 [Dataset Link](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)

---

## ⚙ Tech Stack
- Python
- Pandas, NumPy (data preprocessing)
- Matplotlib, Seaborn (visualization)
- Scikit-Learn (model training and evaluation)

---

## 🚀 Project Workflow
1. *Data Preprocessing*
   - Load dataset
   - Select features: square footage, bedrooms, bathrooms
   - Handle missing values

2. *Exploratory Data Analysis (EDA)*
   - Correlation between features and price
   - Distribution plots

3. *Model Training*
   - Train Linear Regression model
   - Split data into train & test sets
   - Evaluate using R² Score & RMSE

4. *Prediction*
   - Predict house price given square footage, bedrooms, bathrooms

---

## 📊 Results
- The model learns the relationship between house features and price.
- Provides predictions for unseen house data.

---

## ▶ How to Run
```bash
# Clone repo
git clone https://github.com/your-username/house-price-prediction-linear-regression.git

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook HousePricePrediction.ipynb
