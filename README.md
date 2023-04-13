# Credit_Risk_Analysis
Credit Risk Analysis using machin learning

## Overview:

In this study we are aiming to analyze the  Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, we will need to employ different techniques to train and evaluate models with unbalanced classes. Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm. Then, we used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, we compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. lastly we evaluated the performance of these models to predict credit risk.

## Results:

There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models (15 pt)
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

## Summary:

The Summary of the accuracy of different machine learning algorithems for predicting high risk loans are shown in the following tabel.

| Column 1 | RandomOverSampler | SMOTE | ClusterCentroids | SMOTEENN | BalancedRandomForest | EasyEnsemble |
|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|
|   accuracy_score  |    0.62     |    0.62     |    0.50     |    0.64     |    0.79     |    0.93     |
|   f1  |    0.02     |    0.02     |    0.01     |    0.02     |    0.06     |    0.16     |
|   precision  |    0.01    |    0.01     |    0.01     |    0.01     |    0.03     |    0.09     |

As it can be seen, the classifyer method are berforming better than linear regression methods in this study. But still when we look at the hig risk prediction we can see that the models are not performing very well. These model can not predecict the high risk cases very well and they will have false postive cases for high risk cases in these models. 





