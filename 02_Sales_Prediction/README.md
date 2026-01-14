# Sales Prediction using Linear Regression 📊

## 📌 Project Overview
This project focuses on predicting product sales based on advertising expenditure across different media platforms such as TV, Radio, and Newspaper. The objective is to understand how advertising spend impacts sales and to build a regression model that can accurately predict sales values.

This project is part of my **Data Science Internship with MyDailyWork** and demonstrates an end-to-end regression workflow.

---

## 📊 Dataset
- Source: Kaggle (Advertising Dataset)
- Total Records: 200
- Features:
  - `TV` – TV advertising spend
  - `Radio` – Radio advertising spend
  - `Newspaper` – Newspaper advertising spend
- Target Variable:
  - `Sales` – Product sales

All variables are numerical, and the dataset contains no missing values.

---

## 🔍 Exploratory Data Analysis (EDA)
The following observations were made during EDA:
- TV advertising shows a strong positive linear relationship with sales.
- Radio advertising has a moderate impact on sales.
- Newspaper advertising shows a weak relationship with sales.
- Correlation analysis confirmed that TV advertising is the strongest predictor of sales.

---

## 🧠 Correlation Analysis
Correlation matrix results:
- TV vs Sales: ~0.90 (Strong positive correlation)
- Radio vs Sales: ~0.35 (Moderate correlation)
- Newspaper vs Sales: ~0.16 (Weak correlation)

Low correlation among independent variables indicates minimal multicollinearity.

---

## 🤖 Model Building
- Model Used: **Linear Regression**
- Train-Test Split: 80% training, 20% testing
- Features Used: TV, Radio, Newspaper

---

## 📈 Model Evaluation
The model was evaluated using regression metrics:
- **R² Score:** ~0.91  
- **RMSE:** ~1.7

These results indicate that the model explains approximately 90% of the variation in sales with a low prediction error.

---

## 🔎 Model Interpretation
Regression coefficients:
- TV advertising has a strong overall influence on sales.
- Radio advertising has the highest per-unit impact on sales.
- Newspaper advertising contributes minimally to sales prediction.

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn

---

## 📌 Conclusion
The analysis confirms that TV and radio advertising are key drivers of sales, while newspaper advertising has limited impact. Linear Regression proved to be an effective model for predicting sales based on advertising spend.

---

📎 **Internship Task – MyDailyWork Data Science Internship**
