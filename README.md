# Credit Risk Analysis

## Overview of the analysis: 

The purpose of this analysis is to evaluate the performance of machine learning models to predict the credit risk since good loans exceed risky loans, the credit risk encounters unbalanced classification issues.  The credit card credit dataset from LendingClub, a peer-to-peer lending services company was used for this project.  The following six machine learning models were employed to predict the credit risk. 

1. Naive Random Oversampling

2. SMOTE/synthetic minority oversampling technique 

3. Undersampling

4. Combination (Over and Under) Sampling (SMOTEENN/SMOTE and Edited Nearest Neighbors (ENN)) 

5. Balanced Random Forest Classifier

6. Easy Ensemble Classifier

## Results: 

The results of the balanced accuracy scores and the precision and recall scores of all six machine learning models are as follows.
In the classification report, the class 0 represents the high risk loan status and the class 1 represents the low risk loan status. 

1. Naive Random Oversampling 

- The balanced accuracy scores: 65%

- Precision: 1%

- Recall: 71%

![This is an image]() 

2. SMOTE Oversampling

- The balanced accuracy scores: 66%

- Precision: 1%

- Recall: 63%

![This is an image]() 

3. Undersampling

- The balanced accuracy scores: 54% 

- Precision: 1%

- Recall: 69%

![This is an image]() 

4. SMOTEENN 

- The balanced accuracy scores: 67% 

- Precision: 1%

- Recall: 73%

![This is an image]() 

5. Balanced Random Forest Classifier

- The balanced accuracy scores: 87% 

- Precision: 3%

- Recall: 70%

![This is an image]() 

6. Easy Ensemble AdaBoost Classifier

- The balanced accuracy scores: 94% 

- Precision: 9%

- Recall: 92%

![This is an image]()
 
## Summary: 
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)

the balanced accuracy scores and the precision and recall scores
- Accuracy measures how often the model is correct.

Precision is a measure of how reliable a positive classification is.
Of the positives predicted, what percentage is truly positive?

Sensitivity is good at understanding how well the model predicts something is positive.