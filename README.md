# Retail Sales Performance Analysis

## 📊 Project Overview

This project analyzes retail sales performance using Microsoft Excel and the Sample Superstore dataset.

The goal was to build an interactive Excel dashboard that provides insights into sales, profit, profitability, regional performance, category performance, sub-category performance, and sales trends.

## 🗂️ Dataset

The project uses Tableau Public's Sample Superstore dataset.

Source: Tableau Public Sample Data

The dataset contains retail transaction-level information including:

- Order Date
- Sales
- Profit
- Quantity
- Category
- Sub-Category
- Region
- Segment
- Ship Mode
- Discount

> Note: Sample Superstore is a public sample dataset and does not represent real commercial transactions.

## 🎯 Business Questions

This analysis explores:

- What are the overall sales, profit, and profit margin?
- Which categories generate the most sales and profit?
- Which regions generate the most profit?
- Which sub-categories are profitable or loss-making?
- How does profitability vary across furniture sub-categories?
- How are Tables performing across different discount levels?
- How have sales and profit changed between 2024 and 2025?
- How do sales and profit trend over time?

## 🛠️ Excel Skills Used

- Excel Tables
- Structured References
- SUMIFS
- COUNTIFS
- YEAR
- Profit Margin calculations
- Year-over-Year growth calculations
- PivotTables
- PivotCharts
- Slicers
- Timeline filters
- Dashboard design
- Data validation and quality checks
- Conditional formatting
- Custom number formatting

## 🔍 Data Quality Checks

The following checks were performed before analysis:

- Total records: 10,194
- Blank Order IDs: 0
- Blank Sales values: 0
- Blank Profit values: 0
- Negative-profit records were retained because they represent genuine loss-making transactions in the dataset.

## 📈 Analysis Performed

### Overall Performance

- Total Sales: approximately ₹2.33M
- Total Profit: approximately ₹292.30K
- Overall Profit Margin: approximately 12.56%
- Total Quantity: approximately 38.7K

### Category Performance

Technology generates the highest sales among the three product categories.

Furniture has a much lower profit margin than Technology and Office Supplies despite generating substantial sales.

### Regional Performance

The analysis compares profitability across Central, East, South, and West regions.

West generates the highest total profit in the dataset.

### Sub-Category Performance

The analysis identifies both highly profitable and loss-making sub-categories.

Tables and Bookcases are loss-making sub-categories in the dataset.

### Tables & Discount Analysis

The analysis examines Table profitability across observed discount levels.

Higher observed discount levels for Tables are associated with lower profitability in this dataset.

This is an observed association and should not be interpreted as proof that discounts directly cause losses.

## 📊 Dashboard

The interactive dashboard includes:

- Total Sales KPI
- Total Profit KPI
- Profit Margin KPI
- Total Quantity KPI
- Year slicer
- Region slicer
- Category slicer
- Segment slicer
- Ship Mode slicer
- Timeline filter
- Sales and Profit by Category
- Profit by Region
- Profit by Sub-Category
- Monthly Sales and Profit Trend
- Key Business Insights

## 📁 Workbook Structure

The Excel workbook contains:

- `Raw_Data` — original dataset stored as an Excel Table
- `Data_Cleaning` — data quality checks
- `Calculations` — KPI calculations and business analysis
- `Pivot Sheets` — PivotTable-based analysis
- `Dashboard` — interactive final dashboard

## 💡 Key Takeaways

- Technology is the highest-sales category.
- West has the highest regional profit.
- Overall profit margin is approximately 12.56%.
- Tables and Bookcases generate losses.
- Tables show lower profitability at higher observed discount levels.
- 2025 sales and profit increased compared with 2024.

## ⚠️ Limitations

This analysis is based on a public sample dataset rather than live business data.

Observed relationships, such as the relationship between discount levels and Table profitability, should not be interpreted as causal relationships without further analysis.

## 💻 Tools

**Microsoft Excel**

## 👤 Author

This project was created as part of my Data Analyst portfolio to demonstrate practical Excel data analysis, PivotTables, dashboard development, and business insight generation.
