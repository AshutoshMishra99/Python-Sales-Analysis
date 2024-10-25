# Sales Data Analysis with Python Pandas & Matplotlib

This project demonstrates the analysis of a full year of sales data for an electronics store, utilizing Python's Pandas and Matplotlib libraries to answer critical business questions. The dataset, spanning 12 months of purchases, includes product details, costs, and purchase addresses, providing a foundation for in-depth insights.

## Project Overview
The objective of this project is to answer high-level business questions to inform decision-making in areas such as sales forecasting, targeted advertising, product bundling, and inventory management. It covers data cleaning, exploration, and visualization techniques essential to a full-cycle data analysis workflow.

## Table of Contents
- [Dataset Information](#dataset-information)
- [Project Structure](#project-structure)
- [Business Questions](#business-questions)
- [Analysis Process](#analysis-process)
  1. [Data Cleaning](#1-data-cleaning)
  2. [Data Exploration and Analysis](#2-data-exploration-and-analysis)
  3. [Visualization](#3-visualization)
- [Conclusion](#conclusion)

## Dataset Information
The dataset consists of 12 CSV files, each representing sales data for a specific month. Combined, they contain hundreds of thousands of records detailing electronic purchases.

### Key Columns:
- **Order ID**
- **Product**
- **Quantity Ordered**
- **Price Each**
- **Order Date**
- **Purchase Address**

## Project Structure
- **Data Cleaning**: Removing invalid entries and converting columns to suitable data types.
- **Data Exploration and Analysis**: Answering business questions using Pandas methods.
- **Visualization**: Creating charts to visualize and communicate insights.

## Business Questions
The project addresses five key questions:
1. **Best Month for Sales**: Which month had the highest sales, and how much was earned?
2. **Top City for Sales**: Which city sold the most products?
3. **Optimal Advertisement Timing**: When should advertisements be displayed to maximize sales?
4. **Frequently Sold Together**: Which products are often purchased together?
5. **Best-Selling Product**: What was the most popular product, and why?

## Analysis Process

### 1. Data Cleaning
The initial stage involves:
- **Dropping NaN Values**: Removing rows with missing data.
- **Removing Invalid Rows**: Filtering out rows based on specific conditions.
- **Type Conversion**: Converting columns to numeric and datetime types as needed.

### 2. Data Exploration and Analysis
To answer the business questions, various Pandas techniques were employed, including:
- **Concatenating DataFrames**: Combining multiple monthly CSVs into a single DataFrame using `pd.concat`.
- **Adding Columns**: Deriving new columns for analysis, such as Sales and City.
- **String Parsing**: Extracting data from strings (e.g., parsing addresses).
- **Applying Functions**: Using `.apply()` to create new columns.
- **Aggregating Data**: Using `groupby` to perform summary statistics.

### 3. Visualization
Using Matplotlib, visualizations were created to clarify insights:
- **Bar Charts**: Visualized monthly sales trends, city-wise sales, and popular products.
- **Line Graphs**: Displayed sales by time of day, helping pinpoint optimal advertising windows.

## Conclusion
Through detailed analysis of the sales data, business-relevant questions were effectively answered using data. By understanding sales patterns, peak times, and popular product combinations, actionable insights were derived to enhance business strategies.

