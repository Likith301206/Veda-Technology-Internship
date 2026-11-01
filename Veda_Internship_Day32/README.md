# AI-Based Customer Spending Prediction

## Project Overview

This project uses machine learning to predict customer spending categories based on customer information and purchasing behaviour. A Decision Tree Classifier is trained using a sample dataset to classify customers into Low, Medium, or High spending categories.

## Objective

To understand how machine learning can be used to classify customer spending behaviour using selected input features.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Dataset Description

The project uses a sample dataset containing 20 customer records.

### Features

* `Age`: Customer's age.
* `Annual_Income`: Customer's annual income.
* `Purchase_Frequency`: Number of purchases during a defined period.
* `Spending_Score`: Numerical score representing customer spending behaviour.

### Target Variable

* `Spending_Category`: Customer spending category classified as Low, Medium, or High.

## Project Workflow

1. Imported the required Python libraries.
2. Created and explored the customer dataset.
3. Checked for missing values and duplicate records.
4. Cleaned the dataset.
5. Performed exploratory data analysis.
6. Created visualizations to understand customer behaviour.
7. Categorized customers using their spending scores.
8. Selected input features and the target variable.
9. Split the dataset into training and testing sets.
10. Trained a Decision Tree Classifier.
11. Evaluated predictions using accuracy and a classification report.
12. Predicted the spending category of a new customer.
13. Visualized spending category distribution and feature importance.

## Machine Learning Algorithm

**Decision Tree Classifier**

A Decision Tree Classifier learns decision rules from training data to predict the spending category of a customer.

## Evaluation Metrics

* Accuracy Score
* Precision
* Recall
* F1-Score

## Visualizations

* Annual income distribution.
* Annual income versus spending score.
* Purchase frequency versus spending score.
* Distribution of customer spending categories.
* Feature importance.

## Key Learning Outcomes

* Data cleaning and exploratory data analysis.
* Feature selection and target creation.
* Training and testing a machine learning model.
* Predicting customer spending categories.
* Evaluating classification performance.
* Visualizing customer data and model feature importance.

## Limitations

This project uses a small, manually created dataset. The spending categories are derived from predefined spending-score thresholds. Therefore, the model's predictions and evaluation metrics are intended for learning purposes and should not be treated as reliable predictions of real customer behaviour.

## Conclusion

This project demonstrates a basic machine learning workflow, from dataset preparation and visualization to model training, evaluation, and prediction. It provides practical experience with Python and Scikit-learn for a classification problem.
