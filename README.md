# README - Data Cleaning for Assault Data Project

## Overview

This README document describes the data cleaning process implemented for the Assault Data Project. The primary objective of this process is to prepare the dataset for further analysis and machine learning modeling. The dataset in question pertains to assault incidents in Rochester, encompassing various attributes of each incident.

## Files

- `Project_Assault_Data_Rochester.ipynb`: Jupyter Notebook containing the data cleaning code and preliminary analysis.
- `assault_data_raw.csv`: Original dataset (replace with the actual filename).
- `assault_data_cleaned.csv`: Cleaned dataset after processing.

## Data Cleaning Steps

The following steps were implemented in the Jupyter Notebook to clean the assault data:

1. **Initial Data Loading:**

   - The dataset is loaded into a pandas DataFrame, handling potential encoding issues.

2. **Initial Data Assessment:**

   - Exploration of the dataset to identify missing values and understand data types.

3. **Removing Columns with High Missing Values:**

   - Columns with more than 50% missing values were dropped to reduce noise and focus on more complete data.

4. **Replacing Placeholder Values:**

   - Placeholder values represented as '.' were replaced with `NaN` to standardize missing value representation.

5. **Removing Columns with Excessive Missing Values:**

   - Additional removal of columns where over 90% of the values are missing, focusing the dataset on more reliable data.

6. **Data Transformation:**
   - Standardization of numerical features and one-hot encoding of categorical features were applied to prepare the dataset for machine learning algorithms.

## Instructions

1. **Running the Notebook:**

   - Ensure you have Jupyter Notebook installed on your machine.
   - Open `Project_Assault_Data_Rochester.ipynb` in Jupyter Notebook.
   - Run each cell sequentially to view the data cleaning process.

2. **Viewing the Cleaned Data:**
   - The cleaned dataset is saved in `assault_data_cleaned.csv`.
   - You can load this file using pandas for further analysis or modeling.

## Dependencies

- Python 3
- pandas
- numpy
- scikit-learn

## Contact

For any queries regarding this project or the data cleaning process, please contact [Your Name] at [Your Email].
