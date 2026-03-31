# 🚗 Car Selling Price Prediction Model

## 📌 Overview
This project is an end-to-end Machine Learning pipeline that predicts the selling price of used cars. It utilizes a **Random Forest Regressor** to analyze various vehicle features such as age, original showroom price, kilometers driven, and transmission type to provide highly accurate price estimates.

## 📊 Model Performance
The model was evaluated on a testing set and achieved excellent accuracy, capturing the vast majority of the variance in used car pricing:
* **R-squared (R²):** 0.9623 (96.2% accuracy in explaining price variance)
* **Mean Absolute Error (MAE):** 0.61 (Predictions are off by an average of just ~0.61 Lakhs)
* **Root Mean Squared Error (RMSE):** 0.93

## 🧠 Feature Importance
Through feature importance analysis, the model identified the following as the primary drivers of a car's resale value:
1. **Present/Showroom Price** (Heaviest weight)
2. **Vehicle Age (Years of Service)**
3. **Kilometers Driven**
*(Secondary factors included Fuel Type and Transmission)*

## 🛠️ Tech Stack
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (RandomForestRegressor, ColumnTransformer, Pipelines)
* **Visualization:** Matplotlib, Seaborn
* **Model Serialization:** Joblib

## 🚀 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/car-price-prediction.git](https://github.com/YOUR_USERNAME/car-price-prediction.git)
   cd car-price-prediction
