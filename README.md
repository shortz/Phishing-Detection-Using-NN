# Phishing-Detection-Using-NN

### Abstract

Different machine learning algorithms had been used to solve different text classification problems over the years. This project aims to explore the text classification area by detecting phishing websites using their URLs. In this project I will build a robust phishing detection mechanism using machine learning tools and techniques and will compare the different algorithm and their success rates in detecting phishing websites

### Data sources

Several sources could be use:

1. A source with 10,000 websites with 49 'raw' features (5k phishing and 5k normal) : https://data.mendeley.com/datasets/h3cgnj8hft/1/
1. A source with classefied/normilized features (all values are booleans): https://archive.ics.uci.edu/ml/datasets/phishing+websites
1. A phishing DB (only URLs, no features): https://www.phishtank.com/index.php

I used the source with the raw features.

### Models

The purpose of this project is to compare several known classification algorithms. I will compare the following algorithms:

- Logistic Regression
- Decision Tree
- KNN
- SVM (linear and rbf kernel)
- Naive Bayes
- Convolutional Neural Networks

### Methods

Inorder to evaluate the algorithms performance, I will use two methods: simple accuracy and ROC curve.

Several of the features seems to have no real effect on the results, so I will first run the algorithms on the raw data, and then I will try to adujst the features list in order to improve the algorithms run time and accuracy.

### Works to view

- A very good guide for URL phishing detection - https://medium.com/intel-software-innovators/detecting-phishing-websites-using-machine-learning-de723bf2f946
- A paper on how to optimize the neural network - https://dl-acm-org.ezprimo1.idc.ac.il/doi/pdf/10.1145/3227609.3227655
