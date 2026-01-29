# Amazon Product Sales Analysis 📦

## 📌 Project Overview
This project analyzes over 30,000 Amazon products to understand the relationship between **price, product quality (ratings), and "Best Seller" status**. The goal was to determine if higher prices or sales badges actually correlate with customer satisfaction.

## 🔍 Key Insights
* **Price vs. Quality:** There is **no strong correlation** between higher prices and higher ratings. Expensive products are not necessarily rated better than cheaper alternatives.
* **The "Best Seller" Advantage:** Products with the "Best Seller" badge have a **slightly higher median rating** than regular products, but the difference is minimal.
* **Data Volume:** The analysis covers ~30,000 unique products after cleaning.

## 🛠️ Technical Challenges & Solutions
* **Dirty Data:** The raw prices contained currency symbols (`₹`, `,`, `$`) and mixed text.
* **Solution:** Used Python's `regex` (Regular Expressions) to strip non-numeric characters and converted columns to `float` for analysis.

## 📊 Visualizations
* **Scatter Plot:** To visualize the spread of Price vs. Rating.
* **Box Plot:** To compare the rating distribution of Best Sellers vs. Regular Products.

## 💻 Tech Stack
* **Python** (Pandas, Matplotlib, Seaborn)
* **Data Cleaning** (Regex, Type Conversion)