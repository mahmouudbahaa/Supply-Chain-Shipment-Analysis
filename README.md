Supply Chain Logistics: Performance & Cost Optimization

📝 Project Overview
This project provides a comprehensive end-to-end data analytics solution for pharmaceutical supply chain operations. By leveraging SQL Server for data engineering and Power BI for advanced visualization, the project transforms complex logistics data into actionable insights, focusing on freight cost reduction, vendor reliability, and delivery efficiency.

🛠️ Tech Stack
Database: SQL Server Management Studio (SSMS) - T-SQL.
Data Engineering: Star Schema modeling, View-based data virtualization, and rigorous data cleaning.
Data Analysis: DAX (Data Analysis Expressions) for complex KPIs and time-series calculations.
Visualization: Power BI (Interactive Dashboards).

🚀 Key Technical Achievements
1. Data Engineering & Cleaning (SQL)
Data Virtualization: Created a robust suite of ⁠VIEW⁠ tables to structure raw data into a clean, analytical format.
Star Schema Design: Architected a star schema model in Power BI, connecting fact tables with dimension tables (Product, Vendor, Fulfillment, Project) for efficient filtering and performance.
Advanced Cleaning: Implemented ⁠TRY_CAST⁠, ⁠ISNULL⁠, and conditional logic (⁠CASE WHEN⁠) to handle missing values and data anomalies (e.g., legacy/outlier lead times), ensuring data integrity.
2. Advanced Analytics & DAX
On-Time Delivery (OTD) Tracking: Developed a dynamic DAX measure to calculate delivery reliability based on actual vs. scheduled delivery dates.
Risk Analysis: Created vendor performance profiles using statistical methods (standard deviation of lead times) to identify high-risk suppliers.
Cost Efficiency: Engineered financial metrics, including Total Landed Cost and Freight-to-Value ratios, to pinpoint cost-inefficient shipping modes.

📊 Business Insights & Dashboarding
The resulting Logistics Performance Dashboard serves as a centralized decision-support tool, enabling stakeholders to:
Monitor Operational KPIs: High-level executive view of shipments, freight spend, and delivery rates.
Identify Bottlenecks: Used scatter plots to correlate lead time volatility with freight costs, highlighting suppliers that pose risks to the supply chain.
Geospatial Analysis: Leveraged map-based visualizations to identify high-cost regions and shipment density across continents.
 
🎯 Recommendations
Based on the data-driven insights, I recommended:
1 Strategic Sourcing: Prioritizing vendors with low lead-time volatility to reduce safety stock requirements.
2 Mode Optimization: Re-evaluating shipment modes for high-cost routes identified in the freight-to-value analysis.
3 Data Governance: Improving data entry protocols at the system level to mitigate future outliers in lead-time reporting.
