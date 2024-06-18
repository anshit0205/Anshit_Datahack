I have used catboost technique and tuned some of its hyperparameters to implement the task 
I removed 4 columns named hhs_geo_region, census_msa,employment_occupation,employment_industry as it was very irrelevant and the last 2 mentioned columns had lots of missing values.
I used label encoding to convert the non numeric data to numeric
I had also implemented, other algoirthms for the multi label classififcation tasks such as logistic regression, gradient boosting, lightgbm and xgboost.( got the best roc score of 0.845 on my validation data using it)
I have filled the missing values with its mode
I again apologize for the irregular structure of my jupyter file
