# Notebooks Directory

This folder contains the Jupyter Notebook used for all data preprocessing, statistical analysis, and model development for the D502 Data Analytics Capstone project, *An Analysis of Airline Performance: January 2023 – June 2025*.

## Contents

### Jupyter Notebook
- **airline_performance_analysis.ipynb**  
  This notebook includes the full analytical workflow used in the project, including:
  - Importing and inspecting the BTS dataset  
  - Cleaning invalid or missing values  
  - Creating normalized KPIs  
  - Generating exploratory visualizations  
  - Conducting chi-square tests, t-tests, and multiple linear regression  
  - Exporting statistical outputs and diagnostic plots to the `appendices/` directory  

The notebook is fully reproducible and documents each transformation step used to prepare the dataset and conduct the analysis.

### Jupyter Notebook (HTML)
- **airline_performance_analysis.html** 
  This shows the Jupyter Notebook outputs in an HTML for ease of review.
  
## How to Run
1. Install Python 3.10+  
2. Install required libraries (see project-level README): pip install pandas numpy scipy statsmodels matplotlib seaborn
