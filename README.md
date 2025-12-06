# 📘 Amazon Sales Analysis – End-to-End Data Analytics Project

## 📌 Project Overview
This project presents a complete **end-to-end data analytics workflow** designed to analyze Amazon's global sales performance.  
Using **Python** for data cleaning, **SQL** for analytical querying, and **Power BI** for dashboarding, the project uncovers insights into:

- Revenue & profit patterns  
- Region & country performance  
- Category-wise profitability  
- Online vs Offline sales behavior  
- Shipping efficiency  
- Monthly revenue trends  

This project reflects a real-world business intelligence workflow used in data analytics roles.

---

## 🛠 Tech Stack

| Phase | Tools Used |
|-------|------------|
| Data Cleaning | Python, Pandas, NumPy |
| Data Storage & Querying | SQL (MySQL / PostgreSQL syntax) |
| Data Visualization | Power BI |
| Reporting | DAX, Power Query, Interactive Dashboard |
--------------------------------------------------------------

## 📂 Workflow Architecture

# 🧹 1. Data Cleaning (Python)

The Python notebook handled:

### ✔ Dataset Preparation
- Loaded and inspected the raw dataset  
- Removed duplicates  
- Fixed inconsistent or missing data  
- Converted `Order_Date` & `Ship_Date` into datetime format  
- Standardized categorical values  

### ✔ Feature Engineering
- Shipping Duration  
- Profit Margin  
- Month & Year fields for trend analysis  

### ✔ Exporting Clean Data
The cleaned dataset was exported for SQL analysis and Power BI reporting.

---

# 🧮 2. Exploratory Data Analysis (SQL)

SQL queries were used to extract business insights from the cleaned dataset.  
(All SQL queries come from the file `Amazon_Sales_Analysis.sql`.)

### 🔹 Total Revenue Across All Orders
Calculates total revenue generated across the entire dataset.

### 🔹 Highest Revenue-Generating Item Type
Ranks product categories based on generated revenue.

### 🔹 Region-Wise Revenue Contribution
Identifies the strongest and weakest performing regions globally.

### 🔹 Month-wise Sales Trend
Shows seasonal or cyclical patterns in customer demand.

### 🔹 Average Shipping Duration by Region
Reveals logistics efficiency and highlights delays.

### 🔹 Country With Highest Units Sold
Shows geographic sales volume distribution.

### 🔹 Profit Margin by Item Type
Evaluates category profitability to guide inventory decisions.

### 🔹 Online vs Offline Sales Comparison
Determines which channel generates more revenue.

### 🔹 Top 5 Countries by Profit
Highlights the most profitable markets.

### 🔹 Running Total Revenue (Window Function)
Tracks cumulative revenue growth month-over-month.

---

# 📊 3. Power BI Dashboard

The Power BI dashboard visualizes all insights in an interactive and intuitive format.

### ✔ Included Visuals
- **Revenue by Region** (Bar / Map Visual)  
- **Item Type Profitability**  
- **Monthly Revenue Trend (Line Chart)**  
- **Online vs Offline Sales Breakdown**  
- **Shipping Duration Analysis**  
- **Top Countries by Sales & Profit**  
- **KPIs:** Total Revenue, Total Profit, Units Sold  

### ✔ Dashboard Features
- Filters for Region, Item Type, Channel, Year  
- Dynamic visual interactions  
- Clean and professional UI design  
- Insight-driven layout for storytelling  

## 📊 Key Insights

- **North America and Sub-Saharan Africa generate the highest total revenue**, making them the strongest-performing regions.
- **Cosmetics, Beverages, and Office Supplies are the most profitable item categories**, indicating high-margin product opportunities.
- **Online sales channels outperform offline channels**, showing a strong customer preference for e-commerce.
- **Certain regions experience higher shipping delays**, highlighting logistical inefficiencies and improvement opportunities.
- **Monthly revenue trends reveal clear seasonality**, useful for forecasting and inventory planning.
- **Units sold do not always correlate with profit**, suggesting the need for pricing and cost optimization strategies.
- **Running total revenue shows consistent month-over-month growth**, indicating healthy business performance and increasing demand.


---

# 📌 Conclusion

This project demonstrates the complete lifecycle of data analytics:

- **Raw data → actionable insights**  
- **Technical tools → strategic business intelligence**  
- **Data cleaning → SQL logic → BI storytelling**

Through this project, we showcased:

- Ability to work with large datasets  
- Strong SQL analytical thinking  
- Business-focused dashboard creation  
- Practical understanding of ETL + BI pipelines  

This project can support business decisions in operations, logistics, supply chain, marketing, and financial planning.

---


# 🙌 Author
**Sudip Modak**  
Data Analyst | Business Intelligence | Python | SQL | Power BI  

Feel free to connect or reach out for feedback or collaboration!

---





