# Credit-Risk Classification Analysis

This is about evaluating and training a model based on loan risk. With a dataset of previous lending activity from a peer-to-peer lending service company that can be used to identitfy the credit worthiness of a borrower. Lenders allow users to borrow money with the expectation of the user to return the amount borrowed in the first place.



## Overview of the Analysis


* As stated this analysis trains a model that determines the credit worthiness of buyer.
* The historical data used to train the model and ultimately evaluate the model contains over 70000 peer-to-peer entries.
* The values within this model that we are attempting to predict is the y value which is in this case the "loan_status". We want to determine if the loan is deemed "healthy" or "high risk". The other values used within this analysis are interest rates, borrower income, debt_to_income ratio, number of accounts and derogatory marks. 
* The first key step was to split the data into training and testing dataset, from then we assign the variables. Then we used the split data from the original dataset to create a logitic regression model. 
* "Train_test_split" was used to divide the original data into training and testing variables. The training data was then fitted into the model using "logisticregression". Finally to evaluate the model's performance a confusion matrix was performed and a classification report was printed. 

## Results



* Machine Learning Model 1:
  * This model utilises the original data provided within a csv file. 0 is indicated for healthy loan and 1 is for "high risk". The precision of 1.00 (aka 100%) for the healthy loan indicates a great degree of accuracy but this is lower for high risk loans with a score of 0.86 (86%) precision. 
  * Recall values still favour healthy loans with a value of 0.99 which is still very accurate. The recall accuracy for high risk is slightly better than the high risk precision with a value of 0.91.  
  * The macro average evaluates to 92% for overall precision and 95% for recall 





## Summary

Through this it deems to be more accurate to monitor the `0`'s within this analysis as there is more false negatives when solely accounting only the `1`'s. Since only 1 model was used and evaluated, no comment can be made on the preferential use of a model, however there may be more viable models instead of solely applying the linear regression to the original data.

No comment can also be made on whether or not to recommend this model for use by a company solely on the basis that one model was evaluated. Multiple models needs to be tested before recommendation can be made.


