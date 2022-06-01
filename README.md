# synthanic_competition
This is the solution for the [Synthanic competition](https://www.kaggle.com/competitions/tabular-playground-series-apr-2021/submissions) on Kaggle.

The goal is to perform EDA and create a model solving binary classification task using synthetic dataset which is based on a real Titanic dataset.
The statistical properties of this dataset are similar to the original (and well known) Titanic dataset.

Accuracy score on test set:
![image](https://user-images.githubusercontent.com/75207011/171482144-5ea4981d-8b99-4b72-8b38-2cc7fd55c381.png)

The notebook with solution contains:
1. Data quality assessment and missing data imputation.
2. Thorough Data exploration with many plots, observations, summary and feature engineering.
3. Modeling block were I compared 3 algorithms: Logistic Regression, KNN and Random Forests and did model tuning with RandomizeSearchCV, cross validation, feature selection, data scaling and encoding.
