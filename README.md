# Retail-Data-Analysis-PowerBI
End-to-end data analysis project using Excel and Power BI

# Online Retail Sales & Customer Behavior Analysis

## Project Overview
This project focuses on analyzing a retail dataset to extract meaningful business insights regarding sales performance, customer loyalty, and return patterns. The analysis was conducted in two main phases: **Data Preprocessing/KPI Calculation in Excel** and **Data Visualization in Power BI**.

## Objectives
- Clean and transform raw retail data for analysis.
- Identify Top 5 VIP customers based on revenue and order frequency.
- Analyze monthly sales trends and return rates.
- Visualize geographical sales distribution and return patterns.

## Tools Used
- **Microsoft Excel**: Data cleaning, formula-based KPI creation (`Line_Total`, `Return_Flag`), and Pivot Tables.
- **Power BI**: Data modeling, DAX measures, and interactive dashboarding.
- **GitHub**: Project documentation and version control.

## Key Features & Steps

### 1. Data Cleaning & Feature Engineering (Excel)
- Calculated **Line_Total** for each transaction (Quantity × Price).
- Created a **Return_Flag** to distinguish between "Sales" and "Returns" using conditional logic.
- Implemented a helper column for **Distinct Order Count** to bypass memory limitations and accurately count unique invoices per customer.
- Filtered out anomalies and handled data type inconsistencies (e.g., decimal separators).

### 2. Strategic Insights (Excel Pivot Tables)
- Identified the **Top 5 Customers** by total revenue.
- Analyzed customer loyalty by calculating the number of unique orders per Customer ID.

### 3. Advanced Visualization (Power BI)
- **Monthly Revenue vs. Return Rate**: A Clustered Column & Line Chart showing the correlation between sales volume and returns over time.
- **Geographical Breakdown**: A 100% Stacked Bar Chart showcasing the Sales vs. Returns ratio for the Top 10 countries.
- **DAX Measures**: Created custom measures for `Sales_Amount`, `Total_Transactions`, and `Return_Rate`.
- ! [Sales Trend](Screenshots\Στιγμιότυπο οθόνης 2025-12-28 125038.png)
  

## Key Insights
- **Customer Loyalty**: A small percentage of VIP customers contribute to a significant portion of total revenue.
- **Return Patterns**: Identified specific months with higher return rates, suggesting seasonal patterns or post-holiday return trends.
- **Market Performance**: The UK remains the primary market, but specific international markets show higher efficiency (lower return rates).

## How to View
1. Download the `online_retail_analysis.xlsx` to see the raw data and Pivot Tables.
2. Open the `Retail_Analysis_Report.pbix` in Power BI Desktop to interact with the dashboard.

*Created as part of the AI Business Project.*

![Sales Trend]
