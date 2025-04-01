# Business-Sales-Data-Analysis

This project focuses on performing in-depth analysis on business sales data, aiming to gain valuable insights that can drive decision-making. The project consists of exploring and visualizing various aspects of sales data, including trends, product performance, regional sales analysis, and customer segmentation. 

## 📑 **Table of Contents**
1. [Project Overview](#project-overview)
2. [Data Description](#data-description)
3. [File Structure](#file-structure)
4. [Tools and Libraries](#tools-and-libraries)
5. [Project Files Overview](#project-files-overview)
6. [How to Use](#how-to-use)
7. [📜 License](#license)

## 📝 **Project Overview**

This project involves analyzing sales data to identify key insights that businesses can use to improve operations. It includes:

- **Identifying Sales Trends**: Analyzing and visualizing yearly and monthly sales data.
- **Product Performance**: Analyzing which products contribute most to sales and identifying underperforming products.
- **Regional Sales Analysis**: Identifying high-performing regions and customer behavior to target high-revenue areas.
- **Customer Segmentation**: Segmenting customers based on purchasing behavior and identifying correlations for more personalized marketing.
- **Deal Size and Order Status Analysis**: Analyzing sales contribution by deal size and order status breakdown.

## 📊 **Data Description**

The dataset contains various information related to sales, customers, and products:

- **ORDERNUMBER**: Unique order ID
- **QUANTITYORDERED**: Number of units ordered
- **PRICEEACH**: Price per unit
- **ORDERLINENUMBER**: Line number in the order
- **SALES**: Total revenue from the order
- **ORDERDATE**: Date when the order was placed
- **STATUS**: Order status (e.g., shipped, cancelled)
- **PRODUCTLINE**: Category of the product
- **PRODUCTCODE**: Unique product identifier
- **CUSTOMERNAME**: Customer's name
- **COUNTRY**: Customer's country
- **DEALSIZE**: Size of the deal (Small, Medium, Large)

## 📁 **File Structure**

### 1. **Load_and_Explore_Data.csv**
This is the **raw dataset** containing information about the orders, products, and customers. No modifications have been made to this file.

### 2. **Data_Overview_Data_Cleaning**
This file contains the dataset overview, missing data handling, and data type corrections applied to the raw data.

### 3. **Sales_Trend_Analysis**
This file contains the analysis of sales trends over time, visualized with line charts to show yearly and monthly patterns.

### 4. **Products_Performance_Analysis**
Analyzes the performance of different product lines, highlighting the most and least contributing products and possible reasons behind the performance.

### 5. **Customer_Purchase_Regional_Analysis**
This file identifies top-performing regions, high-value customers, and analyzes regional sales trends to help businesses target high-revenue areas and improve low-performing regions.

### 6. **Order_Status_Deal_Size_Analysis**
Analyzes the sales contribution based on deal size and order status breakdown.

### 7. **Advanced_Sales_Insights**
This file contains customer segmentation and correlation analysis for advanced insights into customer behavior and sales performance.

## 🛠️ **Tools and Libraries**

This project uses the following tools and libraries:

- **Python**: The programming language used for data manipulation and analysis.
- **Pandas**: For data manipulation and cleaning.
- **Matplotlib**: For creating visualizations.
- **Seaborn**: For statistical data visualization.
- **Statsmodels**: For time series analysis and forecasting.
- **Scikit-learn**: For machine learning and regression models.

## 📑 **Project Files Overview**

1. **Load_and_Explore_Data.csv**: This is the raw sales data file used for analysis.
2. **Data_Overview_Data_Cleaning.ipynb**: In this notebook, we explore the dataset, handle missing data, and correct data types.
3. **Sales_Trend_Analysis.ipynb**: This notebook visualizes the yearly and monthly sales trends using line charts.
4. **Products_Performance_Analysis.ipynb**: Here we analyze the contribution of each product line to the total sales, identifying the best and least performing products.
5. **Customer_Purchase_Regional_Analysis.ipynb**: This analysis identifies the top-performing regions, high-value customers, and provides insights into regional sales trends.
6. **Order_Status_Deal_Size_Analysis.ipynb**: This file focuses on analyzing the sales contribution by deal size and the breakdown of order statuses.
7. **Advanced_Sales_Insights.ipynb**: The final notebook performs customer segmentation and correlation analysis to uncover deeper patterns in the data.

## 🚀 **How to Use**

1. Clone or download the repository to your local machine.
2. Open the notebooks in any Jupyter Notebook environment (e.g., JupyterLab, Google Colab).
3. Run the code step by step to explore the analysis and visualize the results. 

## 📜 **License**

This project is **not licensed**. All rights are reserved, and you can:
- **View and download** the project for personal learning or exploration.
- **Use** the code in your own analyses, with proper attribution.

However, you **cannot modify, distribute, or use** this code for commercial purposes without explicit permission from the author.

If you wish to use or modify this code for any other purpose, please reach out to the project author for permission.
