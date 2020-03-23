# Predicting Activities using Sensor Data 

## Introduction
Using sensor data collected from smartphones and smart watches, I'm creating models that could predict a person's activity. I collected this dataset from the UCI Machine Learning Repository.
![WISDM Activities](https://github.com/mnnguyen2/WISDM/blob/master/WISDM%20Activities.png)

## About the dataset

Overall, the dataset includes **approx. 75k observations, spanning across 93 variables.**  

Human activity recognition, or HAR for short, is a broad field of study concerned with identifying the specific movement or action of a person based on sensor data. Being able to sense/ recognize human activity can be a huge asset to many fields including but not limited to healthcare, construction, etc...

Members of the WISDM (Wireless Sensor Data Mining) Lab in the Department of Computer and Information Science of Fordham Unversity collected data from the accelerometer and gyroscope sensors of a smartphone and smartwatch as 51 subjects performed 18 diverse activities of daily living. Each activity was performed for 3 minutes, so that each subject contributed 54 minutes of data. These **18 activities** include:

Non-hand-oriented activities: walking, jogging, stairs, standing, kicking
Hand-oriented activities (General): dribbling, playing catch, typing, writing, clapping, brushing teeth, folding clothes
Hand-oriented activities (eating): eating pasta, eating soup, eating sandwich, eating chips, drinking

## About this repository:

In this repo, you can find:
1. The dataset I used for this project. In the folder that I uploaded, the arff data files are re-organized so that I could pull them easily with Python. <br>
Data source:https://archive.ics.uci.edu/ml/datasets/WISDM+Smartphone+and+Smartwatch+Activity+and+Biometrics+Dataset+

2. My notebook for the project. In this notebook, I build, tune, and evaluate various Supervised learning models (Random Forest, K-nearest Neighbors, Support Vector Machines) to predict the activities and activity groups. 

3. My project summary presentation. This would give you a good overview of my models performance and their evaluation metrics comparison. 


