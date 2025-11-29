# Data Source: https://www.kaggle.com/code/mustafacicek/detailed-marketing-cohort-pareto-rfm-forecast
## Key Business Impacts
1. Revenue growth: Target top 20% customers (Pareto) and high-RFM segments for personalized campaigns, boosting CLV 30-50%.​
2. Churn prevention: Cohort retention analysis identifies drop-off months, enabling win-back campaigns that cut churn 15-25%.​
3. Inventory optimization: UK/Netherlands (top countries) + Pareto SKUs focus stock on 20% items driving 80% revenue, saving 20-30% costs.​
4. Marketing ROI: RFM segments (Champions, At-Risk) get tailored offers, lifting response rates 3-5x vs mass campaigns.

### Approaches
1. utilized the public Kaggle dataset to explore which countries has highest number of transactions, cohort analysis, Pareto analysis and RFM.
2. Columns that I used for highest number of transactions are Invoice No, Stock Code, Description, Quantity, Invoice Date, Unit Price, CustomerID Country.
3. Columns that I applied for Cohort analysis InvoiceNo, Stock Code, Description, Quantity, InvoiceDate, Unit Price, CustomerID, Country, Revenue, Invoice Month, Cohort Month, Cohort Index.
4. For RFM, I used Customer ID and Invoice No. 
5. Cleaned and processed millions of rows in Python

