Project Overview:

This project is about a Power BI dashboard designed to monitor ATM cash levels, errors for each ATM and cassette, and analyze transaction across multiple locations.

The dashboard provides total cash inflow/outflow, cassette usage, low cash alerts, and ATM-level error tracking to support operational decision-making.

Tools & Technologies:
- Power BI
- Microsoft Excel
- DAX (Data Analysis Expressions)
- Data Modeling (Star Schema)
- KPI & Trend Analysis

 Key Features:

 KPI Cards:
 
- Total Cash In
- Total Cash Out
- Net Cash
- Total Bills Out
- Cassette Errors
- Low Cash Alerts

 Trend Analysis :
- Cash In vs Cash Out Trend by Date
- Daily Transaction Monitoring

 Error Monitoring:
- ATM Error Count by Machine
- Jam Errors
- Cassette Errors
- Network Errors
- Low Cash Detection

 Geographic Analysis:
- Cash Withdrawal by Country
- Country-based filtering

 Slicers:
- ATM ID Slicer
- Country Filter
- Date Range Filter
- 
Data Model:

The project follows a structured data model:

- ATM_Transactions (Fact Table)
- ATM_Cash (Fact Table)
- ATM_Dim (Dimension Table)
- Country (Dimension Table)

Relationships created using ATM_ID and Country_Code.

Business Use Case

This dashboard helps:
- Monitor ATM 
- Detect high-error machines
- Analyze transaction patterns

