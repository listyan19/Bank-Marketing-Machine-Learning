# Purwadhika-Final-Project-DS-Bank-Marketing

This repository stored my notebooks for my data science & machine learning final project in Purwadhika Start-Up and Coding School (JCDS 07 - Jakarta). The format of the final project consisted of 5 days project preparation followed by a presentation with 3 assessors.

A little bit about this project, I was inspired to take this dataset -- Portuguese Bank Marketing from UCI Machine Learning Repository (https://archive.ics.uci.edu/ml/datasets/Bank+Marketing), maybe quite personal. Sometimes during my lecture at PWDK, I would get a call from a commercial bank, trying to attract me to buy/subscribe to their products. Unfortunately I am in a Target No and wondering what kind of people are more likely to be attracted to this kind of marketing -- via calling, thus becoming the Target Yes. That's when I found this dataset -- and the rest is history...

Just kidding.. I would say this project taught me a lot about data science. Although my project is of course far from perfect (This is my very first time conducting this kind of project), but this project helped me to learn more about data processing, data exploration, and machine learning -- and also getting a lot of insight about economy, banking and business problem. I am also grateful for a lot of valuable feedback during my final presentation. It was a great discussion and an eye opening in a data field. Thank you and cheers to the assessors!

A little bit about the case here: <br>
The data was collected from a direct marketing campaign conducted by Portuguese banking institution to offer term deposits. The data collection was made by phone calls to potential customer from May 2008 to November 2010.<br><br>
My objectives in this case are:
1. Gain insight of bank customers<br>
2. Using machine learning to possibly help identifying positive customers

Unfortunately a lot of people are like me (being in Target No) -- so we have a class imbalance. In this binary classification case, only around 11% of the total customers actually belong to Target Yes.<br>
Therefore the evaluation metrics I chose for this case is not accuracy, but f1 score (balance between precision and recall). However, from the beginning I want to have a model which can help predicting more True Positive customers, so not only f1 score, I also see the recall and TP numbers in the confusion matrix. (I am focusing the aggresive bank strategy here -- acquiring more customers).

I have a lot of files in the machine learning section, but it is actually caused by my laptop -- if the size of the notebook is too big, my laptop is not really happy. Thus I need to separate them. To summarize:<br>
<b>Part 1.</b> Data preparation for ML modelling -- and testing 3 models (logistic regression, XGB, RFC) in 4 datasets (original, resampled under, resampled over, and SMOTE oversampling)<br>
<b>Part 2.</b> Hyperparameter tuning for logistic regression and XGB<br>
<b>Part 3.</b> Attempts to improve logistic regression (features, outliers, threshold and class weight)<br>
<b>Part 4.</b> Training models for model deployment -- and running AUTOML<br>
<b>Deployment.</b> Preparation to deploy the model in the dashboard<br>

In the dashboard sections, unfortunately there are model files that can not be uploaded (the sizes are too big) -- sorry about that.

I would like to extend my gratitude to my lecturer, Cornellius Yudha and my classmates who helped and supported me during this project. Thank you!
