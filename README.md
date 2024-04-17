# CropRecommendationSystemProject
The crop recommendation system is a web application designed to assist farmers in selecting suitable crops based on various factors such as soil nutrients and weather conditions. It leverages machine learning algorithms to analyze input parameters like soil nutrient levels, pH, rainfall, and temperature. The system then provides personalized crop recommendations based on this analysis. By integrating real-time weather data and pre-trained models, the system aims to optimize crop selection, leading to improved agricultural productivity and efficiency for farmers.

This Flask web application for crop recommendation based on input data such as soil nutrients, pH level, rainfall, and location
Importing Libraries: The necessary libraries such as Flask for web framework, numpy for numerical computations, pandas for data manipulation, sklearn for machine learning models, requests for making HTTP requests, and pickle for loading the pre-trained crop recommendation model.
Overall, this Flask application provides a user-friendly interface for farmers or users to input soil nutrients and weather parameters, and based on that, it predicts the most suitable crop for cultivation.


#ML Model
Libraries used :
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.metrics import classification_report
from sklearn import metrics
from sklearn import tree
from sklearn.ensemble import RandomForestClassifier
from sklearn.metrics import accuracy_score

#Model with higher accuracy
Random Forest classifier
