# Task1
# Data Cleaning and Preprocessing

This repository contains a Python script for cleaning and preprocessing a dataset related to appointment no-shows. The following steps were performed to ensure the data is clean, consistent, and ready for analysis.

## Steps Performed

1. **Load the Dataset**: The dataset was loaded into a Pandas DataFrame for manipulation.

2. **Identify and Handle Missing Values**:
   - Checked for missing values using `.isnull()`.
   - Removed rows with missing values using `dropna()`.

3. **Remove Duplicate Records**:
   - Identified and removed duplicate rows using `drop_duplicates()`.

4. **Standardize Text Values**:
   - Standardized categorical text values (e.g., gender) to lowercase and stripped whitespace.

5. **Convert Date Formats**:
   - Converted date columns (`AppointmentDay` and `ScheduledDay`) to a consistent datetime format using `pd.to_datetime()` without specifying a format.

6. **Rename Column Headers**:
   - Renamed columns to be lowercase and replaced spaces with underscores for consistency.

7. **Check and Fix Data Types**:
   - Verified and corrected data types for each column, ensuring that age is an integer and date columns are in datetime format.

## Requirements

- Python 3.x
- Pandas library

## Usage

To run the script, ensure you have the required libraries installed and execute the script in your Python environment. The cleaned DataFrame can be saved for further analysis.

## Conclusion

These preprocessing steps help ensure that the dataset is clean and ready for analysis, improving the quality and reliability of any insights derived from it.
