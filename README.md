# Project Name

A finance service company called the Lending Club offers customers to lend various types of loans. Some of the types of loans are business loans, personal loans, educational loans, home loans etc.
When an applicant applies for a loan, the company has to take a decision for a loan approval based on the applicant’s information.
When a person applies for a loan, there are two types of decisions that could be taken by the company:

Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 
Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

The dataset consists of data dictionary and loans details issued from 2007 to 2011 by the Lending Club. 

Since the company wants to understand the driving factor behind a defaults, only those variables will be considered for the analysis. These variables will be helpful in helping the investor to take a decision on whether or not to invest in the loan request. Customer behaviour information provided in the dataset will not be considered

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Provide general information about your project here.
    The goal of this analysis is to identify whether a applicants/borrower will be able to fully pay the loan with the interest amount. The dataset provided by the Lending Club must help us to analyse the pattern of a Charged Off and Fully Paid customer. This can be used for taking actions such as denying the loan, reducing the amount of loan or lending at a higher interest rate.
- What is the background of your project?
    LendingClub is a financial services company headquartered in San Francisco, California. It was the first peer-to-peer lender to register its offerings as securities with the Securities and Exchange Commission, and to offer loan trading on a secondary market
- What is the business probem that your project is trying to solve?
    The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.
    Lending loans to ‘risky’ applicants can cause credit loss. In such a situation, the customers labelled as 'charged-off' are the 'defaulters'.
- What is the dataset that is being used?
    The data given loan and data dictionary contains the information about past loan applicants and whether they ‘defaulted’ or not.


## Conclusions
1. Lending club should reduce the higher interest rate loans with higher tenure (60 months) , these loans are more prone to default.
2. Small Business loans are more defaulted, So these loan should be reduced.
3. Grade are good metric for detecting defaulters. Loan applicants categorised under lower grades like G, F and E should be examined more stringently.
4. Borrowers with mortgage home ownership are taking higher loan, and defaulted, these loan should be reduced.
5. If Ratio of loan amount and funded amount is lesser than 90%, we see most of borrower tend to defaulted. Its risky for lending club to approve loan for these borrowers

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.8
- Panda - version 2.0.3
- Matplotlib - version 3.4
- Seaborn - version 3.0
- Plotly - version 3.0
- IDE - Jupyter Notebook - version 6.5.2


## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@githubusername] - feel free to contact me!