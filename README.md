# Credit Risk Analysis Using Supervised Machine Learning

## Overview

### Purpose
The purpose of this analysis was to evaluate the performance of machine learning models using a credit card dataset to make a recommendation on whether they should be used to predict credit risk.

## Results

### Resampling Models to Predict Credit Risk
I first oversampled the data using naive random oversampling, SMOTE oversampling, and undersampling algorithms to predict credit risk.

#### Naive Random Oversampling Using RandomOversampler

![Naive Random Oversampling](.Resoures/naive_random_oversampling.PNG)

- The balanced accuracy score is 65%.
- The precision score for high_risk is 1% with a sensitivity score of 63%.
- The precision score for low_risk is 100% with a sensitivity score of 67%.
- Overall, the precision score is 99% with a sensitivity score of 67%.

#### SMOTE Oversampling

![SMOTE Oversampling](.Resources/smote_oversampling.PNG)

- The balanced accuracy score is 63%.
- The precision score for high_risk is 1% with a sensitivity score of 62%.
- The precision score for low_risk is 100% with a sensitivity score of 63%.
- Overall, the precision score is 99% with a sensitivity score of 63%.

#### Undersampling Using ClusterCentroids

![Undersampling](.Resources/undersampling.PNG)

- The balance accuracy score is 53%.
- The precision score for high_risk is 1% with a sensitivity score of 61%.
- The precision score for low_risk is 100% with a sensitivity score of 45%.
- Overall, the precision score is 99% with a sensitivity score of 45%.

### SMOTEENN Algorithm to Predict Credit Risk
I then used a combinatorial approach of over and undersampling with the SMOTEENN algorithm to determine if the results were better at predicting credit risk than the earlier resampling models.

#### Combination (Over and Under) Sampling Using SMOTEENN

![Combination Sampling](.Resources/combination_sampling.PNG)

- The balance accuracy score is
- The precision score for high_risk is
- The precision score for low_risk is
- Overall, the precision score is
