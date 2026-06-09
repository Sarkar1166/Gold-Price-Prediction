# 🥇 Gold Price Prediction using Machine Learning

## 📌 Overview

This project develops a machine learning model to predict gold prices using historical market indicators and financial data. The workflow includes data preprocessing, exploratory data analysis (EDA), feature correlation analysis, model training, and performance evaluation using a Random Forest Regressor.

The objective is to understand the relationship between gold prices and various financial factors while building a predictive model capable of estimating future gold prices.

---

## 🚀 Features

* Historical gold price analysis
* Exploratory Data Analysis (EDA)
* Correlation heatmap visualization
* Feature engineering and preprocessing
* Random Forest Regression model
* Gold price prediction on unseen data
* Model performance evaluation using R² Score

---

## 📂 Dataset

The dataset contains historical financial indicators including:

* **Date** – Trading date
* **SPX** – S&P 500 Index
* **USO** – United States Oil Fund
* **SLV** – Silver ETF Prices
* **EUR/USD** – Euro to USD Exchange Rate
* **GLD** – Gold ETF Price (Target Variable)

---

## 🏗️ Project Workflow

### 1. Data Collection

Load and inspect historical gold price data using Pandas.

### 2. Data Preprocessing

* Handle missing values
* Check data types
* Prepare dataset for analysis

### 3. Exploratory Data Analysis

* Statistical summaries
* Distribution analysis
* Correlation analysis
* Feature relationship visualization

### 4. Feature Selection

Input Features:

* SPX
* USO
* SLV
* EUR/USD

Target Variable:

* GLD (Gold Price)

### 5. Model Training

Train a **Random Forest Regressor** using historical market data.

### 6. Model Evaluation

Evaluate prediction performance using:

* R² Score
* Actual vs Predicted Price Comparison

---

## 📊 Results

The model successfully learns relationships between financial indicators and gold prices, producing accurate predictions on unseen test data. Correlation analysis highlights the influence of related market variables on gold price movements.

---

## 🛠️ Tech Stack

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

### Machine Learning

* Random Forest Regressor

---

## 📈 Future Improvements

* Hyperparameter tuning
* Time-series forecasting models
* XGBoost and Gradient Boosting comparison
* Deployment using Streamlit
* Real-time gold price prediction using APIs

---

## 🎯 Learning Outcomes

Through this project, I gained experience in:

* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Feature selection techniques
* Machine Learning model development
* Model evaluation and interpretation
* Financial data analysis using Python

---

## 📜 License

This project is developed for educational and learning purposes.
