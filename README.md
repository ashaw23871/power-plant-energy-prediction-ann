# ANN-Based Power Plant Energy Prediction

This project implements an Artificial Neural Network (ANN) using PyTorch to predict power plant energy output based on environmental parameters.

The model is trained on the Combined Cycle Power Plant dataset and demonstrates a complete machine learning workflow including preprocessing, feature scaling, model training, validation, and evaluation.

---

## Dataset Features

The dataset contains the following input features:

- Temperature (AT)
- Exhaust Vacuum (V)
- Ambient Pressure (AP)
- Relative Humidity (RH)

### Target Variable
- Electrical Energy Output (PE)

---

## Technologies Used

- Python
- PyTorch
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## Project Workflow

1. Data Loading
2. Data Preprocessing
3. Train-Test Split
4. Feature Scaling
5. ANN Model Creation
6. Model Training
7. Validation
8. Performance Evaluation
9. Prediction and Comparison

---

## Model Architecture

The ANN model consists of:

- Input Layer
- Hidden Layers with ReLU Activation
- Output Layer for Regression

Loss Function:
- Mean Squared Error (MSE)

Optimizer:
- Adam Optimizer

---

## Evaluation Metrics

The model performance is evaluated using:

- Mean Squared Error (MSE)
- R² Score

---

## Results

The ANN model achieved strong regression performance with low prediction error and accurate energy output prediction.

Training and validation loss curves were also plotted to monitor learning performance.

---
