# CDC-Diabetes-Health-Analysis-DeepLearningModel
CDC Diabetes Health Indicators Analysis Using Deep Learning and TensorFlow to classify diabetes status based on health-related indicators from the CDC Diabetes The aim is to explore patterns in health data and evaluate how effectively a neural network distinguishes between individuals with and without diabetes.
Objectives
Analyze health-related indicators associated with diabetes status.
Clean and prepare the dataset for machine learning.
Build and train a neural network using TensorFlow and Keras.
Evaluate model performance using classification metrics and visualizations.

Dataset: CDC Diabetes Health Indicators
Source: Kaggle — CDC Diabetes Health Indicators dataset
Target variable: Diabetes_binary
Target classes:
0: No diabetes
1: Diabetes
The dataset contains health-related indicators, including demographic, lifestyle, and health-condition variables.

Deep Learning Model
The model uses a feedforward neural network with:
Input layer for health indicator features
Dense hidden layer with 32 neurons and ReLU activation
Dropout layer with a rate of 0.2
Dense hidden layer with 16 neurons and ReLU activation
Output layer with one neuron and sigmoid activation.

Results Interpretation
The model achieved 85.36% test accuracy and an AUC of 0.8184. However, its recall for the diabetes-positive class was only 14% at the selected classification threshold of 0.5. This means that the model missed many diabetes-positive cases despite its relatively high overall accuracy.

Conclusion
This project demonstrates an end-to-end deep-learning workflow for diabetes-status classification using TensorFlow. It includes data preprocessing, neural network development, model training, and evaluation. Although the model achieved 85.36% test accuracy and an AUC of 0.8184, its low diabetes-class recall indicates that further improvement is needed before it could be considered for any screening application.

Dense hidden layer with 16 neurons and ReLU activation

Output layer with one neuron and sigmoid activation
