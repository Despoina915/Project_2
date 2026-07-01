# HEnEx-2024-Analysis-PowerBI
Python data preparation and Power BI dashboard analysis of 2024 HEnEx market data, focusing on MCP trends, traded volumes and market classifications.

## Overview

This project was developed as part of a Big Blue Academy assignment.

In collaboration with Petrina Korfiati, we created a data analysis and Power BI dashboard project focused on the 2024 HEnEx Day-Ahead Margiket results.

The purpose of this project is to process, aggregate, model and visualize 2024 HEnEx market data in order to better understand hourly and monthly trends in electricity prices, traded volumes and market behavior.

## Project Description

The analysis is based on 2024 EL-DAM results data from HEnEx.

The project uses Python to clean, combine and aggregate the original HEnEx Excel files into one unified 2024 dataset. This final dataset was then imported into Power BI, where additional transformations, DAX measures and dashboard visualizations were created.

The dataset contains 2024 HEnEx Day-Ahead Market data, cleaned, combined and aggregated into one unified dataset for dashboard analysis.

Key market indicators include:

* Market Clearing Price, also known as MCP
* Hourly MCP trends
* Monthly average MCP
* Buy and sell traded volumes
* Daily MCP spread and monthly average spread
* Traded volume by market classification
* Heatmap of average MCP by month and hour
* Relationship between RES, Natural Gas and average MCP per hour

## Technologies Used

* Python
* Pandas
* Power BI
* Power Query
* DAX
* Microsoft Excel
* Excel files as input data

## Dataset

The project uses Excel files containing 2024 EL-DAM results from HEnEx.

The original HEnEx Excel files were processed with Python and combined into one final dataset:

* DAM_2024_full_dataset.xlsx

The main fields used in the dashboard include:

* DELIVERY_MTU
* MCP
* TOTAL_TRADES
* SIDE_DESCR
* CLASSIFICATION
* ASSET_DESCR
* MONTH
* Date and hour-based columns created for analysis

## Main Analysis Steps

1. Import and combine 2024 HEnEx EL-DAM Excel files using Python
2. Clean and aggregate the data into one unified 2024 dataset
3. Export the final dataset as an Excel file
4. Import the unified dataset into Power BI
5. Convert delivery time data into date and time format
6. Create month, day and hour-based columns
7. Create DAX measures for average MCP and traded volumes
8. Calculate daily MCP spread and monthly average spread
9. Analyze buy and sell traded volumes
10. Analyze traded volume by market classification
11. Create a heatmap of average MCP by month and hour
12. Compare RES and Natural Gas sell volumes with average MCP per hour
13. Build an interactive Power BI dashboard

## Visualizations

The project includes several visualizations, such as:

* Cards for average MCP, total buy volume and total sell volume
* Combo chart of total traded volume and average MCP by hour
* Bar chart of average daily MCP spread by month
* Donut chart of traded volume by market classification
* Heatmap of average MCP by month and hour
* Line and column chart of RES sell volume, Natural Gas sell volume and average MCP by hour
* Date slicer for interactive filtering

## Usage

Before opening the dashboard, make sure that the Excel dataset is available in the correct folder and that the file path in Power BI matches your local directory.

Then, open the Power BI file:

* GitHub2.pbix

If the file path has changed, update the source path through Power Query before refreshing the report.

## Requirements

The project requires the following tools and libraries:

* Power BI Desktop
* Microsoft Excel

## Contributors

* Despoina Alonistioti
* Petrina Korfiati

## Acknowledgements

This project was completed as part of a Big Blue Academy exercise.

## License

This project is for educational purposes.