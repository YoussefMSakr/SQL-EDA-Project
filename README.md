# SQL-EDA-Project


### 📊 Overview
This project demonstrates **Exploratory Data Analysis (EDA)** using SQL on a structured business dataset.  
It provides insights into customer demographics, product performance, sales distribution, and revenue ranking.  
The project focuses on uncovering **key business patterns** and **data-driven KPIs** through SQL queries and aggregations.

---

### 🧠 Objectives
- Understand customer profiles (age, gender, geography).  
- Measure total sales, quantities, and orders.  
- Compare category performance by revenue and cost.  
- Identify top and worst performing products and customers.  
- Build SQL-based business summary reports.

---

### 🧱 Dataset & Tables
All queries are executed on a **star schema** model under the schema `[gold]`:

| Table | Description |
|--------|--------------|
| `fact_sales` | Contains transaction data: sales amount, quantity, price, and customer/product keys |
| `dim_customers` | Customer demographic details: name, gender, country, birth date |
| `dim_products` | Product information: category, subcategory, cost, and price |

---

### 🧩 Project Sections

#### 1️⃣ Basic Business Metrics
- First and last order date  
- Total duration of business (in years)  
- Total sales and total items sold  
- Average selling price  
- Total and unique orders  
- Number of products and customers  

#### 2️⃣ Magnitude Analysis
- Total customers by **country** and **gender**  
- Total products and average cost by **category**  
- Total revenue per **category** and **customer**  
- Distribution of sold items by **country**

#### 3️⃣ Ranking Analysis
- Top 5 and Worst 5 Products by Revenue  
- Top 5 and Worst 5 Subcategories by Revenue  
- Top 10 Customers generating the highest revenue  
- 3 Customers with the lowest revenue  
- Ranking using **SQL Window Functions (ROW_NUMBER)**

---

### 🧮 Example Insights
| Metric | Result |
|--------|---------|
| Total Sales | SUM(sales_amount) |
| Total Orders | COUNT(DISTINCT order_number) |
| Top Product | `Mountain-200 Black, 46` |
| Top Customer | Highest revenue from "Morgan" |
| Best Country | United States (highest quantity and revenue) |

---

### ⚙️ Tools & Technologies
- Microsoft SQL Server  
- Transact-SQL (T-SQL)  
- Data Aggregation and Window Functions  
- Fact-Dimension Data Model (Star Schema)

---

### 📈 Business Value
This project enables:
- Data-driven decision-making through SQL analysis  
- KPI tracking before visualization (Power BI or Tableau)  
- Identification of sales trends and key customers  

---

### 🧑‍💻 Author
**Major General Data Analyst / Youssef Sakr**  
*SQL Exploratory Data Analysis Project (2025)*
