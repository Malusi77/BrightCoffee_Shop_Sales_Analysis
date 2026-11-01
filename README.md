# ☕ Bright Coffee Shop Sales Analysis

## 📌 Project Overview

This project analyzes Bright Coffee Shop sales data for the period **1
January 2023 to 30 June 2023**. The goal is to understand sales
performance, identify customer purchasing patterns, evaluate product and
store performance, and develop practical recommendations to support
better business decisions.

The analysis uses the `Data_Processing.xlsx` workbook, which contains a
processed sales dataset, pivot-table summaries, and a dashboard
worksheet.

## 🎯 Business Objectives

-   Evaluate overall sales and revenue performance.
-   Identify monthly sales trends and changes over time.
-   Determine the strongest and weakest sales periods during the day.
-   Compare revenue across product categories and individual products.
-   Compare sales performance across store locations.
-   Identify opportunities to improve inventory planning and product
    promotion.
-   Recommend actions to improve sales and customer retention.

## 📂 Dataset Description

The workbook contains three worksheets:

  Worksheet       Description
  --------------- ----------------------------------------------
  `result`        Processed sales data used for analysis
  `PivotTables`   Summary tables aggregating sales measures
  `Dashboard`     Dashboard worksheet included in the workbook

The `result` worksheet contains **63,796 rows and 13 columns**.

### Main data fields

  Field                Description
  -------------------- -------------------------------------------
  `transaction_date`   Date associated with the sales record
  `day_name`           Day of the week
  `month_name`         Month of the transaction
  `number_of_sales`    Number of sales represented by the record
  `units_sold`         Number of units sold
  `unique_products`    Number of unique products represented
  `number_of_stores`   Number of stores represented
  `total_revenue`      Revenue associated with the record
  `time_of_day`        Sales time category
  `store_location`     Store location
  `product_category`   Product category
  `product_type`       Product type
  `product_detail`     Individual product description

## 📊 Key Performance Indicators (KPIs)

The following figures were calculated from the processed dataset:

  KPI                                       Result
  --------------------------- --------------------
  Total Revenue                         698,812.33
  Total Sales                              149,116
  Total Units Sold                         214,470
  Number of Records                         63,796
  Analysis Period               January--June 2023
  Number of Store Locations                      3

*Note: The workbook does not explicitly identify the currency, so the
revenue figures are shown without a currency symbol.*

## 🔍 Key Insights and Findings

### 1. Monthly Revenue Performance

Revenue increased considerably during the reporting period, particularly
from March onwards.

  Month           Revenue
  ---------- ------------
  January       81,677.74
  February      76,145.19
  March         98,834.68
  April        118,941.08
  May          156,727.76
  June         166,485.88

**Insight:** June recorded the highest monthly revenue, while February
recorded the lowest. The upward trend from March to June represents an
important opportunity to investigate successful sales patterns and
maintain momentum.

### 2. Sales Performance by Time of Day

  Time of Day        Revenue   Share of Revenue
  ------------- ------------ ------------------
  Morning         388,288.67              55.6%
  Afternoon       204,720.83              29.3%
  Evening         105,802.83              15.1%

**Insight:** Morning is the strongest revenue-generating period. Evening
contributes the smallest share of revenue and may offer an opportunity
for targeted promotions and customer engagement campaigns.

### 3. Revenue by Product Category

  Product Category          Revenue
  -------------------- ------------
  Coffee                 269,952.45
  Tea                    196,405.95
  Bakery                  82,315.64
  Drinking Chocolate      72,416.00
  Coffee Beans            40,085.25
  Branded Products        13,607.00
  Loose Tea               11,213.60
  Flavours                 8,408.80
  Packaged Chocolate       4,407.64

**Insight:** Coffee is the leading category, followed by tea. Together,
these categories contribute approximately 66.7% of total revenue. This
highlights their importance to the business's overall sales performance.

### 4. Best-Selling Products

