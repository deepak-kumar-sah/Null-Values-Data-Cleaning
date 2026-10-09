# Null Values Data Cleaning Project

## Project Overview

This project focuses on identifying and handling missing values in a dataset using Python, Pandas, NumPy, and Jupyter Notebook. The goal is to improve data quality and prepare the dataset for further analysis.

## Objectives

* Identify missing values in each column.
* Detect and remove completely empty rows.
* Handle missing categorical and numerical values.
* Convert columns to appropriate data types.
* Verify the cleaned dataset.
* Export the cleaned data into Excel and CSV formats.

## Tools & Technologies

* Python
* Pandas
* NumPy
* Jupyter Notebook
* Microsoft Excel
* CSV

## Dataset Information

The project uses an employee-related dataset containing columns such as Employee ID, Name, Age, Gender, Department, Salary, Experience, City, Education, Performance, Projects, and Joining Year.

The dataset contains missing values and completely empty rows, making it suitable for practicing data cleaning techniques.

## Data Cleaning Process

1. Loaded the original Excel dataset using Pandas.
2. Checked missing values in each column.
3. Identified and removed completely empty rows.
4. Filled missing categorical values using the mode.
5. Filled missing numerical values using the median.
6. Converted integer-like columns and text columns to appropriate data types.
7. Verified that no missing values remained in the cleaned dataset.
8. Exported the cleaned dataset to Excel and CSV formats.

## Key Results

* Identified and removed 200 completely empty rows.
* Handled missing values using mode and median imputation.
* Converted columns to suitable data types.
* Verified that the cleaned dataset contains zero missing values.
* Saved the cleaned dataset in Excel and CSV formats.

## Project Structure

```text
Null-Values-Data-Cleaning/
│
├── data/
│   ├── large_null_dataset.xlsx
│   ├── cleaned_dataset.xlsx
│   └── cleaned_dataset.csv
│
├── notebooks/
│   └── Null_Values_Data_Cleaning.ipynb
│
├── README.md
└── .gitignore
```

## Output Files

* `cleaned_dataset.xlsx` — Cleaned dataset in Excel format.
* `cleaned_dataset.csv` — Cleaned dataset in CSV format.
* `Null_Values_Data_Cleaning.ipynb` — Notebook containing the data cleaning process.

## How to Run the Project

1. Clone or download this repository.

2. Install the required libraries:

   `pip install pandas numpy openpyxl`

3. Open `notebooks/Null_Values_Data_Cleaning.ipynb` in Jupyter Notebook.

4. Run the notebook cells in order.

## Skills Demonstrated

* Data Cleaning
* Missing Value Handling
* Exploratory Data Preparation
* Pandas and NumPy
* Data Type Conversion
* Excel and CSV File Handling
* Jupyter Notebook

## Author

**Deepak Kumar Sah**
Aspiring Data Analyst | Python | SQL | Excel | Power BI

GitHub: [deepak-kumar-sah](https://github.com/deepak-kumar-sah)
