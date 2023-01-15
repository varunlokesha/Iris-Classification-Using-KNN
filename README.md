# Iris Classification Using KNN

The purpose of the exercise is to effectively code and interpret the nearest neighbour algorithm that classifies Iris flowers.
I will be performing the following tasks

•	Performing cleaning operations to prepare data for modelling

•	Use the K Nearest Neighbour algorithm to build a classification model that uses the features within the dataset to classify them according to species. 

•	Interpret the results and comment on the accuracy of the model and discuss whether the model is good or not.




## Technologies

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)  ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) 



## Intro

The Iris dataset is a multi-variate dataset that contains information collected about the different species of Iris flowers classified based on their different species. 

The dataset contains data for the species - Iris Setosa, Iris Versicolour, and Iris Virginica and information on their petal width and length with sepal width and length.

## Data Cleaning & EDA

Null Value Check, Outlier Check, Checking the categorical feature balance/distribution were some of the data cleaning tasks.

For Exploratory Data Analysis, The features were closely studies and various scatterplots were used to understand how the features were correlated.

## KNN Model

The model was developed by setting up a train and test data with 70-30% split. Then the optimum number of neighbours was determined and the model was trained and tested to produce 97% accuracy.

## Conclusion

It can be seen that the main features for building a model to predict the data the main features are petal and sepal width and length. Using the features, after performing data cleaning, the best nearest neighbour value is estimated using the accuracy metric. Then the model is built using the best value of K and the model produced an accuracy of 97%.
1.	The overall Accuracy of the model is calculated to be 97%.
2. The accuracy of prediciton for the specific species were 100, 92, 100% respectively.
3.	Generally, a model with 65-75% accuracy is considered good. Given that the data was fully cleaned and limited to 150 rows, 97% accuracy even though seems too high is good.



