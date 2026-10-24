# Day 24: Data Type Cleaning Using Pandas

## Overview

This project focuses on identifying and correcting inappropriate data types in a dataset using Python and Pandas.

## Objective

To understand the importance of correct data types in data analysis and machine learning.

## Technologies Used

* Python
* Pandas
* Jupyter Notebook

## Tasks Completed

* Created an employee dataset containing columns stored as strings.
* Inspected column data types using `dtypes`.
* Converted Employee_ID and Age into integer types.
* Converted Salary into a numeric type using `pd.to_numeric()`.
* Converted Joining_Date into a datetime type using `pd.to_datetime()`.
* Verified the corrected data types.

## Key Functions

* `df.dtypes` — Inspects the data types of columns.
* `astype(int)` — Converts values into integers.
* `pd.to_numeric()` — Converts values into numeric types.
* `pd.to_datetime()` — Converts values into datetime objects.

## Expected Results

| Column       | Correct Data Type |
| ------------ | ----------------- |
| Employee_ID  | int64             |
| Name         | object            |
| Age          | int64             |
| Salary       | int64             |
| Joining_Date | datetime64[ns]    |

## Project Structure

```text
Veda_Internship_Day24/
├── Data_Type_Cleaning.ipynb
└── README.md
```

## Conclusion

This task demonstrated how to identify and correct data types using Pandas. Proper data types help improve data consistency and prepare datasets for further analysis and machine learning.
