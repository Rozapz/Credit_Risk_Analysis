# Credit_Risk_Analysis
Credit Risk Analysis using machin learning

## Overview:

Overview of the loan prediction risk analysis: Explain the purpose of this analysis.
The purpose of this analysis is well defined (4 pt)

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

As it can be seen, the classifyer method are berforming better than linear regression methods in this study. We can recommend using Easy Ensemble classifyer method as it has a very good f1 and accuracy score.





