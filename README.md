# 🌍 Global Superstore Sales Analysis Dashboard

## 📑 Table of Contents

1. Project Overview  
2. Dataset Description   
3. Data Preparation & Transformations  
4. DAX Measures  
5. Key KPI Measures  
6. Branch / Location Measures  
7. Dashboard Pages & Visualizations     
8. Drill-Down & Interactivity  
9. Performance Optimization  
10. How to Reproduce / Deliverables  
11. Business Insights
12. Conclusion
13. Dashboard Images

---


# 📌 1. Project Overview

This project analyzes Global Superstore sales data to generate insights related to:

- 🛒 Sales performance  
- 📦 Product profitability  
- 🌍 Regional performance  
- 👥 Customer segments  

### 🎯 Objective:
To improve **sales strategy, profitability, and regional performance** using data-driven insights.

---

# 📊 2. Dataset Description

The dataset contains global retail sales data:

| Column Name        | Description |
|-------------------|------------|
| Order_ID          | Unique order identifier |
| Order_Date        | Date of order |
| Ship_Date         | Date of shipment |
| Ship_Mode         | Shipping method |
| Customer_ID       | Unique customer identifier |
| Customer_Name     | Customer name |
| Segment           | Consumer / Corporate / Home Office |
| Country           | Customer country |
| City              | Customer city |
| Region            | Sales region |
| Product_Category  | Product category |
| Sub_Category      | Product sub-category |
| Product_Name      | Product name |
| Sales             | Revenue generated |
| Quantity          | Units sold |
| Profit            | Profit earned |

---


# 🧹 3. Data Preparation & Transformations

## Step 1: Data Cleaning
- Removed null values  
- Removed duplicates  
- Standardized column names  

---

## Step 2: Data Type Conversion
- Converted Transaction_Date to datetime  
- Ensured numeric columns  

---

## Step 3: Data Validation
- Checked balance consistency
- Verified discharge dates > admission dates


---
##  📐 4. DAX Measures (Power BI)
- ### Total Sales
  Total Sales = SUM('Superstore'[Sales])
- ### Total Profit
 Total Profit = SUM('Superstore'[Profit])
- ### Total Orders
 Total Orders = COUNT('Superstore'[Order_ID])
- ### Profit Margin
 Profit Margin = DIVIDE([Total Profit], [Total Sales])
----


## 📊 6. Key KPI Measures
- 💰 Total Sales
- 📈 Total Profit
- 📦 Total Orders
- 📉 Profit Margin
- 🚚 Average Shipping Days

---

## 📍 7. Region / Segment Measures
- ### Sales by Region
Region Sales = SUM('Superstore'[Sales])
- ### Profit by Segment
Segment Profit = SUM('Superstore'[Profit])
---


# 📊 7. Dashboard Pages & Visualizations

## 1️⃣ Overview Dashboard

### KPIs:

- Total Sales
- Total Profit
- Total Orders
- Profit Margin

### Charts:

- Sales trend (Line chart)
- Category distribution

## 2️⃣ Sales Analysis

### Charts:

- Sales by category
- Monthly sales trends

## 3️⃣ Profit Analysis

### Charts:

- Profit by category
- Loss vs profit analysis

## 4️⃣ Region Analysis

### Charts:

- Sales by region
- Segment performance


# 🔍 8. Drill-Down & Interactivity

### Drill-Down:
- Year → Month 
- Region → City
### Filters:
- Date
- Region
- Category
  
### Interactivity:
- Cross-filtering
- Dynamic visuals

---
# ⚡ 9. Performance Optimization
- Removed unused columns
- Optimized DAX calculations
- Reduced visual load
---


# 📈 11. Business Insights

-🏆 Certain categories generate higher sales but lower profit
- 🌍 Regional performance varies significantly
- 📉 Some products consistently generate losses
- 🚚 Shipping delays impact customer satisfaction

---
# ⭐12. Conclusion

This project demonstrates:
- End-to-end Global Superstore  data analysis
- Dashboard design using Microsoft Excel
- Strong analytical and business insight skills

---

# 💡13. Excel Dashboard 

<img src="https://github.com/GauriPise/Hospital-Data-Analysis/blob/main/Picture1.png" width="1000"> <br> 

