# SuperStore Sales Analysis & Forecasting Dashboard \| Power BI

An interactive Power BI project for exploring SuperStore sales
performance, profitability, customer segments, regional trends, product
categories, shipping modes, and short-term sales forecasts.

## Project Overview

This project uses sales transaction data to build an interactive
dashboard that helps users understand historical business performance
and explore expected sales trends. The report is organized into two main
views:

-   **Sales Analysis Dashboard** --- summarizes key performance
    indicators and compares sales across regions, customer segments,
    payment modes, shipping methods, product categories, and
    sub-categories.
-   **Sales Forecasting Dashboard** --- visualizes historical sales over
    time and presents a **15-day sales forecast** using Power BI's
    forecasting functionality.

The dashboard includes KPI cards, charts, a state-level map, and
interactive region filters to support exploratory analysis.

## Objectives

-   Monitor sales, profit, order volume, and shipping performance.
-   Compare performance across regions and customer segments.
-   Identify leading product categories, sub-categories, and states by
    sales.
-   Explore monthly sales and profit trends.
-   Use time-series forecasting to examine sales trends over a 15-day
    horizon.
-   Present business data in an accessible, interactive visual format.

## Tools & Technologies

-   **Power BI Desktop** --- dashboard development, data visualization,
    interactive filtering, and forecasting.
-   **CSV / Excel** --- sales data input and data inspection.
-   **Time-series analysis** --- historical trend analysis and
    short-term forecasting.

## Dataset

The repository includes `SuperStore_Sales_Dataset.csv`, containing
**5,901 rows and 23 columns**. The fields include order and shipping
dates, shipping mode, customer and geographic details, segment, product
category and sub-category, sales, quantity, profit, returns, and payment
mode.

Key fields used for analysis include:

  -----------------------------------------------------------------------
  Area                                Example fields
  ----------------------------------- -----------------------------------
  Orders & shipping                   `Order ID`, `Order Date`,
                                      `Ship Date`, `Ship Mode`

  Customer                            `Customer ID`, `Customer Name`,
                                      `Segment`

  Geography                           `Country`, `City`, `State`,
                                      `Region`

  Products                            `Category`, `Sub-Category`,
                                      `Product Name`

  Performance                         `Sales`, `Quantity`, `Profit`

  Payment                             `Payment Mode`
  -----------------------------------------------------------------------

## Dashboard Features

### 1. Sales Analysis Dashboard

The overview page contains the following visuals and KPIs:

-   **KPI cards:** Sales, profit, orders, and average shipping days.
-   **Sales by segment:** Consumer, Corporate, and Home Office.
-   **Sales by payment mode:** COD, Online, and Cards.
-   **Regional analysis:** Central, East, South, and West.
-   **Monthly trends:** Sales and profit across the displayed years.
-   **Shipping analysis:** Standard Class, Second Class, First Class,
    and Same Day.
-   **Category and sub-category analysis:** Comparison of product groups
    by sales.
-   **Geographic view:** State-level sales and profit visualization.
-   **Interactive region filters:** Filter the report by Central, East,
    South, or West.

### 2. Sales Forecasting Dashboard

The forecasting page provides:

-   Historical sales trends over time.
-   A **15-day sales forecast** with a forecast range shown in the
    visual.
-   A state-wise sales comparison to provide geographic context.

The forecast is intended to support trend exploration and planning.
Forecast values are estimates, not guarantees of future sales.

## Key Dashboard Highlights

The dashboard currently displays the following rounded figures:

  KPI / Breakdown                                           Dashboard value
  ------------------------------- -----------------------------------------
  Total sales                                            Approximately 1.6M
  Total profit                                           Approximately 175K
  Orders                                                  Approximately 22K
  Shipping days                                                           4
  Largest customer segment                                 Consumer --- 48%
  Leading region by sales share                                West --- 33%
  Leading payment mode                                          COD --- 43%
  Leading category by sales         Office Supplies --- approximately 0.64M
  Leading sub-category shown                  Phones --- approximately 197K
  Highest-sales state shown              California --- approximately 0.34M

*Figures are rounded as displayed in the dashboard and may depend on the
report's filters and aggregation settings.*

## Repository Contents

``` text
SuperStore-Sales-Analysis-Forecasting-Dashboard/
├── Sales Analysis & Forecasting Dashboard.pbix
├── SuperStore_Sales_Dataset.csv
└── README.md
```

If you also upload the exported PDF report, it can be included in the
repository as a convenient preview for people who do not have Power BI
Desktop.

## How to View the Project

1.  Clone or download this repository.
2.  Open `Sales Analysis & Forecasting Dashboard.pbix` in **Power BI
    Desktop**.
3.  If Power BI asks for the data source, point it to the downloaded
    `SuperStore_Sales_Dataset.csv` file and refresh the data.
4.  Explore the report using the region filters and interactive visuals.
5.  Open the forecasting page to view the 15-day forecast.

> **Note:** The Power BI report is an interactive `.pbix` file. GitHub
> can store the file, but it does not render the report as an
> interactive dashboard directly in the repository page.

## Skills Demonstrated

-   Business intelligence and dashboard development
-   Data analysis and visualization
-   KPI reporting
-   Regional and product performance analysis
-   Time-series trend analysis
-   Short-term sales forecasting
-   Interactive report design

## Future Improvements

-   Add a data-cleaning and transformation summary.
-   Include a documented forecast evaluation using a suitable holdout
    period and error metric.
-   Add more detailed profitability and product-level analysis.
-   Publish the report to Power BI Service, where access and sharing
    permissions allow.
-   Add screenshots of both dashboard pages to the repository for a
    quick visual preview.

## Author

**Mehak**

B.Tech Computer Engineering

------------------------------------------------------------------------

*This project was developed for practical experience in sales analytics,
business intelligence, and forecasting using Power BI.*
