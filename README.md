# Thermal Comfort prediction ML App
# Data set
ASHRAE Global Thermal Comfort Database II given by https://datadryad.org/stash/dataset/doi:10.6078/D1F671
# Task
Thermal comfort is calculated conventionally with the Fanger's mathematical model given by Povl Ole Fanger himself. The task of this project is to predict Thermal Comfort with machine Learning for this following steps are taken
# Steps
1. Analysis of data which has observations from all around the world
2. Out of 70 features influencing thermal comfort given in data set, only those six standard features are selected which are used to calculate Fanger's Model
3. Hyperparameter tuning is done with RandomizedSearch Cross Validation among SVM, random forest, and logistic Regression with different arguments of each algorithm respectively out of which SVM with arguments (kernel='linear',C=10) gave accuracy of 93% 
4. Built a front end User Interface with the help of StreamLit Framework by converting the python file into pickle document

![Screenshot](https://user-images.githubusercontent.com/44450467/101834151-419ecc00-3b3a-11eb-95f6-63f464db7c69.PNG)
