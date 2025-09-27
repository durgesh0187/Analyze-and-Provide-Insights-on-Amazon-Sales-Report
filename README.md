Amazon Sales Analysis Report
Project Overview

This project analyzes Amazon sales transaction data to extract actionable business insights. The dataset contains information such as order ID, date, status, fulfillment method, sales channel, product category, size, quantity, amount, shipping details, and more. The goal is to understand sales performance, product popularity, fulfillment efficiency, geographical distribution, and to provide actionable recommendations for business optimization.

Key Objectives

Sales Overview: Analyze overall sales performance, trends, and patterns over time.

Product Analysis: Identify popular and slow-moving products based on category, size, and quantity sold.

Fulfillment Analysis: Evaluate fulfillment methods and their effectiveness in delivering orders.

Customer Segmentation: Segment customers (limited in this dataset; can use Sales Channel and B2B flag).

Geographical Analysis: Explore sales distribution across states and cities.

Business Insights: Provide actionable recommendations to optimize sales strategies, inventory management, and customer satisfaction.

Dataset

The dataset contains columns such as:

Order ID, Date, Status, Fulfilment, Sales Channel, ship-service-level

Category, Size, Qty, Amount, ship-city, ship-state, ship-country, B2B

Original dataset link: Google Drive

Analysis Steps

Load & Inspect Data – Read CSV/XLSX and view columns, sample rows, and dataset info.

Data Cleaning – Normalize column names, convert Date to datetime, handle missing values, strip whitespace.

Sales Overview – Compute total revenue, total orders, items sold, and plot trends over time.

Product Analysis – Aggregate revenue and quantity by category and size, identify top/low-performing products.

Fulfillment Analysis – Analyze revenue and orders by fulfillment type and courier status.

Geographical Analysis – Aggregate revenue and orders by ship-state and ship-city, visualize top regions.

Returns & Cancellations – Compute counts and percentages of cancelled or returned orders.

Actionable Recommendations – Summarize insights with specific recommendations for business strategy.

Key Insights

Top-selling product categories and slow movers identified.

Most revenue comes from specific fulfillment types.

Highest revenue states and cities highlighted for targeted marketing.

Cancellation rates calculated to identify problem areas.

Actionable recommendations generated to optimize sales, inventory, and customer satisfaction.

Tools & Libraries

Python 3

Pandas

Matplotlib / Seaborn for visualization

Google Colab (optional)

How to Run

Clone the repository or upload notebook to Google Colab.

Upload the dataset (.csv or .xlsx) to Colab.

Run all cells sequentially.

Review outputs: tables, charts, and recommendations summary.

Author

Durgesh Singh
LinkedIn: https://www.linkedin.com/in/durgesh-singh05/
