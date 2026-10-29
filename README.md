# HR Employee Attrition Analysis (Excel)

An HR analytics project created in Microsoft Excel to analyze employee turnover, job satisfaction, and salary distribution using the IBM HR Analytics dataset.

## Dashboard Preview

![HR Employee Analysis Dashboard](screenshots/dashboard_preview.jpg)

## Overview

Employee turnover can be costly for organizations. In this project, I used Excel to analyze workforce data, identify key patterns behind attrition, and present the findings in a clear dashboard format.

## Dataset

- **Source:** IBM HR Analytics Employee Attrition & Performance dataset from [Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- **Size:** 1,470 employee records with 35 attributes (department, job role, monthly income, overtime, satisfaction ratings, etc.)
- The full raw data is saved in `data/employee_data.csv`.

## Excel Features Used

- **Pivot Tables:** Summarizing headcount and attrition by department, job role, and experience level
- **Formulas:** `COUNTIF`, `AVERAGEIF`, `SUMIF`, `IF` for calculating dynamic rates and KPI totals
- **Charts:** Clustered column charts for department-wise comparisons and pie charts for overall turnover split
- **Formatting:** Clean gridlines, KPI card highlights, and currency/percentage formatting

## Key Insights

- **Overall Turnover:** Out of 1,470 employees, 237 left the company, representing an attrition rate of approximately 16.1%.
- **Impact of OverTime:** Employees who worked overtime had a significantly higher attrition rate (over 30%) compared to those who did not.
- **Roles with High Turnover:** Sales Representatives and Laboratory Technicians showed the highest turnover percentages.
- **Tenure:** Employees in their first 1-2 years with their current manager were more likely to leave compared to tenured staff.

## Files in this Repo

- `HR_Employee_Attrition_Analysis.xlsx` - The complete Excel workbook with raw data, pivot summaries, and dashboard charts
- `data/employee_data.csv` - The full Kaggle CSV dataset
- `screenshots/dashboard_preview.jpg` - Screenshot of the final dashboard layout
