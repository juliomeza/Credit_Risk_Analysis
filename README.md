# Credit Risk Analysis

# Overview
Predict credic card risk using the credit card credit dataset from LendingClub.

# Results

1. Naive Random Oversampling
   - The classifier is correct only 65% of the time, which is not a good prediction, but is not the worst neither.
   - Since we are only focusing in the 'High Risk' predictions, this is not a good model with a precision of 1% and a recall of 72%.

<img src='https://github.com/juliomeza/Credit_Risk_Analysis/blob/main/screenshots/1-NaiveRandomOversampling.png'>

2. Oversampling SMOTE
   - This model has a low accuracy score as well (66%)
   - It also has a low precision and recall scores (1% and 63%)

<img src='https://github.com/juliomeza/Credit_Risk_Analysis/blob/main/screenshots/2-OversamplingSMOTE.png'>

3. Undersampling Cluster Centroids


balanced accuracy scores
precision
recall

PRECISION: total of 50 people were predicted to have cancer. Of the 50, 30 people actually had cancer. The precision is therefore 30/50, or 0.6.

RECALL(Sensitivity): is a measure of how many people who actually have cancer were correctly diagnosed.


<img src='https://github.com/juliomeza/Credit_Risk_Analysis/blob/main/screenshots/3-UndersamplingClusterCentroids.png'>

- Combination (Over and Under) Sampling SMOTEENN
<img src='https://github.com/juliomeza/Credit_Risk_Analysis/blob/main/screenshots/4-SMOTEENN.png'>

- Balanced Random Forest Classifier
<img src='https://github.com/juliomeza/Credit_Risk_Analysis/blob/main/screenshots/5-BalancedRandomForestClassifier.png'>

- Easy Ensemble AdaBoost Classifier
<img src='https://github.com/juliomeza/Credit_Risk_Analysis/blob/main/screenshots/6-EasyEnsembleAdaBoostClassifier.png'>


# Summary
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.


