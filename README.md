# Mobile Sales Data Analysis

## Project Overview

This project analyzes mobile sales data using **Microsoft Power BI**.
The report presents key sales and profit performance indicators,
compares brand and product performance, and supports time-based analysis
through interactive dashboards.

The dashboard helps users explore sales performance by brand, product,
customer city, month, and year.

## Project Objectives

-   Monitor overall sales, profit, customer, order, and quantity
    performance.
-   Compare sales and profit across brands.
-   Identify products with higher sales values.
-   Analyze monthly sales trends.
-   Compare current-month performance with the previous month.
-   Review year-to-date (YTD) performance.
-   Explore results using interactive report filters.

## Data Model

The Power BI report uses a sales fact table and supporting dimension
tables:

  -----------------------------------------------------------------------
  Table                               Purpose
  ----------------------------------- -----------------------------------
  `FactSales`                         Central table for sales
                                      transactions and KPI calculations

  `DimBrand`                          Provides brand information,
                                      including Brand Name

  `DimProduct`                        Provides product attributes,
                                      including ProductName and Color

  `DimCustomer`                       Provides customer location
                                      information, including City

  `Dim Calender`                      Provides Month and Year fields for
                                      time-based analysis
  -----------------------------------------------------------------------

## Dashboard Pages

### 1. Sales Overview

-   KPI cards: Total Sales, Total Profit, Total Customer, Total Order,
    Total Quantity, and Average Sales.
-   Monthly Sales Trend.
-   Total Sales by Brand Name.
-   Total Sales by ProductName.
-   Total Quantity by Brand Name.
-   Total Profit by Brand Name.

### 2. Time-Based and Brand Performance

-   Current Month vs Previous Month Sales.
-   Current Month vs Previous Month Profit.
-   YTD Sales vs YTD Profit.
-   Sales vs Profit by Brand.
-   MTD Quantity vs Previous Month Quantity.
-   YTD Quantity vs MTD Quantity.

## Key Performance Indicators

-   **Total Sales:** Overall sales value.
-   **Total Profit:** Overall profit generated.
-   **Total Customer:** Customer count based on the report measure.
-   **Total Order:** Order count based on the report measure.
-   **Total Quantity:** Total quantity sold.
-   **Average Sales:** Average sales value.

KPI values depend on the data and selected filters. Open the Power BI
report to view the current results.

## Filters and Interactivity

The report provides slicers for:

-   Brand Name
-   Color
-   City
-   Month
-   Year

Use these slicers to filter visuals and compare performance for selected
segments and periods.

## Tools and Technologies

-   Microsoft Power BI Desktop
-   Power Query
-   Data modeling
-   DAX (Data Analysis Expressions)
-   Power BI charts, KPI cards, and slicers

## How to Use

1.  Open the `Data/Mobile Sales.pbix` file in Microsoft Power BI
    Desktop.
2.  Wait for the report to load and check that the data is available.
3.  Open the **Sales Overview** page to review the main KPIs and sales
    visuals.
4.  Open the second page to review monthly and YTD comparisons.
5.  Use the slicers to filter the report by brand, color, city, month,
    or year.
6.  Select or clear filters to compare different segments.

## Project Folder Structure

``` text
Mobile-Sales-Analysis/
│
├── Data/
│   └── Mobile Sales.pbix
│
├── Documentation/
│   └── Mobile_Sales_Project_Documentation.docx
│
├── Screenshot/
│   ├── Sales_Overview.png
│   └── Sales_Analysis.png
│
└── README.md
```

## Project Files

-   **Data/** -- Contains the Mobile Sales Power BI report (`.pbix`).
-   **Documentation/** -- Contains the detailed Mobile Sales project
    documentation.
-   **Screenshot/** -- Contains screenshots of the Power BI dashboard
    pages.
-   **README.md** -- Provides the project overview, objectives, tools,
    folder structure, and usage instructions.

## Conclusion

This project demonstrates an interactive mobile sales analysis workflow
in Power BI. It brings together sales, brand, product, customer, and
calendar information to support KPI monitoring, product and brand
comparisons, and time-based performance analysis.

------------------------------------------------------------------------

**Note:** This README describes the report structure and visuals.
Specific numerical findings and rankings should be added only after
checking the actual report results and filter selections.
