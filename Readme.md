# 📊 Sales Analysis Dashboard

## Overview

Sales Analysis Dashboard is an interactive data analytics application built using Streamlit, Pandas, NumPy, Matplotlib, Seaborn, and Plotly. The application generates a random sales dataset and provides statistical analysis along with interactive visualizations.

## Features

* Generate custom sales datasets using user-defined ranges.
* Interactive sidebar controls for:

  * Sales Range
  * Profit Range
  * Orders Range
* Display generated dataset in tabular format.
* Calculate:

  * Average Sales
  * Average Profit
  * Total Sales
  * Total Profit
  * Summary Statistics
* Data Visualization:

  * Sales Distribution Histogram
  * Profit Distribution Histogram
  * Monthly Sales Trend
  * Correlation Heatmap
  * Interactive Sales vs Profit Chart

## Technologies Used

* Python
* Streamlit
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly

## Installation

Install the required packages:

```bash
pip install streamlit pandas numpy matplotlib seaborn plotly
```

## Run the Application

```bash
streamlit run sales.py
```

## Project Workflow

1. Select the minimum and maximum values for Sales, Profit, and Orders from the sidebar.
2. Click **Generate Dataset**.
3. The application generates a random yearly sales dataset.
4. Statistical calculations are displayed automatically.
5. Interactive charts and visualizations help analyze the generated data.

## Dataset Columns

| Column        | Description          |
| ------------- | -------------------- |
| Month         | Month Name           |
| Sales         | Monthly Sales Value  |
| Profit        | Monthly Profit Value |
| Orders        | Number of Orders     |
| Customers     | Number of Customers  |
| Profit_Margin | Profit Percentage    |

## Visualizations

* Histogram Analysis
* Trend Analysis
* Correlation Analysis
* Interactive Plotly Charts

## Author

Aditya Sharma

