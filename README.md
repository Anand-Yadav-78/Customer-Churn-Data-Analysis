
Customer Churn Analysis

Introduction:
This project focuses on analyzing customer churn in a telecommunications company. Understanding customer churn is vital for businesses as it helps in identifying factors leading to customer retention or loss. By analyzing various attributes and visualizing the data, this project aims to uncover insights that can help the company improve its services and reduce churn rates.

Features:

Data Loading: Loaded the customer churn dataset for analysis.

Data Exploration:
Displayed the first few rows of the dataset for initial insights.
Obtained basic information about the dataset, including data types and non-null counts.

Data Cleaning:
Replaced spaces in the TotalCharges column with 0 and converted the column to float type.
Handled missing values through median imputation for numeric columns.
Duplicate Check: Verified that there are no duplicated customer IDs in the dataset.

Data Transformation:
Converted the SeniorCitizen column values from binary (0/1) to categorical ('no'/'yes').
Converted relevant categorical columns to the 'category' data type for efficient processing.

Data Visualization:
- Created count plots to visualize the number of customers by churn status.
- Generated pie charts to illustrate the percentage of churned customers.
- Analyzed churn rates based on gender and senior citizen status with visualizations.
- Explored the relationship between tenure and churn with histograms.
- Visualized customer distribution by contract type.
- Developed a correlation matrix for key numerical features.
- Used boxplots to detect outliers in numerical features and visualize churn against various attributes.
- Created multiple count plots to explore churn based on phone and internet-related services.
- Analyzed churn by payment method using a count plot.
