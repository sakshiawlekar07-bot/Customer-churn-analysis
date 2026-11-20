# Customer Churn Analysis Using Python

## Project Overview

This project explores customer churn data to understand which customer
groups and service-related factors are associated with customers leaving
a service. The analysis uses Python for data preparation, exploratory
data analysis (EDA), and visualisation.

## Tools and Libraries

-   Python
-   Pandas -- data loading, cleaning, and analysis
-   NumPy -- numerical operations
-   Matplotlib -- charts and visualisation
-   Seaborn -- statistical plots and visualisation
-   Jupyter Notebook -- running and documenting the analysis

## Dataset

The notebook loads the dataset from a CSV file named
`Customer Churn.csv`.

The analysis uses customer information such as: - Gender and
senior-citizen status - Tenure and contract type - Phone and internet
services - Online security, online backup, device protection, and tech
support - Streaming services - Payment method - Churn status

## Data Preparation

The notebook includes the following preparation steps: 1. Loads the CSV
dataset into a Pandas DataFrame. 2. Checks the dataset structure and
data types using `info()`. 3. Replaces blank values in `TotalCharges`
with `0` and converts the column to a numeric data type. 4. Checks for
missing values, summary statistics, and duplicate customer IDs. 5.
Converts the `SeniorCitizen` values from `1` and `0` into `yes` and `no`
for easier interpretation.

## Exploratory Data Analysis

The notebook investigates customer churn through: - A count plot and pie
chart showing the distribution of churned and retained customers. -
Churn comparisons by gender and senior-citizen status. - A
percentage-based stacked bar chart comparing churn by senior-citizen
status. - A tenure histogram split by churn status. - Contract-type
comparisons. - Count plots for phone service, multiple lines, internet
service, online security, online backup, device protection, tech
support, streaming TV, and streaming movies. - A payment-method
comparison by churn status.

## Key Findings

Based on the visualisations and observations recorded in the notebook:

-   Approximately **26.54%** of customers in the analysed dataset have
    churned.
-   The senior-citizen group has a comparatively higher churn
    percentage.
-   Customers with shorter tenure, particularly those who have been with
    the service for only a short time, show more churn.
-   Month-to-month contract customers are more likely to churn than
    customers on longer-term contracts.
-   Customers without Online Security, Online Backup, and Tech Support
    show noticeably higher churn in the count plots.
-   Fiber Optic internet customers show comparatively high churn among
    the internet-service categories.
-   Electronic check users show higher churn in the payment-method
    comparison.
-   Gender, Phone Service, Multiple Lines, Streaming TV, and Streaming
    Movies are also explored for churn patterns.

These findings describe patterns in the dataset and do not, by
themselves, establish that a particular service or customer
characteristic causes churn.

## How to Run the Project

1.  Download or clone this repository.

2.  Keep the notebook and `Customer Churn.csv` in the same folder.

3.  Install the required libraries:

    ``` bash
    pip install pandas numpy matplotlib seaborn jupyter
    ```

4.  Open Jupyter Notebook:

    ``` bash
    jupyter notebook
    ```

5.  Open the `.ipynb` notebook and run the cells from top to bottom.

## Repository Files

-   `TCA(1).ipynb` -- Jupyter Notebook containing the Python code,
    analysis, and visualisations.
-   `Customer Churn.csv` -- Dataset required by the notebook (include
    this file in the repository if you are permitted to share it).
-   `README.md` -- Project documentation.

## Project Objective

The objective of this project is to use exploratory data analysis to
understand customer churn patterns and highlight areas that a business
could investigate when developing customer-retention strategies.
