# Ensemble-Methods

the code uses different ensembles (baseline, bagging, random forest, ada boost, voting) in sklearn, comparing their accuracies, and contains the foolowing procedures:

read csv file into a dataframe | preprocess data (drop unnecessary rows, handle missing values, normalizing data) | partition the data into test and training data | compute the baseline classification accuracy | build a generic bagging ensemble and print the accuracy | build a random forest model and print the accuracy | calculate and print the top 3 important features | same procedures for ada boost model and voting classifier (incorporating RandomForestClassifier, DecisionTreeClassifier, Support Vector Machine and Logistic Regression)
