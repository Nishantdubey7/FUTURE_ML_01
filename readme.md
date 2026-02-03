# Machine Learning Task 1 (2026)
## Sales & Demand Forecasting for Businesses

This repository contains **Machine Learning Task 1 (2026)** completed as part of the **Future Interns** program.  
The goal of this project is to build a **sales or demand forecasting system** using historical business data and present insights in a clear and practical way.

---

## Project Overview

Sales forecasting is a widely used Machine Learning application in real business environments.  
Accurate forecasts help companies:

- Plan inventory more effectively  
- Manage cash flow  
- Prepare staffing and operations  
- Reduce losses caused by overstocking or stock shortages  

This project focuses on applying Machine Learning to support **real-world business decisions**, not just model development.

---

## Project Objectives

- Predict future sales based on historical data  
- Identify trends and seasonal patterns  
- Create clear and understandable visualizations  
- Demonstrate the business value of sales forecasting  

---

## Tools and Technologies

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Statsmodels  
- Matplotlib  

---

## Dataset

**Store Sales – Time Series Forecasting (Kaggle)**  
https://www.kaggle.com/competitions/store-sales-time-series-forecasting  

The dataset is not included in this repository due to GitHub file size limitations.  
Please download the `train.csv` file from Kaggle and place it in the project directory before running the code.

---

## Workflow

1. Load and preprocess historical sales data  
2. Convert the data into a time-series format  
3. Handle missing dates and values  
4. Train a time-series forecasting model  
5. Evaluate model performance using error metrics  
6. Visualize historical sales and future forecasts  

---

## Outputs

- Sales forecast visualizations  
- Future sales predictions saved as a CSV file  
- Model evaluation metrics such as MSE and MAPE  

All outputs are designed to be easy to understand for non-technical users.

---

## How to Run the Project

1. Clone this repository  
2. Download `train.csv` from Kaggle and place it in the project folder  
3. Run the forecasting script:

```bash
python forecast.py
