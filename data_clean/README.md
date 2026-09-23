# Cleaned Data
 
This folder contains the cleaned and prepared frailty dataset used for analysis.
 
## File
 
- `frailty_data_clean.csv` – Cleaned version of the original frailty dataset.
 
## Data Cleaning
 
The raw frailty dataset was uploaded into Google Colab and cleaned and prepared for analysis by:
 
- Reviewing the dataset structure, summary statistics, column names, and data types
- Removing extra spaces from column names
- Removing whitespace from Height, Weight, Age, and Grip strength values
- Converting Height, Weight, Age, and Grip strength to numeric data types
- Cleaning and standardizing Frailty values to Y and N
- Checking for missing values
- Checking for duplicate rows
- Removing missing values if present
- Verifying the dataset before and after cleaning
- Saving the cleaned dataset as `frailty_data_clean.csv`
 
## Data Quality
 
The dataset was checked for missing values and duplicate rows. The dataset was also verified after the cleaning process before being saved for analysis.
 
## Purpose
 
The original dataset is preserved in the `data_raw` folder. The cleaned dataset is saved as `frailty_data_clean.csv` and used for the analysis completed in the frailty project.
