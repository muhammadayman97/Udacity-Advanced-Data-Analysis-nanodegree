# Prosper Loan Dataset Investigation
## by Muhammad Ayman


## Dataset

> this dataset is containing information about borrowers's status like occupation, income range, loan amount, loss, return and more, which will help us defining who has more chance of accepting his loan request

>This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

>i decided to to work with 16 of these variables.


## Summary of Findings

> the main dataset structure is  (113937, 81) and the the structure after choosing specific variables is  (55089, 17)

> i started with detecting outliers, then i deleted them

> i started my exploration with univariate features then i started to generate countplot for the categorical features

> then i had two questions which i build my exploration process on them and they are : 

- Q1. What factors affect a LoanStatus and BorrowerRate?
- Q2. Are there differences between loans depending on how large the original loan amount was?

> i continued my exploration with features, but now the generated plots for bivariate features to see the relation between any two features

> i found that BorrowerRate is correlated with BorrowerAPR and ProsperRating (numeric) also Recommendations and investors are having effect on LoanStatus which help applicants to complete their loan

>the last thing was Multivariate Exploration, this phase was emphasis what was already found in previous phases

>these are my answers based on previous findings:

- Q1. What factors affect a LoanStatus and BorrowerRate?

for LoanStatus, Recommendations and investors are having effect on LoanStatus which help applicants to complete their loan, also for relation between LoanStatus and EmploymentStatus, if the applicant is employed then the chance to cancel his request is very small and the same for IsBorrowerHomeowner, which makes sense.

for BorrowerRate, from heat map i find that BorrowerRate is stronge positive correlated with BorrowerAPR, also there is a negative correleation between BorrowerRate and ProsperRating (numeric),Recommendations,Investors.

- Q2. Are there differences between loans depending on how large the original loan amount was?

with the increase of LoanOriginalAmount over years, the completed loans are increasing, defaulted and chargedoff loans are going ups and downs, but they are changing in the same form.

finally, cancelled loans are very small and we didn't find any starting with 2010.


## Key Insights for Presentation

> the main keys for this presentation are the plots of every feature and the plots that explain relation between two or more features which made it easier to answer the previous two questions.

> this presentation is presented in the same way that the notebook took but in a conlusive form.
