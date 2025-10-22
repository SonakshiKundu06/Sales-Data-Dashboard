# Sales Data Analysis Dashboard

## Project Overview
This project involves the development of a comprehensive **Sales Data Analysis Dashboard** using Power BI. The dashboard transforms raw sales data into actionable business intelligence, providing key insights into product performance, regional sales distribution, and seasonal trends.

## Project Structure
The project is divided into two main phases:
1.  **Data Preparation & Transformation:** Using Power Query to clean and shape the raw data.
2.  **Data Visualization & Analysis:** Building interactive reports and dashboards in Power BI.

## Data Source
- **File:** `Sales_clean` (or similar raw data source)
- **Contents:** The dataset contains sales transaction records with the following key columns:
  - `OrderID`
  - `OrderDate`
  - `CustomerName`
  - `ProductName`
  - `Region`
  - `UnitPrice`
  - `Quantity`
  - `Size`

## Data Transformation Steps (ETL)
The raw data was cleaned and prepared using Power Query with the following applied steps:

- **Promoted Headers:** Set the first row as column headers.
- **Changed Type:** Corrected data types for all columns (e.g., Date, Text, Number).
- **Text Standardization:** 
  - `Trimmed Text`: Removed leading/trailing spaces.
  - `Cleaned Text`: Removed non-printable characters.
  - `Capitalized Each Word`: Standardized text casing.
- **Data Integrity:**
  - `Removed Duplicates`: Eliminated duplicate records.
  - `Filled Down`: Populated missing values from previous rows.
  - `Replaced Values`: Corrected inconsistent entries and typos.
- **Structural Refinement:**
  - `Split Column by Delimiter`: Separated combined fields.
  - `Removed Columns`: Deleted unnecessary columns.
  - `Renamed Columns`: Updated column names for clarity.

## Key Visualizations & Insights
The dashboard includes the following main analyses:

### 1. Average Unit Price by Product
- **Purpose:** Compare pricing tiers across the product portfolio.
- **Insight:** Identifies premium products (e.g., Laptops) vs. budget-friendly items.

### 2. Sum of Unit Price by Size
- **Purpose:** Analyze revenue contribution by product size variants.
- **Insight:** Highlights the most profitable product sizes (e.g., 6-inch screens drive highest revenue).

### 3. Order Count by Region
- **Purpose:** Understand geographical sales distribution.
- **Insight:** Reveals regional performance gaps (North, West, East each have 30% share vs. South at 10%).

### 4. Average Unit Price & Quantity by Region
- **Purpose:** Correlate pricing strategy with sales volume across regions.
- **Insight:** Helps identify regions favoring premium products vs. high-volume, lower-price markets.

### 5. Sales Count by Month
- **Purpose:** Identify seasonal trends and peak sales periods.
- **Insight:** Key months like September, June, and January show highest sales activity.

## How to Use
1.  Open the `SalesData.pbix` file in Power BI Desktop.
2.  The report pages contain interactive visualizations.
3.  Use filters and slicers to drill down into specific products, regions, or time periods.
4.  Hover over chart elements to see detailed tooltips.

## Business Applications
- **Strategic Planning:** Inform product pricing and portfolio decisions.
- **Resource Allocation:** Optimize inventory and marketing efforts based on regional performance and seasonal trends.
- **Performance Monitoring:** Track key sales metrics against business goals.

## Technical Requirements
- Microsoft Power BI Desktop
- Basic understanding of data analysis concepts

---
*Project by Sonakshi Kundu | Last Updated: October 2025*
