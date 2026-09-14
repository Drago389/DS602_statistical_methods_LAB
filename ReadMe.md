# Lab-4: Applied Statistical Modeling & Interactive Web Dashboard

## 🚀 Live Demo
**[View the Interactive Dashboard Here](https://ds602statisticalmethodslab-n5uhnhbwarm4ewp53sbu2s.streamlit.app/)**



## M.Sc. Data Science — Semester 1
**Course:** Statistical Modeling with Python  
**Student Name:** ABHAY TRIPATHI  
**Roll Number:** 202618044

## Overview
This project implements an end-to-end data science workflow using the **Medical Insurance Costs** dataset. It covers Exploratory Data Analysis (EDA), Hypothesis Testing, OLS Regression Modeling, and Residual Diagnostics, all wrapped in an interactive Streamlit web application.

## Features
1. **Data Exploration:** Interactive filters for Age, Sex, and Smoker status. Descriptive statistics and Plotly visualizations.
2. **Hypothesis Testing Lab:** 
   - Two-sample test (t-test or Mann-Whitney U) comparing Smokers vs. Non-Smokers.
   - One-Way ANOVA comparing charges across geographic regions.
3. **Live Prediction & Diagnostics:** 
   - OLS Regression model (`charges ~ age + bmi + children + smoker`).
   - Gauss-Markov checks: Residuals vs. Fitted, Q-Q Plot, Jarque-Bera Test, and VIF.
   - Real-time prediction tool with 95% Confidence Intervals.

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/Lab4_DS602_MSc.git
cd Lab4_DS602_MSc
