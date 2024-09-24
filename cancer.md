
PCA and Logistic Regression on Breast Cancer Dataset

Project Overview

This project applies Principal Component Analysis (PCA) to the Breast Cancer Dataset from the sklearn library to reduce its dimensionality. The dataset, which contains tumor characteristics, is first standardized and then reduced to two principal components for easier visualization and analysis. As an optional bonus, a Logistic Regression model is implemented on the reduced dataset to classify whether the tumors are malignant or benign. 

Key Objectives:
Dimensionality Reduction: Use PCA to reduce the dataset to two components.
Visualization: Visualize the PCA components to understand the separation between malignant and benign classes.
Classification: Implement Logistic Regression on the reduced dataset to predict cancer type (malignant/benign).
Model Evaluation: Assess the Logistic Regression model using accuracy, confusion matrix, and ROC-AUC score.

Dataset

The dataset used is the Breast Cancer Dataset from sklearn.datasets, which consists of the following:
 Features: 30 features representing various characteristics of a cell nucleus in a breast tumor (e.g., radius, texture, perimeter, area, smoothness, etc.).
 Target: The target variable indicates whether the tumor is malignant (1) or benign (0).

Code Explanation

1. Importing Necessary Libraries
We import the following Python libraries:

2. Loading the Cancer Dataset
We load the Breast Cancer Dataset from sklearn.datasets. The dataset contains 30 features and a binary target indicating whether a tumor is malignant or benign.
Load the dataset

3. Standardizing the Dataset
Before applying PCA, we standardize the features to ensure that each feature has a mean of 0 and a standard deviation of 1, as PCA is sensitive to feature scaling.

4. Performing PCA
We apply PCA to reduce the dataset to two principal components. These two components capture the most variance in the data while minimizing dimensionality.

5. Visualizing the PCA Components
We create a scatter plot of the two principal components, with the color of each point representing whether the tumor is malignant or benign.

6. Logistic Regression (Bonus)
To earn bonus points, we implement Logistic Regression on the reduced dataset (two principal components) to predict whether a tumor is malignant or benign. 

7. Model Evaluation
We evaluate the Logistic Regression model by calculating its accuracy, confusion matrix, and ROC-AUC score.
