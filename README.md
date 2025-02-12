# E-commerce Exploratory Data Analysis (EDA)

## Overview
This repository contains an **Exploratory Data Analysis (EDA)** of an online retail dataset. The analysis aims to uncover meaningful insights, trends, and patterns within the dataset, helping businesses make data-driven decisions.

## Dataset
- **Source**: Online Retail Dataset
- **Time Period**: Historical sales data from an e-commerce store
- **Key Fields**:
  - `InvoiceNo`
  - `StockCode`
  - `Description`
  - `Quantity`
  - `InvoiceDate`
  - `UnitPrice`
  - `CustomerID`
  - `Country`

## Objectives
- Understand sales distribution across different products and countries.
- Identify top-selling products and customer segments.
- Analyze purchasing behavior and trends.


## Key Insights
| Metric                  | Value / Observation |
|------------------------|-------------------|
| **Total Transactions**      |     8536     |
| **Unique CustomerID**       |    14646     |
| **Most Sold Product**       |  PAPER CRAFT , LITTLE BIRDIE MEDIUM CERAMIC TOP STORAGE JAR |
| **Highest Revenue Country** |     UK       |


## Analysis Performed
### 1. Data Cleaning & Preprocessing
- Handled missing values
- Removed duplicate records
- Filtered out negative quantities and prices

### 2. Exploratory Data Analysis
- **Sales Trends:** Identified seasonal patterns and peak sales periods.
- **Top Products:** Analyzed most frequently purchased items.
- **Customer Segmentation:** Grouped customers based on spending behavior.
- **Geographical Insights:** Studied sales distribution across different countries.
- **Revenue Distribution:** Evaluated high-value transactions.

### 3. Visualization
- Bar charts, histograms and trend analysis.
- Scatter plots for customer behavior patterns.
- Time series plots for seasonality insights.

## Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/Rsivamani/E-commerce-EDA.git
   ```
2. Open `Online_retail.ipynb` in Jupyter Notebook.
3. Run the notebook step by step to reproduce the analysis.

## Results
This EDA provides valuable insights into e-commerce sales patterns, customer preferences, and high-revenue regions. The findings can help businesses optimize their inventory, pricing, and marketing strategies.
 
Customer Behavior:
The United States dominates as the top revenue contributor, accounting for 18.21% of total sales.
The most sought-after products among U.S. customers include:
PAPER CRAFT, LITTLE BIRDIE
MEDIUM CERAMIC TOP STORAGE JAR
WORLD WAR 2 GLIDERS ASSTD DESIGNS
Following closely, the Netherlands and EIRE emerge as the next highest revenue-generating regions.

Trends:
November 2011 witnessed a major sales surge, likely fueled by holiday shopping, emphasizing seasonal demand patterns.



