# Traffic Flow Prediction Using Machine Learning
This project applies common machine learning concepts, specifically Random Forest (RF) and Support Vector Regression (SVR), to predict traffic flow. The performance of the models is evaluated using accuracy metrics.

## Table of contents
- Introduction
- Dataset
- Data Format
- Algorithm Used
- Model Performance
- Results
- Reference used

## Introduction
This research-based practice project focuses on predicting traffic congestion using machine learning algorithms. The project explores how different machine learning models, specifically Random Forest and Support Vector Regression, can be used to predict traffic flow based on various factors like date, day, zone, temperature, and traffic levels.

## Dataset 
The dataset used in this project includes the following features:
- **Date**: Recorded in DD/MM/YYYY format.
- **Day**: The day of the week.
- **Coded Day**: Numerical code assigned to each day for easier prediction.
- **Zone**: The specific area where traffic data was recorded.
- **Temperature**: Coded based on typical weather conditions.
- **Traffic**: Coded on a five-level scale representing traffic congestion

## Data Format
- **Date**: DD/MM/YYYY
- **Day Codes**: Assigned to simplify predictions based on the day.
- **Temperature Codes**: Reflect typical weather conditions.

## Algorithms Used
The project utilizes the following machine learning algorithms:
- **Random Forest (RF)**: An ensemble learning method that operates by constructing multiple decision trees.
- **Support Vector Regression (SVR)**: A type of Support Vector Machine used for regression tasks, predicting continuous values.

## Model Performance
The models were evaluated based on accuracy:
- :round_pushpin:**Random Forest (RF)**:
  Error = -10.08 %
  Accuracy= 110.08 %.
  
- :round_pushpin:**Support Vector Regression (SVR)**:
  Error = 12.16 %
  Accuracy = 87.84 %

## Results 
The project demonstrates that Support Vector Regression significantly outperforms Random Forest in predicting traffic flow with the given dataset, achieving an accuracy of 87.84% compared to 110.08%.

## Reference used 
https://github.com/Nupurgopali/Traffic-Prediction-using-SVR-and-RFR/blob/master/svr.py 
https://www.openstreetmap.org/export#map=15/21.2223/72.8374
