# Default-Loan-Prediction-

A machine learning model to find out the unreliable borrowers in advance by analysing their financial background and other factors by  exploring publicly available data from [LendingClub.com](http://localhost:8888/notebooks/Data%20Science%20AI/Py-DS-ML-Bootcamp-master/Refactored_Py_DS_ML_Bootcamp-master/15-Decision-Trees-and-Random-Forests/www.lendingclub.com). Lending Club connects people who need money (borrowers) with people who have money (investors). Hopefully, as an investor you would want to invest in people who showed a profile of having a high probability of paying you back. We will try to create a model that will help predict this.

We will use lending data from 2007-2010 and be trying to classify and predict whether or not the borrower paid back their loan in full. You can download the data from [here](https://www.lendingclub.com/info/download-data.action).

## Dataset 

![data_head](https://github.com/gaurav19940/Default-Loan-Prediction-/assets/70307677/952eaabb-4945-4d06-a61e-4e7dea66246d)

#### Here are what the columns represent:

credit.policy: 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.  
purpose: The purpose of the loan (takes values "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business", and "all_other").  
int.rate: The interest rate of the loan, as a proportion (a rate of 11% would be stored as 0.11). Borrowers judged by LendingClub.com to be more risky are assigned higher interest rates.    
installment: The monthly installments owed by the borrower if the loan is funded.    
log.annual.inc: The natural log of the self-reported annual income of the borrower.    
dti: The debt-to-income ratio of the borrower (amount of debt divided by annual income).    
fico: The FICO credit score of the borrower.      
days.with.cr.line: The number of days the borrower has had a credit line.    
revol.bal: The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).    
revol.util: The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available).    
inq.last.6mths: The borrower's number of inquiries by creditors in the last 6 months.    
delinq.2yrs: The number of times the borrower had been 30+ days past due on a payment in the past 2 years.    
pub.rec: The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments).    

## Training
For the better understanding of data, various feature correlation and visualization is performed, available in notebook.  
Then data is modelled over 3 Machine Learning Algorithms - Logistic Regression, Decision Trees and Random Forest.  

## Output
The Logistic Regression Performed best followed by Decision Trees and Random Forest.


