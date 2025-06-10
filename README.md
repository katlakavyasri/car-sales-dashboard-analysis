# Car Sales Dashboard & Analysis: Insights from 2014-2015 Data

This repository showcases a comprehensive data analysis project focused on understanding historical trends and performance within the car sales market. The project leverages a blend of Python for data preparation and Power BI for creating an interactive, insightful dashboard.

## Project Overview

The primary objectives of this project were to:
- **Clean and preprocess raw car sales data** to ensure data quality and usability for analysis.
- **Develop an interactive Power BI dashboard** that provides a clear overview of key sales metrics and allows for detailed exploration.
- **Implement robust time intelligence measures** to enable dynamic analysis of sales performance over various periods.

## Technologies and Tools

-   **Python:** Utilized for initial data loading, inspection, handling missing values, standardizing column names, and preparing the `saledate` column for time intelligence.
-   **Jupyter Notebook:** Used for the iterative data cleaning and exploration process (as indicated by `Sales Analysis.ipynb`).
-   **Power BI Desktop:** Employed for:
    * Data modeling (including creating a date table or leveraging Power BI's built-in date functionality).
    * Developing complex DAX measures (e.g., Total Sales, Average Price, Number of Cars, Month-to-Date (MTD), Year-to-Date (YTD), and Year-over-Year (YoY) comparisons).
    * Designing interactive visualizations and dashboard layouts.

## Data Source

The analysis is based on a dataset of historical car sales records.
**Note:** The data ranges from **January 1, 2014, to July 20, 2015**. This historical scope is important for interpreting the trends and insights presented in the dashboard.

## Key Features & Dashboard Visualizations

The Power BI dashboard provides a dynamic view of car sales, allowing users to drill down into specific periods and categories. Key visualizations and metrics include:

* **Summary Cards:**
    * **Total Sales:** Overall revenue generated.
    * **Average Price:** Mean selling price per car.
    * **Number of Cars:** Total units sold.
    * **Time Intelligence Metrics:** Dynamic MTD, YTD, and YoY calculations for Sales, Average Price, and Cars Sold, providing period-over-period performance insights.

* **Sales & Price Trends:**
    * **Average Price by Date:** A line chart showing price fluctuations over time (as seen in `image 1.jpg`).
    * **Total Sales by Year:** A bar chart visualizing sales volume across years (`image 1.jpg`).

* **Categorical Breakdowns:**
    * **Average Price by Manufacturer:** Bar chart comparing average prices across different car manufacturers (`image 1.jpg`).
    * **Cars by Body Type:** Donut or pie chart showing the distribution of sales across different vehicle body types (`image 1.jpg`).
    * **Sales by State:** A map visualization indicating sales distribution across geographical regions (`image 1. jpg`).

* **Advanced Analysis:**
    * **Sales by body and price_range:** A scatter plot exploring the relationship between a car's body reading and its price range (`image 1.jpg`).
    * **Key Influencers:** Visualizations that identify the factors (e.g., features, conditions) that influence sales outcomes.

* **Detailed Views:**
    * Dedicated tabs for `Details` and `Total Sales Details` provide granular data tables and further breakdowns by State, Price Range, and Manufacturer, allowing for deeper investigation (`image 2.jpg`, `image 3.jpg`).

## How to Explore the Project

1.  **Clone the repository:**
    ```bash
    https://github.com/katlakavyasri/car-sales-dashboard-analysis.git
    ```
2.  **Open the Power BI Dashboard:**
    * Navigate to the cloned folder.
    * Open `Car Sales.pbix` (or `Car_Sales_Dashboard.pbix` if that's the exact name) using Power BI Desktop.
    * Interact with the filters and visuals to explore the data.
3.  **Review the Data Cleaning Process:**
    * Open `Sales Analysis.ipynb` in a Jupyter Notebook environment to see the Python code used for data preparation.

---
