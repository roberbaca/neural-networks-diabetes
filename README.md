# Diabetes Prediction with Neural Networks

This repository contains a diabetes prediction model implemented in R using neural networks and the PimaIndiansDiabetes dataset.

## Project Overview

This project applies neural networks to predict whether a patient has diabetes based on clinical measurements such as glucose, blood pressure, BMI, age, and others. Three models are compared:

- **Simple Neural Network**  
- **Neural Network with Hyperparameter Tuning**  
- **Multilayer Perceptron (MLP)**  

An economic analysis is included to evaluate the cost of misclassification:

- **False Negatives (FN):** high cost (USD 1,000 per undiagnosed diabetic patient)  
- **False Positives (FP):** lower cost (USD 100 per healthy patient incorrectly diagnosed)  

The workflow covers:

- Data preprocessing and handling missing values  
- Train-test split and class balancing using ROSE  
- Feature scaling  
- Neural network modeling with and without hyperparameter tuning  
- Model evaluation using confusion matrices, ROC curves, AUC, and cost-based analysis  

## Technologies and Libraries Used

- R  
- tidyverse  
- nnet  
- neuralnet  
- caret  
- pROC  
- NeuralNetTools  

## Project Report

You can view the full analysis here: [Neural Networks Diabetes](https://roberbaca.github.io/neural-networks-diabetes/)

## How to Run

1. Clone the repository  
2. Open the RMarkdown file (`.Rmd`)  
3. Run the notebook to reproduce the analysis and generate predictions  

## Links

- Kaggle Notebook: [Diabetes Prediction on Kaggle](https://www.kaggle.com/code/robertonicolsbaca/diabetes-prediction-using-neural-networks-r)  

© 2025 Roberto Baca
