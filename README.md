# Banking_Domain_Risk_Analysis

## Problem Statement :

Develop aa basic understanding of Risk Analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.

## About the Dataset

This dataset basically contains information about bank details, various client details which consists of multiple tables which are interlinked whith each other with keys like Primary Key and foreign key.

The various tables are Banking Relationship, Client-Banking, Gender, Investment Advisor and Period.

## Insights gained after performing EDA :

### Deposits and Savings Behavior

The high correlation between Bank Deposits and Saving Accounts suggests that these may either measure overlapping financial behavior (e.g., total funds a customer keeps in the bank) or that people who actively deposit funds also tend to maintain or grow savings balances.


### Income, Age, and Accumulation

Moderate correlations of Age and Estimated Income with various balances (Superannuation, Savings, Checking) reflect a common financial lifecycle trend: higher income earners and older individuals often accumulate more savings, retirement funds, and may carry higher credit card balances or loans.


### Low Correlation with Properties Owned

Property ownership may depend on external factors (location, real estate market conditions, inheritance, etc.) that are not captured by these particular banking variables. Hence, we see weaker correlations here.


### Business vs. Personal Banking


Business Lending’s moderate link to Bank Loans suggests some customers may have both personal and business debts. However, business lending is relatively uncorrelated with other deposit or property-related metrics, indicating it may serve a distinct subset of customers or needs.


## Dashboard :

### Home Page

<img src="https://github.com/FaizanAhK/Banking_Domain_Risk_Analysis/blob/main/images/Home_Page.png?raw=true" alt="Home Page" width="650"/>


### Loan Analysis

<img src="https://github.com/FaizanAhK/Banking_Domain_Risk_Analysis/blob/main/images/Loan_Analysis.png?raw=true" alt="Loan Analysis" width="650"/>

### Deposit Analysis

<img src="https://github.com/FaizanAhK/Banking_Domain_Risk_Analysis/blob/main/images/Deposit_Analysis.png?raw=true" alt="Deposit Analysis" width="650"/>

### Summary Dashboard

<img src="https://github.com/FaizanAhK/Banking_Domain_Risk_Analysis/blob/main/images/Summary.png?raw=true" alt="Summary" width="650"/>


## KPI's used :

- **Total Clients :** Total Clients KPI represent the total numbers of clients in banking.
- **Total Loans :** Total Loan gives you information about the bank loan + Business Lending + Credit Card Balance of particular investor, gender.
- **Bank Loan :** Bank loan gives you information about the loan amount repaid from the client to the bank.
- **Business Lending :** Business Lending gives you information about the loan amount given to small businesses.
- **Total Deposit :** Total Deposit gives you information about the amount deposited by a particular investor in the bank.
- **Total Fees :** Total fees is nothing but the amount charged by the bank for account-set up, or maintenance charges.
- **Bank Deposit :** Bank Deposit is the money put in the bank.
- **Checking Account Amount :** Checking Account Amount is nothing but the account which offers easy access to your money for daily transactional needs.
- **Total CC Amount :** is nothing but a short term source of financing for a company by the bank.
- **Savings Account Amount :** A savings account is an interest-bearing deposit account held at a bank.
- **Foreign Currency Amount :** An account held in foreign currency.
- **Engagement Account :** Engagement Banking puts the customer at the center and aims to deliver the digital experiences they expect.
- **Credit Cards Balance :** It is the total money currently owned by a cardholder to their credit card bank.
