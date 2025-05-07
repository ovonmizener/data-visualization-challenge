# Data Visualization Challenge: Clinical Study Analysis

## Overview

This project applies our Matplotlib and Pandas skills to a real-world dataset from Pymaceuticals, Inc.—a pharmaceutical company specializing in anti-cancer medications. The dataset comes from an animal study of 249 mice with squamous cell carcinoma (SCC) tumors. Over the course of 45 days, tumor size was tracked as different drug regimens were administered. Our goal is to compare the effectiveness of the company's drug of interest, Capomulin, against other treatments.

## Project Objectives

The analysis is broken down into several key tasks:

- **Data Preparation:**  
  - Merge the `mouse_metadata` and `study_results` datasets into a single DataFrame.
  - Identify and remove duplicate time point entries per mouse ID.
  - Confirm the number of unique mice post-cleaning.

- **Summary Statistics:**  
  - Generate statistics (mean, median, variance, standard deviation, and SEM) for tumor volumes by drug regimen.
  - Create a DataFrame of these summary statistics for quick reference.

- **Visualization – Bar Charts & Pie Charts:**  
  - Create two bar charts (one using Pandas plotting and one using Matplotlib's `pyplot`) showing the distribution of total mouse data points per drug regimen.
  - Create two pie charts (again, one using Pandas and one using Matplotlib) to display the distribution of unique female versus male mice.

- **Box Plot & Outlier Analysis:**  
  - Extract the final tumor volume for each mouse under four promising regimens: Capomulin, Ramicane, Infubinol, and Ceftamin.
  - Calculate quartiles and the interquartile range (IQR) for these values.
  - Identify potential outliers using the lower and upper bounds.
  - Generate a box plot using Matplotlib that highlights these outliers using a distinct style and color.

- **Additional Visualizations & Analysis:**  
  - Create line and scatter plots to demonstrate trends over time.
  - Calculate correlation and regression to further analyze relationships in the data.

## Files in the Repository

- **`mouse_metadata.csv`** and **`study_results.csv`**:  
  These files provide the raw data for mouse demographics and study results, respectively.

- **`data_cleaning.py`**:  
  Script to merge and clean the datasets, ensuring each mouse ID is correctly represented.

- **`summary_stats.py`**:  
  Script to calculate the summary statistics for tumor volume across different drug regimens.

- **`visualizations.py`**:  
  Script containing all the plotting functions for the bar charts, pie charts, box plots, line plots, and scatter plots.

- **`README.md`**:  
  This file, offering an overview and instructions for the project.

## Project Insights

This project demonstrates how effective data visualization can transform raw experimental data into actionable insights. By employing multiple visualization techniques—from bar and pie charts to box plots that highlight outliers—we provide a comprehensive overview of drug performance. These visualizations not only support the technical report needed by the executive team but also serve as a model for data-driven decision-making in clinical study analyses.

## Author

Oliver with some assistance from MS Copilot/Github Copilot to problem solve and debug where necessary. 