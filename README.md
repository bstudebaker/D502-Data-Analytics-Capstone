# An Analysis of Airline Performance: January 2023 – June 2025

Author: Bryant W. Studebaker

## Project Overview
This project analyzes U.S. airline on-time performance from January 2023 through June 2025 to determine whether delay patterns differ across carriers and whether those differences are influenced by airport congestion or weather conditions. The analysis includes data preprocessing in Python, statistical testing, KPI development, and a Tableau Story dashboard.

## Repository Contents
- `notebooks/` – Jupyter Notebook used for data cleaning, preprocessing, and statistical analysis  
- `data/` – Cleaned dataset (or instructions for obtaining it)  
- `dashboard/` – Tableau Story screenshots and supporting visuals  
- `appendices/` – Statistical outputs, diagnostic plots, and supporting materials  
- `README.md` – Project summary and documentation

## How to Run the Analysis
1. Install Python 3.10+  
2. Install required libraries: pip install pandas numpy scipy statsmodels matplotlib seaborn
3. Open the Jupyter Notebook in the `notebooks/` directory  
4. Run each cell in order to reproduce the data cleaning, KPI creation, and statistical tests

## Tableau Dashboard
The full Tableau Story can be viewed here:
https://public.tableau.com/app/profile/bryant.studebaker/viz/AirlinePerformanceAnalysis_17650805818520/AirlinePerformanceAnalysis

## Key Findings
- Airline identity is significantly associated with delay likelihood (χ² = 1499.10, p < 0.001)
- Several carriers show statistically higher average delay minutes (e.g., OH vs PT: t = 5.47, p < 0.001)
- Weather delay minutes and airport identity are strong predictors of arrival delay
- The regression model explained 68.2% of the variance in arrival delay (R² = 0.682, Adjusted R² = 0.680; F-statistic = 313.9, p < 0.001)


## Tools Used
- Python (Pandas, NumPy, SciPy, Statsmodels, Matplotlib, Seaborn)
- Tableau Public
- Jupyter Notebook
- GitHub for version control and documentation

## Purpose of This Repository
This repository serves as evidence of project completion for the D502 Data Analytics Capstone at Western Governors University. It includes all code, outputs, and supporting materials used to conduct the analysis.

## Data Source
All flight performance data was obtained from the U.S. Department of Transportation’s Bureau of Transportation Statistics (BTS). https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp?20=E

## Reproducibility
All analysis steps are fully reproducible using the Jupyter Notebook provided in the `notebooks/` directory.
