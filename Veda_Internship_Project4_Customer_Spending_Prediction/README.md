# AI-Based Customer Spending Prediction

## Project Overview

AI-Based Customer Spending Prediction is a machine learning project that demonstrates customer spending category classification using Python. It classifies customers into Low, Medium, and High spending categories based on selected customer attributes.

## Objectives

* Analyze customer demographic and purchasing data.
* Perform exploratory data analysis using visualizations.
* Train and compare machine learning classification models.
* Evaluate model performance using standard metrics.
* Demonstrate spending category prediction for a sample customer.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Dataset Description

The project uses a synthetic dataset containing 200 customer records.

| Feature           | Description                                                 |
| ----------------- | ----------------------------------------------------------- |
| CustomerID        | Unique customer identifier                                  |
| Age               | Customer age                                                |
| AnnualIncome      | Annual customer income                                      |
| SpendingScore     | Generated spending score used to create the target category |
| PurchasesPerMonth | Number of purchases per month                               |
| AverageOrderValue | Average value of an order                                   |
| SpendingCategory  | Low, Medium, or High spending category                      |

The spending categories are derived from the spending score:

* Low: 1–40
* Medium: 41–70
* High: 71–100

**Note:** The dataset is randomly generated for educational purposes and does not represent real customer behavior.

## Machine Learning Models

### 1. Decision Tree Classifier

A tree-based classification algorithm trained to predict customer spending categories.

### 2. Random Forest Classifier

An ensemble learning algorithm that combines multiple decision trees to make predictions.

The models are compared using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion matrix

## Project Workflow

1. Import required libraries.
2. Generate the synthetic customer dataset.
3. Inspect and clean the data.
4. Perform exploratory data analysis.
5. Visualize customer attributes and feature correlations.
6. Select input features and target categories.
7. Split the dataset into training and testing sets.
8. Train Decision Tree and Random Forest models.
9. Evaluate and compare model performance.
10. Analyze feature importance.
11. Demonstrate a sample customer prediction.

## How to Run the Project

### Prerequisites

Install Python and Jupyter Notebook.

### Install Dependencies

```bash
python -m pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Run the Notebook

Open a terminal in the project folder and execute:

```bash
jupyter notebook
```

Open `customer_spending_prediction.ipynb` and run the cells in order.

## Limitations

The dataset is synthetic, and the spending categories are generated independently of the model's input features. Consequently, model performance does not establish reliable real-world predictive ability.

A practical implementation would require real customer data and a target variable meaningfully related to the input features.

## Conclusion

This project demonstrates a complete introductory machine learning workflow, including data generation, preprocessing, exploratory analysis, classification, model evaluation, and sample prediction.

It provides practical experience with Python-based data analysis and supervised machine learning.
