# Crop-Recommendation
Crop Recommendation - DAC Project 
## Problem statement
Based on predicted rainfall, soil contents and weather parameters the system will recommend the most suitable crop for cultivation. This system also provides details about required fertilizers like Nitrogen(N), Phosphorus (P) and potassium(K) in Kg per hectare and display the required seed for a cultivation in Kg per acre for recommended crop.This system as contain some other feature such as display thecurrent market price and approximated yield in quintal per acre for recommended crop. Those all details will helps to farmers for choosing the most profitable crop.

Crop prediction is an essential task for the decision-makers at national and regional levels for rapid decision-making. An accurate crop yield prediction model can help farmers to decide on what to grow and when to grow.The dataset contains following 22 crops: ['rice', 'maize', 'chickpea', 'kidneybeans', 'pigeonpeas', 'mothbeans', 'mungbean', 'blackgram', 'lentil', 'pomegranate', 'banana', 'mango', 'grapes', 'watermelon', 'muskmelon', 'apple', 'orange', 'papaya', 'coconut', 'cotton', 'jute', 'coffee']

## Dataset
Dataset Link - https://www.kaggle.com/code/prasadchaskar/crop-prediction-99-accuracy/data?select=Crop_recommendation.csv

The dataset contains 2200 rows and 8 cloumns. The values of columns 1 to 7 ['N', 'P', 'K',  'Temperature', 'Humidity', 'pH', 'Rainfall'] determine the outcome - the suitable crop. The dataset contains 22 crops ['rice', 'maize', 'chickpea', 'kidneybeans', 'pigeonpeas', 'mothbeans', 'mungbean', 'blackgram', 'lentil', 'pomegranate', 'banana', 'mango', 'grapes', 'watermelon', 'muskmelon', 'apple', 'orange', 'papaya', 'coconut', 'cotton', 'jute', 'coffee'] that are recommended based on the other column values. 

* N - ratio of Nitrogen content in soil
* P - ratio of Phosphorous content in soil
* K - ratio of Potassium content in soil
* Temperature - temperature in degree Celsius
* Humidity - relative humidity in %
* ph - ph value of the soil
* Rainfall - rainfall in mm
 #### Target variable: Crop

## Model
K-Nearest Neighbor also known as KNN is a supervised learning algorithm that can be used for regression as well as classification problems. Generally, it is used for classification problems in machine learning. First, KNN is a non-parametric algorithm. KNN works on a principle assuming every data point falling in near to each other is falling in the same class. In other words, it classifies a new data point based on similarity

