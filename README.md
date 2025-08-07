# 🍔 Fast Food Giants EDA & Sales Regression

This project explores the sales performance of major fast food chains in the U.S. using Exploratory Data Analysis (EDA) and regression modeling techniques.

## 📈 Overview

This project analyzes the performance of major U.S. fast food chains using data exploration and regression modeling. Below are the key stages of the analysis, along with visualizations that illustrate our findings.

---

### 1. 📊 Revenue vs Popularity

We ranked chains by total systemwide sales to identify market leaders. McDonald’s and Starbucks clearly dominate in terms of revenue.

<img width="924" height="577" alt="Screenshot 2025-08-07 131255" src="https://github.com/user-attachments/assets/bd953db6-cb6b-4a80-86ce-7adf7ff65576" />


---

### 2. 🍔 Top Chains by Category

To better understand category-wise dominance, we analyzed sales across burger, chicken, coffee, and pizza segments. Starbucks leads coffee, McDonald's leads burgers, and Pizza Hut stands out among pizza chains.

<img width="928" height="563" alt="Screenshot 2025-08-07 131350" src="https://github.com/user-attachments/assets/a18f715f-14df-4b57-95dd-d5a89019ff59" />

---

### 3. 🏪 Store Count vs Revenue Relationship

We explored the relationship between store count and sales using linear regression. A positive correlation exists, but some chains like Chick-fil-A generate high revenue with fewer stores.

<img width="991" height="695" alt="Screenshot 2025-08-07 131417" src="https://github.com/user-attachments/assets/497c8052-c55e-4d7d-bc26-be24397359d3" />


---

### 4. 📉 Distribution of Sales per Unit

A histogram of average sales per unit shows that most fast food chains fall within the 1M to 2.2M USD range, with a mean around 1.85M USD.

<img width="964" height="666" alt="Screenshot 2025-08-07 130457" src="https://github.com/user-attachments/assets/595c9fa2-b9b6-44aa-bc5f-7750f1f1becf" />


---

### 5. 📌 Correlation Analysis

We visualized the correlation matrix to identify which features influence systemwide revenue. Total units show a strong positive correlation with revenue.

<img width="987" height="650" alt="Screenshot 2025-08-07 130443" src="https://github.com/user-attachments/assets/d84e093d-f17d-452e-9548-def5d34d7079" />


---

### 6. 🤖 Predictive Modeling

We built a multivariate linear regression model to predict total sales based on store count and average unit sales. The model showed strong performance with an R² of 0.64.

<img width="991" height="695" alt="Screenshot 2025-08-07 131417" src="https://github.com/user-attachments/assets/18f796b8-e854-4f4c-89ed-266bfdf35cd0" />


---

### 7. ✅ Model Evaluation

Predicted sales values from the regression closely align with actual values, demonstrating good explanatory power.

<img width="992" height="575" alt="Screenshot 2025-08-07 131431" src="https://github.com/user-attachments/assets/d56ef485-6860-43b3-bdf0-a897a845a48e" />


---


## 💡 Key Insights

- **McDonald's** dominates the U.S. fast food market with over $40B in annual systemwide sales, followed by **Starbucks** and **Chick-fil-A**.
- Category leaders are clear: McDonald's (burgers), KFC (chicken), Starbucks (coffee), and Pizza Hut (pizza).
- **Total units** have a strong positive correlation (r ≈ 0.71) with systemwide sales, though some brands like Chick-fil-A achieve high revenue with fewer stores.
- Most chains have average sales per unit between $1.08M and $2.13M, with a mean of $1.86M.
- Linear regression shows that both store count and average unit sales significantly contribute to predicting total revenue (R² = 0.64).
- Predicted vs actual sales plots confirm that the model captures market trends effectively, with most points lying close to the regression line.


## 🧪 Techniques Used
- Data cleaning and preprocessing
- Matplotlib & Seaborn for visualizations
- Correlation heatmaps
- Regression modeling using Scikit-learn
- Feature selection with backward elimination
