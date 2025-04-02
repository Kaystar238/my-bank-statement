# Bank Transaction Analysis Project

## Overview

This repository contains a comprehensive analysis of bank transactions spanning three months (January to March 2025). The dataset includes detailed records of credits, debits, and other financial activities, categorized by month, transaction type, and description. The project aims to provide insights into spending patterns, income sources, and overall financial health.

## Dataset Description

The dataset is structured into multiple sheets within an Excel file (`bank_kay.xlsx`), each focusing on a specific aspect of the transactions:

1. **Month_credit**: Summarizes total credits by month.
2. **Month_exp**: Summarizes total expenses (debits) by month.
3. **Credit_alert**: Lists incoming transactions (credits) with descriptions and amounts.
4. **Debit_alert**: Lists outgoing transactions (debits) with descriptions and amounts.
5. **Total_transaction**: Provides the total debits and credits across all months.
6. **statement**: Contains the full transaction history with details such as transaction time, description, credit/debit amounts, balance, and channel.

## Key Insights

- **Total Credits**: ₦3,001,361.40
- **Total Debits**: ₦3,124,555.73
- **Net Balance**: Negative (₦123,194.33), indicating higher expenses than income over the period.

### Monthly Breakdown:
- **January**: Credits - ₦1,042,000.64 | Debits - ₦1,076,646.10
- **February**: Credits - ₦1,006,890.54 | Debits - ₦1,053,682.30
- **March**: Credits - ₦952,470.22 | Debits - ₦994,227.33

### Top Credit Sources:
1. Transfer from Edoko Integrated Resources Ltd - ₦978,783
2. OWealth Deposit (AutoSave) - ₦937,895.70
3. Transfer from Payout - ₦637,736

### Top Debit Categories:
1. OWealth Deposit (AutoSave) - ₦937,895.70
2. OPay Card Payment - ₦694,599
3. Transfer to TITILAYO OMOLAYO EMMANUEL - ₦187,071

## Usage

1. **Data Exploration**: Use the `statement` sheet to explore individual transactions, including timestamps, descriptions, and amounts.
2. **Monthly Trends**: Analyze the `Month_credit` and `Month_exp` sheets to understand income and expenditure trends over time.
3. **Transaction Analysis**: The `Credit_alert` and `Debit_alert` sheets provide categorized views of incoming and outgoing funds.

## Tools

- The dataset is provided in Excel format (`bank_kay.xlsx`).

## Future Work

- **Visualizations**: Create charts to visualize monthly trends and top transaction categories.
- **Budgeting**: Use the data to create a budget or forecast future expenses.
- **Automation**: Develop scripts to automate the extraction and analysis of similar datasets.

