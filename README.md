# AlzAnalysis
Author: Chaeeun Shin

# Overview
This project analyzes an Alzheimer patient using various statistical and machine learning techniques in R. The primary objectives include exploratory data analysis, variable selection, and model performance evaluation. 

# Dataset URL
https://www.kaggle.com/datasets/rabieelkharoua/alzheimers-disease-dataset

# Objectives
1. Conduct exploratory data analysis (EDA) on an Alzheimer patient dataset. 
2. Examine the association between HDL cholesterol levels and symptom development.
3. Examine the association between HDL cholesterol levels and functional assessment scores. 
4. Develop regression models based on different variable selection methods and evaluate their performance.

# Methods
1. Exploratory Data Analysis (EDA)
    * Visualized distributions of continuous variables by density plot.
    * Visualized distributions of categorical variabels by bar plot.
    * Visualized variables based on diagnosis status.
2. Statistical Analysis of HDL (High-Density Lipoprotein) cholesterol
    * Investigated association between HDL cholesterol level and presence of symptoms by hypothesis testing using contingency table.
    * Investigated association between HDL cholesterol level and cognitive and functional scores by hypothesis testing using z-score.
3. Model Development and Feature Selection
    * Stepwise Selection (AIC & BIC): Selected variables based on Akaike Information Criterion (AIC) and Bayesian Information Criterion (BIC).
    * LASSO (Least Absolute Shrinkage and Selection Operator): Applied LASSO regression to identify the most relevant predictors.
    * Recursive Feature Elimination (RFE): Used an iterative approach to eliminate less important features.
    * Each model was evaluated using: Confusion Matrix, Accuracy, Sensitivity, Specificity, Precision
    
# Technologies Used
    * R Programming (tidyverse, glmnet, caret, MASS, ggplot2)
    * Statistical Methods (z-score test, two-way table test, AIC/BIC, LASSO, RFE)
    * Data Visualizaiton (Density plots, Histograms, Boxplots)
    
