# Global Trade Analytics

An Excel-based analysis of global trade performance across products, categories, regions and time, progressing from raw transactional data through data preparation, business metrics, analytical summaries and a professional performance dashboard.

## 📌 Project Overview

This project uses transactional trade data to examine sales, profit, profit margins, shipping costs and performance across different products, categories and geographic regions.

The workbook demonstrates an end-to-end analytics workflow in Excel, including data cleaning and formatting, business metric creation, text parsing, logical classification, lookups, conditional aggregation, pivot analysis, comparative charts and dashboard development.

The final **Trade Performance Dashboard** brings the main business metrics and performance views together into a single business-facing reporting interface.

The project demonstrates how Excel can be used not only for calculations and reporting, but also for structured business analysis and decision-oriented data visualization.

## 🎯 Business Objective

The objective of the analysis is to understand overall trade performance and identify meaningful differences across **regions, products, categories and time**.

The analysis focuses on questions such as:

* How are total sales and profit distributed across regions?
* Which products and categories contribute most to business performance?
* How does performance vary over time?
* What are the differences in sales and profitability across regions and product categories?
* How do shipping costs and profit margins relate to overall trade performance?
* Can the underlying transactional data be transformed into a concise dashboard for business-level monitoring?

The final dashboard summarizes these measures to provide a consolidated view of trade performance.

## 📊 Dataset / Data Context

The primary dataset contains **500 trade order records** covering transactions from **January 2024 through May 2025**.

Each order contains information relating to:

* Order and date details
* Customer and country
* Product and category
* Quantity and unit price
* Total sales
* Shipping cost
* Profit
* Shipping mode
* Order priority
* Region

The workbook also includes supporting reference data for:

* **10 products**, including product category, supplier, origin country and unit cost
* **6 geographic regions**
* Monthly performance information

The source data and supporting datasets are retained as part of the final project repository.

## 🔍 Analysis / Techniques

The project applies a range of Excel-based analytical techniques to move from raw transactional data to business-facing outputs.

### Data Preparation

* Data cleaning and formatting
* Standardization of source fields
* Preparation of structured data for subsequent analysis

### Business Metrics

* Cost of Goods Sold (COGS) calculation
* Profit calculation and analysis
* Profit margin calculation
* Sales and profitability metrics

### Data Transformation

* Text parsing to separate customer first and last names
* Customer code generation
* Logical classification using performance conditions

### Lookups

* Cross-workbook lookup operations
* Retrieval of product supplier and origin information
* Region-related lookup operations

### Conditional Analysis

* `SUMIFS`-based aggregation
* `AVERAGEIFS`-based analysis
* Sales and profit comparisons by region and category

### Pivot Analysis

* Pivot-based aggregation of sales and profit margins
* Region and month-based analysis
* Comparative performance analysis

### Visualization & Reporting

* Comparative charts for monthly sales and profit
* Regional and category-level comparisons
* KPI-based summary reporting
* Trade Performance Dashboard

### Excel Automation

* Macro recording as part of the workbook's Excel automation workflow

## 📈 Dashboard / Output

The final **Trade Performance Dashboard** consolidates the analysis into a business-facing view of overall trade performance.

The dashboard presents key performance indicators including:

* Total Orders
* Total Sales
* Total Profit
* Average Profit Margin
* Average Shipping Cost
* Top Region by Sales
* Top Product by Profit

It also brings together comparative views of performance across regions, products, categories and time, allowing the underlying analysis to be interpreted from a higher-level business perspective.

The supporting workbook contains the detailed calculations, conditional aggregations, pivot analysis and comparative charts used to build the final reporting output.

Dashboard screenshots are included in the repository to provide a quick visual overview without requiring Excel to be opened first.

## 💡 Key Insights

The completed analysis highlights several notable patterns in the trade data:

* **Asia is the leading region by sales**, contributing approximately **$171.2K** in sales and **$47.9K** in profit.
* **Europe is the second-highest region by sales**, with approximately **$115.2K** in sales and **$32.1K** in profit.
* **Denim Jacket is the top product by profit**, making it the strongest individual product contributor to overall profitability.
* **Home Decor generates the highest category-level sales**, at approximately **$129.9K**, followed by Electronics at approximately **$115.0K**.
* Overall trade performance comprises **500 orders**, approximately **$474.7K in total sales** and **$133.6K in total profit**.
* The overall **average profit margin is approximately 27.3%**.
* **December 2024 recorded the highest monthly sales**, at approximately **$39.1K**. Monthly performance varies across the analysis period, including a lower sales figure in May 2025.
* Regional and category-level analysis shows that performance is not evenly distributed, making segmentation useful for understanding where sales and profitability are concentrated.

These insights are presented as observations from the completed analysis rather than as predictive or prescriptive conclusions.

## 🛠️ Tools & Techniques

### Tools

* Microsoft Excel
* Excel VBA / Macros

### Core Techniques

* Data cleaning and formatting
* Formula-based business metrics
* COGS, profit and profit-margin calculations
* Text parsing and ID generation
* Logical classification
* Cross-workbook lookups
* `SUMIFS` and `AVERAGEIFS`
* Pivot analysis
* Comparative charts
* KPI reporting
* Dashboard development
* Macro recording

## 📁 Repository Structure

```text
global-trade-analytics/
│
├── README.md
│
├── Global Trade Analytics.xlsm
│
├── data/
│   ├── [original source dataset files]
│   
│
└── images/
    ├── dashboard_overview.png (![Dashboard Overview](images/dashboard_overview.png))
    └── dashboard_analysis_analysispart1.png (![Dashboard Analysis](images/dashboard_analysis_part1.png))
    └── dashboard_analysis_analysispart2.png (![Dashboard Analysis](images/dashboard_analysis_part2.png))


```

The repository contains the completed Excel workbook, the original source/supporting datasets used by the project, and dashboard screenshots for quick visual reference.

The original dataset filenames are retained rather than renamed to preserve the project artifacts as they were developed.

## 🚀 How to Explore

1. Start with the **dashboard screenshots** in the `images/` folder for a quick overview of the final output.
2. Open **`Global Trade Analytics.xlsm`** in Microsoft Excel to explore the complete project.
3. Begin with **Trade Performance Dashboard** to view the consolidated business results.
4. Explore the supporting analytical worksheets to follow the progression from data preparation and business metrics through aggregation, pivot analysis and visualization.
5. Review **Raw_Data** and the supporting reference datasets when you want to examine the underlying data structure.
6. Because the workbook contains Excel macros, open it as an `.xlsm` file and enable macros only if you want to explore the macro-related functionality.
