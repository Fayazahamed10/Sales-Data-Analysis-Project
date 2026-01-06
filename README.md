# Sales Data Analysis Project | Power BI

## 📌 Project Overview

### LinkedIn Post Summary

📉 **I spent 15 hours building a Power BI dashboard, and it completely changed how I look at sales discounts.**

Everyone pushes for higher sales numbers, but this project reinforced a hard truth: **more sales don’t always mean more profit.**

Through this end-to-end **Sales Data Analysis dashboard**, I uncovered a recurring pattern where poorly structured discount promotions increased sales volume while significantly reducing profitability in specific product categories.

**What this dashboard highlights:**
- Top & Bottom 5 products by Sales, Profit, and Quantity
- Sales trend analysis (daily, monthly, quarterly, yearly)
- Net Sales vs Profit relationship analysis
- Period-over-period performance comparison
- Average discount analysis by promotion category
- Detailed order-level analysis with dynamic slicers (Date, Customer, Product, Promotion, City)

**Key takeaway:**  
Discounts should be treated as a strategic lever, not a default tactic. Without visibility into margins, they can silently erode profitability.

🛠 Tools: Power BI | DAX | Data Modeling | Data Analysis

---

## 🎯 Business Objectives

This project was built to answer the following business questions:

1. Which are the **Top and Bottom 5 products** based on Sales, Profit, and Quantity Sold?
2. How do **sales trends change over time** (daily, monthly, quarterly, yearly)?
3. What is the relationship between **Net Sales and Profit**?
4. How does performance vary between **two selected time periods**?
5. What is the **average discount offered** across different promotion categories?
6. How many **total orders** were placed in a selected period?
7. How do Sales, Net Sales, Profit, and Discounts vary at the **order level**?
8. How is **sales distributed geographically** across cities?

---

## 🗂 Dataset & Data Model

The data is modeled using a **star schema** to ensure performance, clarity, and accurate analysis.

### Fact Table
- Order ID  
- Order Date  
- Customer ID  
- Product ID  
- Promotion ID  
- Quantity Sold  
- Discount Percentage  
- Discount Amount  
- Net Sales  
- Profit  

### Dimension Tables
- **Dim Customers**: Customer Name, City, Region  
- **Dim Products**: Product Name, Category  
- **Dim Promotions**: Promotion Name, Promotion Type  
- **Date Tables**: Used for time intelligence and period comparison  

---

## 🔗 Data Modeling Approach

- One-to-many relationships between dimension tables and the fact table  
- Separate date tables to support **period-over-period comparison**  
- Relationship directions configured to support correct slicer interaction  

This structure ensures accurate aggregation and smooth interactive filtering across all visuals.

---

## 📊 Dashboard Features

### 1. Sales Overview
- Total Sales, Profit, and Quantity Sold  
- Total Number of Orders  
- Sales trends over time  
- Net Sales vs Profit analysis  
- Average Discount by Promotion Category  
- City-wise sales distribution (Map)

**Insight:** High sales volume does not always translate into high profit, especially under heavy discounting.

---

### 2. Product Performance Analysis
- Top 5 and Bottom 5 products by:
  - Sales  
  - Profit  
  - Quantity Sold  

**Insight:** Some products drive revenue but contribute weak margins.

---

### 3. Period Comparison Analysis
- Comparison of Sales, Profit, and Quantity between two user-selected periods  
- Independent date slicers allow flexible time-based comparison  

**Insight:** Performance varies significantly across periods, helping identify growth and decline patterns.

---

### 4. Advanced Slicer Interaction (Key Feature)

This dashboard includes **four interconnected slicers on a single page**:
- Date  
- Customer Name  
- Product Name  
- Promotion Name  

**How slicer interaction works:**
- Selecting a **date** automatically filters customers, products, and promotions relevant to that period  
- Selecting a **promotion** (for example, *Summer Sale*) dynamically updates other slicers to show only:
  - Customers who received that promotion  
  - Products included in that promotion  

This ensures **context-aware analysis**, prevents misleading comparisons, and improves user experience.

---

## 🔍 Key Insights

- Higher sales do not always result in higher profit  
- Discount-heavy promotions can significantly reduce margins  
- Small increases in discount percentage may cause disproportionate profit loss  
- Promotion effectiveness varies across product categories  
- Sales performance differs significantly by city  

---

## 🛠 Tools & Technologies

- Power BI  
- DAX (Measures & Time Intelligence)  
- Data Modeling (Star Schema)  

---
---

## ✅ Conclusion

This project demonstrates how structured data modeling and interactive dashboards can uncover hidden patterns in sales and profitability. Rather than focusing only on revenue growth, the analysis emphasizes **profitability, discount strategy, and informed decision-making**.

The dashboard is designed to be intuitive for business users while maintaining analytical depth, making it suitable for real-world decision support.

---

## 📬 Contact

If you have feedback or suggestions, feel free to connect with me on LinkedIn.
