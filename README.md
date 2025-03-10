# Module 12 Report Template

## Overview of the Analysis
With these machine learning models, we aim to a create a model that can correclty predict which borrowers would be considered high-risk and could therefore be more likely to default on a loan. This information could be highly valuable for a variety of users but especially lenders working to underwrite potential borrowers.

* The model was trained on a variety of data that consisted of: 
	* loan size
	* interest rate
	* borrower's income
	* debt to income ratio
	* number of credit accounts
	* derogitory marks
	* total debt 
	
The main focus of this analysis was on the Loan Status which was entered as either a 0 or a 1. In this case, 0 represented a healthy loan and 1 represents a high-risk loan.
  
* The analysis covers several stages of the machine-learning process. First, the data was gathered into a data frame so it could easily be seperated in X and Y variables. The data was then split into a training and testing data set with counts calculated for both. 
* The machine-learning model was based on a logistical regression which is focused on the probablity of a 0 or 1 for a loan status. 

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1 (Loan Status = 0, Healthy Loan) 
    * Precision: 1.00, model never mis-classified any high-risk loans as healthy
	* Recall: 0.99, model correctly classified 99% healthy loans
* Machine Learning Model 2 (Loan Status = 1, High-risk loan)
	* Precision: 0.84, model mis-classified healthy loans only 16% of the time
	* Recall: 0.94, model correctly classified loans as high-risk

Overall, the model had an accuracy score of 99%. 

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

Both models performed well - model 1 was incredibly percise and had a nearly perfect recall. Model 2 had more issues with precision but still had a F1-score of nearly 90%. Depending on potentioal model users' risk appetities, they might need to stick to Model 1 or use Model 1 and 2 in conjunction to get a better picture of a borrower as Model 2 shows that it is less precise and has a worse recall than model 1. 
