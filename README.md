# SQL Sales Analysis — Superstore Dataset

## Project Overview
Analyzed 9,994 retail sales transactions using PostgreSQL to uncover 
regional performance gaps, category profitability, and seasonal trends.

## Tools Used
- PostgreSQL 
- VS Code + SQLTools extension
- Dataset: Kaggle Superstore Sales Dataset (9,994 rows)

## Key Insights
- West region leads in both sales ($725K) and profit margin (14.9%)
- Central region has disproportionately low margins (7.9%) despite 3rd highest sales
- Furniture category generates high sales ($741K) but only 2.49% profit margin
- Tables sub-category alone loses $17,725 — the largest single loss driver
- Canon imageCLASS Copier is the #1 product by sales ($61,599)
- Sales peak in September and Q4 every year; January–February are consistently slowest

## Skills Demonstrated
- Aggregations (GROUP BY, HAVING)
- Window functions (RANK, running totals)
- CTEs (Common Table Expressions)
- Time-series analysis with DATE_TRUNC
- Subquery and filtering logic