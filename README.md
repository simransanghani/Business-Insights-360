# Business-Insights-360

## Problem Statement 
Atliq Hardware (fictional company) is a prominent computer hardware manufacturer in India and has also successfully expanded its presence in other countries. The company specializes in selling computers and computer accessories through three different channels: retailers, direct sales, and distributors. However, the company recently encountered an unexpected setback when it opened a store in America, with the aim of surpassing its competitors in the market and making data-driven decisions based on surveys. This project is expected to address stakeholders' concerns across various aspects such as finance, sales, marketing, and the supply chain.

## Tech Stack Used 
- SQL
- Microsoft Power BI
- Excel
- DAX language
- DAX Studio (For Optimizing the Report)
- Project Charter File

## Business Related Terms
- Fiscal year : The duration of the project spans a fiscal year, which begins in September instead of the traditional calendar year starting in January. 
               This decision is based on the fact that the company experiences its peak sales during the particular month.

- Gross sales amount = Quantity * Price of the product in a specific Fiscal Year 

- Pre-invoice discount amount = Pre-invoice Discount Percentage * Gross Sales Amount 

- Net invoice Sales Amount = Gross Sales Amount - Pre-Invoice Discount Amount 

- Net Sales = Net Invoice Sales Amount - Post-Invoice Discount Amount 

- Cost Of Goods Sold = Manufacturing Cost + Freight (Transportation) Cost  + Other Costs 

- Gross Margin = Net Sales - Cost of Goods Sold

- Net Profit = Gross Margin - Operational Cost (This Cost is associated with Spending on Marketing, Promotions , etc)

- Net Profit % = Net Profit / Net Sales 

- Gross Margin % = Gross Margin / Net Sales 

- Gross Margin per unit = Gross Margin / Quantity 

- Absolute Net Error = Forecast Quantity - Sales Quantity

- Absolute Net Error % = Sum of absolute Error / Sum of Forecast Quantity

- Forecast Accuracy = 1 - Absolute Net Error 

## Dataset 

1. dim_customer: Contains customer-related data
2. dim_product: Contains product-related data
3. fact_gross_price: Contains gross price information for each product
4. fact_manufacturing_cost: Contains the cost incurred in the production of each product
5. fact_pre_invoice_deductions: Contains pre-invoice deductions information for each product
6. fact_sales_monthly: Contains monthly sales data for each product.



## Dashboard Overview
This interactive Power BI dashboard includes **multiple views**, each designed to provide actionable insights.

### Home Page
- **Navigation Panel**: One-click access to different dashboard views.

---

### Finance View
- **Profit & Loss Matrix** – Summarizes financial performance.
- **Net Sales Trend** – Tracks revenue growth.
- **Top/Bottom Customers & Products** – Identifies key revenue drivers.
- **Gross Margin & Net Profit Analysis** – Provides insights into profitability.
- **Pre & Post Invoice Deductions** – Helps finance teams track cost adjustments.

**🟢 Business Impact:**  
📌 Helps **finance teams** optimize pricing, cut unnecessary deductions, and improve overall profitability.

---

### Sales View
- **Customer & Product Performance** – Identifies high/low-performing customers and products.
- **Gross Margin Analysis** – Evaluates profitability per product/customer.
- **Unit Economics** – Tracks **COGS and deductions** for pricing optimization.

**🟢 Business Impact:**  
📌 Supports **sales teams** in targeting high-value customers and refining sales strategies.

---

### Marketing View
- **Market, Region & Customer Analysis** – Identifies profitable regions and customers.
- **Product Performance Metrics** – Highlights best-selling and underperforming products.
- **Operational Expense Breakdown** – Tracks advertising and marketing expenditures.

**🟢 Business Impact:**  
📌 Enables **marketing teams** to allocate budgets effectively and improve campaign targeting.

---

### Supply Chain View
- **Forecast Accuracy & Net Error Trend** – Compares predicted vs. actual demand.
- **Stock Risks (OOS & Excess Inventory)** – Flags inventory issues.
- **Customer & Product KPIs** – Assesses supply chain efficiency.

**🟢 Business Impact:**  
📌 Helps **supply chain managers** reduce **stockouts and overstocking**, ensuring **better inventory planning**.

---

### Executive View
- **High-Level KPI Summary** – Quick insights into **net sales, gross margin, and net profit**.
- **Comparative Analysis** – Benchmarks performance against targets.
- **Actionable Recommendations** – Suggests key strategies based on data trends.

**🟢 Business Impact:**  
📌 Provides **CEOs & decision-makers** with a **bird’s-eye view** for strategic growth.


## Screenshots

In Home Page, All the View's Buttons will appear. User will land on  a Specific View Page by clicking the button 

- Home Page
![Home Page](https://github.com/simransanghani/Business-Insights-360/blob/main/Snapshot%20of%20Dashboard/Snapshot%20of%20Home%20Page.png)

- Information
![Description](https://github.com/simransanghani/Business-Insights-360/blob/main/Snapshot%20of%20Dashboard/Snapshot%20of%20Information.png)

- Finance View
![Finance View](https://github.com/simransanghani/Business-Insights-360/blob/main/Snapshot%20of%20Dashboard/Snapshot%20of%20Finance%20View.png)

- Sales View
![Sales View](https://github.com/simransanghani/Business-Insights-360/blob/main/Snapshot%20of%20Dashboard/Snapshot%20of%20Sales%20View.png)

- Marketing View
![MARKETING View](https://github.com/simransanghani/Business-Insights-360/blob/main/Snapshot%20of%20Dashboard/Snapshot%20of%20Marketing%20View.png)

- Supply Chain View
![Supply Chain View](https://github.com/simransanghani/Business-Insights-360/blob/main/Snapshot%20of%20Dashboard/Snapshot%20of%20Supply%20Chain%20View.png)

- Executive View
![Executive View](https://github.com/simransanghani/Business-Insights-360/blob/main/Snapshot%20of%20Dashboard/Snapshot%20of%20Executive%20View.png)

## Project Outcome

By Using this Report, Data Driven Decisions can be taken. 
