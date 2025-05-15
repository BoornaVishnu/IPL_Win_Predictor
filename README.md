# IPL_Win_Predictor
### Problem Statement 
This project aims to develop a machine learning system to predict win probability for 
the batting team during the second innings of an Indian Premier League (IPL) cricket 
match. The system utilizes historical IPL match data up to the 2024 season. 
Project Overview 
This project involves the following key stages: 
1. Data Collection & Preprocessing: Gathering and cleaning ball-by-ball data 
from IPL matches up to 2024. 
2. Feature Engineering: Identifying and preparing the input features for the 
models based on the available data columns. 
3. Model Development & Training: Building and training three different 
classification models to predict win probability: 
 - Logistic Regression 
 - Feedforward Neural Network
 - Random Forest 
4. Model Evaluation: Assessing the performance of each model using 
appropriate metrics (1)accuracy (2)precision (3)f1 score. 
5. Analysis: Comparing the models' predictions and identifying strengths. 
Feature Engineering 
The models were trained using the following features derived directly from the 
ball-by-ball dataset: 
Batting_team,bowling_team,city,runs_left,balls_left,wickets_left,runs_target,crr,rrr 
The target variable for prediction is: 
result: Indicates which team won the match (binary outcome based on the batting 
team's success). 
