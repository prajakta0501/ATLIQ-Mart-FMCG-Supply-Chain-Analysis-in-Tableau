# ATLIQ-Mart-FMCG-Supply-Chain-Analysis-in-Tableau
**Problem Statement** 
AtliQ Mart, a growing FMCG manufacturer in India, was facing significant customer churn. Several key customers were not renewing their annual contracts due to persistent delivery service issues, including orders not being delivered on time or in full. To address this and safeguard its expansion plans, management required a comprehensive analytics solution to track and improve delivery performance.

This project involved creating an interactive Tableau dashboard to provide the supply chain team with daily insights into three critical Key Performance Indicators (KPIs): On-Time Delivery (OT) %, In-Full Delivery (IF) %, and On-Time In-Full (OTIF) %.

Final Dashboard Preview Data Model (Star Schema) A robust star schema was implemented in Tableau to support the analysis. The model centers on the fact_orders_aggregate table for high-level KPIs, which is connected to four dimension tables: dim_customers, dim_date, dim_products, and dim_targets_orders. A secondary, more granular fact_order_lines table was used for detailed product-level analysis.

ETL Process: All data was provided in CSV format and was cleaned and transformed in Tableau. Key steps in the ETL process included:

Connecting to multiple CSV source files.

Verifying and correcting data types for all 6 tables.

Ensuring clean and consistent column headers.

The data was then loaded into Tableau Public.

Calculated Fields: Created several calculated fields for the dashboard visuals. 

Insight 1: The Problem is Systemic: The overall OTIF performance was extremely low at 29%. This poor performance was consistent across all three major cities, indicating a widespread operational issue rather than a localized one.

Insight 2: Ahmedabad is the Epicenter: Despite the widespread nature of the problem, the analysis of the customer matrix revealed that the most critical, high-volume customers with the worst OTIF performance were all concentrated in Ahmedabad.

Insight 3: Dairy is the Root Cause: A deeper analysis of the Ahmedabad-based customers showed that their order volume was overwhelmingly dominated by the Dairy product category. This strongly suggests that the root cause of the delivery failures is tied specifically to the dairy supply chain.

Final Recommendation: Based on these insights, the key recommendation for the management team is to conduct a targeted root cause analysis of the end-to-end supply chain for Dairy products in Ahmedabad. This should include an immediate investigation into warehouse inventory levels, picking/packing processes, and last-mile delivery logistics for this specific segment to make the largest and fastest impact on improving performance and retaining key customers.
