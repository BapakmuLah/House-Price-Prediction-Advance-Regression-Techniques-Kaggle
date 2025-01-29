## 🏡 House Price Prediction with Stacking Regressor and Advanced Feature Engineering 📊


## 🔍 Overview
This project predicts house prices using a **Stacking Regressor** model, combining multiple base models like **Lasso**, **Ridge**, **GBM**, **LGBM**, **XGBoost**, and **CatBoost**. The model was optimized through **advanced feature engineering**, **hyperparameter tuning**, and **model evaluation**.


## Features
1. **Exploratory Data Analysis (EDA)**: Analyzed missing values, feature distributions, and correlations.
2. **Feature Engineering**: Handled missing values, dropped irrelevant columns, PCA for multicollinearity, and applied transformations using Yeo-Johnson and One-Hot Encoding.
3. **Modeling**: Used **LazyPredict** for quick model identification and **Optuna** for hyperparameter tuning.
4. **Stacking Regressor**: Final model combines linear and non-linear models to achieve optimal performance.

## 📊 Evaluation Metrics
- RMSLE: 0.11987 ✅
- RMSE: 13,326.51 ✅

## Installation

### Prerequisites
- Python 3.9 or above
- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Missingno, LazyPredict, Optuna, LightGBM, XGBoost, CatBoost.

### Step 1: Clone the repository
```bash
git clone https://github.com/your-username/house-price-prediction.git
cd house-price-prediction
```
### Step 2: Install dependencies
```
pip install -r requirements.txt
```
### Step 3: Run it!
<br>

## 🤝 Contribution
Contributions are welcome! Feel free to open issues, fork the repo, or submit pull requests 💡
