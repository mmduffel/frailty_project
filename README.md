# frailty_project
 
## Project Overview
 
This project focuses on cleaning, preparing, and analyzing a frailty dataset using Python in Google Colab.
 
The project includes data cleaning, feature engineering, exploratory data analysis (EDA), and statistical analysis to examine the relationship between grip strength and frailty.
 
## Project Structure
 
### `data_raw/`
Contains the original frailty dataset before any cleaning or preprocessing.
 
### `data_clean/`
Contains the cleaned frailty dataset after preparing the data for analysis.
  
### `results/`
Contains the final outputs from the analysis:
- `findings.md` with summary statistics and correlation results
- `frailty_data_analyzed.csv` with the final analyzed dataset

### `src/`
Contains the Google Colab notebooks used for the project:
- Data cleaning notebook
- Data analysis notebook
 
## Data Cleaning
 
The data cleaning process includes:
 
- Removing extra spaces from column names
- Removing whitespace from numeric values
- Converting numeric variables to appropriate data types
- Standardizing Frailty values to Y and N
- Checking for missing values
- Checking for duplicate rows
- Saving the cleaned dataset for analysis
 
## Data Analysis
 
The analysis process includes:
 
- Converting height from inches to meters
- Converting weight from pounds to kilograms
- Calculating BMI
- Creating age group categories
- Converting Frailty from Y/N to binary values
- Creating dummy variables for age groups
- Computing mean, median, and standard deviation for numeric variables
- Calculating the correlation between grip strength and frailty
 
## Results
 
The results of the analysis are documented in `results/findings.md`. The final analyzed dataset is stored in `results/frailty_data_analyzed.csv`.
 
## Tools Used
 
- Python
- Pandas
- Google Colab
- GitHub
