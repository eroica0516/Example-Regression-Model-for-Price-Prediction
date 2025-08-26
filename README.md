
# 📊 Fruit & Vegetable Price Forecasting (UK 2017–2022)

Welcome to the **Data Science Portfolio** project, which demonstrates a step-by-step approach to building a predictive model using UK fruit and vegetable price data from Kaggle.

## 🔍 Project Overview

This project aims to forecast average yearly prices for various fruits and vegetables using historical data (2017–2022). It employs a linear regression model and visual analytics to support decision-making in cost control for catering businesses.

📁 Dataset: [Kaggle - Fruit and Vegetable Prices UK](https://www.kaggle.com/datasets/datota/fruit-and-vegatablefrastructure)

- **Python & Pandas** for data manipulation
- **kagglehub** for automated dataset import
- **Matplotlib & Seaborn** for visualisation
- **Scikit-learn** for model training and evaluation

## ⚙️ Data Engineering
- Converted date column to datetime format
- Extracted year and grouped data by item/year
- Calculated average prices and handled missing values using forward fill
- Applied one-hot encoding to item names for regression modeling

## 📈 Visualisations

### 1. Multi-line Chart
Displays price trends and predictions for each item from 2017 to 2023 (predicted).
<img width="602" height="172" alt="Plot1" src="https://github.com/user-attachments/assets/b68a3646-1cf7-4843-856b-1cea09f96f10" />

### 2. Regression Line Plot
Shows historical data and fitted regression lines for selected items.(/assets/img/Plot1.png)
<img width="627" height="416" alt="Plot2" src="https://github.com/user-attachments/assets/412c67fe-d16d-43fd-9c94-5df82a6c7d82" />

## 📊 Model Performance

- **Model Type:** Linear Regression
- **Train/Test Split:** 80/20
- **Mean Squared Error (MSE):** 0.355
- **R-squared (R²):** 0.933

These metrics indicate strong predictive performance and a good fit for the data.

## ⚠️ Limitations & Future Work

- Linear regression may not capture seasonality or complex dynamics.
- Future enhancements could include:
  - Time series models (ARIMA, Prophet)
  - External features (weather, economic indicators)

## 🧠 Ethical & Legal Considerations

- Ensure dataset usage complies with Kaggle's license
- Be transparent about model limitations and biases
- Consider regulatory implications for commercial use

## 👤 Author

This project is anonymized for academic assessment.  
Published under the name: **Data Science Portfolio**

---

📬 For inquiries or feedback, feel free to open an issue or contact via the GitHub portfolio page.
