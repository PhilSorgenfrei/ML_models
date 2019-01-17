# ML_models

## Content of this repository

This repository contains ML models I have written as part of my own education on the subject of machine learning. I am using jupyter notebooks and have tried to make them quite verbose to explain each step in a way that does not assume deep expertise of the subject itself or its implementation. I am not trying to maximize performance of the models, but rather use small datasets and little hyperparameter tuning just for the proof of concept and fast iterations.  

My hope is that somebody might find some of the content useful to progress on their own journey in machine learning

#### Genetic_routing
This notebook tackles the "traveling salesman problem" by using a genetic algorithm to find optimal (i.e., fast) multi-stop routes

#### Predictive_maintenance_aircraft_engines
This notebooks attempts to predict engine failure events in advance of occuring based on time series sensor data. It uses a three-layer LSTM model

#### Credit_card_fraud_detection
This notebooks attempts to predict fraudulent credit card transactions using a gradient boosted decision tree

#### TB_Xray_02 
This notebook attempts detection of TB on X-ray images using various image transformations as well as incorporating a pre-trained image classifier through the tensorflow hub functionality

#### Hand_written_digts
This notebook incorporates my notes on the classical hand-written digits classification problem

#### Feature_engineering_01/02 
These notebookes capture my notes on feature engineering based on the "google cloud - feature engineering" course on coursera and a housing price dataset. It focuses on tensorflow functionalities that aid in feature engineering and also covers some basic concepts, such as feature crosses, and embeddings


## A brief guide to learners

Since this repositiory does not cover much of the underlying theory of machine learning, I am also working on some notebooks that cover topics such as activation functions, loss functions, or parameter initialization: https://github.com/PhilSorgenfrei/ML_notes 

For those who are just beginning to learn more about machine learning, I can wholeheartedly recommended the following resources as a start: 

- CS50, Introduction to Computer Science (Harvardx): This course is excellent for all those who want to learn programming (or those who were always curious about the difference between linked lists, hash tables, and tries;) 
- deeplearning.ai (coursera, Andrew Ng): Andrew does a phenomenal job in teaching neural networks starting with the most basic calculus and linear algebra. I believe there is nothing more informative than implementing forward and backprop in raw numpy and I have him to thank for making the topic so very accessible. There is also no shortage of more practical concepts (especially hyperparameter tuning) and more complex and recent model architectures (deep CNNs, or LSTMs come particularly to mind)
- Andrej Karpathy's blog (https://medium.com/@karpathy): This apparently happens when somebody who knows a topic deeply takes the time to explain it to the rest of us - pure gold! 

If any mistake is spotted in these notebooks, please let me know so that I may fix it! 

In case there are any issues with displaying the notebooks through github, copy/paste the notebook url into nbviewer (https://nbviewer.jupyter.org/)
