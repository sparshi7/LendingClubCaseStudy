# Lending Club Case Study
Lending Club Case Study as part of Upgrad IIIT Bengaluru course in Machine Learning and AI is to identify the driving factors behind loan default for a consumer finance company using Exploratory Data Analysis to minimize the risk of losing money while lending to customers.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusion](#conclusion)
* [Contact](#contact)

## General Information
- The goal of the case study is to identify the driving factors behind loan default for a consumer finance company using Exploratory Data Analysis to minimize the risk of losing money while lending to customers.
- The company specialises in lending various types of loans to urban customers.
- When the company receives a loan application, the company has to make a decision for loan approval based on the applicant's profile. Two types of risks are associated with the bank's decision:
  - If the applicant is likely to repay the loan, then not approving the loan, results in a loss of business to the company.
  - If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.
- **Background**:
  - Use Exploratory Data Analysis to understand how consumer attributes and loan attributes influence the tendency of loan default.
  - Understand risk analytics in banking and financial services and how data is used to minimise the risk of losing money while lending to customers.
- **Problem Statement**: Identify the driving factors behind loan default thereby empowering the company in making a wise decision on loan approval to minimize the financial loss to the company.
- **Dataset**: It contains the complete loan data for all loans issued (**applied and approved**) through the time period 2007 to 2011 for a major consumer finance company. The dataset has data for three kinds of scenarios:
    - _Fully paid_: Applicant has fully paid the loan (the principal and the interest rate).  
    - _Current_: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.  
    - _Charged-off_: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan.  

## Technologies Used
- pandas - version 2.1.4
- matplotlib - version 3.8.0
- seaborn - version 0.13.2

## Conclusion
Major driving factors behind loan default are mentioned below:
 - **Positively correlated variables**:
   - int_rate
   - dti
   - issue_d
   - term
   - delinq_2yrs
- **Negatively correlated variables**:
  - annual_inc
  - grade

## Contact
Created by [@sparshi7] - feel free to contact me!