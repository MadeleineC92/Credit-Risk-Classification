# Credit-Risk-Classification
Module 20


# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
The purpose of this analysis was to evaluate a model based on a datset historical leanding activity from peer-to-peer lending services comput to identify the creditworthiness of borrowers. 

* Explain what financial information the data was on, and what you needed to predict.
                    loan_size	
                    interest_rate	
                    borrower_income	
                    debt_to_income	
                    num_of_accounts	
                    derogatory_marks	
                    total_debt	
                    loan_status

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
we were using the Loan Status as a variable to predict which was better a healthy loan or an unhealthy loan. 


* Describe the stages of the machine learning process you went through as part of this analysis.

firstly i read the CSV file and put it into a datarame so it was easier to read, secondly i separated the data into lables and features so i can pull the loan status column out to work wit. i then spilt the data into training and testing using the train test spilt method.
We then Scored the modle using the LogisitcRegression Modle and saved the feature data predictions. I then evaluated the models performance using the Confusion Matrix metho, i was then able to print this and it showed the classification report for a health loan and a unhealthy loan. 

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithm).
i used the LogisticRegression meathod as well as the Confusion Matrix mmethod. 

## Results

* Machine Learning Model 1:

Precision: 99% (an average--in predicting low-risk loans, the model was 100% precise, though the model was only 87% precise in predicting high-risk loans)
Accuracy: 94%
Recall: 99% (an average--the model had 100% recall in predicting low-risk loans, but 89% recall in predicting high-risk loans)

## Summary

Summarise the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
It would be more benfical to predict "1" ( Unhealthy loans) as this would show the higher risk of defulting than the healthy loans. 
However the data we anilziy shows  18759 heahtly loans and 625 unhealthy loans so the prediction is using more heathly loads which is creating a high precision. 
If the data had more unhealthy loads it would be more accurate. 


