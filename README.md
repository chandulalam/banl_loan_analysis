# banl_loan_analysis

# Bank Loan Analysis (Power BI)

This project analyzes and visualizes **bank loan data** using **Power BI**.  
It provides insights into loan applications, funded amounts, repayments, and borrower details to help in decision-making.

## Features
- Interactive **Power BI dashboards**:
  - **Summary Dashboard** – Key metrics like total applications, funded amounts, repayments, interest rates, and DTI.
  - **Overview Dashboard** – Trends by month, state-wise analysis, loan terms, loan purpose, and borrower employment.
  - **Details Dashboard** – Full loan dataset view with borrower and loan information.

- **KPIs included**:
  - Total Loan Applications (MTD, MoM changes)
  - Total Funded Amount
  - Total Amount Collected
  - Average Interest Rate
  - Average Debt-to-Income (DTI) Ratio
  - Loan Status performance (Good vs. Bad loans)

## Dataset
The data is stored in the table:  
`bank_loan_data`  
with fields such as:
- Loan ID  
- Issue Date  
- Loan Amount  
- Total Payment  
- Loan Status  
- Interest Rate (`int_rate`)  
- Debt-to-Income Ratio (`dti`)  
- Borrower details (State, Employment Length, Purpose, Home Ownership, etc.)

You can use the provided **SQL script** to generate KPIs and summaries.

## How to Use
1. Download or clone this repository.
2. Open the `.pbix` file in **Power BI Desktop**.
3. Connect it to your **SQL database** (or import the `bank_loan_data.csv` if you have it).
4. Explore the dashboards.

or you can use these direct files

## Files
- `Bank-Loan-Analysis.pbix` – Power BI Dashboard
- `bank_loan_queries.sql` – SQL queries for KPI calculation
- `README.md` – Project documentation

## Screenshots
<img width="1326" height="745" alt="Overview" src="https://github.com/user-attachments/assets/8300d79e-c7e5-461f-a8da-0f1ee3f80bfa" />



## Requirements
- Power BI Desktop
- SQL Server / CSV data source (with `bank_loan_data`)
