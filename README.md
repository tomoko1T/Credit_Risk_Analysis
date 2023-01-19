# Credit Risk Analysis

## Overview: 

The purpose of this analysis is to evaluate the performance of machine learning models to predict the credit risk since good loans exceed risky loans, the credit risk encounters unbalanced classification issues.  The credit card credit dataset from LendingClub, a peer-to-peer lending services company was used for this project.  The following six machine learning models were employed to predict the credit risk. 

1. Naive Random Oversampling

2. SMOTE/Synthetic Minority Oversampling Technique 

3. Undersampling

4. Combination (Over and Under) Sampling (SMOTEENN/SMOTE and Edited Nearest Neighbors (ENN)) 

5. Balanced Random Forest Classifier

6. Easy Ensemble Classifier

## Results: 

The results of the balanced accuracy scores and the precision and recall scores of all six machine learning models are as follows.
In each classification report, the class 0 represents the high risk loan status and the class 1 represents the low risk loan status. 

1. Naive Random Oversampling 

- The balanced accuracy scores: 65%

- Precision: 1%

- Recall: 71%

![This is an image](https://github.com/tomoko1T/Credit_Risk_Analysis/blob/main/images/cr_Naive%20Random%20Oversampling.png) 

2. SMOTE Oversampling

- The balanced accuracy scores: 66%

- Precision: 1%

- Recall: 63%

![This is an image](https://github.com/tomoko1T/Credit_Risk_Analysis/blob/main/images/cr_SMOTE.png) 

3. Undersampling

- The balanced accuracy scores: 54% 

- Precision: 1%

- Recall: 69%

![This is an image](https://github.com/tomoko1T/Credit_Risk_Analysis/blob/main/images/cr_undersampling.png) 

4. SMOTEENN 

- The balanced accuracy scores: 67% 

- Precision: 1%

- Recall: 73%

![This is an image](https://github.com/tomoko1T/Credit_Risk_Analysis/blob/main/images/cr_SMOTEENN.png) 

5. Balanced Random Forest Classifier

- The balanced accuracy scores: 87% 

- Precision: 3%

- Recall: 70%

![This is an image](https://github.com/tomoko1T/Credit_Risk_Analysis/blob/main/images/cr_BalancedRandomForestClassifier.png) 

6. Easy Ensemble AdaBoost Classifier

- The balanced accuracy scores: 94% 

- Precision: 9%

- Recall: 92%

![This is an image](https://github.com/tomoko1T/Credit_Risk_Analysis/blob/main/images/cr_EasyEnsembleClassifier.png)


## Summary: 

Based on this analysis, easy ensemble adaboost classifier would be the best model among six machine learning models to predict the risky loan because the model's accuracy score is 94%.  However, precision score is only 9% while recall score is 92% so these scores are not good enough to state that this model is appropriate for predicting the risky loans.  Additionally, F1 score is only 16%.  Since F1 score indicates the preciseness and robustness of the model, the easy ensemble adaboost classifier model should not be used at this point. The recommendation is to narrow down the features to be used in the model based on the feature importance.  With that dataset, the scores could improve and supports to determine the risky loans better.