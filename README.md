# SQL Analysis of Inbound Tourism in Japan
![SQL](https://img.shields.io/badge/SQL-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

This project analyzes inbound tourism trends in Japan using SQL and Python.

## Overview
The analysis combines:
- yearly inbound visitors
- average USD/JPY exchange rate
- average REER
- tourism spending
- spending per person

Monthly tourism and exchange-rate data were aggregated into yearly data using SQL, and then merged with yearly tourism spending data.

## Tools
- Python
- pandas
- DuckDB
- matplotlib

## Analysis Flow
1. Load monthly exchange rate data and monthly inbound visitor data
2. Clean and rename columns
3. Aggregate monthly data into yearly data using SQL
4. Merge yearly tourism spending data
5. Visualize the relationship between exchange rates, visitors, and spending

## Key Outputs
- USD/JPY vs Yearly Visitors
![USD/JPY vs Yearly Visitors](images/usd_jpy_vs_visitors.png)

- USD/JPY vs Spending per Person
![USD/JPY vs Spending per Person](images/usd_jpy_vs_spending_per_person.png)

## Main Finding
The relationship between exchange rates and inbound visitors appears positive, but the relationship between exchange rates and spending per person appears stronger.
