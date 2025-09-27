# Project Title: Bank Loan Analysis
## Project Objective
To conduct a comprehensive analysis of bank loan data to understand key metrics, identify trends and evaluate risk factors for a bank that provides loan services to its customers.
## Dataset Used:
https://github.com/kirti2222/Python-Project/blob/main/financial_loan.xlsx
## Project Questions
1.	What are the total loan amounts and the total payments collected from borrowers?
2.	What is the breakdown and distribution of loans by their current status?
3.	Does the term of the loan significantly impact the total amount paid or the loan performance/ risk?
4.	How are loan applications distributed across different borrower home ownership categories?
5.	Are there significant differences in loan amount, interest rate, or loan status across the various states where borrowers reside?
## Project Process
### 1. Setup and Data Acquisition
•	Import Libraries: The project starts by importing necessary Python libraries, such as pandas for data manipulation, numpy for numerical operations, and matplotlib/seaborn/plotly for data visualization.
•	Load Data: Read the loan dataset (likely a CSV file) into a pandas DataFrame.
•	Initial Data Review: Perform initial checks like viewing the first few rows (df.head()), checking data types (df.info()), and inspecting the shape of the dataset
### 2. Data Cleaning and Preprocessing
•	Handle Missing Values: Identify and address columns with missing values (e.g., imputation or removal, depending on the extent of missingness).
•	Handle Duplicate Data: Check for and remove any duplicate records.
•	Data Type Conversion: Ensure all columns are in the correct data format (e.g., converting interest rates from strings to numerical format).
### 3. Exploratory Data Analysis (EDA)
•	Univariate Analysis: Analyze individual features to understand their distribution (e.g., a histogram of loan_amount, a count plot of home_ownership).
•	Bivariate/Multivariate Analysis: Analyze the relationship between key variables and the target variable, which is typically loan_status (e.g., checking the average interest rate by grade, or the default rate across different purpose categories).
•	Visualization: Use various plots (bar charts, box plots, treemaps etc) to visually explore patterns and correlations within the data.
### 4. Answering Key Questions (Core Analysis)
•	Risk Assessment: Perform detailed analysis to identify which features (e.g., dti, annual_income, grade) are statistically significant in predicting loan risk.
•	Performance Metrics: Calculate and compare key performance indicators (KPIs) like default rates, total payments received, and net returns across different segments of the loan portfolio.
•	Reporting: Summarize all findings and present the results in a clear, actionable manner including the visualizations created in the EDA phase.
## Project Insight
1.	The loan book is generally healthy, with over 8 out of 10 loans successfully paid off, resulting in a substantial positive financial return
2.	The most significant risk indicator is the 60-month loan term, which has a failure rate (Charged Off Rate) of 23.36%. A review of the underwriting criteria for the 60-month term is crucial to reduce risk exposure and prevent future losses.
3.	The core borrower base consists of renters and mortgage holders, suggesting the primary market is composed of individuals seeking non-secured loans (like debt consolidation or personal use) who have not yet paid off their primary residence.
4.	While California is the largest market by volume, New Jersey (NJ) is a critical area for immediate attention. NJ accounts for both a high average loan value and the highest Charged Off Rate (18.06%), indicating a combination of high exposure and high risk. Future strategies should consider tighter lending standards or higher risk-adjusted pricing specifically for NJ and for the 60-month term loans.
## Final Conclusion
The bank loan analysis demonstrates strong overall health and profitability, evidenced by a high 82.70% 'Fully Paid' rate and a significant positive return (Total Payments exceeding Total Loan Amounts). However, the analysis clearly identifies a critical area of high risk that requires immediate strategic intervention. The 60-month loan term. Loans with this longer term exhibit a Charged Off Rate 23.36% that is nearly triple that of the 36-month term loans.To sustain profitability and mitigate future losses, the bank should strategically re-evaluate and tighten the underwriting criteria for 60-month term loans, particularly for high-risk segments like the New Jersey market, to reduce the disproportionately high risk exposure currently concentrated in this product offering. This action is crucial to optimize the risk-return profile and maximize the long-term success of the lending program of the bank.



