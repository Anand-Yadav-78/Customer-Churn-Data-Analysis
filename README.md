
<H1><b>Customer Churn Analysis</b></H1>

<H2><b>Introduction:</b></H2>

This project focuses on analyzing customer churn in a telecommunications company. Understanding customer churn is vital for businesses as it helps in identifying factors leading to customer retention or loss. By analyzing various attributes and visualizing the data, this project aims to uncover insights that can help the company improve its services and reduce churn rates.

<H2><b>Features:</b></H2>

<H3><b>Data Loading:</b></H3>

- Loaded the customer churn dataset for analysis.

<H3><b>Data Exploration:</b></H3>
- Displayed the first few rows of the dataset for initial insights.
- Obtained basic information about the dataset, including data types and non-null counts.

<H3><b>Data Cleaning:</b></H3>
- Replaced spaces in the TotalCharges column with 0 and converted the column to float type.
- Handled missing values through median imputation for numeric columns.
- Duplicate Check: Verified that there are no duplicated customer IDs in the dataset.

<H3><b>Data Transformation:</b></H3>
- Converted the SeniorCitizen column values from binary (0/1) to categorical ('no'/'yes').
- Converted relevant categorical columns to the 'category' data type for efficient processing.

<H3><b>Data Visualization:</b></H3>
- Created count plots to visualize the number of customers by churn status.
- Generated pie charts to illustrate the percentage of churned customers.
- Analyzed churn rates based on gender and senior citizen status with visualizations.
- Explored the relationship between tenure and churn with histograms.
- Visualized customer distribution by contract type.
- Developed a correlation matrix for key numerical features.
- Used boxplots to detect outliers in numerical features and visualize churn against various attributes.
- Created multiple count plots to explore churn based on phone and internet-related services.
- Analyzed churn by payment method using a count plot.
