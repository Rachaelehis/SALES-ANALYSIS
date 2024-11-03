# SALES-ANALYSIS
# Sales Performance Analysis for a Retail Store

## Project Overview
This project aims to analyze the sales performance of a retail store using historical sales data. The objective is to uncover insights on top-selling products, regional performance, and monthly sales trends. The findings will be displayed in an interactive Power BI dashboard.

## Data Source
The project uses a CSV file ['SALES_DATA.csv'](https://github.com/Rachaelehis/SALES-ANALYSIS/blob/main/Sales%20Data.xlsx) containing historical sales records. This dataset includes information on:
- Order details (Order ID, Date)
- Customer details
- Product details (Product type, Unit price, Quantity sold)
- Revenue generated per order
- Regional data for each sale

## Folder Structure
The repository is organized as follows:
- **data/**: Contains raw data files, including the main sales dataset (`SALES_DATA.csv`).
- **notebooks/**: Jupyter notebooks for exploratory data analysis (EDA) and initial insights.
- **scripts/**: Python scripts for data cleaning, transformations, and analysis.
- **output/**: Contains any generated files or visualizations.
- **dashboard/**: Power BI dashboard file and related resources.

## Analysis Steps
1. **Data Cleaning and Preparation**:
   - Handle missing values in key columns.
   - Convert data types for date columns and other relevant fields.
   - Calculate additional metrics if needed, such as monthly revenue or average revenue per product.

2. **Exploratory Data Analysis (EDA)**:
   - Analyze top-selling products by revenue and quantity sold.
   - Evaluate performance across different regions.
   - Identify monthly and seasonal sales trends.

3. **Visualization and Dashboard**:
   - Build an interactive Power BI dashboard to display key insights, including:
     - Top-performing products
     - Regional sales performance
     - Monthly and seasonal sales trends

