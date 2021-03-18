# Credit Risk Analysis 

## Project Overview 

The purpose of this project is to employ difference techniques to train and evaluate models with unbalanced classes. This project will use a credit card dataset from LendingClub, a peer-to-peer lending services company. As credit risk is an inherently unbalanced classification problem due to good loans outnumbering risky loans, this analysis will oversample data using RandomOverSampler and SMOTE algorithms, and undersample data using ClusterCentroids algorithm. A combinatorial approach of over- and undersampling is utilized with the SMOTEENN algorithm. Machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, are compared in thier ability to predict credit risk. The results will be evaluated

## Results 

**Random Oversampling** 

![image1](/images/1oversampling.png)

**SMOTE Oversampling**

![image2](/images/2SMOTEoversampling.png)

**ClusterCentroids Undersampling**

![image3](/images/3undersampling.png)

**SMOTEENN Combination (Over and Under) Sampling**

![image4](/images/4SMOTEENN.png)

**Balanced Random Forest Classifier**

![image5](/images/5balancedrandomforest.png)

**AdaBoost Classifier**

![image6](/images/6adaboost.png)

## Summary

|  | Balanced Accuracy Score | Precision | Recall |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  |  | High Risk | Low Risk | Avg | High Risk | Low Risk | Avg |
| ROS | 0.66 | 0.01 | 1.00 | 0.99 | 0.74 | 0.58 | 0.74 |
| SMOTE | 0.65 | 0.01 | 1.00 | 0.99 | 0.62 | 0.68 | 0.68 |
| Under Sampling | 0.65 | 0.01 | 1.00 | 0.99 | 0.69 | 0.40 | 0.40 |
| SMOTEEN | 0.54 | 0.01 | 1.00 | 0.99 | 0.72 | 0.57 | 0.57 |
| Balanced Random Forest | 0.78 | 0.04 | 1.00 | 0.99 | 0.67 | 0.91 | 0.91 |
| AdaBoost | 0.69 | 0.85 | 1.00 | 1.00 | 0.38 | 1.00 | 1.00 |



