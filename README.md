# Lending Club Case Study
Detailed analysis about past loan applicants. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc
Using EDA understand how consumer attributes and loan attributes influence the tendency of default.


## Table of Contents
* [General Information]
* [Approach]
* [Conclusions]


## General Information
- Analyse loan.csv than contains information of past loan applicants.
- Understand consumer attributes and loan attributes
- Find out variable that can be used as indicator to find whether applicant will default or not.

## Approach
- Remove the columns having null value count greater than 90%
- Remove the columns that are not useful for analysing purpose
- Remove the outliers
- Do Univariate, Segmented Univariate, Bivariate Analysis.
- Create Business-driven or Type-drive columns and Analyse
  
## Conclusions
Below are important 5 Variables which can be used as indicators to predict if a loan will be default.

- Interest Rate : Loans taken at high interest rate are most likely to be default irrespective of annual income of the borrower.
- Grade : Grade is quality score assigned by bank to customer based on credit history, quality of colateral and likelihood of repayment.
           E, F and G category of loan are most likely to default
- Home Ownership Status : Borrowers with home ownership status “OTHER” taken comparatively high loan amount and paying high
           monthly instalments are most likely to default the loan. 
- Revolving credit : This is a open-ended credit account that can be used and paid repeatedly as long as account is remain open.
           Borrowers most likely to default if their revolving credit utilistaion exceeds 50%
- Loan to Income Ratio : If loan amount is 50% of the annual Income then 30% of borrowers belong to same income group are
           Defaulters.


