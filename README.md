# **📊 Sales & Customer Performance Dashboard**

## **🔍 Overview**

I built this Power BI project to analyze end-to-end **sales performance, customer behavior, and profitability** using advanced visuals, DAX calculations, and RFM segmentation. The dashboard provides a business-ready view of how revenue is generated, which customers drive value, and where improvement opportunities lie across products, regions, and sales teams.

This project combines **data modeling, DAX, RFM scoring, What-If analysis, Pareto analysis**, and KPI-driven reporting to support effective decision-making.

---

# **📌 Key KPIs I Developed**

* **Total Sales** *(Sales – Returns)*
* **% Target Achieved**
* **% Margin** *(Profit / Sales Amount)*
---

# **📈 1. Sales Performance Analysis**

I designed a dedicated Sales Performance section with **four sub-views**, each tailored for a specific business question.

### **a) Overall Sales View**

* 4-year **historical sales trend**
* **Current year vs previous year** comparison
* Revenue, Profit, Margin%, Avg Discount KPIs
* Breakdown by **Segment**, **Category**, and **Region**

### **b) Target / Benchmark Analysis**

* Highlighted **regions, states, and categories** that achieved or missed targets
* Included **target variance** (absolute & percentage)
* Enabled quick benchmarking across business units

### **c) What-If Analysis**

* User-controlled **discount percentage slider**
* Predicted **Profit %** recalculated dynamically
* Helps decision-makers simulate the impact of discount strategies

### **d) Pareto Analysis**

* Built a **dynamic Pareto chart**
* Allowed users to pick a percentage of customers (e.g., top 10%, 20%, 30%)
* Automatically showed **what % of total sales** those customers contribute
* Helps in identifying **high-value customer clusters**

---

# **👥 2. Customer Analysis (RFM + Advanced Insights)**

### **a) RFM Segmentation**

Using the last available date in the dataset, I calculated:

* **Recency:** Sales amount in the last 180 days
* **Frequency:** Number of purchases
* **Monetary:** Total spending

I classified customers into:

* **High-value**
* **Medium-value**
* **Low-value**

Then I visualized:

* Customer distribution
* Segment-wise sales contribution
* Buying patterns & growth opportunities

### **b) Customer Scoring Model**

I built a scoring framework combining:

* RFM behaviour
* Profit impact
* Recency & activity score

This helped identify:

* Customers suitable for **targeted marketing campaigns**
* Customers at risk of churn
* Upsell-ready high-value customers

### **c) New Customer Performance (2021)**

I extracted and analyzed:

* Number of **new customers acquired in 2021**
* Their **total sales amount**
* **Total quantity purchased**
* **Total discount amount** offered

### **d) Top 5 Salespersons (State & City Level)**

For each segment, I identified:

* **Top 5 performing salespersons**
* Their **total sales** contribution
* Their **average discount %**
* Added drill-through filters for State → City → Salesperson insights

---

# **🛠️ Tools & Techniques**

* Power BI Desktop
* Power Query for ETL
* DAX Measures for KPIs
* What-If Parameters
* RFM Segmentation
* Dynamic drill-through pages
* Pareto visualization

---

# **🚀 What I Achieved**

* Transformed raw data into a **business-focused analytics dashboard**
* Automated performance measurement
* Built an effective segmentation model (RFM + scoring)
* Delivered interactive tools for strategic planning
* Enhanced decision-making through clear KPIs and insights

---

# **📎 How to Use**

1. Download the `.pbix` file
2. Open in **Power BI Desktop**
3. Refresh data if needed
4. Interact with slicers, drilldowns, and What-If parameters
