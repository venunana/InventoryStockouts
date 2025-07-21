# 🛒 Retail Data Analysis

This project analyzes retail data to uncover patterns in stockouts and how they're influenced by factors such as store, product, category, seasonality, and promotions.

---

## 📂 Data Loading and Preparation

- Retail data is loaded from a CSV file (`retail_data.csv`) into a pandas DataFrame.
- A new column called `stockout` is created to indicate whether a stockout occurred (i.e., `Inventory Level == 0`).

---

## 📊 Exploratory Data Analysis (EDA)

The analysis explores various dimensions of stockouts:

- **Overall Stockout Rate:**  
  Calculates the percentage of total stockouts across all data points.

- **Stockout Rate by Product and Store:**  
  Analyzes the frequency of stockouts for each product-store combination.

- **Total Stockouts per Store:**  
  Aggregates stockouts per store to identify which stores experience the most frequent stockouts.

- **Stockout Heatmap (Store vs. Product):**  
  A heatmap visualizes average stockout rates for each product within each store — helping to pinpoint high-risk combinations.

- **Total Stockouts by Store-Product Pair:**  
  A bar plot shows total stockouts for every unique store-product pair for detailed insights.

- **Stockouts by Category:**  
  Aggregates total stockouts for each product category.

- **Stockouts by Promotion Status:**  
  Compares stockout occurrences during promotional vs. non-promotional periods.

- **Stockouts by Seasonality & Epidemic Events:**  
  Evaluates whether stockouts are influenced by seasons or epidemic-related events.

---

## 📦 Units Sold Analysis

This section explores how units sold vary across different conditions:

- **By Season:**  
  Summarizes units sold across different seasons to detect seasonal demand trends.

- **By Store and Category:**  
  Analyzes which product categories perform best in each store.

- **By Promotional Status:**  
  Compares total units sold during promotional vs. non-promotional periods to assess promo impact.

---

## 📈 Pareto Analysis by Store & Category

- **Pareto Charts:**  
  For each store, a Pareto chart shows:
  - Stockouts per category
  - Cumulative contribution of each category to total stockouts  
  Helps prioritize categories that contribute the most to stockout issues.

---

## ✅ Conclusion

This analysis reveals:
- Which stores, products, and categories are most affected by stockouts
- The influence of promotions, seasonality, and external factors on stockouts and sales
- Key insights to support better inventory planning, demand forecasting, and promotion strategies

Use these findings to reduce stockouts, boost sales, and improve customer satisfaction.

---
