# Data_Mining_Project2_SNAPP

# [Creadit risk analysis](https://www.kaggle.com/datasets/rameshmehta/credit-risk-analysis)

# Introduction

In the GitHub repository, you will discover code and comprehensive documentation related to our Data Mining course project. Our project's primary focus revolves around conducting an in-depth exploratory data analysis (EDA) and developing classification models. Our objective is to offer a thorough comprehension of the dataset we have at hand, as well as construct and evaluate  models through a systematic approach. This project serves as a valuable opportunity for us to gain hands-on experience in handling data, preparing it for analysis by addressing data cleaning tasks, and systematically building and refining regression models. This practical endeavor enriches our understanding and expertise in the realm of data analysis and modeling.

# TEAM 21 SNAPP

### - Priyanka Lalwani - 202218058
### - Sakshi Parihar - 202218042
### - Anisha Anilkumar - 202218038
### - Prachi Shah - 202218027
### - Nandini Parekh - 202001455

# Project Pipeline
![Final_Chart](LINK)

# Table of Contents

## [ 1. Dataset description ](#1-dataset-description)
## [ 2. Data Preprocessing ](#1-dataset-description)
## [ 3. Data Visualisation - EDA_category.ipynb ](#3-data-visualisation---eda_categoryipynb)
## [ 4. Machine Learning Pipeline ](#5-machine-learning-pipeline)
## [ 5. Conclusion ](#6-conclusion)

## 1. Dataset description

The 'Credit Risk Analysis' dataset, available on Kaggle, encompasses a comprehensive collection of data pertinent to loans, borrowers, and their credit profiles. This dataset is meticulously curated for tasks involving the analysis and prediction of credit risk, with a specific focus on assessing and forecasting the likelihood of loan defaults. It serves as a valuable resource for honing data cleaning and exploratory data analysis (EDA) skills, as well as for constructing classification models aimed at predicting loan defaults based on an array of borrower attributes and loan characteristics. By delving into this dataset, data enthusiasts and machine learning practitioners gain hands-on experience in the realm of credit risk assessment, making it an ideal resource for learning and practical application.

Atrributes :- 

'funded_amnt' : The total amount funded for the loan.

'term' : The term length of the loan (e.g., 36 months, 60 months).

'int_rate' : The interest rate on the loan.

'installment' : The monthly installment payment.

'grade' : A rating assigned to the loan based on creditworthiness.

'sub_grade' : A sub-rating within a grade.

'home_ownership' : The type of home ownership (e.g., RENT, OWN).

'annual_inc' : The annual income of the borrower.

'verification_status': The status of income verification.

'purpose': The purpose of the loan (e.g., credit_card, car, home_improvement).

'dti': Debt-to-Income ratio.

'delinq_2yrs' : The number of 30+ days delinquencies in the borrower's credit file.

'inq_last_6mths': The number of inquiries in the last 6 months.

'open_acc' : The number of open credit lines in the borrower's credit file.

'pub_rec' : The number of derogatory public records.

'revol_bal' : The borrower's revolving balance (credit card balance).

'revol_util' : The percentage of credit used by the borrower.

'total_rec_late_fee' : The total late fees received.

'collections_12_mths_ex_med' : Number of collections in the last 12 months, excluding medical collections.

'application_type' : The type of application (e.g., INDIVIDUAL, JOINT).

'acc_now_delinq' : The number of accounts currently delinquent.

'tot_coll_amt': Total collection amounts ever owed.

'tot_cur_bal' : Total current balance of all accounts.

'default_ind' : The target variable indicating loan default (1 for default, 0 for non-default).
