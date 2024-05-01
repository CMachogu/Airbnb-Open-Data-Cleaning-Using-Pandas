# Airbnb-Open-Data-Cleaning-Using-Pandas

## Overview
This repository contains the code and documentation detailing the process of cleaning an Airbnb dataset sourced from Kaggle using the Pandas library in Python.

## Dataset
The Airbnb dataset used in this project is sourced from Kaggle(https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata) and contains information about Airbnb listings. It includes various features such as Name, host ID, location, price, availability, and more.

## Data Cleaning Process
The data cleaning process involved several steps to ensure the dataset was ready for analysis:

1. **Importing the Dataset**: The dataset was imported into a Pandas DataFrame using the `pd.read_csv()` function.

2. **Handling Missing Values**: Missing values in the dataset were identified and handled appropriately. Depending on the context, missing values were either filled in with appropriate values or dropped from the dataset.

3. **Dealing with Mixed Data Types**: Columns with mixed data types were addressed to ensure consistency. This involved explicitly specifying data types for columns using the `dtype` parameter or setting `low_memory=False` to suppress warnings.

4. **Removing Duplicates**: Duplicate rows, if any, were identified and removed from the dataset to avoid redundancy and ensure data integrity.

5. **Standardizing Data Formats**: Data formats were standardized where necessary to ensure uniformity and ease of analysis.

6. **Data Validation**: The cleaned dataset underwent validation to ensure that it met the necessary quality standards and was ready for further analysis.

## Files
- `airbnb_data_cleaning.ipynb`: Jupyter Notebook containing the Python code used for data cleaning.
- `airbnb_cleaned.csv`: Cleaned dataset in CSV format.
- `README.md`: This documentation file providing an overview of the project and its contents.

## Usage
To replicate the data cleaning process:
1. Clone or download this repository to your local machine.
2. Open the airbnb_data_cleaning.ipynb notebook using Jupyter Notebook or JupyterLab.
3. Follow along with the code and comments to understand each step of the data cleaning process.
4. Execute the code cells to perform the data cleaning operations.
5. The cleaned dataset will be saved as `airbnb_cleaned.csv` for further analysis.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

Feel free to reach out if you have any questions or suggestions for improvement! 
