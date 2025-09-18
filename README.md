# Walmart Price Prediction

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.2-green)
![Algorithm](https://img.shields.io/badge/Algorithm-RandomForest-orange)
![License](https://img.shields.io/badge/License-MIT-yellow)

Predict weekly Walmart sales (or product prices) using **Random Forest Regression**.  
This project leverages historical sales data and external factors to provide accurate predictions.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Features](#features)
- [Algorithm](#algorithm)
- [Model Performance](#model-performance)
- [Installation](#installation)
- [Usage](#usage)
- [Future Improvements](#future-improvements)
- [Author](#author)
- [License](#license)

---

## Project Overview
Walmart’s sales and prices depend on multiple factors such as holiday events, store locations, seasonal trends, and customer behavior.  
This project uses a **Random Forest model** to predict sales more accurately than traditional regression methods.

---

## Dataset
The dataset includes the following features:

| Feature         | Description                                   |
|-----------------|-----------------------------------------------|
| Store           | Store ID                                      |
| Dept            | Department ID                                 |
| Date            | Week of sales                                 |
| Weekly_Sales    | Target variable: Walmart sales/price          |
| Holiday_Flag    | Whether the week is a holiday week (1/0)      |
| Temperature     | Average temperature of the region             |
| Fuel_Price      | Cost of fuel in the region                    |
| CPI             | Consumer Price Index                          |
| Unemployment    | Unemployment rate of the region               |

**Source:** [Walmart Sales Forecasting Dataset on Kaggle](https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting)

---

## Features
- Store and department details  
- Date and holiday indicators  
- Regional economic data (Fuel Price, CPI, Unemployment)  
- Target: Weekly Sales  

---

## Algorithm
**Random Forest Regression** was chosen because:
- Handles **non-linear relationships** between features  
- Reduces overfitting compared to decision trees  
- Works well with both numerical and categorical features  

---

## Model Performance
- **Algorithm:** Random Forest  
- **Accuracy:** ~ (add your R² score or MAE here)  
- Strong performance on validation data, especially in handling seasonal/holiday variations.  

---

## Installation
1. Clone the repository:
```bash
git clone <repository-url>
