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
   - The Cluster Centroids accuracy score is the lowest so far, with only 54% accuracy.
   - The precision (1%) and recall (69%) scores remains low.

<img src='https://github.com/juliomeza/Credit_Risk_Analysis/blob/main/screenshots/3-UndersamplingClusterCentroids.png'>

4. Combination (Over and Under) Sampling SMOTEENN
   - The SMOTEENN model has a accuracy score of 67%. Still a low number, specially if we combine this number with the precision and recall scores.
   - This model has a low precision (1%) when predicting 'High Risk' credits, and a not too bad recall recall (72%) score. Combining the precision and recall score, this is not a good model neither.

<img src='https://github.com/juliomeza/Credit_Risk_Analysis/blob/main/screenshots/4-SMOTEENN.png'>

5. Balanced Random Forest Classifier
   - The Blalanced Random Forest model has a high accuracy score. 79% of the time predicts correctly.
   - The precision score has increased to 3%. Even though is a low number, it is 3 times better than all previous models so far.
   - The recall score if not too bad. 70% of the time predicts correctly.

<img src='https://github.com/juliomeza/Credit_Risk_Analysis/blob/main/screenshots/5-BalancedRandomForestClassifier.png'>

6. Easy Ensemble AdaBoost Classifier
   - 



balanced accuracy scores
precision
recall

PRECISION: total of 50 people were predicted to have cancer. Of the 50, 30 people actually had cancer. The precision is therefore 30/50, or 0.6.

RECALL(Sensitivity): is a measure of how many people who actually have cancer were correctly diagnosed.


<img src='https://github.com/juliomeza/Credit_Risk_Analysis/blob/main/screenshots/6-EasyEnsembleAdaBoostClassifier.png'>


# Summary
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.


