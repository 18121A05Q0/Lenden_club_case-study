# Lending club case study
> Analyzing loan data to predict default risk. We'll delve into data cleaning, analysis, and key insights that can help lenders make informed decisions.


## Table of Contents
* Business Understanding
* Importing Libraries
* Data Understanding
    1. Importing Data
    2. Data Info
* Data Preparation
    1. Data Cleaning
    2. Outlier Treatment
    3. Data Imputation
* Data Analysis & visualization

## Business Understanding

You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

 
The data given below contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

 
In this case study, you will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.

## Importing Libraries
import warnings # library to show warning messages
import numpy as np # math library
import pandas as pd # to work with datasets
import matplotlib.pyplot as plt # used for plotting simple 2D graphs
import seaborn as sns # visualization library based on matplotlib
import re # library to work on string manipulation
# pandas configures display options to control how data is presented when displaying DataFrames in a Jupyter notebook or other interactive environments
pd.options.display.float_format = '{:.2f}'.format # Ensures floating-point numbers are displayed with two decimal places instead of the default format
pd.options.display.max_columns = None # Removes any limitation on the number of columns displayed when printing a DataFrame.

# we can ignore warnings that arise because of any incompatabile versions
warnings.filterwarnings('ignore')

## Data Understanding

* Reading the data and analysing the columns of meta data which all present in the csv file

  
## Data Preparation

1. Data Cleaning:Removing irrelevant or incomplete data points to ensure data accuracy and reliability.
2. Outlier Treatment:Identifying and addressing extreme values that could skew analysis results.
3. Data Imputation:Filling in missing values using appropriate methods to maintain data integrity.

## Data Analysis & visualization

To identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA to get more insights with different types of scatter plot,boxplot,histograms and countplot
