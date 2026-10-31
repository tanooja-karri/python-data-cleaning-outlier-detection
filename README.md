# Python Data Cleaning and Outlier Detection

## Project Overview

This project demonstrates data cleaning and preprocessing techniques using Python. The notebook explores a customer dataset and addresses data quality issues such as missing values, inconsistent formats, duplicate records, and potential outliers.

## Objectives

- Explore dataset structure and summary statistics.
- Identify and handle missing values.
- Standardize inconsistent categorical values.
- Convert columns to appropriate data types.
- Identify duplicate records.
- Visualize numerical distributions using boxplots.
- Apply Z-score-based outlier detection.

## Tools and Libraries

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow

1. **Data Exploration:** Inspected the dataset using summary statistics, data types, and unique values.
2. **Missing Values:** Examined missing values and applied suitable handling methods.
3. **Data Cleaning:** Standardized text values and converted columns to appropriate data types.
4. **Duplicate Handling:** Identified duplicate records and removed duplicates where appropriate.
5. **Visualization:** Created boxplots for Age, Purchase Amount, and Feedback Score.
6. **Outlier Detection:** Applied absolute Z-scores with a threshold of 3 to Age and Purchase Amount.

## Key Learning

Data cleaning is an important step in preparing reliable data for analysis. Outliers should be investigated carefully before removal because extreme values may represent valid observations rather than errors.

## Repository Contents

- `data cleaning.ipynb` — Jupyter Notebook containing the data cleaning and outlier detection workflow.

## How to Run

1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy scipy matplotlib seaborn jupyter
   ```

3. Open the notebook in Jupyter Notebook.
4. Ensure the input dataset is available at the file path used in the notebook.
5. Run the notebook cells in order.

## Future Improvements

- Compare dataset statistics before and after cleaning.
- Report the number and percentage of rows removed.
- Investigate extreme values before filtering.
- Compare Z-score and IQR-based outlier detection methods.
