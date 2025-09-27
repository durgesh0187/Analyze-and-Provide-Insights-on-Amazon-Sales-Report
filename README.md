# 📊 Amazon Sales Analysis Report

![Python](https://img.shields.io/badge/python-3.12-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-data%20analysis-brightgreen)
![Matplotlib](https://img.shields.io/badge/matplotlib-visualization-orange)

---

## 🚀 Project Overview

This project provides a **comprehensive analysis of Amazon sales transactions** to derive actionable insights. The dataset includes order details, product categories, quantities, revenue, fulfillment methods, shipping information, and B2B flags. The objective is to analyze sales trends, product performance, fulfillment efficiency, and geographical distribution to support strategic business decisions.

---

## 🎯 Key Objectives

1. **Sales Overview:** Evaluate overall sales performance and identify trends over time.
2. **Product Analysis:** Analyze category, size, and quantity to identify top-performing and slow-moving products.
3. **Fulfillment Analysis:** Assess fulfillment methods and delivery effectiveness.
4. **Customer Segmentation:** Segment customers by behavior and relevant attributes (limited to Sales Channel and B2B flag).
5. **Geographical Analysis:** Identify top-performing states and cities.
6. **Business Insights:** Provide actionable recommendations to improve sales strategies, inventory management, and customer satisfaction.

---

## 🗂 Dataset

The dataset contains the following key columns:

['Order ID', 'Date', 'Status', 'Fulfilment', 'Sales Channel', 'ship-service-level',
'Category', 'Size', 'Qty', 'Amount', 'ship-city', 'ship-state', 'ship-country', 'B2B']

yaml
Copy code

- Dataset link: [Google Drive](https://drive.google.com/file/d/1YrjYKtS1WHmINL6eafRsrDzrZaw2_WvX/view?usp=sharing)

---

## 🛠 Tools & Libraries

- **Python 3**
- **Pandas** – data manipulation and cleaning
- **Matplotlib / Seaborn** – data visualization
- **Google Colab / Jupyter Notebook** – interactive environment

---

## 📈 Analysis Workflow

1. **Load & Inspect Data:** Check structure, column names, and sample rows.
2. **Data Cleaning:** Normalize column names, convert dates, handle missing values, and trim whitespace.
3. **Sales Overview:** Compute total revenue, total orders, items sold, and visualize trends over time.
4. **Product Analysis:** Aggregate revenue and quantity by category and size; identify top and low-performing products.
5. **Fulfillment Analysis:** Evaluate revenue and order distribution across fulfillment types.
6. **Geographical Analysis:** Aggregate revenue and orders by state and city; visualize top regions.
7. **Returns & Cancellations:** Calculate rates of cancelled or returned orders.
8. **Actionable Recommendations:** Summarize insights and provide strategic suggestions for business decisions.

---

## 🔑 Key Insights

- Top-selling categories and sizes identified.
- Revenue distribution across fulfillment types highlighted.
- High-revenue states and cities pinpointed for targeted marketing.
- Cancellation rates identified to mitigate operational issues.
- Recommendations provided to optimize inventory, sales, and customer satisfaction.

---

## 📝 How to Use

1. Clone the repository:

```bash
git clone <repo-link>
Open the notebook in Google Colab or Jupyter Notebook.

Upload the Amazon dataset (.csv or .xlsx).

Run all cells sequentially to generate visualizations, tables, and recommendations.

📝 Author
Durgesh Singh
LinkedIn: https://www.linkedin.com/in/durgesh-singh05/

💡 Notes
Customer segmentation is limited due to missing customer_id.

SKU-level and price distribution insights can be added if dataset includes detailed pricing.

All analysis is robust to column name variations and missing values, ensuring reproducibility.

📊 Example Visualizations
Revenue by Product Category: Top categories contributing to sales.

Revenue by State/City: Geographical distribution of sales.

Orders by Status: Delivered, Cancelled, or Returned orders.

python
Copy code
# Example visualization snippet
import matplotlib.pyplot as plt

df.groupby('category')['amount'].sum().plot(kind='bar', color='skyblue')
plt.title('Revenue by Product Category')
plt.ylabel('Revenue')
plt.show()

🎯 Summary
This repository provides a complete end-to-end analysis of Amazon sales data, including data cleaning, visualization, insights extraction, and actionable recommendations. It serves as a professional guide for business decision-making and strategy optimization.
