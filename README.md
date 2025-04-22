# EDA of Music Sales Data

This project performs an exploratory data analysis (EDA) on a dataset containing music sales data. The goal is to understand the distribution and trends in the data, and generate insights through visualisations and summary statistics.

## Table of Contents

- [Overview](#overview)
- [Setup and Installation](#setup-and-installation)
- [Dataset](#dataset)
- [Exploratory Data Analysis](#exploratory-data-analysis)
  - [Key Insights](#key-insights)
- [Visualisations](#visualisations)

## Overview

In this project, I use Python libraries such as Pandas, Seaborn, and Matplotlib to analyse and visualise trends in music sales data. The data includes information on music sales across different formats, metrics, and years. The main objectives of the analysis are to:

- Explore trends over time (e.g., total sales per year)
- Understand the distribution of sales across different formats and metrics
- Investigate relationships between different variables

## Setup and Installation

### Prerequisites

- Python 3.x
- Jupyter Notebook or JupyterLab (for interactive notebooks)
- pandas
- seaborn
- matplotlib

### Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/mahfuzur12/music-sales-eda.git
   ```

2. Navigate to the project directory:
   ```bash
   cd music-sales-eda
   ```

3. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Open the notebook and begin analysing the data.

## Dataset

The dataset used in this project is a CSV file named `MusicData.csv`. It contains the following columns:

- `Year`: The year the data was recorded.
- `Format`: The format of the music (e.g., CD, Vinyl).
- `Metric`: The type of metric used (e.g., Sales, Revenue).
- `Value (Actual)`: The actual value for the metric (e.g., number of sales or revenue).
- `Number of Records`: The number of records sold.

## Exploratory Data Analysis

In this notebook, the following steps are performed:

1. **Data Loading & Preprocessing**: The dataset is loaded into a Pandas DataFrame, and we perform basic cleaning steps.
2. **Data Exploration**: Summary statistics (`describe()`) and unique values are inspected for key columns.
3. **Grouping and Aggregation**: Data is grouped by different columns (e.g., Year, Format) to analyse the total or average values.
4. **Visualisations**: Various plots (e.g., bar plots, line plots, box plots) are created to visualise the distribution and trends in the data.

### Key Insights

- The **top 5 years with the highest average value** across the dataset show the years with the most significant sales.
- **Sales by format** reveal which formats were the most popular over the years.
- **Trends in total sales per year** provide insight into how music sales have changed over time.

## Visualisations

The following visualisations are included in the project:

1. **Average Sales per Year**: A bar plot showing the mean sales value for each year.
2. **Sales by Format**: A bar plot showing the number of records sold for each music format.
3. **Sales Over Time**: A line plot showing the trend of sales over the years.
4. **Distribution by Format**: A boxplot showing the distribution of sales across different formats.
5. **Pairplot**: A pairplot visualising relationships between year, number of records, and sales values, broken down by format.
6. **Total Sales per Year by Metric**: A stacked bar plot showing the total sales per year by metric (e.g., Sales, Revenue).
7. **Average Value by Format and Year**: A plot showing the average sales by format and year.