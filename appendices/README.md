# Appendices Directory

This folder contains supporting materials for the D502 Data Analytics Capstone project, *An Analysis of Airline Performance: January 2023 – June 2025*. These files provide evidence of statistical testing, model diagnostics, and KPI visualization used throughout the analysis.

## Contents

### Statistical Outputs
- **chi-square_test.txt**  
  Contains the results of the chi-square test of independence evaluating whether airline identity is associated with delay status. Includes the test statistic, degrees of freedom, p-value, and interpretation.

- **t-statistic_test.txt**  
  Contains results from independent samples t-tests comparing mean delay minutes between selected carriers OH and PT. Includes the test statistic, p-value, and interpretation.

- **regression_summary.txt**  
  Full output from the multiple linear regression model predicting arrival delay minutes using airline, airport, and weather delay as predictors. Includes R², adjusted R², F-statistic, coefficient estimates, and p-values.

### Visualizations
- **monthly_delay_rate.png**  
  Time series plot showing the overall monthly delay rate across all carriers. Supports trend analysis and seasonal variability.

- **monthly_delay_rate_delayed_flight.png**  
  Time series plot showing the average delay minutes for flights that were delayed. Highlights operational impact and performance variability.

- **top5_carrier_delay_rate.png**  
  Time series plot comparing monthly delay rates for the top five carriers. Supports comparative analysis and reinforces chi-square findings.

## Purpose
These materials provide transparency and reproducibility for the statistical methods and visualizations used in the project. They support the conclusions presented in the final report and demonstrate that the analysis was conducted using valid inputs and documented outputs.
