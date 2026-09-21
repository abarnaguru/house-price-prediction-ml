# 🏠 House Price Prediction Using Machine Learning

## 📌 Project Overview

This project uses Machine Learning to predict house prices based on property characteristics such as living area, bedrooms, bathrooms, lot size, condition, and year built.

The project follows an end-to-end Data Science workflow:

**Data Collection → Data Cleaning → Exploratory Data Analysis → Feature Selection → Model Training → Model Evaluation → Price Prediction**

## 🎯 Objective

The objective of this project is to build a Machine Learning regression model that can estimate house prices from property-related features.

## 📊 Dataset

The dataset was obtained from Kaggle.

- Original records: 4,600
- Records after cleaning: 4,551
- Target variable: `price`
- Missing values: None
- Duplicate rows: None
- Invalid zero-price records removed: 49

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- GitHub

## 🤖 Machine Learning Model

A Random Forest Regressor was used for house price prediction.

A logarithmic transformation was applied to the target variable to reduce the influence of extreme price values.

## 📈 Model Performance

| Metric | Result |
|---|---:|
| MAE | $156,883.99 |
| RMSE | $263,992.24 |
| R² Score | 0.5315 |

Among the approaches tested, the log-target Random Forest provided the strongest overall combination of R² and RMSE.

## 🔎 Important Features

The model identified the following features as the most important:

1. `sqft_living` — 51.78%
2. `sqft_lot` — 12.79%
3. `yr_built` — 12.19%
4. `sqft_above` — 6.40%
5. `bathrooms` — 3.85%

## 🔮 Sample Prediction

For a sample house with:

- 2,000 sq ft living area
- 3 bedrooms
- 2.5 bathrooms
- 2 floors
- 5,000 sq ft lot
- Built in 2005

the model predicted:

**$373,524.96**

## 📂 Project Files

- `House_Price_Prediction_Machine_Learning.ipynb` — Complete analysis and Machine Learning notebook
- `README.md` — Project documentation

## 🚀 Future Improvements

- Hyperparameter tuning
- Cross-validation
- Additional regression algorithms
- Advanced feature engineering
- More detailed location-based features
- Model deployment as a web application

## ⚠️ Disclaimer

This project is intended for educational and portfolio purposes. The model should not be considered a professional property valuation system.
