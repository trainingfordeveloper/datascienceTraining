# Diamonds Data Exploration

## Dataset

The Prosper loan dataset contain 113937 loans with 81 features where 60 are numerics and 21 non-numerics (categorical, date). The dataset can be found in the https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv.


## Summary of Findings

In the exploration, There is high correlation between BorrowerAPR and BorrowerRate, also between MonthlyLoanPayment and LoanOriginalAmount where the relationship is approximately linear. 
Charged off for loan status, 10-Cosmetic Procedure for listing category, teacher's aide for occupation and not employed status have higher borrower rate.
In general, more the amount of loan increase, lower is the borrower rate.
Borrower using 12 monthts Term borrow lower amount of loan but have higher monthly loan payement.
the few borrowers having monthly loan payment more than around 1200 use only 12 month Term and they have low borrower rate.
More than 95% of borrower pay monthly loan less than 1000.
Not available empoyement status have the lower borrower rate.
For borrower using 12 and 60 months Term, more the monthly loan payment increase, the borrower rate decrase.
surprise : Client having a house do not have better borrower rate

## Key Insights for Presentation

For the presentation, visualizations show:
-  the correlation between numeric variables and highlight the high correlation between Borrower rate and Borrower APR, also between Monthly Loan Payment and Loan Original Amount.
- a suprise that borrower having house do not have higher borrower rate.
- more the amount of loan increase, lower is the borrower rate and borrower using 12 monthts Term borrow lower amount of loan.
- more than 95% of borrower pay loan monthly less than 1000. Also for borrower using 12 and 60 months Term, more the monthly loan payment increase, the borrower rate decrase. Last, the few borrowers having monthly loan payment more than around 1200 use only 12 month Term and they have low borrower rate.
- 25000 is the highest Loan Original Amount for 12 months Term. Then, 35000 is the highest Loan Original Amount for 36 and 60 months Terms. Lower is the Term of payment, higher is the Monthly Loan Payment.