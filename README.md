# 📊 Sales Forecasting with Linear Regression

## 📁 Project Overview

This project is part of the **RISE Internship - Data Science & Analytics Program** by Jamizan Skills. The goal is to implement a **linear regression model** to forecast future sales based on historical sales data.

## 🧠 Problem Statement

Businesses often struggle to estimate future sales performance. This project aims to solve that challenge using a predictive regression model trained on past sales data.

## 🎯 Objective

To develop a machine learning model using **Linear Regression** that accurately predicts future sales by analyzing historical sales patterns.

## 📋 Requirements

The project meets the following criteria:

- ✅ Use a CSV file containing fields: `Date`, `Product`, `Quantity`, and `Revenue`
- ✅ Data preprocessing including:
  - Handling null values
  - Converting dates and cleaning data
- ✅ Apply **Linear Regression** using scikit-learn
- ✅ Visualize:
  - Actual vs Predicted sales using scatter plots
  - Sales trends over time

## 🧾 Dataset Structure

The CSV dataset used includes:

| Column Name | Description               |
|-------------|---------------------------|
| Date        | Date of the sale          |
| Product     | Product sold              |
| Quantity    | Number of units sold      |
| Revenue     | Total revenue generated   |

## ⚙️ Technologies Used

- Python 🐍
- Pandas 🧾
- NumPy 🔢
- Matplotlib 📊
- Scikit-learn 🤖
- Jupyter Notebook 📒

## 📈 Model Implementation

The model was implemented in the following steps:

1. **Data Loading & Cleaning**  
   - Read the CSV file
   - Checked and handled null/missing values
   - Converted dates to datetime objects

2. **Feature Engineering**  
   - Extracted features like days since start

3. **Model Training**  
   - Used `LinearRegression()` from `sklearn.linear_model`
   - Split data into training and test sets (80/20)

4. **Prediction & Evaluation**  
   - Compared predictions with actual values
   - Visualized results

5. **Visualization**  
   - Actual vs Predicted Scatter Plot  
   - Sales Forecast Trends

## 📊 Expected Outcome

- Clear visualizations showing sales predictions
- Tabular and graphical representation of forecasted results
- A baseline model that can be extended to more complex forecasting solutions

## 🔮 Sample Output

Here’s an example of output generated:

- ✅ **Scatter plot** comparing actual vs predicted sales
- ✅ **Forecast graph** to visualize upcoming sales
- ✅ **Table of predicted revenue** for future periods

## 📦 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/sales-forecasting-linear-regression.git
   cd sales-forecasting-linear-regression

Install the required packages:
```bash
pip install pandas numpy matplotlib scikit-learn

Run the Jupyter Notebook:
``bash
jupyter notebook sales_forecast.ipynb

Future Improvements:-
Incorporate multiple regression or time series (ARIMA/LSTM) models
Use advanced metrics (MAE, RMSE)
Include seasonal and holiday effects in data
