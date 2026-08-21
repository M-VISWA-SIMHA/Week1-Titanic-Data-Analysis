# Week 3 – Statistical Analysis and Hypothesis Testing in Python

## Project Overview

This project focuses on statistical analysis and hypothesis testing using the Wine Quality dataset.

The objective is to determine whether observed differences and relationships in the dataset are statistically significant using appropriate statistical methods.

## Dataset

The project uses red and white wine quality datasets containing physicochemical measurements and wine quality scores.

The red and white datasets were combined into a single dataset, and a `wine_type` variable was added to distinguish between red and white wines.

The combined dataset contains 6,497 observations.

## Research Questions

The analysis investigates three main questions:

1. Is there a statistically significant difference in mean alcohol content between red and white wines?
2. Does mean alcohol content differ significantly across wine quality score groups?
3. Is wine type statistically associated with the defined quality group?

## Hypothesis Testing

A significance level of:

**α = 0.05**

was used for the statistical tests.

### Hypothesis 1 – Welch Independent Samples t-test

**Null Hypothesis (H₀):**  
There is no statistically significant difference in mean alcohol content between red and white wines.

**Alternative Hypothesis (H₁):**  
There is a statistically significant difference in mean alcohol content between red and white wines.

### Hypothesis 2 – One-Way ANOVA

**Null Hypothesis (H₀):**  
Mean alcohol content is the same across all wine quality score groups.

**Alternative Hypothesis (H₁):**  
At least one wine quality group has a different mean alcohol content.

### Hypothesis 3 – Chi-Square Test

**Null Hypothesis (H₀):**  
Wine type and the defined quality group are independent.

**Alternative Hypothesis (H₁):**  
Wine type and the defined quality group are significantly associated.

## Statistical Methods

The following statistical methods were performed:

- Welch Independent Samples t-test
- 95% Confidence Interval
- One-Way ANOVA
- Tukey HSD Post-Hoc Test
- Chi-Square Test of Independence

Effect sizes were also calculated:

- Cohen's d
- Eta-squared
- Cramér's V

## Data Analysis and Visualization

Exploratory visualizations were created using Matplotlib and Seaborn to understand the dataset before performing statistical tests.

The analysis includes visualizations of:

- Red and white wine distribution
- Alcohol distribution by wine type
- Alcohol content across wine quality scores
- Statistical relationships supporting the hypothesis tests

## Key Findings

The analysis found statistically significant results for:

- The difference in mean alcohol content between red and white wines.
- Differences in mean alcohol content across wine quality groups.
- The association between wine type and the defined quality group.

Effect sizes were also examined to understand the practical magnitude of the statistical findings.

## Tools and Technologies

- Python
- Pandas
- NumPy
- SciPy
- Statsmodels
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

## Project Files

```text
Week_3/
│
├── README.md
├── Week_3_Wine_Statistical_Analysis.ipynb
├── Week_3_Wine_Statistical_Analysis_Report.docx
├── winequality-red.csv
└── winequality-white.csv
