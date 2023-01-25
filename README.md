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

The details of the Naive Random Oversampling are as follows:
- Balanced Accuracy Score: 65% (Meaning that this model predicted the credit risk accurately 65% of the time)
- Precision of high risk: 0.01
- Precision of low risk: 1.00 
- Recall Score of high risk: 68%  
- Recall Score of low risk: 62%

***<ins>SMOTE Oversampling</ins>***

![SMOTE Oversampling](https://github.com/Kcav18/Credit_Risk_Analysis/blob/main/Images/Smote_Oversampling.png)

The details of SMOTE Oversampling are as follows:
- Balanced Accuracy Score: 66% (Meaning that this model predicted the credit risk accurately 66% of the time)
- Precision of high risk: 0.01
- Precision of low risk: 1.00 
- Recall Score of high risk: 63%  
- Recall Score of low risk: 68%

***<ins>Undersampling</ins>***

![Undersampling](https://github.com/Kcav18/Credit_Risk_Analysis/blob/main/Images/Undersampling.png)

The details of Undersampling are as follows:
- Balanced Accuracy Score: 54% (Meaning that this model predicted the credit risk accurately 54% of the time)
- Precision of high risk: 0.01
- Precision of low risk: 1.00 
- Recall Score of high risk: 69%  
- Recall Score of low risk: 40%

### Use the SMOTEENN Algorithm to Predict Credit Risk

***<ins>Combination Sampling</ins>***

![Combination Sampling](https://github.com/Kcav18/Credit_Risk_Analysis/blob/main/Images/Combination_Sampling.png)

The details of Combination Sampling are as follows:
- Balanced Accuracy Score: 68% (Meaning that this model predicted the credit risk accurately 68% of the time)
- Precision of high risk: 0.01
- Precision of low risk: 1.00 
- Recall Score of high risk: 76%  
- Recall Score of low risk: 59%


### Use Ensemble Classifiers to Predict Credit Risk**

***<ins>Balanced Random Forest Classifier</ins>***

![Balanced Random Forest Classifier](https://github.com/Kcav18/Credit_Risk_Analysis/blob/main/Images/Balanced_Random_Forest_Classifer.png)

The details of Balanced Random Forest Classifier are as follows:
- Balanced Accuracy Score: 79% (Meaning that this model predicted the credit risk accurately 79% of the time)
- Precision of high risk: 0.03
- Precision of low risk: 1.00 
- Recall Score of high risk: 70%  
- Recall Score of low risk: 87%

***<ins>Easy Ensemble AdaBoost Classifier</ins>***

![Easy Ensemble AdaBoost Classifier](https://github.com/Kcav18/Credit_Risk_Analysis/blob/main/Images/Easy_Ensemble_AdaBoost.png)

The details of Easy Ensemble AdaBoost are as follows:
- Balanced Accuracy Score: 93% (Meaning that this model predicted the credit risk accurately 93% of the time)
- Precision of high risk: 0.09
- Precision of low risk: 1.00 
- Recall Score of high risk: 92%  
- Recall Score of low risk: 94%

## Summary

The Easy Ensemble AdaBoost Classifier is the best model out of those used for predicting credit risk. The Balanced Random Forest Classifier comes in second place! These models had the highest balanced accuracy scores, meaning they performed better than the other methods to correctly classify high and low risk loans. The Easy Ensemble AdaBoose Classifier had a balanced accuracy score of 93%. There does however appear to be issues with the precision scores with all models- including the Easy Ensemble AdaBoose Classifier. I think the Easy Ensemble AdaBoost is the best option with the models we used but it wouldnt be a bad idea to investigate other options that might balance the accuracy, precision, and recall scores better. I also think that regardless of the model that is chosen, quality checks from human specialists would be a great idea!




