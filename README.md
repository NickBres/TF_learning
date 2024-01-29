# Machine Learning Project: Wine Review Classification and Diabetes Prediction

This repository contains two machine learning projects, both of which are practical applications of machine learning concepts and neural network implementation using Python and TensorFlow. The projects were inspired by a course from freecodecamp.org, taught by Kylie Ying. The course provides an introduction to machine learning concepts such as classification, regression, training/validation/test datasets, loss functions, neural networks, and model training.

## Project 1: Wine Review Classification

In the first project, we implement a feedforward neural network to classify wine reviews. The dataset used contains various features of wines, including a detailed description, points awarded, price, variety, and winery. The goal is to predict whether a wine will score 90 points or more based on its description, using binary classification.

## Project 2: Diabetes Prediction

The second project involves predicting whether a person has diabetes based on various diagnostic measurements. We use a feedforward neural network to make the predictions. The dataset includes several medical predictor variables and one target variable, Outcome. Predictor variables include the number of pregnancies the patient has had, their BMI, insulin level, age, and more.

## Project Structure

Each project is structured as a Jupyter notebook, which contains all the code and visualizations. The notebooks are divided into several sections:

1. **Data Loading and Preprocessing**: In this section, we load the dataset, handle missing values, and preprocess the data for our machine learning models.

2. **Data Visualization**: We visualize the distribution of the target variable in the dataset.

3. **Data Preparation**: We create a new binary label for our classification task and split the data into training, validation, and test sets.

4. **Model Building and Training**: We build and train a neural network model. The model uses a pre-trained text embedding as the first layer, which converts text inputs into a fixed-length vector.

5. **Model Evaluation**: We evaluate the performance of our model on the test data.

## Acknowledgements

These projects were inspired by the "Machine Learning with Python: Zero to GBMs" course on freecodecamp.org, taught by Kylie Ying. The course provides a comprehensive introduction to machine learning and neural networks, and I highly recommend it to anyone interested in these topics.
