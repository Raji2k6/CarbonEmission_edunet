## CarbonEmission_edunet
This repository contains my work on a data preprocessing on carbon emission dataset across countries

# Files in this Repository:
* `climate_change_download_0.xlsx` – The original dataset with missing and unprocessed values.
* `data_cleaned.csv` – The cleaned and transformed dataset ready for analysis.
* `data_preparation.ipynb` – Jupyter Notebook containing the code used for cleaning and transforming the data.

# Project Overview:
* Loaded the Excel file into a DataFrame using **Pandas**.
* Displayed initial records, examined descriptive statistics, and checked unique entries in key columns like `Series Code` and `Series Name`.
* Identified and removed unnecessary columns such as `Country Name`, `Series Code`, `Scale`, and `Decimals`.
* Handled missing values represented as `".."` by replacing them with `NaN` and converting all data columns to numeric types.
* Dropped rows with completely missing or irrelevant data.
* Performed data transformation to standardize the dataset and make it suitable for further analysis.
* Exported the final cleaned DataFrame to a CSV file for future use.

