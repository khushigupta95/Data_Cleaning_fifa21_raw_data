# FIFA 21 Data Cleaning

## Project Overview
This project focuses on cleaning and preprocessing the raw FIFA 21 dataset to ensure data quality and usability for analysis. The dataset contains various attributes related to player statistics, contracts, and performance.

## Tools Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook

## Files Included

- -<a href="https://github.com/khushigupta95/Data_Cleaning_fifa21_raw_data/blob/main/fifa21%20raw%20data%20v2.csv">Dataset</a> – The original dataset before cleaning.

- <a href="https://github.com/khushigupta95/Data_Cleaning_fifa21_raw_data/blob/main/Fifa_raw_data_cleaning.ipynb">Jupyter notebook</a> – Jupyter Notebook containing step-by-step cleaning process.


- ## Steps Performed

1. **Handling Missing Values:**
   - Identified missing values in various columns.
   - Used **mean** for numerical attributes like `height`, **median** for `weight`, and **mode** for categorical attributes like `club` to fill missing values.

2. **Data Type Conversion:**
   - Converted numerical columns stored as strings (e.g., `value`, `wage`) into appropriate numerical formats.
   - Standardized date formats where necessary.

3. **Removing Duplicates:**
   - Checked for and removed duplicate records to avoid redundancy.

4. **Fixing Inconsistent Data:**
   - Standardized club names and positions.
   - Corrected incorrect numerical values where needed.

5. **Feature Engineering:**
   - Extracted relevant information from complex columns (e.g., breaking down `contract` into start and end dates).
   - Created new features based on existing attributes where necessary.

6. **Final Export:**
   - Saved the cleaned dataset for further analysis.

## Conclusion
By applying the above cleaning steps, the dataset is now structured and free of inconsistencies, making it suitable for further exploratory data analysis and modeling.

