# Day 31: Features and Target Selection

## Objective

To understand the basic structure of supervised machine learning by selecting suitable input features and a target variable from a dataset.

## Project Description

This project uses a student performance dataset containing study hours, attendance, previous scores, and final marks. The input features and target variable are selected using Pandas.

## Technologies Used

* Python
* Pandas
* Jupyter Notebook

## Tasks Performed

* Created a student performance dataset.
* Selected input features using Pandas.
* Selected the target variable separately.
* Checked the shapes of the features and target.
* Verified the selected column names.
* Checked for missing values.
* Explained the reasons for selecting the features and target.

## Selected Features

The following columns are used as input features:

1. `Hours_Studied`
2. `Attendance`
3. `Previous_Score`

These variables may provide useful information for predicting student performance.

## Selected Target

* `Final_Marks`

This is the value that a supervised machine learning model would attempt to predict.

## Expected Output

* Features (`X`) shape: `(10, 3)`
* Target (`y`) shape: `(10,)`
* Three input feature columns.
* One separate target column.

## Key Learning

Features are the input variables used by a machine learning model, while the target is the output the model attempts to predict. Keeping the target separate from the input features helps establish the correct structure for supervised learning.

## Conclusion

This exercise demonstrates how to select features and a target variable using Pandas. These are fundamental steps in preparing a dataset for supervised machine learning.
