In this repository I will keep all the ensemble models 
 - Voting Ensemble
 - Bagging - Random Forest
 - Boosting - AdaBoost, Gradient Boost, XGBoost
 - Stacking

 Random Forest - 
 Random - Type of Bagging - Bootstrapped Aggregation
Forest - Group of Decision Trees
Bootstrapping - Bootstrapping in the context of machine learning refers to the technique of resampling the dataset with replacement to create multiple subsets, known as bootstrap samples. Each bootstrap sample is of the same size as the original dataset, and because it's created with replacement, some data points from the original dataset may appear multiple times in a single bootstrap sample, while others may not appear at all.
For Bootstraping we can use - Row sampling, column sampling or combined sampling
OUtput from each decision tree - If its classification then we take the mode of most frequent out from each tree. If its regression then we take the mean of all trees
