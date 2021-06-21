# Credit Risk Analysis Using Supervised Machine Learning

## Overview

### Purpose
The purpose of this analysis was to evaluate the performance of machine learning models using a credit card dataset to make a recommendation on whether they should be used to predict credit risk.

## Results

### Resampling Models to Predict Credit Risk
I first oversampled the data using naive random oversampling, SMOTE oversampling, and undersampling algorithms to predict credit risk.

#### Naive Random Oversampling using RandomOversampler

![Naive Random Oversampling](.Resoures/naive_random_oversampling.PNG)

- The balanced accuracy score is 65%.
- The precision score for high_risk is 1% with a sensitivity score of 63%.
- The precision score for low_risk is 100% with a sensitivity score of 67%. The high precision score can be attributed to the high low_risk population.


