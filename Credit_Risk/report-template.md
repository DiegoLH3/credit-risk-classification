# Module 12 Report Template

## Overview of the Analysis

* Purpose:
    * The purpose of this analysis is to allow us to determine if someone is credit worthy enough to give a loan.
* Explain what financial information the data was on, and what you needed to predict:
    * Some factors that were brought into play in order to predict if the customer was worthy were: on the loan size, interest rate, income, debt to income, number of accounts, derogatory marks and total debt.
    * What we were looking to predict using these factors were if they were a health risk borrower.
* Provide basic information about the variables you were trying to predict:
    * As mentioned before the variables that we were taking into account was their loan worthiness based on the factors listed above.
* Describe the stages of the machine learning process you went through as part of this analysis:
    * First we divided up the labels(loan_status) and features(every factor other than loan_status).
    * Then split the data into training and testing (train_test_split).
    * Classified the logistic regression and fit it to our X and y train.
    * Made predictions using our clssifier but did it with the X_test. While showing both "Predicitons" and "Actual" with our actual being used from the y_test.
    * Finally, we evaluated the model's performance by generating a confusion matrix and printing the classification report.

## Results

* Machine Learning Model 1:
    * Our loan healthiness was nearly perfect from looking into the classification report the precision was 84%. As for the recalls were also high at 94%. For the accuracy shows that it was 99% accurate.

## Summary

* I believe that the model used worked as intended because it managed to show if a borrower was a high-risk or not, gave the averages and even the accuracy. I would say that it is more important to predict the '1s'. 
If you do not recommend any of the models, please justify your reasoning.
