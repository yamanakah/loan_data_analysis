# Data Exploration on Loan Data from Prosper
## by Hyoson Yamanaka


## Dataset

- The dataset in this report contains 113,937 loans from the Prosper marketplace. It provides borrower and loan characteristics with 81 variables such as loan amount, interest rate, loan status, borrower income, employment status, credit history, etc.


- Data source: https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv


- Explanation of the variables included in the dataset: 
https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit?usp=sharing


## Summary of Findings

- A siginifcant number of loans in the Propser dataset are defaulted, with the peak of defaults stemming from loans originated before and during the period of the financial crisis.

- Different states in the US show very divergent default rates, showing that the regional performance of the loans is not homogenous.

- Borrowers who defaulted generally came from lower income levels. This holds across almost all employment types. They also show generally higher levels of APR and lower Prosper Scores (for loans past 2009).

- Connectsion between the APR and defaults or income could not be established.

- Most borrowers have incomes between 25,000 to 75,000 USD.


## Key Insights for Presentation

- The focus for the explanatory presentation is to show certain characteristics of the defaulted loans. First, the default rate development over time shows that the economic environment seems to be a key link to the loan performance. Second, the charactersitics of defaulted loans show that certain regions in the US were performing much worse and that borrowers who defaulted generally had lower income levels. The APR and Prosper Score also seem indicative about if a loan defaulted or not (for post-2009 data).
