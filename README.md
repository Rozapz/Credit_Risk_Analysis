# Credit_Risk_Analysis
Credit Risk Analysis using machine learning

## Overview:

In this study, we are aiming to analyze Credit risk as an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, we will need to employ different techniques to train and evaluate models with unbalanced classes. Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we oversampled the data using the RandomOverSampler and SMOTE algorithms and undersampled the data using the ClusterCentroids algorithm. Then, we used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, we compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. lastly, we evaluated the performance of these models to predict credit risk.

## Results:

### Over Sampling

- Random Over Sampler
![RandomOverSampler](Images/random.PNG)

- SMOTE
![SMOTE](Images/SMOTE.PNG)

### Under Sampling

- Cluster Centroids
![ClusterCentroids](Images/ClusterCentroids.PNG)

### Under and Over Sampling

- SMOTEEN
![SMOTEEN](Images/SMOTEEN.PNG)

### Classifiers method

- Balanced Random Forest Classifier
![BalancedRandomForestClassifier](Images/BRF.PNG)

- Easy Ensemble Classifier
![EasyEnsembleClassifier](Images/EEC.PNG)


## Summary:

The Summary of the accuracy of different machine learning algorithms for predicting high-risk loans is shown in the following table.

| Column 1 | RandomOverSampler | SMOTE | ClusterCentroids | SMOTEENN | BalancedRandomForest | EasyEnsemble |
|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|
|   accuracy_score  |    0.62     |    0.62     |    0.50     |    0.64     |    0.79     |    0.93     |
|   f1  |    0.02     |    0.02     |    0.01     |    0.02     |    0.06     |    0.16     |
|   precision  |    0.01    |    0.01     |    0.01     |    0.01     |    0.03     |    0.09     |

The classifier method is performing better than the linear regression methods in this study. But still when we look at the high-risk prediction, we can see that the models are not performing very well. These models can not predict the high-risk cases very well and they will have false positive cases for high-risk cases in these models. 





