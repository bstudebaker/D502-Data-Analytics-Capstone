# Data Directory

This folder contains documentation related to the data used in the D502 Data Analytics Capstone project, *An Analysis of Airline Performance: January 2023 – June 2025*.

## Raw Data
The raw dataset from the U.S. Department of Transportation’s Bureau of Transportation Statistics (BTS) is in this repository as well as the dataset definitions and cleaned data file that is created through the Jupyter Notebook pre-processing. The dataset can also be downloaded directly from the BTS website:

https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp?20=E

The dataset includes flight-level records with variables such as:
- `arr_delay` (arrival delay in minutes)
- `carrier` (airline code)
- `airport` (origin/destination airport)
- `weather_delay` (weather-related delay minutes)
- Additional operational delay fields

## Cleaned Data
The cleaned dataset used in the analysis is generated automatically by running the Jupyter Notebook located in the `notebooks/` directory. Cleaning steps include:
- Removing rows with invalid negative delay values
- Dropping records with missing weather delay fields
- Normalizing KPIs by flight volume
- Creating a binary delay flag for flights delayed more than 15 minutes
- Converting categorical variables into dummy variables for statistical modeling

## Reproducibility
To reproduce the cleaned dataset:
1. Install Python and required libraries (see project-level README).
2. Open the notebook in the `notebooks/` directory.
3. Run all cells in sequence.
4. The cleaned dataset will be generated as part of the preprocessing workflow.

This documentation ensures transparency and supports reproducibility for evaluators and future users.
