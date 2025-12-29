# Business Sales Prediction

This project predicts monthly sales for a small business based on advertising spend, store visitors, and competitor pricing.  
It uses Linear Regression to estimate sales and provides actionable insights for business planning.

---

## Dataset

The dataset contains 12 months of data with the following columns:

- **Month**: Month number (1-12)
- **Advertising**: Advertising budget in ₹
- **Store_Visitors**: Number of visitors to the store
- **Competitor_Price**: Competitor's average price
- **Sales**: Actual sales (target)

---

## Features and Target

- **Features (X)**: Advertising, Store_Visitors, Competitor_Price  
- **Target (y)**: Sales

---

## Model

- **Linear Regression** was used because Sales is a continuous numeric value.

---

## Insights

1. Higher Advertising spend directly increases Sales.  
2. More Store Visitors lead to higher Sales.  
3. Higher Competitor Prices slightly decrease Sales.  
4. Model predictions are reasonably close to actual Sales (check MAE).  
5. This notebook can help the business forecast monthly Sales and plan budgets.

---

## How to Run

1. Open `business_sales_prediction.ipynb` in Jupyter or VS Code.  
2. Run all cells sequentially.  
3. The dataset will be generated automatically, model trained, and predictions displayed.
