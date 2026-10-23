# Day 23: Duplicate Data Removal Using Pandas

## Project Overview

This project demonstrates how to identify and remove duplicate records from a dataset using Python and Pandas.

## Objective

Learn a basic data-cleaning technique used to improve data quality before analysis and machine learning.

## Technologies Used

* Python
* Pandas
* Jupyter Notebook

## Dataset Description

A sample student dataset containing the following columns:

* `Student_ID`
* `Name`
* `Department`
* `Marks`

The dataset contains 8 records, including 2 duplicate rows.

## Tasks Performed

1. Created a sample student dataset using Pandas.
2. Displayed the original dataset.
3. Identified duplicate records using `duplicated()`.
4. Counted the duplicate records.
5. Removed duplicates using `drop_duplicates()`.
6. Compared row counts before and after cleaning.
7. Verified that no duplicate rows remained.

## Key Results

| Metric                      | Result |
| --------------------------- | -----: |
| Original Rows               |      8 |
| Duplicate Records           |      2 |
| Rows After Cleaning         |      6 |
| Rows Removed                |      2 |
| Remaining Duplicate Records |      0 |

## Python Functions Used

* `pd.DataFrame()` — Creates a DataFrame.
* `duplicated()` — Identifies duplicate rows.
* `drop_duplicates()` — Removes duplicate rows.
* `len()` — Counts the number of rows.
* `sum()` — Counts duplicate records.

## Project Structure

```text
Veda_Internship_Day23/
├── Duplicate_Data_Removal.ipynb
└── README.md
```

## Conclusion

This project demonstrates how Pandas can identify and remove duplicate records efficiently. Removing duplicate data helps improve dataset quality and supports more reliable data analysis.

## Internship Details

**Organization:** Veda Technology
**Track:** Artificial Intelligence and Machine Learning
**Task:** Day 23 — Duplicate Data Removal
