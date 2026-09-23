# Source Code
 
This folder contains the Google Colab notebooks used to clean and analyze the frailty dataset.
 
## Data Cleaning Notebook
 
This notebook contains the Python code used to clean and prepare the raw frailty dataset.
 
The cleaning process includes:
 
- Reviewing the dataset structure, data types, and column names
- Removing extra spaces from column names
- Removing whitespace from numeric values
- Converting Height, Weight, Age, and Grip strength to numeric data types
- Cleaning and standardizing Frailty values to Y and N
- Checking for missing values
- Checking for duplicate rows
- Removing missing values if present
- Verifying the dataset shape before and after cleaning
- Saving the cleaned dataset as `frailty_data_clean.csv`
 
## Data Analysis Notebook
 
This notebook contains the Python code used to analyze the cleaned frailty dataset.
 
The analysis process includes:
 
- Converting height from inches to meters
- Converting weight from pounds to kilograms
- Calculating BMI
- Creating age group categories
- Converting Frailty from Y/N to binary values
- Creating dummy variables for the age group categories
- Computing the mean, median, and standard deviation for numeric variables
- Calculating the correlation between grip strength and frailty
- Saving the statistical results to `results/findings.md`
- Saving the final analyzed dataset as `frailty_data_analyzed.csv`
 
## Purpose
 
The cleaning and analysis processes are stored in separate Google Colab notebooks to keep each stage of the project organized and clearly documented.
