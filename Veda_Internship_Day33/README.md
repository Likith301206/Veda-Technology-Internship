# Day 32: AI-Based Customer Spending Prediction

## Project Overview

This project uses machine learning classification algorithms to predict customer spending categories based on customer characteristics and purchasing behavior.

## Objectives

* Prepare and explore customer data.
* Analyze relationships between customer features.
* Train classification models.
* Compare model performance using evaluation metrics.
* Predict spending categories for new customers.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Dataset

The project uses a small, manually created sample dataset containing 20 customer records.

Features:

* Age
* Annual Income
* Purchase Frequency

Target:

* Spending Category: Low, Medium, or High

The categories are derived from spending-score thresholds. The dataset is intended for educational purposes and is not representative of actual customers.

## Machine Learning Models

1. Decision Tree Classifier
2. Random Forest Classifier

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* Macro F1-score
* Confusion Matrix

## Visualizations

* Annual income distribution
* Annual income versus spending score
* Purchase frequency versus spending score
* Spending category distribution
* Feature importance comparison

## Results

Both classification models are evaluated using a held-out test set. Their performance is compared using accuracy, precision, recall, and macro F1-score.

Because the dataset is small, the results should not be interpreted as evidence of reliable real-world predictive performance.

## How to Run

1. Install Python.
2. Install the required libraries:
   `pip install pandas numpy matplotlib seaborn scikit-learn`
3. Open `Customer_Spending_Prediction.ipynb` in Jupyter Notebook or VS Code.
4. Execute the notebook cells in order.

## Conclusion

This project demonstrates a basic customer spending classification workflow, including data preparation, exploratory analysis, model training, evaluation, and prediction.
