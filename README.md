# Amazon Sales Analysis Dashboard

This project is a Power BI dashboard designed to provide insights into Amazon's sales performance across various regions, product categories, and time periods. The dashboard is aimed at helping businesses understand key sales trends, monitor KPIs, and make data-driven decisions.

## Project Files

- **Amazon_Sales_Analysis.ipynb**: Jupyter Notebook containing data preprocessing and analysis steps. This file provides a detailed breakdown of data processing and insights generated before visualization.
- **Amazon_Sales.csv**: The raw dataset, which includes records of Amazon's sales, revenue, order quantities, customer information, and geographical distribution.
- **Amazon_Sales.pbix**: Power BI dashboard file that visualizes the insights from the Amazon sales data.

## Project Overview

### Objective

The purpose of this dashboard is to offer insights into:
- Sales performance across regions and product categories.
- Monthly and yearly revenue trends.
- Key performance indicators (KPIs) such as total revenue, total units sold, and average order value.

### Key Metrics and Visuals

- **KPIs**: Total Sales, Total Units Sold, Average Order Value, Total Revenue by Region.
- **Visualizations**:
  - Revenue by Product Category
  - Sales Trends by Month and Year
  - Geographical Sales Distribution
  - Customer Segmentation Analysis

## Data Source

The dashboard uses data from the `Amazon_Sales.csv` file, which includes the following fields:
- `Order Date`: The date the order was placed.
- `Product Category`: The category of each product sold.
- `Region`: Geographic location of the sale.
- `Order Quantity`: Number of units ordered.
- `Sales Revenue`: Revenue generated from the sale.
- `Customer Segment`: Customer demographic information.

## Setup and Installation

1. **Power BI Desktop**: Ensure you have [Power BI Desktop](https://powerbi.microsoft.com/) installed to open the .pbix file.
2. **Data Source**: The `Amazon_Sales.csv` file should be in the same directory as the .pbix file or connected within Power BI.

### Steps to Use

1. Open `Amazon_Sales.pbix` in Power BI Desktop.
2. Load the `Amazon_Sales.csv` dataset if not already loaded.
3. Refresh data to update visualizations.
4. Interact with the dashboard filters to explore specific time periods, regions, and product categories.

## How to Modify

1. **Edit Data Source**: Update the data source by clicking on `Transform Data` in Power BI to modify or clean the dataset.
2. **Customize Visuals**: Use the visualizations pane to adjust colors, chart types, or add new visuals.
3. **Add Calculated Fields**: Use DAX (Data Analysis Expressions) to create new calculated fields or measures for additional insights.

## Jupyter Notebook Analysis

The `Amazon_Sales_Analysis.ipynb` file includes preliminary data analysis, cleansing, and insights. This Jupyter Notebook should be executed in an environment with necessary libraries (e.g., pandas, matplotlib) installed. Run the notebook to see the preprocessing and data insights steps before visualization in Power BI.
