# Week 1 - Titanic Data Acquisition, Cleaning and EDA

## Project Overview

This project demonstrates the basic data science workflow of acquiring, cleaning, preprocessing, and exploring a publicly available dataset.

The Titanic dataset was selected for this project because it contains both numerical and categorical variables, missing values, and useful features for exploratory data analysis.

## Objectives

- Acquire a publicly available dataset
- Inspect the dataset
- Identify missing values
- Check duplicate records
- Clean and preprocess the data
- Perform exploratory data analysis
- Create visualizations
- Identify important patterns and insights

## Dataset

The Titanic dataset contains passenger information including:

- Passenger ID
- Survival status
- Passenger class
- Name
- Sex
- Age
- Siblings/Spouses
- Parents/Children
- Ticket
- Fare
- Cabin
- Embarked

The original dataset contained 891 rows and 12 columns.

## Data Cleaning

The following cleaning methods were applied:

- Missing Age values were replaced with the median Age.
- Missing Embarked values were replaced with the most frequent category.
- The Cabin column was removed because it contained a large amount of missing data.
- Duplicate records were checked.
- Data types were inspected and verified.

## Exploratory Data Analysis

The following analyses were performed:

- Survival distribution
- Survival by gender
- Survival by passenger class
- Age distribution
- Age vs Fare
- Correlation analysis
- Fare outlier analysis
- Survival rate by passenger class

## Key Findings

- Overall survival rate was approximately 38.38%.
- Female passengers had a substantially higher survival rate than male passengers.
- First-class passengers had the highest survival rate among the three passenger classes.
- Passenger age and fare distributions showed considerable variation.
- Correlation analysis was used to examine relationships between numerical variables.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Project Files

- `Week1_Titanic_Data_Analysis.ipynb` — Python analysis notebook
- `titanic_cleaned.csv` — cleaned dataset

## Author
M V VISWA SIMHA
