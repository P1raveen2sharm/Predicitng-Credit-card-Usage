# Predicitng-Credit-card-Usage
Key Actions Performed

Combined three datasets: Customer Demographics, Customer Behavioral Data, and Credit Consumption Data (49 attributes, 20,000 records).
Handled missing data:
Imputed missing values using mean or mode for both continuous and categorical variables.
Managed 5,005 missing entries across key columns like cc_cons (credit consumption).
Converted categorical variables (e.g., gender, account_type) to numerical form for model readiness.
Exploratory Data Analysis (EDA):

Analyzed consumption trends for April, May, and June, capturing month-over-month changes.
Identified key patterns in:
Credit and debit card usage.
Spending behavior across customer segments (e.g., NetBanking_Flag, Income levels).
Detected high variability in monthly spending:
April credit card consumption: Mean $17,857, Max $441,031.
June credit card consumption: Mean $12,136, Max $382,914.
Segmentation Analysis:

Grouped customers by age, tenure, and income levels to assess their consumption behavior.
Found top contributors to high spending patterns were middle-aged customers (35–55 years) with active loans and high tenure.
Predictive Modeling:

Applied Linear Regression to predict future credit card consumption based on historical data and demographic variables.
Split data into:
Training set: 15,000 records.
Test set: 5,000 records.
Model performance:
Mean Absolute Error (MAE): ~
Root Mean Squared Error (RMSE): ~
Model effectively captured the linear relationship between independent features and consumption patterns.
Insights and Visualizations:

Generated heatmaps and visualizations to highlight missing data and consumption trends.
Monthly averages showcased declining credit usage:
April: $17,857
May: $16,188
June: $12,136
Quantitative Highlights:

Data Volume: 20,000 customers, 49 attributes.
Variables:
Continuous: 27 (e.g., cc_cons_apr, credit_amount_jun).
Categorical: 22 (e.g., gender, region_code).
Model Inputs: Historical spending, loan statuses, income, age, and banking flags.
Prediction Target: Expected credit consumption for the next three months.
Technologies Used:

Python (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib) for data preprocessing, analysis, and visualization.
Linear Regression for predictive modeling.


