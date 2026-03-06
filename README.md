# Breast_Cancer_ml_Prediction
Machine learning models to predict breast cancer mortality and survival months using classification and regression techniques in Python.

# Breast Cancer Mortality & Survival Prediction 

# Project Overview
This project was developed as part of a Data Mining coursework. The aim was to build machine learning models to predict:

1. **Breast cancer mortality (classification)**
2. **Breast cancer survival months (regression)**

The project applies data preprocessing, feature selection, machine learning modelling, and evaluation techniques to healthcare data.


## Dataset
The dataset contains patient demographic and clinical information including:

- Age
- Sex
- Race
- Tumor Size
- Cancer Stage (T Stage, N Stage)
- Estrogen Status
- Progesterone Status
- Regional Nodes Examined
- Regional Nodes Positive
- Survival Months
- Mortality Status


# Part A: Mortality Prediction (Classification)

## Algorithms Used
- Naïve Bayes
- Logistic Regression
- K-Nearest Neighbors (KNN)

## Evaluation Metrics
- Recall
- F1 Score
- AUC-ROC

## Key Result
Naïve Bayes performed best for identifying **high-risk (dead) patients**, achieving the highest recall compared to Logistic Regression and KNN.


## Part B: Survival Months Prediction (Regression)

## Algorithm Used
- Decision Tree Regressor

## Evaluation Metrics
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R² Score

## Key Result
The pruned decision tree model improved generalization and provided accurate predictions of survival months.


# Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## Project Files
- `breast_cancer_model.ipynb`- Machine learning implementation
- `Report.pdf`- Full coursework report
- `dataset.csv` - Dataset used for analysis

# Author
**Lala Bigvava**  
MSc Data Science and Analytics  
University of Westminste
