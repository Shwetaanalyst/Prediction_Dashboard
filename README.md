# 📊 Teen Birth Trends & Prediction Dashboard (USA) | Streamlit App

This project analyzes, visualizes, and predicts teen birth rates across U.S. states from 1991 to 2015 using public health data from the CDC's National Center for Health Statistics (NCHS). It includes an interactive dashboard built with **Streamlit**, along with a simple **machine learning model** for forecasting.

---

## 🗂️ Dataset

- **Title**: U.S. and State Trends on Teen Births  
- **Source**: [CDC NCHS - Data.Gov](https://catalog.data.gov/dataset/nchs-u-s-and-state-trends-on-teen-births)  
- **Format**: CSV  
- **Time Period**: 1991–2015  
- **Features**:
  - State
  - Year
  - Age Group (e.g., 15-17 years)
  - Birth Rate (per 1,000)

---

## 🎯 Key Features

✅ Cleaned and explored the CDC teen birth dataset  
✅ Built an interactive dashboard using **Streamlit**  
✅ Visualized national and state-wise birth trends  
✅ Trained a **Linear Regression model** to predict future birth rates  
✅ Allowed filtering by **state**, **year**, and **age group**

---

## 📊 Visualizations

- Line plot: Birth rates over time by state
- Heatmap: Correlation matrix of numerical fields
- Bar charts: Top & bottom 10 states by birth rate
- Predictive chart: Projected birth rates beyond 2015

---

## 🧠 Model

- **Type**: Linear Regression
- **Input Features**: `State`, `Year`, `Age Group`
- **Target**: Birth Rate (per 1,000)
- **Libraries Used**: `pandas`, `scikit-learn`, `seaborn`, `matplotlib`

https://github.com/Shwetaanalyst/Data-Analysis--Dashboard


## 🛠️ Tech Stack
Python 3.11

Pandas, Numpy

Seaborn, Matplotlib

Scikit-learn

Streamlit

## 📌 Project Structure

├── data/
│   └── teen_birth_data.csv
├── models/
│   └── linear_model.pkl
├── teen_birth_dashboard.py
├── requirements.txt
└── README.md

##🔮 Sample Prediction
Year	State	Age Group	Predicted Birth Rate
2022	Texas	15–17 years	17.56
2022	California	15–17 years	8.74



