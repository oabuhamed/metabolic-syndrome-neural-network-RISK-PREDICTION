# Metabolic Syndrome Prediction using Machine Learning and Neural Networks

## Project Overview

This project aims to predict metabolic syndrome using clinical and demographic health data.  
Metabolic syndrome is a group of conditions that increase the risk of cardiovascular disease and diabetes.

Machine learning techniques and a neural network model were implemented to classify patients as having metabolic syndrome or not.

The project demonstrates a full machine learning workflow including data preprocessing, model training, hyperparameter tuning, and model evaluation.

---

## Dataset

The dataset contains clinical measurements and demographic information for patients.

Each row represents an individual patient, and the target variable indicates whether the patient has metabolic syndrome.

Key features include:

- Age
- Sex
- BMI
- Waist circumference
- Blood glucose
- HDL cholesterol
- Triglycerides
- Other metabolic indicators

---

## Methodology

The following steps were performed:

1. Data exploration and preprocessing
2. Train-test split
3. Feature scaling using StandardScaler
4. Building a neural network classifier with TensorFlow/Keras
5. Training the model with EarlyStopping
6. Hyperparameter tuning using Keras Tuner
7. Model evaluation using classification metrics and confusion matrix

---

## Neural Network Architecture

The neural network consists of:

- Input layer (13 features)
- Dense hidden layer with ReLU activation
- Dropout layer for regularization
- Output layer with sigmoid activation for binary classification

Loss Function: Binary Cross Entropy  
Evaluation Metrics: Accuracy, Precision, Recall

---

## Hyperparameter Tuning

Hyperparameter tuning was performed using **Keras Tuner** to improve model performance.

Parameters tuned include:

- Number of hidden layer units
- Dropout rate
- Optimizer

Best configuration found:
Units: 30
Dropout: 0.0
Optimizer: Nadam

---

## Model Performance

Final model performance on the test dataset:

- Accuracy ≈ 83%
- Precision ≈ 0.77
- Recall ≈ 0.73

The confusion matrix indicates strong performance in identifying healthy individuals and reasonable detection of metabolic syndrome cases.

---

## Technologies Used

- Python
- TensorFlow / Keras
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Keras Tuner

---

## Repository Structure
metabolic-syndrome-prediction-ml
│
├── metabolic_syndrome_neural_network.ipynb
├── README.md
---

## Author

Osama Abu Hamed  
Medical Doctor | Data Science Trainee
