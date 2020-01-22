# Classification-of-Hurricanes-and-Typhoons-
# Brief Introduction

Objective of this project was to train a multi-class classification model where the target variable classifies hurricanes and typhoons into the correct category utilizing two datasets having respective information.

The project involved training a multi-class classifier model, Hyperparameter tuning.
Decision Trees, Random Forest, Naive Bayes and Support Vector Clustering algorithms were used.

#Details about the project

DESCRIPTION
Dataset: Pacific_train.csv and Pacific_test.csv

Dataset Description:

The NHC publishes the tropical cyclone historical database in a format known as HURDAT, short for HURricane DATabase. These databases (Atlantic HURDAT2 and NE/NC Pacific HURDAT2) contain six-hourly information on the location, maximum winds, central pressure, and (starting in 2004) size of all known tropical cyclones and subtropical cyclones.

Columns:

ID
Name
Date
Time
Event
Status
Latitude
Longitude
Maximum Wind
Minimum Pressure
Low Wind NE
Low Wind SE
Low Wind SW
Low Wind NW
Moderate Wind NE
Moderate Wind SE
Moderate Wind SW
Moderate Wind NW
High Wind NE
High Wind SE
High Wind SW
High Wind NW


Problem Statement 

You are provided with two data sets “Pacific_train.csv” and “Pacific_test.csv” having hurricane and typhoon information.

You are required to make a multi-class classification model where the target variable is “Status” to classify hurricanes and typhoons into the correct category.

Carry out the following tasks and select the appropriate features and make classification models using the following algorithms having a 10-fold cross validation score : 

Decision Trees ( Applying different criterion and choosing the best )
Random Forest
Naive Bayes


Which is the best model? 

NOTE: Let's say Naive Bayes Algorithm is the best algorithm for the above scenario with accuracy 0.7, then print GaussianNB(Name of Naive Bayes function in sklearn) and its respective accuracy score in a CSV file in the row order format.

Output Format:

Perform the above operations and write your output to a file named output.csv

