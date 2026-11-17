# Retail Sales and Profit Analysis

Analysis of retail sales and profit from 2009 to 2012 by region, product category, product and customer segment, to find the strongest markets and the most profitable customers.

**Tools:** Excel (cleaning and analysis), Power BI (dashboard)
**Data:** Sample retail sales dataset, 2009 to 2012, with Canadian sales regions. Source: \[add dataset source or link]

!\[Retail Sales and Profit Analysis Dashboard](images/Retail\_Sales.png)

## Headline numbers

|Metric|Value|
|-|-|
|Total sales|$14.92M|
|Total profit|$1.52M (about 10% margin)|

## Business questions and findings

**1. Which region generates the highest sales?**
The West region ($3.6M), followed by Ontario ($3.1M), Prairie ($2.8M), Atlantic ($2.0M) and Quebec ($1.5M).

**2. Which product category sells and earns the most?**
Technology is the largest category ($5.98M, 40% of sales), followed by Furniture ($5.18M, 34.7%) and Office Supplies ($3.75M, 25.1%). Technology is also the most profitable category.

**3. Which products generate the highest revenue?**
The Global Troy Executive Leather Low-Back Tilter is the top product ($276K).

**4. Which customer segment contributes the most profit?**
Corporate, with $0.60M, about 39% of total profit. Home Office and Small Business each earned $0.32M and Consumer $0.29M.

**5. What is the monthly sales trend?**
Demand changes over time and the peak month is different each year: April 2009, September 2010, November 2011 and February 2012. With all years combined, October is the highest month ($1.42M) and August the lowest ($0.94M).

## Recommendations

* Focus growth efforts on lower-performing regions such as Quebec and Atlantic.
* Plan inventory from historical monthly trends to avoid stock shortages and overstocking.
* Increase marketing for high-demand products and build on the Corporate segment.

## Cleaning and analysis (Excel)

\- Checked the data for duplicate rows and missing values, and \[removed X duplicates / found none].

\- Standardised the order date column and added Year and Month columns so sales could be compared by month and by year from 2009 to 2012.

\- Built pivot tables for sales and profit by region, product category, product and customer segment.

\- Calculated the main KPIs: total sales ($14.92M) and total profit ($1.52M), which is about a 10% margin.

\- Built the Power BI dashboard with a year filter, using sum-of-sales and sum-of-profit measures.

## Repository contents

```
├── README.md
├── data/        dataset or a link and column list
├── excel/       analysis workbook (.xlsx)
├── dashboard/   Power BI file (.pbix)
├── images/      dashboard screenshots
└── report/      report PDF
```

