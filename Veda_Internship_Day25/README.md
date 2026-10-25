# Day 25: Basic Data Cleaning Using Pandas

## Overview

This project demonstrates basic data-cleaning techniques using Python and Pandas.

## Objective

To clean a dataset by handling missing values, removing duplicate records, and correcting data types.

## Technologies Used

* Python
* Pandas
* Jupyter Notebook

## Tasks Completed

* Created an employee dataset.
* Identified missing values using `isnull().sum()`.
* Removed duplicate records using `drop_duplicates()`.
* Converted Employee_ID, Age, and Salary into numeric data types.
* Replaced missing names with "Unknown".
* Filled missing numerical values using the median.
* Verified missing values and duplicate records after cleaning.

## Key Functions

* `df.isnull().sum()` — Identifies missing values.
* `df.drop_duplicates()` — Removes duplicate records.
* `pd.to_numeric()` — Converts values into numeric types.
* `df.fillna()` — Handles missing values.
* `df.reset_index()` — Resets the row index.

## Expected Results

* Missing values are handled.
* Duplicate records are removed.
* Numeric columns have appropriate data types.
* The cleaned dataset is ready for further analysis.

## Project Structure

```text
Veda_Internship_Day25/
├── Basic_Data_Cleaning.ipynb
└── README.md
```

## Conclusion

This task provided practical experience in combining essential data-cleaning techniques using Pandas. These techniques help improve data quality before performing data analysis or developing machine learning models.

## Internship Details

**Organization:** Veda Technology
**Track:** Artificial Intelligence and Machine Learning
**Task:** Day 25 — Basic Data Cleaning
