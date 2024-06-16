# Module 4 Challenge - Wholesale Data Analysis

## Overview
Using a dataset from a fictional e-commerce company to explore and identify top customers, popular product categories, calculate profits, etc.

## Running the program
`wholesale_data_analysis_starter_code.ipynb`

## Notes
Renamed index to for more consistency

## References
* checked how to group by columns and get sums: https://stackoverflow.com/questions/46431243/how-to-get-groupby-sum-of-multiple-columns
* query .isin used to filter client_summary df for only values in the top 5 client list: https://stackoverflow.com/questions/12096252/use-a-list-of-values-to-select-rows-from-a-pandas-dataframe
* copy() is needed to remove SettingWithCopyWarning: https://stackoverflow.com/questions/20625582/how-to-deal-with-settingwithcopywarning-in-pandas
* Use map for series https://stackoverflow.com/questions/19798153/difference-between-map-applymap-and-apply-methods-in-pandas