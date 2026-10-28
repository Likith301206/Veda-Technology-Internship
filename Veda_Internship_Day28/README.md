# Day 28: Outlier Detection Using Python

## Overview

This project focuses on identifying potential outliers in a numerical dataset using Python, Pandas, and Matplotlib. A box plot is used to visualize the distribution of student marks and identify unusually high values.

## Objective

To understand basic outlier detection techniques through data visualization and statistical analysis.

## Technologies Used

* Python
* Pandas
* Matplotlib
* Jupyter Notebook

## Tasks Completed

* Created a student marks dataset.
* Calculated the first quartile (Q1) and third quartile (Q3).
* Calculated the interquartile range (IQR).
* Determined the lower and upper bounds for potential outliers.
* Identified potential outliers using the IQR method.
* Created a box plot to visualize the distribution of marks.
* Recorded observations based on the analysis.

## Outlier Detection Method

The Interquartile Range (IQR) method is used to identify potential outliers.

**Formula:**

* IQR = Q3 - Q1
* Lower Bound = Q1 - 1.5 × IQR
* Upper Bound = Q3 + 1.5 × IQR

Values below the lower bound or above the upper bound are flagged as potential outliers.

## Key Findings

* Most student marks fall within a relatively lower range.
* A mark of 150 is identified as a potential outlier.
* The box plot helps visualize the spread of marks and unusually high values.
* Outliers should be investigated before deciding whether to remove them.

## Key Python Functions

* `quantile()` — Calculates quartiles.
* `df["Marks"].min()` — Finds the minimum value.
* `df["Marks"].max()` — Finds the maximum value.
* `plt.boxplot()` — Creates a box plot.
* `display()` — Displays the dataset in a readable format.

## Project Structure

```text
Veda_Internship_Day28/
├── Outlier_Detection.ipynb
└── README.md
```

## Conclusion

This task provided practical experience in identifying potential outliers using the IQR method and visualizing them with a box plot. Outlier detection is an important step in exploratory data analysis because unusual values can influence statistical summaries and machine learning models.

## Internship Details

**Organization:** Veda Technology
**Track:** Artificial Intelligence and Machine Learning
**Task:** Day 28 — Outlier Detection
