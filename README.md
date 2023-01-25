# Credit Risk Analysis

## Overview

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, I used several different techniques to train and evaluate models with unbalanced classes. Jill asked me to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using a credit card credit dataset from LendingClub, a peer-to-peer lending services company, I oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm. Then, I used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, I compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Lastly, I will evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

This project consists of three technical analysis deliverables and a written report:

- Deliverable 1: Use Resampling Models to Predict Credit Risk.
- Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk.
- Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk.
- Deliverable 4: A Written Report on the Credit Risk Analysis 

## Results

### Use Resampling Models to Predict Credit Risk

***<ins>Naive Random Oversampling</ins>***

![Naive Random Oversampling](https://github.com/Kcav18/Credit_Risk_Analysis/blob/main/Images/Naive%20_Random%20_Oversampling.png)

***<ins>SMOTE Oversampling</ins>***

![SMOTE Oversampling](https://github.com/Kcav18/Credit_Risk_Analysis/blob/main/Images/Smote_Oversampling.png)

***<ins>Undersampling</ins>***

![Undersampling](https://github.com/Kcav18/Credit_Risk_Analysis/blob/main/Images/Undersampling.png)

### Use the SMOTEENN Algorithm to Predict Credit Risk

***<ins>Combination Sampling</ins>***

![Combination Sampling](https://github.com/Kcav18/Credit_Risk_Analysis/blob/main/Images/Combination_Sampling.png)

### Use Ensemble Classifiers to Predict Credit Risk**

***<ins>Balanced Random Forest Classifier</ins>***

![Balanced Random Forest Classifier](https://github.com/Kcav18/Credit_Risk_Analysis/blob/main/Images/Balanced_Random_Forest_Classifer.png)

***<ins>Easy Ensemble AdaBoost Classifier</ins>***

![Easy Ensemble AdaBoose Classifier](https://github.com/Kcav18/Credit_Risk_Analysis/blob/main/Images/Easy_Ensemble_AdaBoost.png)

## Summary
