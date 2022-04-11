# Artificial Neural Network And Deep Learning Projects

This repository contains the code for the two homework projects of the course Artificial Neural Networks And Deep Learning held at Politecnico Di Milano.

# About the First Homework

## Specifications 

The problem is a multiclass classification problem. 

In this homework we were required to classify images of leafs, which are divided into categories according to the species of the plant to which they belong. Being a classification problem, given an image, the goal is to predict the correct class label.

The metric used to evaluate models was the Mean Accuracy. The score is computed as
MeanAccuracy = Σ 1≤i≤N(prediction == target) / N , where N is the total number of images in the test set.

# About the Second Homework

## Specifications

The competition consists of a multivariate time series forecasting problem. Thus, we must provide a prediction for each time step in the test prediction window. 
The metric used to evaluate models is the Root Mean Squared Error (RMSE). 

Being multivariate forecasting, the total RMSE is computed considering all the samples in the test window from all the features in the multivariate problem.

The goal is to design and implement forecasting models to learn how to exploit past observations in the input sequence to correctly predict the future. 


# Built With

Both projects were developed using Jupiter Notebook and Tensorflow library.

For both project you can find code, a report with all explainations and datasets in the respective folders. For running the first homework you have to use the riordina_directory.py script to prepare the dataset to be correctly loaded.

# Authors 

* [Matteo Braceschi](https://github.com/matteobraceschi)
* [Alice Cariboni](https://github.com/A1iceCariboni)
* Claudio Corradini
