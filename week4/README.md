# Week 4: Machine Learning Model Development and Evaluation

## Machine Learning Model Development Using Logistic Regression

## Project Overview

This project demonstrates the complete machine learning model development and evaluation process using Python and Scikit-learn.

The Breast Cancer Wisconsin dataset is used to develop a binary classification model using Logistic Regression.

The project covers the complete workflow from data exploration and preprocessing to model training, prediction, evaluation, visualization, and analysis of model limitations.

---

## Project Objective

The main objective of this project is to develop and evaluate a basic machine learning classification model.

The project includes:

- Dataset exploration
- Data cleaning
- Missing-value checking
- Duplicate-value checking
- Target class analysis
- Train-test splitting
- Feature standardization
- Logistic Regression model development
- Model training
- Prediction
- Performance evaluation
- Confusion matrix visualization
- ROC curve visualization
- Overfitting analysis
- Error and limitation analysis
- Suggestions for model improvement

---

## Dataset

### Breast Cancer Wisconsin Dataset

The project uses the Breast Cancer Wisconsin dataset available through Scikit-learn.

The dataset contains:

- **569 observations**
- **30 numerical features**
- **2 target classes**

The target classes are:

- Malignant
- Benign

### Target Distribution

The dataset contains:

- **212 malignant observations**
- **357 benign observations**

This makes the problem a **binary classification problem**.

---

## Technologies Used

The project was developed using:

- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Algorithm

### Logistic Regression

Logistic Regression was selected because this project is a binary classification problem.

It is:

- Simple
- Efficient
- Interpretable
- Widely used for classification
- Suitable as a baseline classification model

The model learns patterns from the training data and predicts the class of previously unseen observations.

---

## Project Workflow

The machine learning workflow used in this project is:

```text
Dataset
   |
   v
Data Exploration
   |
   v
Data Cleaning
   |
   v
Train-Test Split
   |
   v
Feature Standardization
   |
   v
Logistic Regression
   |
   v
Model Training
   |
   v
Prediction
   |
   v
Model Evaluation
   |
   +-------------------+
   |                   |
   v                   v
Confusion Matrix    ROC Curve
   |
   v
Overfitting Analysis
   |
   v
Final Results
