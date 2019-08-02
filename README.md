# Sparkify: User churn prediction

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [Folder Structure](#folderStructure)
4. [Feature Engineering](#featureEngineering)
5. [Modelling](#model)
6. [Results](#results)
6. [Licensing, Authors, and Acknowledgements](#licensing)

### Installation <a name="installation"></a>

Apart from Anaconda distribution of Python, this code requires pyspark either in standalone or in clustered environment for execution.

### Project Motivation <a name="motivation"></a>

Predicting churn rates is a challenging and common problem that data scientists and analysts regularly encounter in any customer-facing business. In this notebook, Sparkify mini dataset has been used to perform analysis on the contents of the data and further build a model based on spark ML libraries in order to predict user churn.

### Folder Structure <a name="folderStructure"></a>

- Sparkify.ipynb
	
	- Containts all code for data cleaning, data exploration, modelling and conclusions.


### Feature Engineering <a name="featureEngineering"></a>
Following features were used for the model

* Average Session length
* Number of Platforms used by the user
* Number of artists
* Number of Thumbs Up
* NUmber of Thumbs Down
* Number of Sessions
* Number of days since registration
* Gender
* Platform
* Level of subscription
* Churn (label)
* Downgraded


### Modelling <a name="model"></a>
Following models were tried based on the features that were created from the dataset after cleaning and exploration.

* Logistic Regression
* Gradient Boosting Trees
* Random Forest Classifier

Out of the above models that were tried GBT performs the best, followed by RFC and LR models with 86%, 83% and 79% F1 scores respectively.

### Results <a name="results"></a>

The main findings can be found on the blog post [here](https://medium.com/@pradeep.thalasta/sparkify-user-churn-prediction-c63b7a447d52)


### Licensing, Authors, and Acknowledgements <a name="licensing"></a>

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

* [Udacity](https://www.udacity.com/)
