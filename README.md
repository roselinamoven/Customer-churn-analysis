# Customer-churn-analysis
This Python script performs an exploratory analysis on customer data from telecom services. It involves several key steps:

Data Import: Reads three CSV files containing charges, personal information, and plan details into Pandas DataFrames.

Handling Missing Values:

Monthly Charges: Fills missing values with the trimmed mean of existing monthly charges.
Total Charges: Fills missing values using the product of monthly charges and tenure.
Feature Engineering:

Tenure Binning: Discretizes tenure into four bins and adds a new column tenureBinned.
Churn Rate Calculation: Computes the percentage of customers who have churned.

Data Merging: Combines the charges, personal, and plan datasets into a single DataFrame.

Additional Analysis:

Calculates the percentage of customers older than 60.
Counts unique values in the internetService column.
The script outputs a dictionary with:

The mean of monthly charges (trimmed mean),
The updated charges DataFrame,
The churn percentage,
The merged DataFrame,
The percentage of customers older than 60,
Counts of different internet service types.
This analysis provides insights into customer behavior, service usage, and demographic information, essential for strategic decision-making.
