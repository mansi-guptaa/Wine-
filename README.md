# Wine Quality Prediction Using Machine Learning
![Img](Image.jpg)
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

#### Support Vector Machine (SVM)

The Support Vector Machine model was implemented to see if a more complex, non-linear model could improve predictive performance over Logistic Regression.

### 3. Model Evaluation

The models were evaluated based on **Accuracy**, **Precision**, **Recall**, and **F1-Score**. Both models were cross-validated to ensure that the results were generalizable and not due to overfitting.

## Results

| Metric       | Logistic Regression | Support Vector Machine |
|--------------|---------------------|-------------------------|
| Accuracy     | 0.78                | 0.82                   |
| Precision    | 0.80                | 0.84                   |
| Recall       | 0.75                | 0.78                   |
| F1-Score     | 0.77                | 0.81                   |

Based on the above metrics, **SVM outperformed Logistic Regression** slightly in terms of accuracy and other metrics, making it the preferred model for this classification problem.

## Conclusion

- **SVM performed better** than Logistic Regression, which suggests that the relationship between the wine’s physicochemical properties and its quality is likely non-linear.
- The **model can be improved further** with hyperparameter tuning and possibly by adding more features or using ensemble methods.


## Technology Stack

- **Python Libraries**: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
- **Machine Learning Algorithms**: Logistic Regression, Support Vector Machine (SVM)

  
This project demonstrates the process of building, evaluating, and interpreting machine learning models to solve real-world classification problems, like predicting wine quality.
