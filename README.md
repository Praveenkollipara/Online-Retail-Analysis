# Online-Retail-Analysis

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset Overview](#dataset-overview)
- [Technologies Used](#technologies-used)
- [Data Cleaning and Feature Engineering](#data-cleaning-and-feature-engineering)
- [Exploratory Data Analysis and Visualization](#Exploratory-data-analysis-and-visualization)
- [Conclusion](#conclusion)
- [Acknowledgements](#acknowledgements)


## Project Overview
This project explores a comprehensive data analysis workflow using a dataset containing half a million sales transactions from a UK online retailer. The analysis covers key aspects such as:
- Exploratory Data Analysis (EDA)
- Customer segmentation with RFM analysis
- Customer churn analysis

## Dataset Overview
The dataset we will be using contains half a million records with the following columns:
- Invoice Number
- Stock Code (Product ID)
- Description
- Quantity
- Invoice Date
- Unit Price
- Customer ID
  

## Technologies Used
- Python (for data analysis and visualization)
- Pandas (initial data manipulation)
- Matplotlib (visualization)
- Google Colab (execution environment)

## Data Cleaning and Feature Engineering
### Handling Missing Data :
- Replace missing descriptions using the most frequent description for each stock code.
- Drop remaining rows with missing values.
### Removing Invalid Entries :
- Filter out negative values in quantity and unit price.
### Feature Creation :
To enhance our analysis, we will create new features.
- Compute total sales as Quantity * Unit Price.
- Extract the month from the invoice date for trend analysis.









