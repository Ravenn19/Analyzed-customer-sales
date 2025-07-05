# 🛍️ Customer Sales Data Analysis with Python

This project focuses on analyzing customer sales data using **Python**, leveraging libraries like `pandas`, `matplotlib`, and `seaborn`. The goal is to uncover purchasing trends, identify best-selling products, and determine top-performing customers through clean and insightful data analysis.

---

## 📊 Project Objectives

- Analyze sales patterns across different products and months.
- Visualize revenue performance using bar and line charts.
- Identify high-value customers based on total purchases.
- Derive actionable insights for business decision-making.

---

## 🔧 Tools & Libraries

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter/Colab Notebook

---

## 📁 Dataset

A synthetic dataset was created with the following fields:

| Column        | Description                         |
|---------------|-------------------------------------|
| Customer_ID   | Unique ID of the customer           |
| Product       | Product name (e.g., Laptop, Tablet) |
| Quantity      | Number of units bought              |
| Price         | Unit price of the product           |
| Date          | Date of transaction                 |
| Total         | Quantity × Price                    |

The dataset simulates 100 transactions across four product categories.

---

## 📈 Key Visualizations

- **Bar chart** of total sales by product
- **Line chart** showing monthly revenue trends
- **Horizontal bar** for top 5 customers by total purchase

<p align="center">
  <img src="https://raw.githubusercontent.com/yourusername/yourrepo/main/sample_bar_chart.png" width="500"/>
  <br/>
  <em>Sample Visualization – Product Sales</em>
</p>

---

## 🧠 Insights

1. **Top-Selling Product**: Laptops accounted for the highest revenue share.
2. **Revenue Peak Month**: March 2024 showed the highest total sales.
3. **Top Customer**: Customer ID `1021` made the largest total purchase.

---

## 🚀 How to Run

> You can run this notebook directly in Google Colab:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/your-colab-link-here)

Or clone the repo and run locally:

```bash
git clone https://github.com/yourusername/sales-data-analysis.git
cd sales-data-analysis
jupyter notebook
