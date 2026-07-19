# 🛒 Retail Sales Analysis using SQL & Python

## 📌 Project Overview

This project performs an end-to-end analysis of a retail sales dataset using **MySQL** for data storage and querying, and **Python** for data analysis and visualization.

The objective is to extract meaningful business insights from transactional sales data by analyzing customer behavior, product performance, regional sales, profitability, discounts, and shipping trends.

This project demonstrates practical data analytics skills including:

- SQL querying and database management
- Data cleaning and exploration
- Business KPI analysis
- Data visualization using Python
- Business insight generation

---

## 📂 Dataset

**Dataset:** Sample Superstore Dataset

The dataset contains approximately **10,000 retail transactions** with information related to:

- Orders
- Customers
- Products
- Sales
- Profit
- Discounts
- Shipping
- Regions

### Important Columns

- Order Date
- Ship Date
- Customer ID
- Customer Name
- Segment
- Region
- State
- Category
- Sub-Category
- Product Name
- Sales
- Quantity
- Discount
- Profit

---

# 🛠 Tech Stack

| Technology | Purpose |
|------------|----------|
| MySQL | Database & SQL Analysis |
| Python | Data Analysis |
| Pandas | Data Manipulation |
| Matplotlib | Visualization |
| Seaborn | Statistical Visualization |
| Jupyter Notebook | Analysis & Reporting |
| VS Code | Development Environment |

---

# 📁 Project Structure

```
Retail-Sales-Analysis-SQL-Python/
│
├── sql/
│   ├── schema.sql
│   ├── 01_basic_metrics.sql
│   ├── 02_customer_analysis.sql
│   ├── 03_product_analysis.sql
│   ├── 04_discount_analysis.sql
│   └── 05_region_shipping.sql
│
├── dataset/
│   └── Sample-Superstore.csv
│
├── notebook.ipynb
│
└── README.md
```

---

# 📊 SQL Analysis

The project answers several real-world business questions.

## 1. Sales Performance

- Total Sales
- Total Profit
- Total Orders
- Average Order Value
- Monthly Sales Trend
- Yearly Sales Trend

---

## 2. Customer Analysis

- Top Customers by Sales
- Top Customers by Profit
- Customer Lifetime Revenue
- Average Order Value by Segment

---

## 3. Product Analysis

- Top Selling Products
- Most Profitable Products
- Sales by Category
- Sales by Sub-Category
- Loss Making Products

---

## 4. Discount Analysis

- Discount vs Profit
- Average Profit by Discount Band
- High Discount Orders
- Impact of Heavy Discounts

---

## 5. Regional & Shipping Analysis

- Sales by Region
- Sales by Customer Segment
- Average Shipping Days
- Shipping Performance

---

# 📈 Python Analysis

The Jupyter Notebook connects directly to the MySQL database and generates interactive business insights.

Visualizations include:

- Monthly Sales Trend
- Monthly Profit Trend
- Yearly Sales & Profit
- Top 10 Products
- Sales by Region
- Sales by Customer Segment
- Profit by Sub-Category
- Discount vs Average Profit
- Shipping Time Analysis
- Order Value Distribution
- Correlation Heatmap
- Sales vs Profit Scatter Plot

---

# 📌 Business Insights

Some key findings from the analysis include:

- Sales show consistent growth over the years.
- Consumer segment contributes the highest revenue.
- Technology products generate the highest profit.
- Furniture contains several low-profit products.
- Discounts above 40% frequently result in negative profit.
- Western region contributes the highest sales.
- Standard Class shipping has the longest delivery time.
- A small percentage of products generate the majority of revenue.

---

# 🚀 How to Run

## Step 1

Clone the repository

```bash
git clone <repository-url>
```

---

## Step 2

Create a MySQL database

```sql
CREATE DATABASE superstore_db;

USE superstore_db;
```

---

## Step 3

Run the schema

Execute

```
schema.sql
```

This creates the **orders** table.

---

## Step 4

Import Dataset

Import

```
Sample-Superstore.csv
```

into the **orders** table using MySQL Workbench.

---

## Step 5

Run SQL Files

Execute the SQL scripts in the following order:

```
01_basic_metrics.sql

02_customer_analysis.sql

03_product_analysis.sql

04_discount_analysis.sql

05_region_shipping.sql
```

---

## Step 6

Install Required Python Packages

```bash
pip install pandas matplotlib seaborn mysql-connector-python jupyter
```

---

## Step 7

Update Database Credentials

Open

```
notebook.ipynb
```

Update

```python
host="localhost"
user="root"
password="YOUR_PASSWORD"
database="superstore_db"
```

---

## Step 8

Run the Notebook

Launch Jupyter Notebook

```bash
jupyter notebook
```

or

```bash
jupyter lab
```

Run all notebook cells to reproduce the analysis and visualizations.

---

# 📚 Skills Demonstrated

- SQL
- Joins
- Aggregations
- Group By
- Window Functions (where applicable)
- Business KPI Analysis
- Data Cleaning
- Python Programming
- Pandas
- Data Visualization
- MySQL
- Business Intelligence
- Exploratory Data Analysis (EDA)

---

# 🎯 Project Objectives

- Analyze retail sales performance
- Identify high-value customers
- Discover profitable products
- Evaluate discount effectiveness
- Analyze regional performance
- Measure shipping efficiency
- Generate actionable business insights

---

# 📸 Sample Visualizations

The notebook generates:

- 📈 Monthly Sales Trend
- 📊 Yearly Sales vs Profit
- 🏆 Top Products
- 🌍 Regional Sales
- 💰 Discount Analysis
- 🚚 Shipping Analysis
- 🔥 Correlation Heatmap

*(Add screenshots of your charts here after running the notebook.)*

---

# 👨‍💻 Author

**Rahul Rajak**

Electrical Engineering Undergraduate | NIT Silchar

Aspiring Data Analyst | SQL | Python | Power BI | Data Visualization

---

# ⭐ If you found this project useful, consider giving it a star!
