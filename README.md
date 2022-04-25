# Credit Risk Analysis

# Overview
Predict credit card risk using the credit card credit dataset from LendingClub.

# Results
1. Naive Random Oversampling
   - The classifier is correct only 65% of the time, which is not a good prediction, but is not the bad either.
   - Since we are only focusing in the 'High Risk' predictions, this is not a good model with a precision of 1% and a recall of 72%.

<img src='https://github.com/juliomeza/Credit_Risk_Analysis/blob/main/screenshots/1-NaiveRandomOversampling.png'>

2. Oversampling SMOTE
   - This model has a low accuracy score as well (66%).
   - It also has a low precision and recall scores, 1% and 63% respectively.

<img src='https://github.com/juliomeza/Credit_Risk_Analysis/blob/main/screenshots/2-OversamplingSMOTE.png'>

3. Undersampling Cluster Centroids
   - The Cluster Centroids accuracy score is the lowest so far, with only 54% accuracy.
   - The precision (1%) and recall (69%) scores remain low.

<img src='https://github.com/juliomeza/Credit_Risk_Analysis/blob/main/screenshots/3-UndersamplingClusterCentroids.png'>

4. Combination (Over and Under) Sampling SMOTEENN
   - The SMOTEENN model has a accuracy score of 67%. Still a low number, especially if we combine this number with the precision and recall scores.
   - This model has a low precision (1%) when predicting 'High Risk' credits, and a not too bad recall (72%) score. Combining the precision and recall score, this is not a good model neither.

<img src='https://github.com/juliomeza/Credit_Risk_Analysis/blob/main/screenshots/4-SMOTEENN.png'>

5. Balanced Random Forest Classifier
   - The Balanced Random Forest model has a high accuracy score. 79% of the time predicts correctly.
   - The precision score has increased to 3%. Even though is a low number, it is 3 times better than all previous models so far.
   - The recall score if not too bad. 70% of the time predicts correctly.

<img src='https://github.com/juliomeza/Credit_Risk_Analysis/blob/main/screenshots/5-BalancedRandomForestClassifier.png'>

6. Easy Ensemble AdaBoost Classifier
   - The AdaBoost model has an accuracy score of 93%, which is really good.
   - The precision score has increased to 9%, the best model out of the 6.
   - The recall score if also high, with 92% correct predictions.

<img src='https://github.com/juliomeza/Credit_Risk_Analysis/blob/main/screenshots/6-EasyEnsembleAdaBoostClassifier.png'>

# Summary
- Out of the 6 models, the best model is the 'AddaBoost Classifier', with an accuracy score of 93%, a precision of 9% and a recall of 92%.
- Even though this is the best model out of the six, it fails on predicting 'High Risk' credits, with a precision of only 9%. Since we are focusing on High-Risk credits only, this is not a good model neither. We need to try other different models where the 'High Risk' precision is above 70% at least.