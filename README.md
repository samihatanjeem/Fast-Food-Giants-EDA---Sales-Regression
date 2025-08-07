# 🍔 Fast Food Giants EDA & Sales Regression

This project explores the sales performance of major fast food chains in the U.S. using Exploratory Data Analysis (EDA) and regression modeling techniques.

## 📈 Overview

## 📈 Overview

This project analyzes the performance of major U.S. fast food chains using data exploration and regression modeling. Below are the key stages of the analysis, along with visualizations that illustrate our findings.

---

### 1. 📊 Revenue vs Popularity

We ranked chains by total systemwide sales to identify market leaders. McDonald’s and Starbucks clearly dominate in terms of revenue.

![Top Chains by Sales](images/Screenshot_2025-08-07_131255.png)

---

### 2. 🍔 Top Chains by Category

To better understand category-wise dominance, we analyzed sales across burger, chicken, coffee, and pizza segments. Starbucks leads coffee, McDonald's leads burgers, and Pizza Hut stands out among pizza chains.

![Top Chains by Category](images/Screenshot_2025-08-07_131350.png)

---

### 3. 🏪 Store Count vs Revenue Relationship

We explored the relationship between store count and sales using linear regression. A positive correlation exists, but some chains like Chick-fil-A generate high revenue with fewer stores.

![Sales vs Store Count](images/Screenshot_2025-08-07_131417.png)

---

### 4. 📉 Distribution of Sales per Unit

A histogram of average sales per unit shows that most fast food chains fall within the 1M to 2.2M USD range, with a mean around 1.85M USD.

![Avg Sales per Unit](images/Screenshot_2025-08-07_130457.png)

---

### 5. 📌 Correlation Analysis

We visualized the correlation matrix to identify which features influence systemwide revenue. Total units show a strong positive correlation with revenue.

![Correlation Matrix](images/Screenshot_2025-08-07_130443.png)

---

### 6. 🤖 Predictive Modeling

We built a multivariate linear regression model to predict total sales based on store count and average unit sales. The model showed strong performance with an R² of 0.64.

![Regression Results](images/Screenshot_2025-08-07_131431.png)

---

### 7. ✅ Model Evaluation

Predicted sales values from the regression closely align with actual values, demonstrating good explanatory power.

![Predicted vs Actual](images/Screenshot_2025-08-07_131431.png)

---


## 🧠 Key Insights
- Companies with fewer stores may outperform in revenue
- Average meal prices and store density show interesting correlations
- Some chains achieve high revenue with fewer locations

## 🧪 Techniques Used
- Data cleaning and preprocessing
- Matplotlib & Seaborn for visualizations
- Correlation heatmaps
- Regression modeling using Scikit-learn
- Feature selection with backward elimination
