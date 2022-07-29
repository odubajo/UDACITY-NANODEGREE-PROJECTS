
> Discover insights from data via Python.


### Prerequisites

You'll need to install:

* [Python (3.x or higher)](https://www.python.org/downloads/)
* [Jupyter Notebook](https://jupyter.org/)
* [Numpy](http://www.numpy.org/)
* [Pandas](http://pandas.pydata.org/)
* [Matplotlib](https://matplotlib.org/)
* [Seaborn](https://seaborn.pydata.org/)

And additional libraries defined in each project.

Recommended:

* [Anaconda](https://www.anaconda.com/distribution/#download-section)


### P4: Communicate Data Findings

## by Odubajo Qoyyum


## Dataset Overview

# Prosper loans dataset Investigation

This dataset contains information on peer to peer loans facilitated by credit company Prosper. There are 113,937 loans with 81 variables. For the purpose of this investigation I've taken the following variables: Term, LoanStatus, BorrowerRate, EstimatedReturn, ProsperRating (Alpha), ListingCategory (numeric), EmploymentStatus, IsBorrowerHomeowner, StatedMonthlyIncome, TotalProsperLoans, LoanOriginalAmount, LoanOriginationDate and Investors.


## Summary of Findings

- Prosper ratings are almost normally distributed. Distribution of monthly stated income is very varied: with a lot of outliers and very large range of values. Most loans are below $15,000, seems like most loans are increments of $5,000.

- Prosper rating D is the most frequent rating among defaulted credits.

- A vast amount of the loans was taken for debt consolidation.

- majority of the loans are taken for 36 months followed by 60 months.

- Default credits tend to be given to individuals with lower rating.
 
- The borrower rate tends to be higher for defaulted credits.

- Mid term (36 months) credits are riskier than short term (12 months) and long term(60 months).

- Borrower rate for low rating is higher.


## Key Insights for Presentation

I've chosen key plots with high data-to-ink ratio for the presentation. The plots I've chosen shows distribution of main variables, Loan status, monthly income, Prosper rating and I've tried to tell a story what are major predictors for loan status and Prosper rating variables.
