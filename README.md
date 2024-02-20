# ML_Projects
Melbourne Housing Price Prediction Project - 
This project explores a comprehensive approach to predicting Melbourne house prices using Linear Regression and Lasso Regularization. It encompasses data exploration with various visualizations to understand feature distributions, preprocessing steps to prepare the dataset for modeling, and the development of predictive models.

Dataset - 
The Melbourne Housing dataset (Melbourne_housing.csv) contains information about various properties in Melbourne, including features like location, number of rooms, land size, 		building area, and price.

Data Exploration and Visualization - 
In this project, I explore the Melbourne Housing dataset to understand various features and their impact on house prices. I utilize visualizations such as histograms, scatter plots, and box plots to gain insights into the distribution of different features.

Linear Regression Model Development - 
I develop a Linear Regression model to predict house prices in Melbourne. The dataset is preprocessed to handle missing values, encode categorical variables, and remove unnecessary columns. I explain the steps taken in preparing the data and developing the model. 

Model Evaluation - 
The linear regression model is evaluated using appropriate metrics after splitting the dataset into training and testing sets. I interpret these metrics to assess the model's performance and discuss whether it is deemed good based on the evaluation results.

Regularization - 
I investigate the need for Lasso regularization and compare the results of training and testing sets. A Lasso regression model with specified parameters is set up and fitted to the training data. I perform Lasso regression on both training and test data and analyze how the results differ from the linear regression model.

Out-of-sample Performance - 
For this section, I split the data into a new training and test set with an 80-20 split. I train both the linear regression and Lasso regression models on the training data. Then, I estimate Akaike Information Criterion (AIC), Corrected Akaike Information Criterion (AICc), Bayesian Information Criterion (BIC), as well as 5-fold Cross Validation (CV) for both models using only the training data. The true out-of-sample performance of the models is estimated by computing their deviance on the test data. I compare all deviance values and determine which Information Criterion is most similar to the models' true out-of-sample performance. Additionally, I discuss how 5-fold CV compares in estimating the model's performance.

