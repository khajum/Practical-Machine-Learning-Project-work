## Machine Learning Final Project

In this final project of the Machine Learning class, we will use machine leaning to build models with the Weight Lifting Exercise Dataset from Human Activity Recognition website (http://groupware.les.inf.puc-rio.br/har). The dataset will be splitted (60/40) into a training and testing dataset. The goal is to predict the manner in which the subject performed the exercise, which is the “classe” variable in the training set. Three algorithms are picked to fit the models, they are

1. Recursive Partitioning and Regression Trees, ‘rpart’
2. Gradient Boosting Machine, ‘gbm’
3. Random Forest, ‘rf’

The fitted models will be compared by their out of sample errors. The best model then will be used to predict the outcome of a 20 different test cases.

The result rmarkdown html can be found in http://rpubs.com/WPShen53/169520
