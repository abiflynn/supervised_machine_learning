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

### 1.3. Regression

- Using regression create a model to predict the exact price of a house.
- Evaluating the model in a regression task, means you will most likely never predict the exact number. I will use performance metrics to determin how close I get to it.

### 1.4. Technical Skills

- Python
- Pandas
- Scikit-learn
- KMeans
- Matplotlib
- Seaborn 
- Machine Learning Classification
- Machine Learning Regression

## 2. Project Process

### 2.1. Explore & Clean the Data
In Machine Learning there is a common phrase: garbage in, garbage out. Modelling means finding patterns in the training data, which means the model is only going to be as good as the data you have. Exploring the data involves discovering features that do not make sense, or that will not be available the moment you need to use the model for new predictions, detecting inconsistencies and, in general, determining if the data can be trusted —we’ve also referred to this process as data quality. Cleaning refers to the process of transforming the data so that it is digestible by your tools (e.g. dealing with data types).

### 2.2. Data Pre-Processing
Some Machine Learning models are going to perform much better if you feed them the data in a particular shape. Replacing missing values with an appropriate imputation strategy, scaling the data, selecting/excluding or engineering features… All those transformations are often much more “manual” than what the term “Artificial Intelligence” would suggest —and they usually have a much bigger impact in the performance of the model compared with the next step.

### 2.3. Modelling
Training a model means finding its parameters. Here’s where “the magic happens”, and at the same time it is the most automatable part of the whole process. Sit back, relax, and let the computer do the heavy lifting: training a model can take from some milliseconds to several days, depending on the data size, the complexity of the model and the hardware doing the computation. Comparing different models with each other (“model selection”) can also be automated to some degree.

### 2.4. Error Analysis
Machine Learning predictions are never 100% accurate —if they are, you might want to double check whether you made a mistake somewhere. “All models are wrong, but some are useful“. This is the stage where you find out “how much wrong” is your model. For example: if you were classifying images of tumours between benign or malignant, you want to see how many of your errors are false positives (you predicted malignant, it was really benign) or false negatives (you predicted benign, it was malignant), because those errors have very different implications. This stage is crucial for determining the extent to which you can use the model in practice.

### 2.5. Implement your Solution
Each ML task might have a different implementation, but they usually fall into two main categories: reporting and deployment. Writing a report is typically the outcome of a “one-shot” analysis, where Machine Learning has been used to gain knowledge about a topic (e.g. studying which features that are the most important for determining the price of a house). Deployment, on the other hand, means making the model available for “live” predictions. This might mean to create an API that can take requests (input data) and provides responses (predictions). Most of the time, software engineers will take care of model deployment, but Data Scientists might be involved in the monitoring of the results.

As you can imagine, all these phases are not a simple, single linear process. Following an agile approach to Machine Learning, you want to quickly create and implement a simple solution (a Minimum Viable Product, or MVP), because in doing so you will uncover problems or questions you could not have anticipated. Once the whole process is done in a simple way, you can focus on perfecting it in further iterations. This would be a more realistic Machine Learning workflow:


## 3.  

