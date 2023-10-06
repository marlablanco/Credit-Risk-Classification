# Credit-Risk-Classification

# Overview
A dataset of historical lending activity from a peer-to-peer lending service company was ued to build a machine-learning model that evaluates loan risk. This information is used to determine if a borrower's creditworthiness. In order to analyze the dataset, it was split into training and testing sets. The training set was used to build the first Logistic Regression Model that would then be applied to the testing data. This evaluated balanced accuracy, precision and recall score, resulting in a determined high or low-risk assessment. The original training data was resampled with the RandomOverSampler to get rid of imbalances and to build the second Logistic Regression Model.  

# Results
**Logistic Regression Model 1:**

-Balanced Accuracy: 94% 

-Precision: avg of 93% (high-risk=87%, low-risk=100%) of predicted positives were correct

-Recall scores: avg of 95% (high-risk=89%, low-risk=100%) in measuring true positive values out of all positive predictions made


**Logistic Regression Model 2:**

-Balanced Accuracy: 100% 

-Precision: avg of 93% (high-risk=87%, low-risk=100%) of predicted positives were correct

-Recall scores: 100% in measuring true positive values out of all positive predictions made

# Result Summary

Based on the results of two Logistic Regression Models, I would reccomend Model 2 because it had fewer false predictions of the testing data along with 100% accuracy and recall, making it the better of the two. Although both models only had 87% precision in predicting high-risk loans (with 100% precision with low-risk), Model 1's recall and accuracy percentages were  lower making it less reliable. 
