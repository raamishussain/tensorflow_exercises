# Tensorflow Projects

This repository contains various projects which I have worked on using machine learning algorithms
implemented via Tensorflow.

All implementations use Tensorflow 2.5. Note that the code shown here will not be compatible with
Tensorflow 1.x due to substantial changes in the structure of Tensorflow between version 1 and 2.

A summary of the projects in this repository is shown below.

# Titanic Survivors

This folder contains a solution to the famous Titanic dataset from kaggle.com. The notebook 
in the folder uses logistic regression to predict survivors of the Titanic based on
features such as Sex of the passenger, the class they were in, their age, etc. More 
information on the dataset itself can be found here: https://www.kaggle.com/c/titanic/data

# Classification

This folder contains a notebook called `mnist_fashon.ipynb` which implements a DNN to classify
images of different articles of clothing from the MNIST Fashion dataset. The dataset can be
accessed diectly from Tensorflow: `tf.keras.datasets.fashion_mnist`.

# Regression

This folder contains two examples of projects solved via DNN regression.

The first project is in the `fuel_efficiency.ipynb` notebook. This project predicts fuel
efficiency of a vehicle based on various properties of the vehicle. The notebook contains
an example of a linear regressor as well as a DNN regressor and compares both models.

The second project is in the `housing_regression.ipynb` notebook. This project attempts
to predict the median house value in different housing blocks in California based on 
census data from 1990. This notebook also uses a DNN regressor as the model.


