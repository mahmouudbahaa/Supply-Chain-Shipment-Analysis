# 🚚 Supply Chain & Logistics Performance Optimization (SQL)

## 📌 Project Overview
This repository contains a comprehensive relational database analysis focused on supply chain efficiency, procurement optimization, logistics cost management, and vendor risk analysis. Utilizing a structured **Star Schema**, this project transforms granular transactional records into high-level business metrics including **Total Landed Cost**, **On-Time Delivery Rates**, and **Vendor Lead-Time Volatility**.

## 🏗️ Data Architecture (Star Schema Implementation)
The analytics framework is built on a specialized Fact-Dimension architecture optimized for corporate reporting:
- **`fact_table`**: Stores operational milestones, core dollar values (Freight, Pack Price, Insurance), and volume quantities.
- **`dim_product`**: Contains SKU details, sub-classifications, and pharmaceutical details (Dosage, Molecule Test).
- **`dim_vendor` / `dim_project`**: Tracks source manufacturing sites, ownership, and target fulfillment countries.
- **`dim_fulfillment`**: Houses logistics channel details and Incoterms.

---

## 🛠️ Key Analytical Metrics Formulated

1. **Total Landed Cost ($):** $$\text{Landed Cost} = \text{Line Item Value} + \text{Freight Cost} + \text{Insurance}$$
   Crucial for evaluating the *true* profitability of procured items by including all logistics overheads.
   
2. **Vendor Lead Time Variability:** Calculates both `AVG` and `STDEV` of procurement spans to assess which suppliers introduce chaos into the warehouse replenishment schedule.

3. **Freight Cost Percentage of Value:** Identifies financial inefficiency where transit expense outweighs the intrinsic product value.

---

## 📂 File Deliverables
- `04_Supply_Chain_Analysis.sql`: Full localized T-SQL production script containing the View layers and advanced operational analytical metrics.
- `business_insights.md`: Executive advisory briefing translating mathematical query results into strategic, bottom-line supply chain interventions.
