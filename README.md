# 🚚 Supply Chain Logistics & Procurement Analytics  
**End-to-End Data Engineering & Supply Chain BI Project using SQL Server & Power BI**

---

## 📌 Project Overview  

This project transforms complex global supply chain and procurement data into a structured analytics solution using SQL Server and Power BI.

The objective is to improve supply chain visibility, reduce operational risk, and optimize procurement decisions through data-driven insights.

The solution includes:
- Data transformation & quality control
- Star schema data warehouse design
- Advanced logistics & cost analytics
- Vendor risk & performance evaluation
- Interactive Power BI dashboards

---
## 📷 Dashboard Preview

<p align="center">
  <img src=Screenshots/Dashboard.jpg width="500">
</p>

---

## 🛠️ Tech Stack  

- SQL Server (T-SQL)  
- Power BI (DAX, Data Modeling)  
- Data Warehousing (Star Schema)  
- Advanced SQL (CTEs, CASE WHEN, STDEV, DATEDIFF)  
- Supply Chain Analytics & KPI Modeling  

---

## 🏗️ Data Architecture  

A Star Schema design was implemented to ensure scalable and high-performance analytics.

### Core Tables:
- **Fact_Analytics** → procurement transactions, cost, and logistics metrics  
- **Dim_Product** → product classification and categories  
- **Dim_Vendor** → supplier profiles and locations  
- **Dim_Project** → project and country mapping  
- **Dim_Fulfillment** → shipping modes and Incoterms  

---

## ⚙️ Key Business Logic & Transformations  

### 📦 Total Landed Cost Modeling  
Calculated full procurement cost per item:

- Product cost + freight + insurance  
→ Provides complete cost visibility per transaction  

---

### 🚚 Lead Time & Delivery Performance  
- Calculated lead time using `DATEDIFF()`  
- Measured delivery delays vs promised dates  
- Evaluated fulfillment efficiency across regions  

---

### 🌍 Geographic Segmentation  
- Regional classification (NA / EU / Asia) using CASE logic  
- Enables cross-country logistics comparison  

---

### 🧪 Data Quality Controls  
- `TRY_CAST()` for safe numeric conversion  
- `NULLIF()` to prevent division errors  
- NULL handling for consistent analytics  

---

## 📊 Advanced Analytics  

- Supplier performance variability using **STDEV**  
- Freight vs product value optimization analysis  
- Monthly landed cost trends using **EOMONTH**  
- Vendor risk scoring based on delivery consistency  
- Time-series logistics performance tracking  

---

## 📈 Executive Insights  

### 🚚 Supply Chain Performance  
- Significant variation in supplier lead times across vendors  
- Certain suppliers show high delivery inconsistency → operational risk  

---

### 💰 Cost Optimization  
- Freight cost significantly impacts total landed cost  
- Optimization opportunities exist in shipping mode selection and Incoterms strategy  

---

### ⚠️ Vendor Risk Analysis  
- High lead-time variability correlates with supply chain inefficiency  
- Unstable vendors represent strategic risk to operations  

---

### 🌍 Geographic Insights  
- Regional differences significantly affect logistics cost and delivery performance  
- Cross-country procurement requires tailored logistics strategies  

---

## 💡 Business Impact  

This analysis enables stakeholders to:

- Reduce supply chain risk through vendor performance tracking  
- Optimize procurement cost structure using landed cost analysis  
- Improve logistics efficiency and delivery reliability  
- Identify high-risk suppliers early  
- Support strategic sourcing decisions  

---

## 🚀 Conclusion  

This project demonstrates how raw supply chain data can be transformed into actionable business intelligence using SQL Server and Power BI.

It bridges the gap between data engineering, logistics analytics, and strategic procurement decision-making.

---

## 👤 Author  

**Bahaa Mandour**  
Data Analyst | Supply Chain BI Developer | SQL & Power BI Enthusiast  


