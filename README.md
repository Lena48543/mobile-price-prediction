# Mobile Phone Price Prediction 📱 
Random Forest Regression | Machine Learning Project

Author: Olena Hrytsyk

## 📌 Project Overview

This project analyzes a dataset of mobile phones (2014–2025) to predict smartphone launch prices in the USA using Random Forest Regression.

The primary objectives were to:

- Identify key factors influencing smartphone prices

- Perform exploratory data analysis (EDA)

- Build and evaluate a machine learning model

- Interpret feature importance

- Translate findings into business insights

## 📊 Dataset

Source: Kaggle – Mobiles Dataset (2025)
https://www.kaggle.com/datasets/abdulmalik1518/mobiles-dataset-2025

## Features Used
- Company Name: The brand or manufacturer of the mobile phone.
- Model Name: The specific model of smartphone.
- Mobile Weight: The weight of the mobile phone (in grams).
-	RAM: The amount of Random Access Memory (RAM) in the device (in GB).
-	Front Camera: The resolution of the front (selfie) camera (in MP).
-	Back Camera: The resolution of the primary rear camera (in MP).
-	Processor: The chipset or processor used in the device.
-	Battery Capacity: The battery size of the smartphone (in mAh).
-	Screen Size: The display size of the smartphone (in inches).
-	Launched Price: (Pakistan, India, China, USA, Dubai): The official launch price of the mobile in the respective country at the time of its release. Prices vary based on the year the mobile was launched.
-	Launched Year: The year the mobile phone was officially launched.

## 🧹 Data Cleaning & Preprocessing

Converted textual specifications to numeric format

Cleaned currency formatting (e.g., "USD 396,22")

One-hot encoded categorical features (Brand, Processor)

Removed missing and inconsistent rows

Addressed multicollinearity considerations

## 🔎 Exploratory Data Analysis (EDA)

Key insights discovered:

📈 Strong positive correlation between screen size, battery capacity, and weight

💰 Right-skewed price distribution (budget phones dominate the market)

📊 RAM shows a strong positive relationship with price

🏷 Brand significantly influences pricing strategy

🔋 Battery capacity has steadily increased over time

These findings guided feature selection and model choice.

## 🤖 Model Development

Model Used: Random Forest Regressor

Why Random Forest?

Handles non-linear relationships

Works well with mixed numeric & categorical data

Robust to outliers

No scaling required

Data Split

80% Training

20% Testing

## 📈 Model Performance
### Metric	Result
R² Score	0.84
MAE	$105.78
Interpretation

The model explains 84% of price variation

Average prediction error is approximately $106

Most accurate for budget and mid-range phones

Less accurate for high-end premium devices ($1500+)

## 🔍 Feature Importance

Top predictors of price:

- RAM

- Battery Capacity

- Screen Size

- Brand

These results align with real-world smartphone pricing trends.

## 🛠 Technologies Used ![PythonPoweredGIF](https://github.com/user-attachments/assets/9b1124da-d874-4c69-83f4-f3beced75324)


Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

## 📚 Skills Demonstrated

Data Cleaning & Feature Engineering

Exploratory Data Analysis

Machine Learning (Regression)

Model Evaluation & Interpretation

Business Insight Communication

## 🚀 Future Improvements

Apply cross-validation

Address class imbalance in high-price range

Compare with Gradient Boosting models

Deploy model as a simple web app

## 📎 Project Structure
mobile-price-prediction

💠AnalysisProjectHrytsyk.ipynb

💠 README.md
