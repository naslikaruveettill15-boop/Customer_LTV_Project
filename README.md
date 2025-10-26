# Customer Lifetime Value (LTV) Prediction Model

## Project Overview
This project predicts the **lifetime value (LTV)** of customers based on their purchase behavior. The predictions help businesses identify high-value customers, optimize marketing strategies, and improve customer retention.

## Features
- Calculates key customer metrics:
  - **Recency:** Days since last purchase
  - **Frequency:** Number of purchases
  - **Average Order Value (AOV):** Average purchase amount
- Predicts **Total Spend (LTV)** using XGBoost regression
- Segments customers into **Low, Medium, High-value groups**
- Visualizes customer segments and trends

## Tools Used
- Python (Pandas, Numpy, Matplotlib, Seaborn)
- XGBoost
- Jupyter Notebook (VS Code supported)


## How to Run
1. Open `LTV_model.ipynb` in **VS Code** or **Jupyter Notebook**.
2. Install required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost
Run all cells in the notebook to generate:

Customer LTV predictions (LTV_predictions.csv)

Visualizations (segment_distribution.png, recency_vs_ltv.png)

Insights

High-value customers identified for targeted marketing.

Segmentation helps optimize promotions and campaigns.

Data-driven insights improve customer retention and revenue.
