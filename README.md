# "Credit_Risk_analysis" Week 16 Challenge
## Overview
This project used scikit-learn and imbalanced-learn to train and evaluate models to determine credit card risk using a credit card dataset. Six different techniques were used to train and evaluate models with unbalanced classes to determine credit risk. Various libraries and algorithms were used to build and evaluate models using resampling including: 
1. imbalanced-learn 
2. scikit-learn
3. RandomOverSampler
4. SMOTE algorithms
5. ClusterCentroids algorithm
6. SMOTEENN algorithm
7. BalancedRandomForestClassifier (bias reduction model)
8. EasyEnsembleClassifier (bias reduction model)

## Results:
The results for the six machine learning models including their respective balanced accuracy, precision, and recall scores are as follows:      

### Naive Random Oversampling
![Naive Random Oversampling](https://github.com/rudiferr/Credit_Risk_Analysis/blob/main/Images/NROS.png)     
1. Balanced Accuracy: 0.6533977140416822
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = .67/.91

### SMOTE Oversampling
![SMOTE Oversampling](https://github.com/rudiferr/Credit_Risk_Analysis/blob/main/Images/SSO.png)     
1. Balanced Accuracy: 0.6512291961274883
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = .64/.66

### Undersampling
![Undersampling](https://github.com/rudiferr/Credit_Risk_Analysis/blob/main/Images/US.png)     
1. Balanced Accuracy: 0.6512291961274883
2. Precision:  The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = .61/.45

### Combination Under-Over Sampling
![Combination Under-Over Sampling](https://github.com/rudiferr/Credit_Risk_Analysis/blob/main/Images/CUOS.png)     
1. Balanced Accuracy: 0.5293026900499977
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = .70/.57

### Balanced Random Forest Classifier
![Balanced Random Forest Classifier](https://github.com/rudiferr/Credit_Risk_Analysis/blob/main/Images/BRFC.png)     
1. Balanced Accuracy: 0.7877672625306695
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = .67/.91

### Easy Ensemble AdaBoost Classifier
![Easy Ensemble AdaBoost Classifier](https://github.com/rudiferr/Credit_Risk_Analysis/blob/main/Images/EEAC.png)     
1. Balanced Accuracy: 0.925427358175101
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = .91/.94

## Summary:
When working with balanced accuracy, the highest compared accuracy between 0 and 1 and is closest to 1 is the best machine learning model.  For the credit card data set, the Easy Ensemble AdaBoost Classifier is the best model to choose with its .93 balanced accuracy.  The other models were below .80 balanced accuracy.  The precision for all models were similar and within an appropriate range.  The recall score also needs to fall within 0 and 1, with numbers closer to 1 being the better model.  The Easy Ensemble AdaBoost Classifier had the highest recall score, making it the final best machine learning model to choose for further credit card analysis.