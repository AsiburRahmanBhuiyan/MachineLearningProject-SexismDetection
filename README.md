# Project Summary

The dataset, named "Hierarchical classification of online sexism," is a Comma Separated Values file available on Kaggle under "Sexism Prediction." It contains 14,000 rows and 5 columns, including features such as Rewire_ID and Text, and labels such as Label_sexist, Label_category, and Label_vector. The Label_sexist column is tag-based. Notably, the dataset exhibits an imbalance, with 75.7% of values labeled as not sexist and 24.3% as sexist.

## Problem Type
This is a classification problem where the goal is to predict whether a text is sexist or not based on predefined classes. 

## Data Pre-processing
### Handling Null Values:
Missing values were addressed using the ".isna().sum()" method to count them, and columns with missing values were dropped.
### Data Labelling:
A binary labeling scheme was adopted, assigning 1 to sexist content and 0 to non-sexist content in the "label_sexist" column.
### Data Cleaning:
Regular expressions were used to clean the data, converting text to lowercase, removing punctuation, emojis, hyperlinks, and newlines.

## Data Splitting
The dataset was split into a training set (80% of the data) and a testing set (20% of the data) for model evaluation.

## Model Accuracy Comparison

Based on the demonstrations of the four models, it is evident that:
- The Logistic Regression model produces the highest accuracy score of 81%.
- The SVM model generates a score of 76%.
- The Decision Tree model generates a score of 78%.
- The KNN model produces the lowest accuracy score of 75%.

## Dataset
[Hierarchical classification of online sexism](https://www.kaggle.com/datasets/bbiswabasuroy/hierarchical-classification-of-online-sexism?select=train.csv)

