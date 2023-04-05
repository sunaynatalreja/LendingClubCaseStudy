# Lending Club Case Study
>Using EDA to understand how consumer attributes and loan attributes influence the tendency of default. 
>Identify patterns in loan defaulters, so that such loans can be reduced thereby cutting down loss.
>Identify patterns in loan payers, so that such loans can approved.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
####Business Objectives
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

 

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

 

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

 

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 

![image](https://user-images.githubusercontent.com/52531057/230127738-eb2601fd-d6df-4bfd-aae8-6960a5716a45.png)

## Conclusions
#### Factors driving High default rate
- Long tenure (60 months)
- Rental & Mortgage home ownership
- E,F,G grade and all sub grades in this category
- >11% interest rate
- Non-collateralized categories such as credit card, Debt consolidation and High risk categories such as small business
#### Next Steps for Lending Club
- Deploy LCs (loan collectors) effectively for user verification. Currently the quality of assessment is sub par
- Ensure that grading has been done for all loans that fall into high risk category (left section). Grades marked below C are highly prone to get defaulted
- Manage LC resources effectively by deploying more resources in second half of year as more loans are issued during the same time
#### Future scope of analysis
- The final cleaned data can be used up and loan status can be marked as 0 for Charged off and 1 Fully paid
- Longer term data if available can be sourced, cleaned and can be added
- ML models such as Logistic regression, RF or SVM can be applied to build a model that takes up customer information (~22 features) to assess credit worthiness

## Technologies Used
- Pandas
- NumPy
- Seaborn
- MatplotLib
