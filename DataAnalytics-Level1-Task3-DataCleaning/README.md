# Data Cleaning

## Oasis Infobyte Internship

Name: Prince Kumar
Track:Data Analytics  
Level: Level 1 
Task: Task 3 - Cleaning Data  



## Objective

The objective of this project is to demonstrate professional-level
data cleaning skills by systematically transforming a messy dataset
into a clean and analysis-ready dataset.



## Dataset
The Titanic dataset from Kaggle was used for this data cleaning project.

The dataset contains passenger information such as:
- Passenger ID
- Survival status
- Passenger class
- Name
- Sex
- Age
- Number of siblings/spouses aboard
- Number of parents/children aboard
- Ticket
- Fare
- Cabin
- Port of Embarkation


## Data Cleaning Process
The following data cleaning steps were performed:
1. Loaded and inspected the dataset.
2. Created a data quality report.
3. Checked missing values in each column.
4. Checked and removed duplicate rows where applicable.
5. Handled missing values using appropriate strategies.
6. Standardised categorical text values.
7. Detected potential outliers using the IQR method.
8. Reviewed extreme values and retained legitimate observations.
9. Corrected data types according to the nature of each column.
10. Created a before-versus-after data quality summary.
11. Performed final data quality validation.
12. Saved the cleaned dataset as `cleaned_titanic.csv`.



## Missing Data Handling
Different strategies were used according to the data type and characteristics of each column.

- Age: Missing values were replaced using the median.
- Embarked: Missing values were replaced using the mode.
- Cabin: Missing values were represented as `Unknown` to avoid significant data loss.

These decisions were made to preserve as much useful information as possible while maintaining data quality.


## Outlier Detection
The Interquartile Range (IQR) method was used to identify potential outliers in numeric columns such as Age, Fare, SibSp, and Parch.
Potential extreme values were reviewed instead of being automatically removed because some extreme values can represent legitimate passenger characteristics.



## Before vs After Cleaning
The dataset was compared before and after cleaning using:
- Row count
- Column count
- Missing values
- Duplicate rows
- Data type accuracy

The final dataset was validated after applying the cleaning procedures.



## Technologies Used
- Python
- Pandas
- NumPy
- Google Colab
- Jupyter Notebook
- IQR Method


## Files Included
- `train.csv` - Original Titanic dataset
- `cleaned_titanic.csv` - Cleaned dataset
- `OIBSIP_DataAnalytics_Level1_Task3_DataCleaning.ipynb` - Project notebook
- `screenshots/` - Project screenshots


## Conclusion
The Titanic dataset was systematically cleaned and transformed into an analysis-ready dataset.
The project demonstrates a structured approach to data quality assessment, missing value handling, duplicate checking, data standardisation, outlier detection, and data type correction.
The cleaned dataset can now be used for further analysis and machine learning tasks.



## Internship
This project was completed as part of the Oasis Infobyte Data Analytics Internship.
Level: Level 1  
Task: Task 3 - Cleaning Data
