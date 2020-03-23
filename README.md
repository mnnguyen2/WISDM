# Predicting Activities using Sensor Data

## Introduction
Using sensor data collected from smartphones and smart watches, I'm creating models that could predict a person's activity. I collected this dataset from the UCI Machine Learning Repository.

## About the dataset
Human activity recognition, or HAR for short, is a broad field of study concerned with identifying the specific movement or action of a person based on sensor data. Being able to sense/ recognize human activity can be a huge asset to many fields including but not limited to healthcare, construction, etc...

Members of the WISDM (Wireless Sensor Data Mining) Lab in the Department of Computer and Information Science of Fordham Unversity collected data from the accelerometer and gyroscope sensors of a smartphone and smartwatch as 51 subjects performed 18 diverse activities of daily living. Each activity was performed for 3 minutes, so that each subject contributed 54 minutes of data. These activities include:

Non-hand-oriented activities: {walking, jogging, stairs, standing, kicking}
Hand-oriented activities (General): {dribbling, playing catch, typing, writing, clapping, brushing teeth, folding clothes}
Hand-oriented activities (eating): {eating pasta, eating soup, eating sandwich, eating chips, drinking}

## About this repository:
In this repository, you should find the following files:
1. arff_python folder. This folder contains the dataset that I used. I rearranged the files so that I could pull from the folder seemlessly from Python. Data source: https://archive.ics.uci.edu/ml/datasets/
2. Python notebook. This notebook contains the models that I built, tuned, and evaluated to predict the 18 activities. 
3. Project Summary Presentation (PDF). This file should give you a good overview of the project and a summary for the model performances. 

## Table of Contents
1  Introduction
1.1  About the dataset
2  Pre-processing
2.1  Getting the data
2.2  Cleaning data
2.3  DataFrames for Analysis
3  Exploratory Data Analysis
3.1  Handling Outliers
3.2  Inspiration questions:
3.3  Categories imbalance
3.4  Feature Selection
3.5  Correlation Matrix
3.6  Dimensionality Reduction
3.7  Evaluation metrics
4  Building models - Phase I
4.0.1  Train-Test Split
4.1  KNN 1 - Baseline
4.2  GBM 1
4.3  GBM - Tuning n_estimators and Learning rate
4.4  GBM - Tuning max_depth
4.5  GBM 1 - Tuned
4.6  Phase I Evaluation
5  Building models - Phase II
5.1  KNN 2
5.2  Tuning KNN
5.3  GBM 2
5.4  Trying out SVC 2
5.5  RFC 2
5.6  RFC 2 - Grid search
5.7  RFC - Base vs. Tuned
5.8  Phase II Evaluation
6  Building models - Phase III
6.1  SVC 3 - OVR
6.2  What if our PCA has more features?
6.3  KNN 3 (pca = 30)
6.4  RFC 3
6.5  GBM 3
6.6  Phase III Evaluation
7  Re-defining the problem prompt - Phase IV
7.1  Re-shape and re-define the question.
7.2  KNN 4
7.3  RFC 4
8  Last round of models - Phase V
8.1  PCA 5
8.2  KNN 5
8.3  RFC 5
8.4  SVC 5
8.5  SVC 5 - Tuning
8.6  Phase V - Final Evaluation
9  Summary
9.1  Conclusion
9.2  The Chosen One
9.3  A plot of all model evaluation metrics
