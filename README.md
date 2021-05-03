# Daniel Majer Portfolio
Below is a sample of my completed projects over the last 2 and a half years. 

# Machine Learning Projects
## [Project 1: Supervised Classification Task](https://danielmajer24.github.io/Wine-Classification/)
### Project Overview:

The purpose of this report was to identify the patterns present in the dataset by performing principal component analysis and accurately classify the wine type of the dataset using a number of supervised classification techniques.

Principal Component Analysis was used for exploratory analysis and to reduce the dimensionality of the dataset. 

![](/images/wine_pca_graph.png)

The classification techniques I used included:
- Naive Bayes Analysis
- Linear Discriminant Analysis
- Quadratic Discriminant Analysis
- k Nearest Neighbour Cluster

This measured accuracy, error, precision, recall, F1 statistic and AUC to compare the respective models.

![](/images/wine_results_table.png)

This project was completed in R and can be found [here](https://github.com/DanielMajer24/Wine-Classification). 

## [Project 2: Comparing Machine Learning algorithms to a Neural Net in a Regression Task](https://danielmajer24.github.io/Comparing-a-VNN-to-SVM/)
### Project Overview:

The purpose of this project was to implement a Vanilla Neural Network (VNN) and compare it to the performance of a selected machine learning (ML) algorithm. The dataset that was supplied was a time series dataset which contained the Australia’s unemployment rate and other supplementary features.

The techniques I used included:
- Random Forest and Support Vector Machine (SVM) ML algorithm
![](/images/rf_and_svm_graph.png)

- VNN with 3 hidden layers and a Relu activation
![](/images/nn_graph.png)

The final ML model in the comparison with the VNN was the SVM algorithm. The metrics used for the comparison include RSME, RSquared and Mean Absolute Error.
![](/images/nn_svm_results_table.png)

This project was completed in R and can be found [here](https://github.com/DanielMajer24/Comparing-a-VNN-to-SVM). 

## [Project 3: Suport Vector Machines and XGBoost Machine Learning Algorithms](https://danielmajer24.github.io/SVM-Analysis/)
### Project Overview: 

This project was broken up into two parts: 

1) manually implement Support Vector Machine (SVM) algorthim using user-defined functions

2) Compared the performance between SVM and a selected ML algorithm

The techniques I used included:
- successfully applied SVM using user defined functions to plot the optimal separating hyperplane in the supplied dataset
![](/images/svm_graph.png)
- implemented SVM and XGBoost algorithms on a supervised classfication task using Credit Default Data
These algorithms were compared using accuracy, error, precision, recall, F1 statistic and AUC.
![](/images/xgboost_vs_svm.png)

This project was completed in R and can be found [here](https://github.com/DanielMajer24/SVM-Analysis)

## [Project 4: Using Natural Language Processing to Create a University Textbook Recommender System](https://github.com/DanielMajer24/University-Recommender-System)
### Project Overview

The purpose of this project was to gain experience with NLP content-based and dynamic recommender systems in Python. This python notebook contains two working recommender systems, a Static and Dynamic recommender, which recommend the user relevant books from the key words entered into the console.

The techniques I used in the recommender system included:
- Enriching the data using GoogleBooks and NLA Trove APIs
- Developed text ontology by added a field of education to all texts
- used ngram_range(2,3) to extract all bi and tri-grams to reduce dimensionality
- Implemented a KNN clustering and cosine similarity matrix


# Data Visualisation
## [Project 5: Visualisating the NGRT Reading Results of Tully State High School](https://danielmajer24.github.io/NGRT_4_Years/)
### Project Overview:

The purpose of this project was to inspect the results of the New Group Reading Test of year 7 students over the past 4 years at Tully SHS. Specifically this report assessed various demographic aspects such as gender and indigenous status. However, this report primarily focussed on any patterns or at risk groups observed in the primary schools that students had arrived from over the past 4 years. 

The techniques I used in this report:
- Enriched the NGRT data by merging demographic data on student's identification numbers
- Displayed a number of clear graphics to identify the at risks subsects over the last 4 years and the reading age distribution for each group. 

Due to child protection and privacy laws the data for this project could not be shared. 

