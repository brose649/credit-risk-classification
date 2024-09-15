# credit-risk-classification

## Overview 
This module covered supervised machine learning. The challenge had us create a classification model that focused on predicting and categorizing credit risk in order to identify safe and unsafe borrowers.

## Results
* Accuracy Score: 99% However, this is misleading as there is a significant imbalance of healthy to high-risk loans - only 3% of the training data had high-risk borrowers 
* Precision Score: 94% macro average, 87% for high-risk loans specifically
* Recall Score: 97% macro average, 95% for high-risk loans specifically

## Summary
While the model perfectly predicts healthy loans, it predicts high-risk loans only 91% of the time from the f1-score, when looking at high risk loans specifically. If I were a loan manager at a bank, giving out money that may not be returned around 10% of the time seems like a lot of clean-up in the long term. Solutions to increase the scores, given the data has been properly cleaned, include resampling, trying different algorithms, and adjusting which features have been selected.