https://www.kaggle.com/competitions/ba476-2024s-predicting-loan-defaults/overview

Introduction
Financial loan services are leveraged by companies across many industries, from big banks to financial institutions to government loans. One of the primary objectives of companies with financial loan services is to decrease payment defaults and ensure that individuals are paying back their loans as expected. In order to do this efficiently and systematically, many companies employ machine learning to predict which individuals are at the highest risk of defaulting on their loans, so that proper interventions can be effectively deployed to the right audience.

Description
This dataset is generated from Coursera's Loan Default Prediction Challenge data and will provide you the opportunity to tackle one of the most industry-relevant machine learning problems with a unique dataset that will put your modeling skills to the test. The dataset contains 200000 rows and 18 columns in total, 150000 of these rows appear in the training set, 10000 in the public test set and 40000 in the private test set.

Files
train.csv - the training set
test.csv - the test set
sample_submission.csv - a sample submission file in the correct format
Columns
ID - unique identifier for each instance
Age (integer) - age of borrower
Income (integer) - annual income of the borrower
LoanAmount (integer) - amount being borrowed
CreditScore (integer) - credit score, indicating creditworthiness
MonthsEmployed (integer) - number of months employed in current position
NumCreditLines (integer) - number of open credit lines
InterestRate (float) - loan interest rate
LoanTerm (integer) - term length of the loan
DTIRatio (float) - debt-to-income ratio, comparing borrower's debt to income
Education (categorical) - highest level of education (PhD, Master's, Bachelor's, High School)
EmploymentType (categorical) - type of employment of borrower (Full-time, Part-time, Self-Employed, Unemployed)
MaritalStatus (categorical) - marital status of borrower (Single, Married, Divorced)
HasMortgage (categorical) - Whether the borrower has a mortgage (Yes, No)
HasDependents (categorical) - Whether the borrower has depenents (Yes, No)
LoanPurpose (categorical) - purpose of loan (Home, Auto, Education, Business, Other)
HasCoSigner (categorical) - whether the loan has a cosigner (Yes, No)
Default (categorical) - binary target variable indicating default (1 means default, 0 repaid)
