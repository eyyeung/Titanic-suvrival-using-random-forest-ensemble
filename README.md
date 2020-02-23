# Titanic- Classification problem of survival using Random Forest Classifer
* Based on Kaggle learning dataset Titanic
* I end up using random forest classifier and finetuning the hyperparamter n_estimators

## My Approach
1. get the files
2. check the relationship between input and output through graphs
3. check missing data and preprocess
4. try out different classifier and hyperparamter tuning using cross validation dataset
5. focus on one model and hyperparamter, predict the test data
6. export output file

## Result
* A classification accuracy of ~75%
* Seems to be overfitting the training data
    * could try logistic regression with regularization - needs to normalize the features
    * could try trimming the trees
    * test out using title as a feature but only as a highly-regarded or not binary feature