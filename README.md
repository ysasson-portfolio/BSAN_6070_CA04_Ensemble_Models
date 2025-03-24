# BSAN_6070_CA04_Ensemble_Models

## Description

### This code is utilizing census data in order to determine the amount of income that the person will make. Based on certain categorical variables within the census data, this code will be using decision trees in order to find the best performing model that will make an accurate decision. The data will start grouped and we start to split the data into a training group and a test group based on the flag variable. We will then use this data to test the performance of several ensemble models by only adjusting the number of estimators value for each model. These models include the Random Forest, ADABoosting, Gradient Boosting, and XGBoosting. The performance measures that we are using this time to evaluate the models are the Accuracy Score and the Area Under the Curve Score (AUC). Plotting the performance allows us to visualize this and analyze the optimal number of estimators for the performance. 

## Necessary Libraries and Versions

* Numpy (Version 1.18.0)
* Pandas (Version 2.2.3)
* Scikit Learn (Version 1.6.1)
* Matplot_lib (Version 3.10.0)
* Scikit Learn (DecisionTreeClassifier function from sklearn.tree) (Version 1.6.1)
* Scikit Learn (Metrics section with accuracy_score, precision_score, recall_score, f1_score, roc_auc_score, and confusion_matrix function) (Version 1.6.1)
* Scikit Learn (export_graphviz function from sklearn.tree) (Version 1.6.1)
* Scikit Learn (RandomForestClassifier, AdaBoostClassifier, GradientBoostingClassifier from sklearn.ensemble) (Version 1.6.1)
* XGBoost (XGBClassifier) (Version 3.0.0)
* Scikit Learn (LabelEncoder function from sklearn.preprocessing) (Version 1.6.1)


## Data Set and the Source

### The data set is an excel sheet with census data that is all compiled in one place. The data is already binned (or grouped together) based on certain continuous thresholds or categorical groupings. This data set was provided by Professor Arin Brahma. You can find the dataset either on this GitHub repository with census_data.csv or you can link it online at (https://github.com/ArinB/MSBA-CA-03-Decision-Trees/blob/master/census_data.csv?raw=true). 

## Source Code Acknowledgement

### There was no source code that was being utilized for this project. There were some pieces of the code that were given to us in the instruction pages provided by Professor Arin Brahma. Some of the DQA code that was utilized in this code was drawn from a previous assignment (the link is https://github.com/ysasson-portfolio/BSAN_6070_CA_03_Decision_Tree_Algorithm). Although we could not run the AutoViz code on this python file (because the AutoViz library messes with the matplotlib display functions), the code still applies since it is the same data set from the previous assignment.

## Software Being Used

### Google CoLab


## Installation

### In order to run this code you need to make sure the following:
* You have internet connection if you plan on getting the data from the direct link to Professor Brahma's GitHub
* If you are planning on doing it on Jupyter Notebook or Google Colab through a direct file, download the census_data.csv file and access it by using the right directory when using the read_csv function.
* Make sure that all necessary packages and libraries are installed. (There is one that is most likely not install. I left the install code for it at the very beginning of the code file)
