# Ecommerce_Dashboard:
An interactive **Power BI Ecommerce Dashboard** built to analyze sales performance, customer behavior, product categories, payment methods, and profitability across different states and quarters.

---
##  Project Overview:
This dashboard helps businesses monitor key sales metrics and gain actionable insights from ecommerce transaction data. It provides a clear view of revenue, profit, quantity sold, customer contribution, category performance, and payment preferences.

---
##  Business Objectives:
- Track overall sales and profit performance.
- Analyze customer purchasing behavior.
- Identify top-performing product categories.
- Monitor state-wise sales distribution.
- Understand preferred payment methods.
- Compare quarterly and monthly profitability.
---

##  Key Performance Indicators (KPIs):

| KPI | Value |
|------|------|
| 1.KPI Cards:
   - Total Sales Amount
   - Total Quantity Sold
   - Total Profit
   - Average Order Value (AOV)
2. Visual Analysis:
  - Sales by State
  - Profit by Month
  - Quantity by Category
  - Profit by Sub-Category
  - Sales by Customer
  - Payment Mode Distribution (COD, UPI, Card)
3. Interactive Filters:
 - Quarter-wise (Q1–Q4)
 - State-wise filtering
 - Drill-down support
4. User-Friendly UI:
 -- Dark-themed professional dashboard
 -- Easy navigation and readable charts
---
##  Dashboard Features:
###  Quarterly Sales Filter
Interactive slicer to analyze data by:
- Qtr 1
- Qtr 2
- Qtr 3
- Qtr 4

###  State Filter
Allows users to filter dashboard metrics by specific states.

###  Sales Amount by State
Displays state-wise sales contribution.

###  Quantity by Category
Analyzes sales quantity across product categories:
- Clothing
- Electronics
- Furniture

###  Profit by Month
Tracks monthly profit trends and highlights profitable or loss-making months.

###  Sales Amount by Customer
Identifies top customers contributing to revenue.

###  Quantity by Payment Mode
Shows customer payment preferences:
- UPI
- COD
- EMI
- Debit Card
---
##  Tools & Technologies:
- Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Excel Dataset
---
##  Dataset Information:
The dataset contains ecommerce transaction details such as:
- Order Date
- Customer Name
- State
- Category
- Sub-Category
- Quantity
- Amount
- Profit
- Payment Mode

---

##  Sample DAX Measures:

### Total Sales
```DAX
Total Sales = SUM(Orders[Amount])
```

### Total Profit
```DAX
Total Profit = SUM(Orders[Profit])
```

### Total Quantity
```DAX
Total Quantity = SUM(Orders[Quantity])
```

### Average Order Value
```DAX
AOV =
DIVIDE(
    SUM(Orders[Amount]),
    DISTINCTCOUNT(Orders[Order ID])
)
```
### Profit Margin %
```DAX
Profit Margin % =
DIVIDE(
    SUM(Orders[Profit]),
    SUM(Orders[Amount])
) * 100
```
---

##  Key Insights:
- Clothing contributes the highest sales quantity.
- UPI is the most preferred payment method.
- Kerala generates the highest sales amount in the selected view.
- Some months show negative profit, indicating loss periods.
- Trousers are the most profitable sub-category.
- A small number of customers contribute significantly to total sales.
---
##  Outcomes:
Through this project, I learned:
- Data Cleaning using Power Query
- Data Modeling in Power BI
- Creating DAX Measures
- Interactive Dashboard Design
- KPI Analysis and Business Intelligence Reporting
---

##  Author:
**Sushanta Sahoo**
- MCA Student
- Fresher
- Aspiring Data Analyst


