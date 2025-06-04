# Mobile-Sales-Dashboard
This Power BI project delivers an interactive dashboard to analyze mobile sales data. It covers the full data pipeline—from Excel import to modeling and visualizations—enabling users to explore trends, track KPIs, and make informed decisions. Tools used include Power BI, Power Query, and DAX.

Certainly! Here's the revised `README.md` file with **no emojis** and a fully professional tone:

---

# Mobile Sales Report

**Interactive Sales Analysis Dashboard in Power BI**

## Project Overview

This project presents an interactive Power BI dashboard developed to analyze mobile sales data and deliver actionable insights. The dashboard enables users to monitor key performance metrics, explore sales trends, and support strategic business decision-making.

---

## ETL Process

### 1. Data Import

* Imported raw sales data from an Excel file.

### 2. Data Cleaning and Transformation

* Merged and split columns for structured formatting
* Removed irrelevant rows and replaced specific values
* Standardized data types for consistency and analytical readiness

### 3. Data Modeling

* Defined one-to-many and many-to-one relationships to ensure accurate data representation and analysis

---

## Key Features

### Visuals

* Column, bar, line, area, funnel, and map charts
* Table and pie charts for detailed data exploration

### Filters and Interactions

* Drop-down slicers to filter by mobile brand, model, payment method, and month
* Visual interaction configuration using the Edit Interaction tool for a dynamic user experience

### User Experience Enhancements

* Cards displaying key performance indicators: total sales, total quantity, transactions, and average price
* Page navigator for seamless transition between dashboard sections

---

## Technologies Used

* Power BI Desktop
* Power Query
* DAX (Data Analysis Expressions)

---

## DAX Measures

Custom measures created to support deeper analysis, including:

* `SUM()`: Aggregate total sales
* `SUMX()`: Perform row-wise calculations across tables
* `COUNTROWS()`: Count total transactions
* `AVERAGE()`: Calculate average order value
* `TOTALMTD()`: Calculate month-to-date sales
* `SAMEPERIODLASTYEAR()`: Compare metrics with the same period from the previous year
* `CALCULATE()`: Apply context filters for conditional aggregation
* Custom Calendar Table: Supports time intelligence functions and analysis over various time frames

---

## Dashboard Pages

### 1. Main Dashboard

**Filters**: Mobile brand, model, payment method, and month
**Visuals Include**:

* KPI cards: Total sales, quantity, transactions, and average price
* Map: Total sales by city
* Line chart: Quantity sold by month
* Funnel chart: Customer ratings
* Pie chart: Transactions by payment method
* Bar chart: Top 3 mobile models by sales
* Area chart: Sales by day of the week
* Table: Brand, total sales, and transactions

### 2. MTD Report

**Purpose**: Analyze month-to-date sales performance
**Visuals Include**:

* Line chart: MTD sales by year, quarter, month, and day
* KPI cards: Same metrics as the main dashboard

### 3. Same Period Last Year

**Purpose**: Year-over-year performance comparison
**Visuals Include**:

* KPI cards: Total sales, quantity, transactions, and average price
* Table: Sales by year and quarter
* Column charts: Sales trends by year, month, and quarter

---

## Screenshots

Include dashboard screenshots in this section to visually support the project documentation.

---

## Usage

1. Open the `.pbix` file using Power BI Desktop
2. Refresh the dataset as needed
3. Use slicers to filter and explore the data
4. Navigate between report pages for detailed insights

---


