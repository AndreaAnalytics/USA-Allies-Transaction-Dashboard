# USA-Allies-Transaction-Analysis
The **USA Allies Transaction Analysis** The USA Allies Transaction Analysis was cleaned in Excel, imported into SQLite for efficient data retrieval and management, and visualized in Power BI for comprehensive reporting and insights. It compares the distribution of illegal and legal transactions across various transaction types, evaluate transaction amounts by country, and provides a detailed breakdown of the total sum of money each country sent through various transaction types (e.g., Cash Withdrawal, Stocks Transfer, Offshore Transfer).


## Dataset used

[Global Black Money Transaction](https://github.com/AndreaAnalytics/USA-Allies-Transaction-Dashboard/blob/main/Big_Black_Money_Dataset.csv)


## Questions (KPIs)

- What is the percentage distribution of legal vs. illegal transactions across all transaction types?

- How much money does each country transfer across different transaction types?

- What is the total sum of money transferred by each country, and which countries are leading in terms of transaction volume?

- Dashboard Interactive <a href="https://github.com/AndreaAnalytics/USA-Allies-Transaction-Dashboard/blob/main/USA%20Allies%20Transaction%20Dashboard.png">View Dashboard</a>

## Process

- Imported the raw USA Allies Transaction dataset into Excel.

- Ensured data is consistent and clean for the data type, values, and data format.

- Write SQL queries to group transactions by legality (legal/illegal), sum transaction amounts by country, and calculate the total sums for different transaction types (e.g., Cash Withdrawal, Stocks Transfer, Offshore Transfer).

- Import SQLite data into Power BI for visualization and reporting.


 ## Dashboard

![USA Allies Transaction Dashboard](https://github.com/user-attachments/assets/6f6cb0ea-f600-4b49-9b80-290a5119d99e)


## Project Insights
- Legal transactions dominate the dataset, accounting for 69% of all transactions, while illegal transactions make up 31%.

- Brazil demonstrates a strong performance in various transfer categories, leading Offshore Transfers with $584.7 million and making significant contributions in Stock Transfers, totaling $507.8 million. India exhibits the highest volume of Cryptocurrency transactions at $529 million, alongside $526.4 million in Stocks Transfers. Singapore distinguishes itself in Offshore Transfers with $547.5 million and in Property Purchases, amounting to $501 million. The UK maintains a balanced distribution across transfer types, notably excelling in Cash Withdrawals at $538.9 million and Stocks Transfers at $512.8 million. Meanwhile, the USA ranks first in Cryptocurrency transactions, recording $510.2 million, and shows robust activity in Cash Withdrawals, totaling $495.4 million.

- The United Kingdom leads in total transaction volume, with a remarkable $2.53 billion across all transaction types. Brazil follows closely behind, transferring $2.51 billion, while India ranks third with a total of $2.47 billion. The United States comes next, reporting $2.43 billion in transactions. Singapore also makes a significant contribution, transferring $2.49 billion, largely driven by its Offshore Transfers and Property Purchases.


## How to Use
- Download the Excel file and input case data.

- Analyze caseload trends and case status using the pre-built PowerBI tables and charts.
