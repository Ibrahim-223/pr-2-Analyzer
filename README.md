# Sales Analyzer

**pr-2 Analyzer.xlsx**

This Excel file is created for **data analysis practice**.  
It focuses on **customer sales, profit analysis, and business insights** using real-world structured data.

---

## 📂 Dataset Overview

### Sheet Name: Sales_Data

### Columns Used
| Column Name | Description |
|------------|------------|
| Customer_ID | Unique customer identifier |
| Customer_Name | Name of the customer |
| Region | Sales region (North, South, East, West, Central) |
| Product_Category | Product type (Books, Electronics, Furniture, etc.) |
| Sales | Total sales amount |
| Quantity | Number of units sold |
| Discount | Discount applied (in %) |
| Order_Date | Date of order |
| Profit | Profit earned |

---

## 🎯 Project Objectives
- Analyze customer-wise and region-wise sales
- Measure impact of discount on profit
- Identify high-value customers
- Track monthly sales growth
- Build an interactive dashboard

---

## 🧪 Tasks Performed

### 1️⃣ Top 10 Customers Analysis
- Used **Pivot Table**
- Applied **Conditional Formatting**
- Highlighted top 10 customers based on total sales

---

### 2️⃣ What-If Analysis (Discount Impact)
- Created profit calculation formula  
  ```excel
  =Sales*(1-Discount)*0.3


3️⃣ Linear Regression (Profit vs Sales)

Enabled Analysis Toolpak

Used Regression tool

Analyzed relationship between sales and profit

4️⃣ Descriptive Statistics

Applied Descriptive Statistics from Toolpak

Calculated:
Mean
Maximum
Minimum

Standard Deviation

5️⃣ Monthly Sales Growth

Extracted month from Order_Date

Created Pivot Table

Applied Up/Down Arrow Conditional Formatting

6️⃣ Timestamp Column

Used:=NOW()

Generated real-time timestamp

7️⃣ High-Value Customers

Used INDEX + MATCH

=INDEX(Customer_Name, MATCH(MAX(Sales), Sales, 0))

Identified customers with highest sales

8️⃣ Region & Product Analysis

Pivot Table:
Rows → Region
Columns → Product_Category
Values → Sum of Sales

9️⃣ Data Visualization

Bar Chart → Sales by Region

Line Chart → Monthly Sales Trend

🔟 Dashboard Creation

KPIs:
Total Sales
Total Profit
Top Customer
Used:
Pivot Charts
Slicers (Region, Category)

🛠 Tools & Features Used
Excel 2021
Pivot Tables
Conditional Formatting
What-If Analysis
Analysis Toolpak
INDEX & MATCH
Charts & Dashboard


