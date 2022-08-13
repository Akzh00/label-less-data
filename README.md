# label-less-data
About: Showcasing general ways used to clean and predict using label less data

Files:
- README.md: read me file
- data.csv: csv file containing original data
- predict.csv: csv file containing predicted values
- run.ipynb: jupyter notebook containing all the codes used
- test_data.arff: arff file containing test data
- test_data.csv: csv file containing test data
- train_after_split.arff: arff file containing training data after balancing
- train_after_split.csv: csv file containing training data after balancing
- train_data.arff: arff file containing training data
- train_data.csv: csv file containing training data
- val_data.arff: arff file containing validation data
- val_data.csv: csv file containing validation data

Summary of process showcased:
- Removing duplicate columns and rows
- Visualizing numerical and categorical variables
- Fill missing values
- Change datatype
- Standardize numerical data and encode categorical data
- Save and load arff files
- Balance data with SMOTE to avoid overfitting
- Search best parameters with gridsearch
- Train and compare accuracy of multiple models (KNN, Decision Tree, Gaussian Naive Bayes, SVM)
