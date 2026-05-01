# Titanic-Survival-Analysis-An-Exploratory-Data-Study

This repository contains an exploratory data analysis (EDA) of the classic Titanic dataset. The goal of this project was to clean the data and identify the primary factors that influenced passenger survival.

## Project Structure

The analysis is broken down into six core tasks:
1. **Data Loading & Inspection**: Initial look at the dataset structure and data types.
2. **Data Cleaning**: Identifying missing values and handling the `Age` column using median imputation.
3. **Simple Analysis**: Calculating the overall survival rate (38.38%).
4. **Filtering**: Segmenting the data by age (minors), fare (high spenders), and class.
5. **Feature Creation**: Creating a `FamilySize` variable to see how traveling with family affected survival.
6. **Insights & Sorting**: Identifying the oldest passengers and those who paid the highest fares.

## Key Insights
Based on the analysis in `titanic_dataset.ipynb`, the following conclusions were reached:
* **Gender**: Females had a significantly higher survival rate than males.
* **Socio-Economic Status**: Passengers in 1st Class had the highest survival rates.
* **Family Ties**: People traveling in families were more likely to survive than those traveling alone.
* **Overall Survival**: Approximately 38.38% of the passengers in this dataset survived.

## Technologies Used
* **Python 3**
* **Pandas** for data manipulation
* **Jupyter Notebook**

## How to Run
1. Clone this repository.
2. Ensure you have `pandas` installed: `pip install pandas`.
3. Open `titanic_dataset.ipynb` in Jupyter Notebook or VS Code to view the full analysis.

