# Wine Quality Prediction Using Machine Learning

This project focuses on predicting the quality of wines based on various physicochemical properties. We employed two classical machine learning algorithms, **Logistic Regression (LR)** and **Support Vector Machine (SVM)**, to build predictive models.

## Dataset

The dataset used in this project is the [Wine Quality dataset](https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009) from Kaggle. The dataset contains information on the physicochemical properties of wine and its quality rating. The classes are ordered but unbalanced (i.e., there are more wines of average quality than excellent or poor ones).

## Problem Statement

This project aims to build a classification model to predict whether a wine’s quality is **Good** (quality > 7) or **Bad** (quality <= 7) based on its features. This model could assist winemakers in assessing wine quality during production and adjusting parameters to improve the final product.

## Project Summary

**Project Name:** Wine Quality Prediction Model  
**Project Type:** Classification  
**Contribution:** Individual  
**Team Member:** Mansi Gupta

## Approach

### 1. Data Preprocessing

Extensive data preprocessing was performed to prepare the dataset for model building:
- **Handling Missing Values:** Ensured there were no missing values in the dataset.
- **Feature Scaling:** Standardized the numerical features to bring them to a similar scale.
- **Encoding Categorical Variables:** Although this dataset has no categorical features, this step would typically be necessary for such data.

### 2. Model Building

#### Logistic Regression (LR)

Logistic Regression was selected as a baseline model due to its simplicity and interpretability. It was trained on the preprocessed dataset to set a benchmark for the model's performance.
