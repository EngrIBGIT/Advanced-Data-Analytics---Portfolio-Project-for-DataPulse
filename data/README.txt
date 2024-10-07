
# Data Analysis with Financial Quarters

This repository provides a step-by-step guide to performing data analysis on a dataset that includes financial years and quarters. The notebook includes functionalities to read, merge, clean, transform, and analyze the data. Additionally, it contains functions for converting financial years and quarters into actual dates.

## Overview

The goal of this project is to:
- Read data from multiple Excel sheets and merge them into a single DataFrame.
- Provide basic exploratory analysis on the merged data.
- Transform financial years and quarters into accurate date values for further analysis.

## Features

- **Reading Excel Files:** The notebook demonstrates how to load and concatenate multiple sheets from an Excel file into a single DataFrame.
- **Financial Year and Quarter Conversion:** A custom function is provided to convert financial years and quarters into real dates, allowing for easier time-based analysis.
- **Exploratory Data Analysis (EDA):** The notebook includes basic data analysis, providing insights into the dataset with basic statistics.

## Requirements

To run this notebook, the following Python packages are required:

```bash
pip install pandas numpy
```

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/data-analysis-with-financial-quarters.git
   ```

2. Navigate to the project directory:
   ```bash
   cd data-analysis-with-financial-quarters
   ```

3. Open the Jupyter notebook:
   ```bash
   jupyter notebook Sample.ipynb
   ```

4. Replace the `excel_file_path` in the notebook with the path to your own Excel file containing the financial data.

5. Run the cells step-by-step to:
   - Load and merge data sheets.
   - Inspect the data.
   - Convert financial years and quarters to date format.
   - Perform basic exploratory data analysis.

## Project Structure

```
.
├── Sample.ipynb           # The main Jupyter notebook with code and analysis
├── README.md              # This README file
└── dataset/               # Folder where your dataset will be stored
```

## Notebook Details

### 1. Reading and Merging Excel Sheets

The notebook first reads an Excel file containing multiple sheets. Sheets are concatenated into one DataFrame for analysis.

### 2. Data Inspection

The merged DataFrame is inspected for dimensions, data types, and any missing or null values.

### 3. Converting Financial Years and Quarters

A custom function `convert_financial_year_quarter` is provided to convert financial years and quarters into valid date formats.

### 4. Exploratory Data Analysis (EDA)

Basic statistics such as count, mean, and standard deviation are computed on the numeric data columns.

## License

This project is licensed under the MIT License.
