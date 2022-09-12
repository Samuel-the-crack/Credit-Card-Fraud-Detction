# Credit-Card-Fraud-Detction
Making a fraud detection model for credit card using neural network 

<p align = 'center'>
<img src = 'https://github.com/Samuel-the-crack/Credit-Card-Fraud-Detction/blob/main/Picture/1200x680px-getid-26.png' width = '500'> 

## A. Background 
Credit Card Fraud has been a serious crime scene for the last few years, therefore I'm curious for making a Credit Card Fraud detection model for preventive step. This model is a basic model and can be developed in the upcoming years. My Credit card fraud detection model using a [PCA-ed data](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) to protect customers personal informations. The machine learning algrithm that used here is Neural Network. 

***Requirements : Pandas, Numpy, Seaborn, Matplotlib, Imblearn, Sklearn***

## B. Overview
  As I have mentioned before that in this model I'm using [Neural network](https://scikit-learn.org/stable/modules/neural_networks_supervised.html) algorithm. In this data there are four main columns: Time, V1-V28, Ammount, and Class. Because Neural network is a supervised machine learning so I have to define the target and feature (class, V1-V28). 
  
 <p align = 'center'>
 <img src = "https://github.com/Samuel-the-crack/Credit-Card-Fraud-Detction/blob/main/Picture/Countplot%20unbalanced.JPG" width = 300>
 
 Because the data is to unbalanced, I decided to balanced it with oversampling method. The data's countplot after balancing turns out to be like the picture below. 
 
 <p align = 'center'>
 <img src = "https://github.com/Samuel-the-crack/Credit-Card-Fraud-Detction/blob/main/Picture/Countplot%20balanced.JPG" width = 300>
 
 The output of this model is a line plot of neural network with four different numbers of hidden layers. After normalize the data and splitting it I made a machine learning model to predict the output and it turns out to be like the picture below.

<p align = 'center'>
<img src = "https://github.com/Samuel-the-crack/Credit-Card-Fraud-Detction/blob/main/Picture/Output.JPG" width = 300> 

From the graph above we can conclude that the best accuracy of this model was the one with 50 hidden layers with 97.7% of accuracy. 

**For the complete code you can see it [here](https://github.com/Samuel-the-crack/Credit-Card-Fraud-Detction/blob/main/credit%20fraud%20detection.ipynb)**
