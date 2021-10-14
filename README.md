# Featurization-Model-Selection-Tuning

-> Project Description 

Featurization: It’s often said that “data is the fuel of machine learning.” This isn’t quite true: data is like the crude oil of machine learning which means it has to be refined into features — predictor variables — to be useful for training a model. Without relevant features, you can’t train an accurate model, no matter how complex the machine learning algorithm.
Model Selection & Tuning:  Model selection in Machine learning can be considered for both algorithm selection & defining the hyperparameters that work as an input for the model. A key challenge in the system is to select an appropriate model/ hyperparameters especially when no prior information is available. It is also important that the model being deployed yields the optimal results without out overfitting or underfitting. This can be only achieved by modifying the necessary hyperparameters. This process of amending the hyperparameters is model tuning.
This project will focus on the need and various steps for data preprocessing. We address various ways of improving model performance while dealing with the issues with model complexity. We shall also address the problems with having imbalanced classes in classification problems and ways to deal with them. 

-> Project Objectives
1. Select Appropriate features of the input data
2. Understand the role of Hyperparameters in Model performance
3. Understand the complexity of algorithm vs Error
4. Apply upsampling and down-sampling
 

-> Project Prerequisites
1. Should be thorough with supervised & unsupervised Learning algorithms
2. Knowledge of Python is very crucial

-> Project Content
-> Feature Engineering and Cross-Validation 
1. Need for data preprocessing
2. Various tools and ways through which we obtain and transform data
3. Analytical base table
4. Exploring data through a pair plot
5. The issue with multiple Gaussians
6. Dealing with outliers
7. K fold cross-validation
8. Bootstrap Sampling
9. Leave One Out Cross-validation

-> Model Performance Measures & Hyperparameter tuning
1. Model complexity vs error
2. Need for multiple iterations of performance measurement and model tuning
3. Need for a validation set
4. Need for up-sampling and down-sampling
4. Concept of Hyperparameters
5. Grid Search
6. Randomized search


-> DATA DESCRIPTION:

sensor-data.csv : (1567, 592)
The data consists of 1567 examples each with 591 features.
The dataset presented in this case represents a selection of such features where each example represents a single production entity with
associated measured features and the labels represent a simple pass/fail yield for in house line testing. Target column “ –1” corresponds to
a pass and “1” corresponds to a fail and the data time stamp is for that specific test point.

-> PROJECT OBJECTIVE:

To build a classifier to predict the Pass/Fail yield of a particular process entity and analyse whether all the
features are required to build the model or not.
