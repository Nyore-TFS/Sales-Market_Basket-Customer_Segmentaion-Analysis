# 🍕 Pizza Sales Analysis Dashboard & Insights

This project delivers an end-to-end analysis of a fictional pizza restaurant’s sales data. It covers **sales trend analysis**, **customer segmentation**, and **market basket analysis**, offering actionable business insights using Python and essential data science techniques.

---

## 🔍 Project Overview

The primary goal is to extract business value from raw transactional data to:

- Identify top-performing products and categories  
- Understand customer ordering behavior  
- Discover upselling and cross-selling opportunities  
- Segment customers for personalized marketing strategies  

The dataset includes detailed order-level information such as date, time, pizza name, category, size, quantity, and total price.

---

## 📁 Contents

| Section                 | Description                                        |
|-------------------------|----------------------------------------------------|
| `sales_analysis`        | Time-based trends in sales, revenue, and products |
| `market_basket_analysis`| Association rules generated via Apriori algorithm |
| `customer_segmentation` | Customer profiling using K-Means clustering       |
| `visualizations`        | Clean, insightful charts with Seaborn & Matplotlib|
| `data/`                 | Excel dataset: `Data Model - Pizza Sales.xlsx`    |
| `notebook/`             | Jupyter Notebook with complete analysis           |

---

## 📈 Sales Analysis Highlights

- **Total Revenue:** `$817,860.05`  
- **Average Transaction Value:** `$16.82`  
- **Top-Selling Pizzas:** Classic Deluxe, BBQ Chicken, Hawaiian  
- **Best Performing Category:** Classic  
- **Peak Sales Hours:** 12–1 PM, 5–8 PM (Lunch & Dinner)  
- **Top Performing Days:** Fridays and Weekends  

> ✅ Sales performance was analyzed by **month**, **day**, **hour**, **pizza size**, and **category** to identify patterns for operational and promotional improvements.

---

## 🛒 Market Basket Analysis

Using the **Apriori algorithm**, association rules were generated at the **category level** (rather than pizza name level) to reduce data sparsity and improve result generalization.

### Key Parameters:
- `min_support = 0.005`  
- `lift ≥ 1.0`  
- `confidence ≥ 0.25`  

### Sample Rules:
- Customers who order **Classic, Veggie, and Supreme** are likely to add **Chicken**
- Recommender system logic: Suggest the next likely category based on current selection

> ✅ Supports dynamic bundle offers and intelligent up-selling  
> ✅ Category-based analysis improves scalability and clarity  

---

## 👥 Customer Segmentation

K-Means clustering was applied to identify distinct customer profiles based on:

- Total Spend  
- Unique Pizzas Ordered  
- Total Quantity Purchased  

### Segments Identified:

| Segment               | Description                                           |
|-----------------------|-------------------------------------------------------|
| 💎 **Premium Customers** | High spenders with diverse orders — ideal for loyalty programs |
| 🔁 **Regular Customers** | Consistent ordering patterns — perfect for upselling     |
| 🎯 **Occasional Buyers** | Low activity — ideal for re-engagement campaigns       |

> ✅ Optimal number of clusters was selected using the **Elbow Method**  
> ✅ Segments named based on business impact for easy stakeholder interpretation  

---

## 🧰 Tools & Technologies

- **Python** – Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn  
- **MLxtend** – Apriori, Association Rule Mining  
- **Jupyter Notebook**  
- **Excel** – Raw dataset  
- **GitHub / VS Code** – Version control and collaboration  

---

## 📬 Contact

Feel free to fork this repo, suggest improvements, or connect for collaboration.

---