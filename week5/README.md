# Week 5 - Comprehensive Data Science Project

## Breast Cancer Classification Using Machine Learning

This project presents an end-to-end data science workflow using the Breast Cancer dataset available through scikit-learn.

## Project Objective

The objective of this project is to analyze the dataset, perform exploratory data analysis and statistical hypothesis testing, develop machine learning classification models, evaluate their performance, and provide research-oriented recommendations.

## Dataset

The project uses:

`sklearn.datasets.load_breast_cancer`

The dataset contains:

- 569 samples
- 30 numerical features
- 2 target classes
- Malignant
- Benign

## Methodology

The project includes:

1. Data loading and understanding
2. Data quality checking
3. Exploratory data analysis
4. Statistical hypothesis testing
5. Data preprocessing
6. Machine learning model development
7. Model evaluation
8. Model comparison
9. Feature importance analysis
10. Strategic recommendations

## Machine Learning Models

Three classification models were evaluated:

- Logistic Regression
- Decision Tree
- Random Forest

## Best Model

Logistic Regression achieved the best performance.

- Accuracy: 98.25%
- Precision: 98.61%
- Recall: 98.61%
- F1 Score: 98.61%

## Statistical Analysis

A Chi-square test was conducted to examine the association between mean-radius grouping and diagnosis.

The result was statistically significant with a p-value of approximately:

6.08 × 10^-53

## Visualizations

The project includes:

- Class distribution
- Mean radius comparison
- Correlation heatmap
- Model performance comparison
- Confusion matrix
- Feature importance

## Important Note

This project is an educational and research-oriented machine learning analysis. The model should not be considered a clinically validated medical diagnostic system.

## Files

- `Week_5_Comprehensive_Data_Science_Project.ipynb` - Complete Python analysis
- `Week_5_Comprehensive_Data_Science_Project_Report.docx` - Comprehensive project report
- `images/` - Project visualizations
