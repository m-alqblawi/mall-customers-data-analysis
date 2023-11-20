# Mall Customers Data Analysis

## Overview

This repository contains code for analyzing the "Mall_Customers" dataset, which includes information about customers in a mall. The analysis is performed using Python with pandas, seaborn, and scikit-learn libraries. The results are visualized, and the dataset is saved for further exploration in Power BI.

## Dataset

The "Mall_Customers" dataset consists of the following features:

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## Code Overview

1. **Data Analysis:**

   - `mall_customers_analysis.ipynb`: Jupyter Notebook containing Python code for data analysis, visualization, and customer segmentation.

2. **Data Visualization:**

   - Various visualizations using seaborn and matplotlib to explore relationships between different features.

3. **Customer Segmentation:**

   - Customer segmentation using k-means clustering algorithm from scikit-learn.

4. **Data Export:**
   - The final dataset is saved to a CSV file (`mall_customers_analysis with Segment.xlsx`) for further analysis in Power BI.

## Instructions for Power BI

1. **Import Data:**

   - Open Power BI Desktop.
   - Click on "Get Data" in the Home tab.
   - Choose "Text/CSV" and select the CSV file (`mall_customers_data.csv`) saved from the analysis.

2. **Explore and Visualize:**
   - Power BI will load the data, and you can start building visualizations and reports.
   - Remember to refresh your data in Power BI if you make any updates to the CSV file.

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/m-alqblawi/mall-customers-data-analysis.git
   cd mall-customers-data-analysis
   ```
