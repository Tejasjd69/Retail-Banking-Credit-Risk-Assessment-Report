# Retail-Banking-Credit-Risk-Assessment-Report
Banks face high financial risk when approving loans due to uncertain repayment behavior. Without proper data analysis, lending decisions can lead to increased defaults and losses. The challenge is to use data-driven insights to minimize risk and improve decision-making.

Problem Statement

Banks face significant financial risk when approving loans due to uncertain customer repayment behavior. Without structured data analysis, lending decisions can lead to increased defaults and revenue losses. The project aims to leverage data analytics to improve risk assessment and enhance lending strategies.

Dataset Description

The dataset consists of multiple interrelated tables, including Clients-Banking, Banking Relationship, Investment Advisor, Gender, and Period. These tables are connected using primary and foreign keys to ensure relational integrity and accurate analysis.

Data Preparation and Transformation

Data cleaning and transformation steps included:

Creation of calculated columns such as Engagement Timeframe and Engagement Days using DATEDIFF.

Income categorization into defined Income Bands.

Implementation of Processing Fees logic based on fee structure.

Structured data modeling to enable effective reporting.

Key DAX Functions Used

SUM() for aggregations

DISTINCTCOUNT() for calculating total clients

SUMX() for dynamic fee calculations

SWITCH() for conditional logic

DATEDIFF() for engagement duration analysis

Key Performance Indicators

Total Clients

Total Loan (Bank Loan, Business Lending, Credit Card Balance)

Total Deposit

Total Fees

Engagement Length

Account-wise Deposit Distribution

Dashboard Insights

The dashboard provides insights into loan distribution, deposit analysis, client segmentation, engagement trends, and bank performance comparison. It enables management to make informed, data-driven lending decisions.

Tools and Technologies

Microsoft Power BI

DAX (Data Analysis Expressions)

Data Modeling and Visualization
