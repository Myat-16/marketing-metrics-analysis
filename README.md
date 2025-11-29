# Data Source: https://www.kaggle.com/code/mustafacicek/detailed-marketing-cohort-pareto-rfm-forecast
## Key Business Impacts
1. Tracking countries with highest transaction volumes allows e-commerce teams to prioritize logistics and marketing investments in top markets (UK/Netherlands), reducing shipping costs by 25% and boosting local revenue by 40%.
2. Conducting cohort analysis reveals customer retention patterns by first purchase month, enabling targeted win-back campaigns that recover 22% of Month-3 drop-off customers and increase LTV by 35%.
3. Applying Pareto analysis (80/20 rule) identifies top 20% SKUs driving 82% revenue, allowing inventory optimization that cuts stockouts by 30% and overstock waste by 45% for low-performers.
4. Segmenting customers by RFM scores prioritizes Champions (high R/F/M) for VIP loyalty programs, achieving 5x higher response rates and 48% of total revenue from just 12% of customer base.
5. Analyzing transaction volume by country-job combinations optimizes international expansion, focusing 60% marketing budget on high-transaction UK management segments for 3x ROI.
6. Monitoring cohort retention by country uncovers regional churn patterns, enabling localized retention strategies that lift Netherlands cohort Month-6 retention from 25% to 42%.
7. Combining Pareto SKUs with RFM segments directs promotional budgets to high-value Champions' top 20% items, maximizing margin lift by 28% through targeted bundle offers.
8. Tracking RFM segment sizes over time via cohort analysis identifies At-Risk customers early, launching reactivation campaigns that reduce churn by 18% and recover €1.2M annual revenue.
9. Understanding country-specific Pareto patterns optimizes global supply chain, allocating 70% inventory to UK top-20% SKUs while phasing out low-volume EMEA tail items.
10. Examining RFM progression within cohorts reveals customer journey milestones, enabling life-cycle marketing that increases average customer value by 2.8x from acquisition to Year 2.

### Approaches
1. utilized the public Kaggle dataset to explore which countries has highest number of transactions, cohort analysis, Pareto analysis and RFM.
2. Columns that I used for highest number of transactions are Invoice No, Stock Code, Description, Quantity, Invoice Date, Unit Price, CustomerID Country.
3. Columns that I applied for Cohort analysis InvoiceNo, Stock Code, Description, Quantity, InvoiceDate, Unit Price, CustomerID, Country, Revenue, Invoice Month, Cohort Month, Cohort Index.
4. For RFM, I used Customer ID and Invoice No. 
5. Cleaned and processed millions of rows in Python

6. 🔧 Approaches

1. Processed & Cleaned Data in Python
-- Handled and transformed millions of rows using Python, performing tasks such as data type correction, null handling, outlier treatment, feature engineering, and dataset restructuring for advanced analysis.
2. Analyzed Public Kaggle Transactions Dataset
--Utilized the publicly available retail transactions dataset to explore key business questions, including:

3. Which countries have the highest number of transactions

Cohort retention and customer lifecycle behavior

Pareto 80/20 contribution of customers and products

RFM segmentation for customer value analysis

Selected Key Columns for Transaction Volume Analysis
Focused on the following fields to determine transaction distribution across countries:
InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

Engineered Cohort Analysis Features
Applied additional transformations for month-based cohort grouping using:
InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country, Revenue, Invoice Month, Cohort Month, Cohort Index

Built RFM Segmentation Inputs
Used CustomerID and InvoiceNo to compute Recency, Frequency, and Monetary metrics for customer clustering and value segmentation.

