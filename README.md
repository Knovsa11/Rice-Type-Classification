# Rice-Type-Classification

This project aims to predict the probability of Jasmine and Gonen rice grains using a dataset with 12 numerical attributes. The target attribute is "Rice (Jasmine or Gonen)", which indicates whether the given or input specification refers to Jasmine or Gonen rice grains. The goal is to help consumers select rice based on their specific rice consumption preferences. The model achieved an accuracy of 90% using the SVM algorithm.

## Project Purpose
The main purpose of this project is to develop a machine-learning model that can accurately classify Jasmine and Gonen rice grains. This classification can assist consumers in selecting the type of rice that best suits their preferences.

## Problem Statement
Consumers often have specific preferences regarding the type of rice they consume. However, distinguishing between different types of rice grains, such as Jasmine and Gonen, can be challenging based on visual inspection alone. This project addresses this problem by using a machine learning model to classify rice grains based on numerical attributes, ensuring that consumers get the type of rice they desire.

## Background
Rice is a staple food for many people worldwide, and there are various types of rice with distinct characteristics. Jasmine and Gonen rice grains are two popular types with different textures, flavors, and culinary uses. Accurate classification of these rice types is essential for consumers, retailers, and producers to meet quality standards and consumer preferences.

## Project Output
The output of this project includes:
A trained machine learning model that classifies rice grains as either Jasmine or Gonen.
Predictions on new data to identify the type of rice.
An inference dataset containing the predictions made by the model.

## Methods
The project utilizes the following methods:
Feature Engineering: Creating and selecting features from the dataset.
Modeling: Building and training the Support Vector Machine (SVM) algorithm to classify rice grains.
Model Inference: Testing the trained model on new data to make predictions.

## Technology Stack
The project is developed using the following technologies:
Programming Language: Python
Data Analysis and Manipulation: Pandas
Machine Learning: Scikit-learn
Notebook Environment: Jupyter Notebook

## Files
1. Rice Type Classification.ipynb
This notebook includes:
Dataset Information: Detailed description of the dataset used for training and testing.
Feature Engineering: Process of creating and selecting features for the model.
Modeling: Building and training the machine learning model.
Model Saving: Saving the trained model for later use.

2. P1M2_kelvinn_rizky_inf.ipynb
This notebook is used for:
Model Inference: Testing the trained model on new data to make predictions.

3. riceClassification.csv
This is the main dataset used in the project, containing the features and labels for different types of rice.

4. inference.csv
This dataset is saved as part of the inference process, containing the predictions made by the model on new data.

5. model.pkl
This file contains the trained model resulting from the training and testing processes in the Rice Type Classification.ipynb notebook.

6. url.txt
This file contains url deployment huggingface. 
