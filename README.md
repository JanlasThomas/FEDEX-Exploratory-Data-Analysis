1. Project Overview

This project conducts a comprehensive Exploratory Data Analysis (EDA) on the SCMS Delivery History Dataset, which captures shipment data for global health commodities. The primary goal is to evaluate the efficiency and reliability of the international medical supply chain, uncovering patterns in logistics, pricing, and delivery performance across different regions.

2. Objectives

Logistics Optimization:
Analyze the distribution and performance of various shipment modes (Air, Truck, Ocean) to assess their impact on delivery reliability and efficiency.
Cost Analysis:
Investigate relationships between Unit Price, Line Item Value, and Insurance Costs to understand cost drivers and pricing consistency.
Performance Benchmarking:
Identify regional risk zones by evaluating delivery delays across countries and managing offices, enabling targeted improvements.
Operational Efficiency:
Examine the influence of Lead Times (from PO sent to scheduled delivery) and Incoterms on the likelihood of on-time delivery.

3. Dataset Characteristics

The dataset comprises 10,000+ shipment records, including:

Categorical Variables:
Shipment Mode, Country, Managed By, Vendor Inco Term, Product Group
Numerical Variables:
Weight (Kilograms), Unit Price, Line Item Value, Insurance (USD)
Temporal Variables:
PO Sent Date, Scheduled Delivery Date, Actual Delivery Date
4. Technical Approach

The analysis was performed using the Python data science ecosystem:

Data Wrangling:
Utilized pandas for data cleaning, including type conversion (e.g., handling non-numeric entries), missing value imputation (median/mode), and feature engineering (e.g., calculating Delivery Delay and Lead Time).
Visualization:
Employed Seaborn and Matplotlib to create insightful visualizations such as box plots, violin plots, density plots, and multivariate scatter plots, including log-scaled analyses for skewed data.
Statistical Validation:
Applied correlation analysis and distribution checks to validate key hypotheses and identify potential supply chain bottlenecks.
5. Key Outcomes

This EDA provides actionable insights to support strategic decision-making, including:

Optimizing shipment mode selection to balance cost and reliability
Standardizing unit measures and packaging for improved warehouse efficiency
Enhancing delivery predictability through better lead time planning and buffer management
Identifying high-risk regions and processes for targeted operational improvements
