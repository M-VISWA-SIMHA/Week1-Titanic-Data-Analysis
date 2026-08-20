# Week 2 – Advanced Data Visualization and Storytelling with Python

## Project Overview

This project focuses on advanced data visualization and data storytelling using the Titanic dataset.

The objective is to transform the cleaned Titanic dataset from Week 1 into meaningful visualizations that communicate important patterns and insights about passenger survival.

## Dataset

The Titanic dataset contains information about passengers, including:

- Passenger ID
- Survival status
- Passenger class
- Name
- Gender
- Age
- Siblings/Spouses
- Parents/Children
- Ticket
- Fare
- Port of Embarkation

The cleaned dataset used in this project is:

`titanic_cleaned.csv`

## Objective

The main objective of this project is to analyze:

- Overall passenger survival
- Survival by gender
- Survival by passenger class
- Age distribution by survival
- Survival rate by passenger class and gender
- Relationships between numerical variables
- Interactive relationships between age, fare, class, gender, and survival

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Google Colab / Jupyter Notebook

## Visualizations

The project contains the following visualizations:

### 1. Overall Passenger Survival

A count plot comparing passengers who survived with those who did not survive.

### 2. Survival by Gender

A comparison of survival outcomes between male and female passengers.

### 3. Survival by Passenger Class

An analysis of survival outcomes across First, Second, and Third Class.

### 4. Age Distribution by Survival

A visualization comparing the age distributions of survivors and non-survivors.

### 5. Survival Rate by Passenger Class and Gender

A combined analysis showing how passenger class and gender relate to survival rate.

### 6. Correlation Heatmap

A heatmap showing relationships between numerical variables in the dataset.

### 7. Interactive Plotly Visualization

An interactive scatter plot exploring the relationship between:

- Age
- Fare
- Survival
- Passenger Class
- Gender

## Key Findings

The analysis indicates that:

1. The number of passengers who did not survive was higher than the number who survived.
2. Survival outcomes differed considerably between male and female passengers.
3. Passenger class was associated with different survival outcomes.
4. Age distributions differed between survivors and non-survivors.
5. Combining gender and passenger class provides a more detailed understanding of survival patterns.
6. Correlation analysis helps identify relationships between numerical variables.
7. Interactive visualization provides an additional way to explore the dataset.

## Data Story

The analysis begins by examining the overall survival outcome. It then investigates gender and passenger class as important factors associated with survival.

Age provides additional demographic context, while the combined analysis of gender and passenger class gives a more detailed view of survival patterns.

Finally, correlation analysis and interactive visualization provide additional perspectives on relationships within the dataset.

## Conclusion

This project demonstrates how Python visualization libraries can transform a dataset into a clear and understandable data story.

The analysis shows that gender and passenger class are important factors associated with survival in the Titanic dataset, while age and other numerical variables provide additional context.

## Files

```text
Week_2/
│
├── README.md
├── Week_2_Titanic_Data_Visualization.ipynb
├── Week_2_Titanic_Data_Visualization_Report.docx
└── titanic_cleaned.csv
