# Movie Industry: Correlation Analysis

Exploratory analysis of a movie dataset to find which factors are most correlated with box-office gross revenue.

## Steps (`MoviesProject.ipynb`)
1. Check missing data and column types
2. Look for outliers and remove duplicates
3. Scatter and regression plots of budget versus gross and score versus gross
4. Pearson and Spearman correlation matrices and heatmaps across numeric and encoded categorical variables, filtered to the strongest pairs (|r| > 0.5)
5. Top production companies by gross revenue

## Stack
Python, pandas, NumPy, seaborn, matplotlib.

## Running
The `movies.csv` dataset is not included; place it next to the notebook and update the path in the second cell.
