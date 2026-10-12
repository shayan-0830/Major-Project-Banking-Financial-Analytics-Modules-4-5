# Banking & Financial Analytics Platform: Modules 4 & 5

Group 4 project. This repository covers the dashboards for **Module 4 (Transaction Analytics)** and **Module 5 (Fraud Analytics)** of the Banking & Financial Analytics Platform, built in Microsoft Excel.

## Project Overview

The platform is made up of five analytics modules:

| Module | Name |
|--------|------|
| 1 | Customer Analytics |
| 2 | Loan Analytics |
| 3 | Credit Risk Analytics |
| **4** | **Transaction Analytics** (this repo) |
| **5** | **Fraud Analytics** (this repo) |

Modules 4 and 5 turn raw banking data into interactive, easy-to-read dashboards. Each module lives in its own sheet of the workbook.

## Module 4: Transaction Analytics

This dashboard analyses customer transaction activity across the bank's dataset. It helps answer questions such as how much money is moving, which transaction types and channels are most used, and how activity changes over time.

**Typical insights covered**
- Total transaction count and total transaction value
- Breakdown by transaction type and channel
- Trends over time (daily, monthly)
- High-value and unusual transaction patterns

## Module 5: Fraud Analytics

This dashboard focuses on identifying and monitoring suspicious activity. It helps the bank understand where fraud is happening, how often, and which transactions or accounts carry the most risk.

**Typical insights covered**
- Number and share of flagged or fraudulent transactions
- Fraud by transaction type, channel, and time period
- High-risk accounts and patterns
- Fraud amount versus normal transaction amount

## Datasets Used

| File | Purpose |
|------|---------|
| `Banking_Connected_Dataset.xlsx` | Main connected banking data (customers, accounts, transactions) |
| `Loan_Analytics_200_Rows.xlsx` | Loan data used alongside the banking dataset |

## Tools & Techniques

- **Microsoft Excel**: data cleaning, formulas, PivotTables, PivotCharts, slicers
- **Power BI** (optional): the Excel data can be imported to rebuild the dashboards

## Repository Structure

```
.
├── README.md
├── data/
│   ├── Banking_Connected_Dataset.xlsx
│   └── Loan_Analytics_200_Rows.xlsx
└── dashboards/
    └── Banking_Analytics_Dashboards.xlsx   # Module 4 and Module 5 sheets
```

## How to Use

1. Download or clone this repository.
2. Open the dashboard workbook in Microsoft Excel.
3. Go to the **Transaction Analytics** sheet for Module 4 and the **Fraud Analytics** sheet for Module 5.
4. Use the slicers and filters on each sheet to explore the data.

To open the data in Power BI: **Home → Get data → Excel workbook**, select the file, and click **Load**.

## Team

Group 4

- Mohammad Shayan Ansari: Module 4 (Transaction Analytics) and Module 5 (Fraud Analytics)
