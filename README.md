# Stock Analysis Project

## Overview
This project analyzes stock price trends across industries using Python, Yahoo Finance API, Supabase (SQL), and Power BI. The workflow includes data collection, storage, processing, analysis, and visualization.

## Project Timeline

### Week 1: Data Collection and Storage Setup

#### Defining Project Scope and Requirements
- Identified the objective: Analyzing stock price trends across industries.
- Selected key stocks from multiple industries (Technology, Healthcare, Energy, Communication).
- Planned data storage and retrieval mechanisms.

#### Fetching Stock Data Using Yahoo Finance API
- Used the `yfinance` Python library to fetch historical stock price data.
- Extracted key attributes like Open, Close, High, and Low prices.
- Dropped unnecessary columns such as Dividends and Stock Splits.
- Standardized stock metadata (ticker, industry classification).

#### Storing Data in Supabase (SQL)
- Created a Supabase database to store historical stock price data.
- Designed appropriate table schemas for structured storage.
- Uploaded cleaned datasets to Supabase for persistent storage.
- Validated data integrity and ensured proper indexing.

---

### Week 2: Data Processing and Analysis

#### Data Cleaning and Transformation
- Ensured date-time consistency by converting timezone-aware datetime fields.
- Checked for missing values and handled them appropriately.
- Verified data consistency across different stock symbols and industries.

#### Exploratory Data Analysis (EDA) in Python
- Generated summary statistics and visualized stock trends using `matplotlib` and `pandas`.
- Compared stock performance across industries.
- Identified trends and anomalies in price movements.

#### Statistical Analysis (T-Test)
- Conducted a t-test comparing stock high and low prices across different financial quarters.
- Interpreted the results: No statistically significant difference in stock price variation across quarters (P-value > 0.05).
- Documented insights from the analysis.

---

### Week 3: Data Visualization and Reporting

#### Power BI Dashboard Setup
- Designed visualizations

#### Project Review and Final Presentation
- Reviewed the workflow, ensuring data accuracy and analysis consistency.
- Prepared a final report summarizing key findings and insights.
- Created a presentation for project evaluation.

## Conclusion
This structured 3-week approach ensured systematic data collection, analysis, and visualization, resulting in a comprehensive stock trend analysis using Python, SQL, and Power BI.

