# Kaggle-Titanic

The Titanic challenge on Kaggle is a competition in which the task is to predict the survival or the death of a given passenger based on a set of variables:

* Survived: Outcome of survival (0 = No; 1 = Yes)
* Pclass: Socio-economic class (1 = Upper class; 2 = Middle class; 3 = Lower class)
* Name: Name of passenger
* Sex: Sex of the passenger
* Age: Age of the passenger (Some entries contain NaN)
* SibSp: Number of siblings and spouses of the passenger aboard
* Parch: Number of parents and children of the passenger aboard
* Ticket: Ticket number of the passenger
* Fare: Fare paid by the passenger
* Cabin Cabin number of the passenger (Some entries contain NaN)
* Embarked: Port of embarkation of the passenger (C = Cherbourg; Q = Queenstown; S = Southampton)

Since we're interested in the outcome of survival for each passenger or crew member, we can remove the Survived feature from this dataset and store it as its own separate variable outcomes. We will use these outcomes as our prediction targets.


Goal:
* It is your job to predict if a passenger survived the sinking of the Titanic or not. For each PassengerId in the test set, you must predict a 0 or 1 value for the Survived variable.


Metric
* Your score is the percentage of passengers you correctly predict. This is known simply as "accuracy”.


The submission file should have exactly 2 columns:

PassengerId (sorted in any order)
Survived (contains your binary predictions: 1 for survived, 0 for deceased)


I have Predicted the survival of the Titanic passengers using Random Forest and Logistics Regression algorithm with the help of following techniques:

1. Assess Data Quality & Missing Values
2. Exploratory Data Analysis
3. Feature selection & Recursive feature elimination
4. Feature ranking with recursive feature elimination and cross-validation
5. Model evaluation metrics
6. Model evaluation based on simple train/test split using train_test_split()
7. Model evaluation based on K-fold cross-validation using cross_val_score() and cross_validate()
8. GridSearchCV evaluating using multiple scorers


***** I have uploaded the train and test dataset along with my final prediction on test set from both the algorithms
