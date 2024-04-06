﻿# House-Price-Prediction
# 1. Introduction
The ever-changing real estate market necessitates the development of reliable methods for predicting house prices. This report details the exploration of linear regression, random forest regression and random forest regression after finding best estimators techniques for housing price prediction. We aim to establish a model that can analyze various factors influencing house prices and generate accurate estimates. This will empower potential buyers, sellers, and investors with valuable insights for informed decision-making within the housing market.
Furthermore, the insights gleaned from this project can extend beyond individual applications. By identifying the key features that drive house prices, we can gain a deeper understanding of the housing market as a whole. This knowledge can be utilized by policymakers and urban planners to develop strategies that promote housing affordability and market stability.
Our initial approach will involve linear regression, a widely used technique that establishes a linear relationship between the target variable (house price) and several explanatory features (e.g., square footage, number of bedrooms). This method offers a clear and interpretable model, allowing us to understand how each feature directly impacts the predicted price.
However, real-world housing prices often exhibit complex relationships with influencing factors. To address this, we will also explore Random Forest Regression, a powerful ensemble learning technique. Random Forest builds multiple decision trees, each making predictions based on a random subset of features. The final prediction is an average of the individual tree outputs, leading to a more robust model capable of capturing non-linear relationships.
Finally, we will delve into hyperparameter tuning for Random Forest Regression. Hyperparameters control the learning process of the model. By employing techniques like Grid Search or Random Search, we can explore various hyperparameter combinations and identify the configuration that optimizes the model's performance on unseen data. This process helps mitigate overfitting and ensures the model generalizes well to new housing data.

# 2.	Dataset description
This is the dataset used in the second chapter of Aurélien Géron's recent book 'Hands-On Machine learning with Scikit-Learn and TensorFlow'. It serves as an excellent introduction to implementing machine learning algorithms because it requires rudimentary data cleaning, has an easily understandable list of variables and sits at an optimal size between being to toyish and too cumbersome.
The data contains information from the 1990 California census. So although it may not help you with predicting current housing prices like the Zillow Zestimate dataset, it does provide an accessible introductory dataset for teaching people about the basics of machine learning.
The data pertains to the houses found in a given California district and some summary stats about them based on the 1990 census data. The columns are as follows, their names are pretty self explanitory:
Inline-style: 
![Data Information](./Utils/house_price.ipynb%20–%20house_price.ipynb%2007-04-2024%2000_43_03.png)
[Dataset Histograph](./Utils/Dataset%20Histograph.png)
**Figure 1**: Dataset Histograph
[Dataset Heat Map](./Utils/Dataset%20Heat%20Map.png)
**Figure 2**: Dataset Heat Map
