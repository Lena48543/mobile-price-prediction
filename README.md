📱 Mobile Price Prediction Using Random Forest
👩‍💻 Author

Olena Hrytsyk
Data & Business Analyst | Excel • SQL • Python • Power BI

📌 Project Overview

This project analyzes a dataset of mobile phones (2014–2025) to predict smartphone launch prices in the USA using Random Forest Regression.

The goal was to:

Identify key factors influencing smartphone prices

Build a predictive model

Evaluate model performance

Interpret feature importance

📊 Dataset

Source: Kaggle – Mobiles Dataset (2025)

Features include:

RAM

Battery Capacity

Screen Size

Mobile Weight

Processor

Brand

Launch Year

USA Launch Price (target)

🔎 Exploratory Data Analysis (EDA)

Key insights:

Strong correlation between screen size, weight, and battery capacity

Right-skewed price distribution (budget phones dominate)

Positive relationship between RAM and price

Brand significantly influences pricing

Battery capacity increases over time

🤖 Model

Model Used: Random Forest Regressor

Why Random Forest?

Handles non-linear relationships

Works well with mixed data types

Robust to outliers

Train/Test Split:

80% Training

20% Testing

📈 Model Performance

R² Score: 0.84

MAE: $105.78

The model explains 84% of price variation and predicts within ~$106 on average.

Most accurate for:

Budget & mid-range phones

Less accurate for:

Premium devices ($1500+)

🔍 Feature Importance

Top predictors:

RAM

Battery Capacity

Screen Size

Brand

🛠 Tools Used

Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)

Jupyter Notebook

Random Forest Regression

Data Cleaning & Feature Engineering

📚 Key Skills Demonstrated

Data Cleaning & Preprocessing

Feature Engineering

Exploratory Data Analysis

Machine Learning (Regression)

Model Evaluation

Business Insight Interpretation

🚀 Next Improvements

Address price imbalance

Add cross-validation

Try Gradient Boosting models

Deploy as a simple web app