The five highest-revenue individual products are:

  Product                            Revenue
  ------------------------------ -----------
  Sustainably Grown Organic Lg     21,151.75
  Dark Chocolate Lg                21,006.00
  Latte Rg                         19,112.25
  Cappuccino Lg                    17,641.75
  Morning Sunrise Chai Lg          17,384.00

**Insight:** These products are important contributors to product-level
revenue. Maintaining sufficient inventory and monitoring demand can help
reduce the risk of stockouts.

### 5. Store Location Performance

  Store Location         Revenue
  ----------------- ------------
  Hell's Kitchen      236,511.17
  Astoria             232,243.91
  Lower Manhattan     230,057.25

**Insight:** Hell's Kitchen recorded the highest revenue, followed by
Astoria and Lower Manhattan. The difference between locations is
relatively small, suggesting broadly comparable revenue performance
across the three stores.

### 6. Lower-Revenue Products

Examples of products with the lowest recorded product-level revenue
include:

  Product                           Revenue
  ------------------------------ ----------
  Dark chocolate                     755.20
  Earl Grey                        1,270.90
  Spicy Eye Opener Chai            1,335.90
  Guatemalan Sustainably Grown     1,340.00
  Lemon Grass                      1,360.40

**Insight:** These products could be investigated for promotional
opportunities, product bundling, or improved placement. Lower revenue
alone does not establish that a product is unprofitable; cost and margin
information would be needed for that conclusion.

## 💡 Business Recommendations

### 1. Launch Marketing Campaigns During Slow Time Slots

-   Introduce targeted evening promotions and limited-time offers.
-   Test afternoon discounts and product bundles.
-   Use campaigns to encourage customers to visit during quieter
    periods.
-   Compare revenue and sales activity before and after each campaign.

### 2. Maintain Stock of Best-Selling Products

-   Prioritize inventory planning for high-revenue products.
-   Monitor stock levels during peak morning periods.
-   Establish reorder thresholds based on historical demand.
-   Review product demand regularly to reduce stockouts and unnecessary
    inventory.

### 3. Promote Underperforming Products

-   Introduce sampling and targeted discounts.
-   Bundle lower-revenue products with popular coffee and tea products.
-   Improve product visibility and placement.
-   Monitor promotional performance before making product-retention
    decisions.

## 🚀 Next Steps

1.  **Automate daily sales reporting:** Develop an automated reporting
    process to monitor revenue, units sold, product performance, and
    store performance.
2.  **Track multiple locations:** Expand the reporting framework to
    accommodate additional stores and compare performance consistently.
3.  **Implement customer loyalty programmes:** Use purchasing patterns
    and peak customer time slots to develop targeted rewards and
    encourage repeat visits.
4.  **Monitor business performance:** Establish regular reviews of KPIs
    and promotional results to support data-driven decisions.

## 🛠️ Tools and Skills Demonstrated

This project demonstrates the following data analytics concepts and
skills:

-   Data processing and preparation.
-   Data aggregation and summarization.
-   Exploratory data analysis (EDA).
-   Key performance indicator (KPI) analysis.
-   Monthly sales trend analysis.
-   Product and category performance analysis.
-   Time-of-day sales analysis.
-   Store-level performance comparison.
-   Business insight generation.
-   Data-driven recommendations.
-   Dashboard and business reporting.

**Workbook:** `Data_Processing.xlsx`\
**Reporting period:** January--June 2023\
**Project type:** Sales Data Analysis / Business Intelligence

## 📌 Conclusion

The analysis highlights the importance of coffee and tea sales, the
strength of morning trading, and the substantial revenue growth recorded
between March and June 2023. It also identifies opportunities to improve
evening sales, optimize inventory, and promote lower-revenue products.

By automating reporting, expanding location-level tracking, and
introducing targeted loyalty programmes, Bright Coffee Shop can use its
sales data to make more informed operational and marketing decisions.

------------------------------------------------------------------------

*This project is presented as part of a data analytics portfolio to
demonstrate the use of sales data in identifying business trends,
communicating insights, and developing actionable recommendations.*
