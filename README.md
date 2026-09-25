
# Teacher Salary Panel Analysis

R code for a state-level panel study of teacher salaries in 12 U.S. states, 2010–2020.

## What it does
- Aggregates IPUMS USA (ACS) microdata to the state-year level using survey weights
  (median household income, female labor-force participation, unemployment, demographics)
- Merges with NCES teacher salary and union data
- Adjusts income to constant 2018 dollars
- Estimates pooled OLS and state and two-way fixed-effects models
  with state-clustered standard errors (CR2 for FE models)
- Includes data quality checks for missing values and duplicate state-years

## Data
Data files are not included. IPUMS USA extracts are available at usa.ipums.org;
salary and union data come from NCES.

## Credits
Co-authored research project with Harrison Cerone, Washington and Lee University.
Code by Jack McClure.
