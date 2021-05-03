# Daniel Majer Portfolio
A list of my completed projects over the last 2 and a half years. 

# Machine Learning Projects
## [Project 1: Supervised Classification Task](https://danielmajer24.github.io/Wine-Classification/)
### Project Overview:

The purpose of this report was to identify the patterns present in the datset by performing principal component analysis and accurately classify the wine type of the dataset using a number of supervised classification techniques.

Principal Component Analysis was used for exploratory analysis and to reduce the dimensionality of the dataset. 

![](/images/wine_pca_graph.png)

The classification techniques I used included:
- Naive Bayes
- Linear Discriminant Analysis
- Quadratic Discriminant Analysis
- k Nearest Neighbour Cluster

This measured accuracy, error, precision, recall, F1 statistic and AUC to compare the respective models.

![](/images/wine_results_table.png)

This project was done in R and code can be found [here](https://github.com/DanielMajer24/Wine-Classification). 

## [Project 2: Comparing Machine Learning algorithms to a Neural Net](https://danielmajer24.github.io/Comparing-a-VNN-to-SVM/)
### Project Overview:

The purpose of this project was to implement a Vanilla Neural Network (VNN) and compare it to a selected machine learning (ML) algorithm on a supplied time series dataset to predict the Australia’s unemployment rate.

The techniques I used included:
- Random Forest and Support Vector Machine (SVM) ML algorithm
![](/images/rf_and_svm_graph.png)

- VNN with 3 hidden layers and a Relu activation
![](/images/nn_graph.png)

The final ML model in the comparison with the VNN was the SVM algorithm. The metrics used for the comparison include RSME, RSquared and Mean Absolute Error.
![](/images/nn_svm_results_table.png)

This project was done in R and code can be found [here](https://github.com/DanielMajer24/Comparing-a-VNN-to-SVM). 

## [Project 3: Suport Vector Machines and XGBoost Machine Learning Algorithms](https://danielmajer24.github.io/SVM-Analysis/)
### Project Overview: 

This project was broken up into two parts: 

1) manually implment the Support Vector Machine (SVM) algortihm using user-defined functions

2) Compared the performance between SVM and a selected ML algorithm

The techniques I used included:
- successfully applied SVM using user defined functions
![](/images/svm_graph.png)
- implemented SVM and XGBoost algothirms on a supervised classfication task using Credit Default Data
These algorithms were compared using accuracy, error, precision, recall, F1 statistic and AUC.
![](/images/xgboost_vs_svm.png)

This project was done in R code for this project can be found [here](https://github.com/DanielMajer24/SVM-Analysis)


