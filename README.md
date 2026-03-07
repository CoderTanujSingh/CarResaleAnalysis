# **🚗 Car Resale Price Prediction — Machine Learning Pipeline**

An end-to-end Machine Learning project that predicts the resale price of used cars using real-world vehicle listing data.

This project demonstrates how raw, messy marketplace data can be transformed into a production-ready ML pipeline using Python and Scikit-learn.

📊 Dataset Size: 17,000+ car listings

🎯 Problem Type: Regression

📉 Model Accuracy: R² = 0.87

# 📊 Project Overview

Used car marketplaces contain messy and inconsistent data, such as:

₹ 5.45 Lakh

40,000 Kms

1197 cc

83.1 bhp

21.4 kmpl

Before training a machine learning model, these values must be cleaned, structured, and transformed.

This project focuses on:

✔ Data cleaning

✔ Feature engineering

✔ ML pipeline creation

✔ Model training & evaluation

✔ Model persistence using joblib


# 🧠 Machine Learning Pipeline

<img width="768" height="512" alt="Car Resale Price Prediction layout" src="https://github.com/user-attachments/assets/9153f94a-a05f-4a04-a37c-4742c216ccab" />



This pipeline ensures reproducibility and no data leakage.

# ⚙️ Features Used

<img width="768" height="512" alt="Car Resale features Infrographics" src="https://github.com/user-attachments/assets/cf32abb0-16ed-419a-ac27-1e17515a0985" />



# 📈 Model Used
RandomForestRegressor

Why Random Forest?

✔ Handles nonlinear relationships

✔ Works well with structured tabular data

✔ Robust against outliers

📊 Model Performance

Metric	Score

MAE	~114K

RMSE	~349K

R² Score	0.87

📌 The model explains 87% of the variance in resale prices.

# 📉 Prediction Visualisation

Actual vs Predicted Car Prices

Scatter Plot:
Actual Price vs Predicted Price

This helps evaluate how close model predictions are to real car prices.

# 🛠 Tech Stack

<img width="768" height="512" alt="tech used" src="https://github.com/user-attachments/assets/148e8e76-12fc-4245-b973-b439af428fe1" />


# 💾 Model Saving

The entire ML pipeline is saved using:

joblib

joblib.dump(model_pipeline,"car_price_pipeline.pkl")

This saves:

✔ preprocessing

✔ encoding

✔ trained model

So predictions can be made directly on new data.

## Power BI Dashboard

A Power BI dashboard was created to analyse the used car market using the cleaned dataset.

The dashboard provides insights into:

• Brand-wise resale price trends  

• Fuel type price comparison  

• Mileage vs price relationships  

• City-wise market differences  

• Interactive filtering for deeper exploration

<img width="712" height="400" alt="image" src="https://github.com/user-attachments/assets/28a49cba-44ee-415a-8144-6a1a3995627e" />


# 🔮 Future Improvements

Possible upgrades:

Hyperparameter tuning (GridSearchCV)

Feature importance analysis

XGBoost / LightGBM models

Streamlit prediction web app

API deployment (FastAPI)


# 📌 Key Learning

This project highlights the importance of:

✔ Data preprocessing

✔ Feature engineering

✔ ML pipelines

✔ Model evaluation


Real-world ML success depends more on clean data pipelines than complex algorithms.

# 👨‍💻 Author

**Tanuj Singh**

Data Analyst | Machine Learning Enthusiast | Python Developer

⭐ If you like this project

Give the repo a ⭐ and connect with me on LinkedIn.

https://www.linkedin.com/in/tanuj-singh-coder/
