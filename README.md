# Credit Risk Analysis

## Overview of Credit Analysis
...............................

### PURPOSE
Looking at a dataset of imbalanced values on loan originations, the purpose of this analysis was to test the effectiveness of our machine learning techniques. We then used resampled data to see how effective this alternative approach would be in predicting creditworthiness.

* In this analysis, we were provided data on various loans with values for loan size, interest rate, borrower income, dabt-to-income, number of accounts, derogatory marks and total debt. This with information, we were asked to predict the likelihood of the loan being paid given the information provided.


* In this analysis, we used variables to help us make predictions. The first dataset used a value count of 75036 for "0" (healthy loans) and 2500 for "1" (high risk loans). We were able to get an accuracy score of 0.952 with this set. We then used a resampled set of data with a value count of 56271 for both "0" and "1". The resampled dataset proved a remarkable accuracy score of 0.9936.

* In this analysis we retreived the data, seperated it into labels and features, trained and tested the data, evaluated the models performance and then reviewed the prediticions. We compared the performance of both datasets and compared the two in order to see which set allowed for the best results.

* In this analysis, we split the data into training and testing, using "train_test_split", we then fit a Logistic Regression Model with our data. We calculated accuracies scores for both datasets as well as confusion matrix for both. We then predictied classification reports for each.

...............................

### RESULTS
The results for the data are shown below:

* Machine Learning Model 1:
    * Model 1 was pretty good to begin with, having an accuracy score of 0.952, a preciiosn score of 0.85 for predicting high-risk scores, and a recall of 0.91.

* Machine Learing Model 2:
    * Model 2 imporved on the first ones predictive modeling but having an accuracy score of 0.993, a precion score of 0.84 for high-risk loans and recall of 0.99. Only the precion score for the first model was better then the second.



...............................

### SUMMARY
It seems the second model was able to produce better predictive modeling results with a higher accuracy rating and overall higher classification report. Therefore it seems the resampled data size was able to help with predicting high-risk loans.

* Precision Score: Original data set produced a score of 85% and the resampled data produced 84%. This is a slight difference, so not much occured in this field.

* Recall: The recall score saw an imporved score of 99% for the resampled data. The original data porduced a score of 91%. This helps with the models ablility to predict actual fraudulent transactions.  

* F1 Score: The F1 scored improved from 88% from the original data to 91% with the resampled data. This is impressive and shows the Harmonic Mean value has  increased making the model more efficient and accurate.