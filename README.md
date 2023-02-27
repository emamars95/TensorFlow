# Tutorial Machine Learning #

This tutorial is designed for beginner and intermediate users that gain experience with the commonly used tools for data analysis and molecular dynamics simulation using Machine Learning (ML) and Neural Networks (NN). The folder contains 6 tutorials that span several topics from Computer vision using TensorFlow to running atomistic molecular dynamics using a Deep Learning Neural Network.

## Data Analysis with KKR ## 

In this tutorial, we introduce Kernel ridge regression (KKR) and apply it to an energy profile computed with Full CI. We define the KKR formula inside the class KKR and apply it to a sample dataset. This tutorial is implemented using Google Colab, a free cloud-based service for running Jupyter Notebooks with GPU support.

## Data Analysis with Unsupervised Learning ## 

We give two examples of unsupervised ML methods applied to molecular dynamics and nonadiabatic molecular dynamics. 

### Tutorial 1 ### 

In this tutorial devised with Jupyter notebook, we explore data analysis using pandas and scikit-learn. We perform Principal Component Analysis (PCA) and Kernel PCA to investigate the most important modes featuring the molecular dynamics of ethylene. 

### Tutorial 2 ###

In this tutorial devised with Jupyter notebook, we investigate the recently released ulamdyn package: a general open-source software for unsupervised ML which finds application in nonadiabatic molecular dynamics. We use both PCA and nonlinear reduction methods (isomap) to rationalize the photochemistry of fulvene. 

## Computer Vision ## 

In this tutorial, we take our first steps with TensorFlow and build a simple, single-layer neural network to recognize different objects from a set of images extracted from the MNIST library. While the focus is not on the detailed algorithms behind neural network optimization, the tutorial provides a first introduction to neural network concepts.

## Train a Neural Network ## 

In this tutorial devised with Jupyter notebook, we use PyTorc to train a simple Neural Network and explore the different parameters that may influence its performance. We are going to investigate the activation functions, training sets, and optimization procedures. 

## Molecular Dynamics with Deep Learning ## 

In this tutorial devised with Jupyter notebook, we introduce Schnetpack: open-source software to run molecular dynamics and nonadiabatic molecular dynamics. Schnetpack is a  neural network able to predict the energy and forces of a molecule given a particular geometry which allows to speed up considerably the underlined atomistic molecular dynamics simulation. 
