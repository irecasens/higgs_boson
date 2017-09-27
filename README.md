# higgs_boson

This report demonstrates the development of a supervised classification model to predict a binary variable (described only as ‘class’) using 31 contextless features (‘f1’, ‘f2’, …, ‘f31’).
The development was approached in four parts, often overlapping. First, learners were compared using ‘area under the ROC curve’ (AUC) on a test partition of the data. Second, features (as-given, transformed, and engineered) were selected using forward/backward stepwise search and Top-N. Third, learner parameters were tuned using grid search. Fourth, logistic regression was used as a meta-algorithm to stack and blend models.
Our top model uses XGBoost and achieved an AUC of 0.80939 on the Kaggle public leaderboard.

View the report here.

View the code here. 

View the original challenge here. 