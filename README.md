# Supervised Machine Learning: Predicting Housing Prices

## 1. Project Objectives & Overview

### 1.1. Business Problem

Working for a consultancy specialising in real estate wiht many clients including developers, agencies, and investors. Pricing is a central aspect to the business. Traditionally, it’s the domain of home appraisers to determine the value of a property, which must be executed in an unbiased way, following an official criteria to ensure that there is no bias towards neither the buyer nor the seller.

When the appraisal price is set, my clients need to decide whether they should buy the property or not. It all boils down to this simple question: is the “true value” of the property above or below the price set by the appraisal? 

The consultancy wants to use data to be able to answer this question reliably and efficiently. It has acquired a dataset containing a historical register of housing prices in Ames, a small city in Iowa —the actual prices at which the properties were sold. For each house, it also contains around 80 different features, such as the area, the state of the property, whether it has a backyard or not, etc.

 My task is to create a model that predicts the price of a house based on its characteristics.

### 1.2. Classification

- Using classification create a model to predict whether a house is expensive or not. 
- Evaluating the model in a classification task, means you can either make a correct prediction or an incorrect one. 

**1.2.1. housing_prices_classification**
- 1_housing_prices: Intuition-Based Model, Decision Tree Model, Pipeline Creation, Grid Search(Best Parameters) and Accuracy Score. 
- 2_housing_prices: One Hot Encoding, Decision Tree Model, Pipeline Creation, Grid Search(Best Parameters) and Accuracy Score.
- 3_housing_prices: Ordinal Encoding, Confusion Matrix, F1 Score and Cohen's Kappa Score. 
- 4_housing_prices_challenge: Decision Tree, K-Nearest Neighbor, Random Forest and Accuracy Score. 

### 1.3. Regression

- Using regression create a model to predict the exact price of a house.
- Evaluating the model in a regression task, means you will most likely never predict the exact number. I will use performance metrics to determin how close I get to it.

**1.3.1. housing_prices_regression**
- 5_housing_prices: Intuition-Based Model, Decision Tree, SGD Regressor, mean_absolute_error, mean_squared_error, mean_absolute_percentage_error, r2_score. 
- 6_housing_prices: Principal Component Analysis.
- housing_prices_kaggle_competition: Decision Tree, K-Best, Random Forest, SGD Regressor.

### 1.4. Technical Skills

- Python: Pandas, Matplotlib, Seaborn 
- Encoding: One Hot Encoding and Ordinal Encoding
- Machine Learning Algorithms: Logistic Regression, K-Nearest Neighbors (KNN), Decision Trees, Random Forest, K-Best, SGD. 


## 2. Project Process

1. Reading Data & Create an Intuition-Based Model: Non-Machine Learning Solution that Operates as a Baseline.
2. Data Pre-processing & Cleaning
3. Splitting Data into Training and Test Data
4. Creating Pipeline
5. Applying Algorithms
6. Reviewing Accuracy Scores
7. Using the Model on the Test Data
8. Revieiwng Final Accuracy Scores. 



