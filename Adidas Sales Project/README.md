# Adidas Sales Analysis Dashboard

## Project Overview

This project is an interactive **Adidas Sales Analysis Dashboard** built
entirely in **Microsoft Power BI**.

The objective is to analyze Adidas sales performance across regions,
states, retailers, products, sales methods, and time periods, and
provide stakeholders with an easy-to-use dashboard for monitoring
business performance and identifying sales trends.

The complete data preparation and analysis workflow was performed inside
Power BI:

**Excel Dataset → Power Query → Data Cleaning & Transformation → Data
Model & DAX Measures → Interactive Power BI Dashboard**

------------------------------------------------------------------------

## Business Problem

Adidas needs a centralized dashboard to understand overall sales and
profitability and identify the major factors contributing to business
performance.

The dashboard is designed to help stakeholders:

-   Monitor total sales and total profit.
-   Track total units sold and average price per unit.
-   Evaluate average profit margin.
-   Analyze monthly sales trends and seasonal patterns.
-   Compare sales performance across regions and states.
-   Evaluate retailer and product performance.
-   Analyze different sales methods.
-   Identify top-performing products and retailers.
-   Filter the analysis by date and sales method.

------------------------------------------------------------------------

## Dataset

**Dataset:** Adidas US Sales Dataset

**Source file:** `Adidas US Sales_Datasets.xlsx`

The dataset contains **9,653 sales records** and includes the following
fields:

  Column             Description
  ------------------ ---------------------------------------
  Retailer           Name of the retailer
  Retailer ID        Unique retailer identifier
  Invoice Date       Date of the sales transaction
  Region             Sales region
  State              U.S. state
  City               Sales city
  Product            Adidas product/category
  Price per Unit     Selling price per unit
  Units Sold         Number of units sold
  Operating Profit   Profit generated from the transaction
  Operating Margin   Operating profit margin
  Sales Method       Method/channel used for the sale

------------------------------------------------------------------------

## Tools & Technologies

-   **Microsoft Power BI**
-   **Power Query** -- Data cleaning and transformation
-   **DAX** -- KPI calculations and analytical measures
-   **Power BI Data Model** -- Data organization and analysis
-   **Microsoft Excel** -- Source dataset

> No SQL, Python, or external data-cleaning tools were used in this
> project. The complete analysis workflow was performed within Power BI.

------------------------------------------------------------------------

## Data Cleaning & Transformation

The source Excel dataset was imported directly into Power BI and
prepared using **Power Query**.

The data preparation process included:

-   Reviewing the structure and data types of columns.
-   Setting appropriate data types for dates and numerical fields.
-   Checking the dataset for data-quality issues.
-   Preparing the `Invoice Date` field for time-based analysis.
-   Preparing categorical fields such as Region, State, Retailer,
    Product, and Sales Method.
-   Preparing numerical fields such as Price per Unit, Units Sold, and
    Operating Profit for analysis.
-   Creating the required transformed fields for dashboard analysis.

------------------------------------------------------------------------

## KPI Analysis

The dashboard provides the following key performance indicators:

### Total Sales

Measures the overall revenue generated from Adidas sales.

### Total Profit

Measures the total operating profit generated from sales.

### Total Units Sold

Shows the total quantity of products sold.

### Average Price per Unit

Shows the average selling price of the products.

### Average Profit Margin

Measures the average profit margin generated from sales.

These KPIs provide stakeholders with a quick overview of overall
business performance.

------------------------------------------------------------------------

## Dashboard Analysis

The Power BI dashboard contains the following analytical views:

### 1. Monthly Sales Trend

Analyzes sales performance over time and helps identify:

-   Monthly sales patterns
-   Growth and decline periods
-   Seasonal trends
-   Changes in sales performance

### 2. Sales by State

Provides a geographical view of sales performance across U.S. states and
helps identify high-performing and low-performing locations.

### 3. Sales by Region

Compares sales contribution across different regions to understand
regional performance.

### 4. Sales by Product

Analyzes product-level sales performance and helps identify
products/categories contributing the most to total sales.

### 5. Sales by Retailer

Compares retailer performance based on total sales and helps identify
the strongest retail partners.

### 6. Sales Method Analysis

Allows stakeholders to analyze sales performance across different sales
methods.

### 7. Interactive Filters

The dashboard provides interactive filtering capabilities, including:

-   Sales Method
-   Month
-   Year

These filters allow users to perform focused analysis without changing
the underlying dataset.

------------------------------------------------------------------------

## Key Business Questions

The dashboard was designed to answer questions such as:

1.  What is the total sales generated by Adidas?
2.  What is the total operating profit?
3.  How many units were sold?
4.  What is the average price per unit?
5.  What is the average profit margin?
6.  How do sales change month by month?
7.  Which regions generate the highest sales?
8.  Which states perform best in terms of sales?
9.  Which products contribute the most to sales?
10. Which retailers generate the highest sales?
11. Which sales methods contribute most to overall sales?
12. Are there noticeable seasonal sales patterns?

------------------------------------------------------------------------

## Dashboard Features

-   Interactive KPI cards
-   Monthly sales trend analysis
-   Regional sales comparison
-   State-level sales analysis
-   Product performance analysis
-   Retailer performance analysis
-   Sales method analysis
-   Date filtering
-   Interactive slicers
-   Business-focused visualizations

------------------------------------------------------------------------

## Project Workflow

``` text
Adidas Excel Dataset
        ↓
Import into Power BI
        ↓
Power Query
(Data Cleaning & Transformation)
        ↓
Power BI Data Model
        ↓
DAX Measures & KPIs
        ↓
Interactive Visualizations
        ↓
Adidas Sales Dashboard
        ↓
Business Insights
```

------------------------------------------------------------------------

## Project Structure

``` text
Adidas-Sales-Project/
│
├── Adidas US Sales_Datasets.xlsx
├── Adidas Analysis Problem Statement.pptx
├── README.md
│
└── images/
    ├── Adidas_logo.png
    ├── Total Sales.png
    ├── Total Profit.png
    ├── Total unit sold.png
    ├── Avg price per unit.png
    ├── Profit Margin.png
    └── 6159296.png
```

------------------------------------------------------------------------

## Skills Demonstrated

This project demonstrates practical skills in:

-   Power BI
-   Power Query
-   Data Cleaning
-   Data Transformation
-   DAX
-   KPI Development
-   Data Modeling
-   Data Visualization
-   Business Analysis
-   Sales Performance Analysis
-   Profitability Analysis
-   Time-Series Analysis
-   Regional Analysis
-   Retailer Analysis
-   Product Analysis
-   Interactive Dashboard Development

------------------------------------------------------------------------

## Conclusion

The Adidas Sales Analysis Dashboard converts raw sales data into an
interactive business intelligence solution using **Power BI**.

By combining Power Query for data preparation, DAX for KPI calculations,
and interactive Power BI visualizations, the project provides
stakeholders with a clear view of sales, profit, product performance,
retailer performance, regional performance, and sales trends.

The dashboard can support business decisions related to **sales
strategy, product performance, regional growth, retailer management, and
overall profitability**.
