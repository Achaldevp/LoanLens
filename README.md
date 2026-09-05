# LoanLens
Banking Risk &amp; Financial Analytics project using SQL, Python, EDA, and Power BI.

##  Project Overview

LoanLens is a banking analytics project developed to analyze customer, loan, deposit, and financial data and provide insights that support data-driven banking and risk analysis.

The project uses SQL, Python, Exploratory Data Analysis (EDA), and Power BI to transform banking data into meaningful business insights.

##  Problem Statement

To understand how data can be used in banking and financial services to analyze customer profiles and financial information, minimize lending risk, and support better decision-making.

##  Tech Stack

- **SQL** – Data extraction, filtering, aggregation & analysis
- **Python** – Data analysis and preprocessing
- **Pandas** – Data manipulation
- **NumPy** – Numerical analysis
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **EDA** – Exploratory Data Analysis
- **Power BI** – Interactive dashboards & reporting
- **DAX** – KPI and calculated measure development
- **Data Modeling** – Relationships between banking tables

##  Dataset

The dataset consists of multiple interconnected banking tables linked through primary and foreign key relationships.

### Tables Used

1. Banking Relationship
2. Client-Banking
3. Gender
4. Investment Advisor
5. Period

## Data Cleaning & Transformation

The following calculated/derived fields were created during the analysis:

- **Engagement Timeframe** – Represents the client's timeline with the bank.
- **Engagement Days** – Calculates the number of days since the client joined the bank.
- **Income Band** – Categorizes estimated income into defined income groups.
- **Processing Fees** – Calculates processing fees based on the fee structure.

##  DAX Functions Used
The Power BI analysis used several DAX functions, including:

- `SUM()`
- `DISTINCTCOUNT()`
- `SUMX()`
- `SWITCH()`
- `DATEDIFF()`

### Example
DAX
Total Clients =
DISTINCTCOUNT('Clients - Banking'[Client ID])

Key KPIs
The dashboard includes KPIs such as:

Total Clients
Total Loan
Bank Loan
Business Lending
Total Deposit
Bank Deposit
Savings Account
Checking Account
Foreign Currency Account
Total Fees
Credit Card Balance
Engagement Length

Power BI Dashboard

The project contains 4 main dashboard views:

Home Dashboard

Provides an overall view of banking-related metrics and customer information.

Loan Analysis

Analyzes loan exposure, business lending, and credit card-related financial information.

Deposit Analysis

Provides insights into deposits across different account types.

Summary Dashboard

Provides an overall summary of key banking KPIs and insights.

Key Insights
Analyzed total loan exposure across different customer profiles.
Compared customer distribution across banking relationships.
Identified banking loan trends across nationalities.
Analyzed different types of customer account balances.
Evaluated customer engagement with the bank.
Compared income bands and their relationship with banking metrics.

Business Insights
💡 Business Value

LoanLens demonstrates how banking data can be transformed into actionable insights through data analysis and visualization. The dashboards help analyze loans, deposits, customer profiles, account balances, and engagement to support data-driven banking decisions.



