# Hindi Letter Recognition using Logistic Regression and PCA

This is a machine learning project that uses logistic regression and PCA to classify images of Hindi characters into different classes. 

## Overview

The objective of this project is to build a machine learning model that can recognize different Hindi characters. The dataset used in this project consists of 9 different classes of Hindi characters. The classes are:

* cha
* ka
* ma
* na
* pa
* pha
* ra
* ta
* thaa
* wa

The dataset is in the form of images, and each image represents a character from one of the above classes. 

## Requirements

* Python 3
* Numpy
* Pandas
* Matplotlib
* Plotly
* scikit-learn
* OpenCV

## How to run the code

1. Create or DOwnload the dataset from the relevent data source site, in my case i created my own set for 9 caracters with 9 directories and extracted them inn the code. 

2. Open the Jupyter notebook and run the code. The code will load the dataset, preprocess it, perform PCA on the data, train a logistic regression model, and test its accuracy. 

## Results

The logistic regression model achieved an accuracy of over 90% on the test data. This shows that the model is able to recognize different Hindi characters with a high degree of accuracy. 

The results are also visualized using different graphs generated using the `plotly` library.
