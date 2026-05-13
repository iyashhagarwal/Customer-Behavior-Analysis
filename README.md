# 🛒 Customer Shopping Behavior Analysis

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

### End-to-End Data Analytics Project using Python, SQL & Power BI

</div>

---

# 📌 Project Overview

This project focuses on analyzing customer shopping behavior to uncover business insights using:

- 🐍 Python for Data Cleaning & Exploratory Data Analysis
- 🗄️ SQL for Business Analysis
- 📊 Power BI for Dashboard Storytelling

The goal of this project is to transform raw retail data into meaningful insights that help businesses understand customer behavior, product performance, discount effectiveness, and revenue trends.

---

# 🎯 Business Objective

Retail businesses often struggle to answer questions like:

- Which products generate the most revenue?
- Do discounts actually improve sales?
- Which customer groups spend the most?
- Which products have the best customer ratings?
- How do subscriptions affect purchasing behavior?

This project answers these questions through data analysis and visualization.

---

# 🛠️ Tools & Technologies Used

| Tool | Purpose |
|------|----------|
| Python | Data Cleaning & Analysis |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| Matplotlib & Seaborn | Data Visualization |
| SQL | Business Query Analysis |
| Power BI | Dashboard Development |
| Jupyter Notebook | Analysis Workflow |

---

# 📂 Dataset Features

The dataset contains customer shopping transaction information including:

- Customer ID
- Age
- Gender
- Item Purchased
- Category
- Purchase Amount
- Review Rating
- Subscription Status
- Shipping Type
- Discount Applied
- Previous Purchases
- Payment Method
- Purchase Frequency

---

# 🔄 Project Workflow

## 1️⃣ Data Cleaning using Python

Performed:
- Handling missing values
- Removing duplicate records
- Standardizing column names
- Fixing category inconsistencies
- Preparing clean dataset for SQL & Power BI

### Libraries Used
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

---

## 2️⃣ Exploratory Data Analysis (EDA)

Analyzed:
- Revenue distribution
- Product category performance
- Gender-wise spending
- Customer review trends
- Shipping method analysis
- Subscription customer behavior

---

## 3️⃣ SQL Business Analysis

SQL queries were used to answer business-critical questions such as:

### 📌 Revenue by Category
```sql
SELECT category,
SUM(purchase_amount) AS revenue
FROM customer_behavior_analysis
GROUP BY category
ORDER BY revenue DESC;
```

### 📌 Discount Impact Analysis
```sql
SELECT discount_applied,
AVG(purchase_amount) AS avg_purchase
FROM customer_behavior_analysis
GROUP BY discount_applied;
```

### 📌 Customer Segmentation
```sql
SELECT
CASE
WHEN previous_purchases = 0 THEN 'New Customer'
WHEN previous_purchases BETWEEN 1 AND 15 THEN 'Repeat Customer'
ELSE 'Loyal Customer'
END AS customer_segment
FROM customer_behavior_analysis;
```

---

# 📊 Power BI Dashboard

The Power BI dashboard includes:

✅ KPI Cards  
✅ Revenue Analysis  
✅ Category-wise Sales  
✅ Customer Segmentation  
✅ Discount Analysis  
✅ Subscription Insights  
✅ Product Rating Analysis  
✅ Shipping Trends  

---

# 💡 Key Insights

- 📈 Certain product categories generated the highest revenue.
- 🎯 Subscription customers contributed more consistent purchases.
- 💰 Discounts influenced customer buying behavior.
- ⭐ Highly rated products showed stronger sales performance.
- 🚚 Shipping methods impacted average order value.

---

# 📷 Dashboard Preview

> Add your Power BI dashboard screenshots here.

Example:

```md
![Dashboard Screenshot](dashboard.png)
```

---

# 📁 Project Structure

```bash
Customer-Shopping-Behavior-Analysis/
│
├── customer_shopping.ipynb
├── customer_behavior_SQL.sql
├── Customer_behavior_analysis.pbix
├── README.md
├── reports/
└── presentation/
```

---

# 🚀 How to Run the Project

## Clone Repository

```bash
git clone https://github.com/yourusername/customer-shopping-behavior-analysis.git
```

## Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy pyodbc
```

## Run Jupyter Notebook

```bash
jupyter notebook
```

## Open Power BI Dashboard

Open:

```bash
Customer_behavior_analysis.pbix
```

---

# 📈 Business Recommendations

- Focus marketing efforts on top-performing categories
- Improve low-rated products using customer feedback
- Optimize discount strategies
- Enhance subscription programs for better retention
- Use customer segmentation for targeted campaigns

---

# 🎓 Learning Outcomes

This project helped improve my skills in:

- Data Cleaning
- Exploratory Data Analysis
- SQL Querying
- Dashboard Design
- Business Intelligence
- Data Storytelling
- Insight Generation

---

# 🔮 Future Improvements

- Machine Learning-based customer prediction
- Customer churn analysis
- Sales forecasting
- Real-time dashboard integration
- Recommendation system

---

# 🤝 Connect With Me

## 👨‍💻 Yash Agarwal

- LinkedIn: www.linkedin.com/in/yashhagarwal

---

# ⭐ Support

If you found this project useful:

- ⭐ Star the repository
- 🍴 Fork the project
- 📢 Share feedback

---

<div align="center">

### 🚀 Made with Python, SQL & Power BI

</div>
