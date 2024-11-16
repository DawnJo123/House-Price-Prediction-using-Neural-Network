# House-Price-Prediction-using-Neural-Network

This repository contains a Python script that builds and trains a neural network using PyTorch to predict housing prices based on the California Housing dataset. The project implements a simple feedforward neural network and evaluates its performance using Mean Squared Error (MSE).

## Features
- **Data Preprocessing**:
  - Uses the California Housing dataset from `sklearn.datasets`.
  - Features are scaled using `StandardScaler` for better convergence.
  - Dataset is split into training and testing sets using an 80-20 split.

- **Neural Network Model**:
  - Implemented in PyTorch.
  - Composed of three layers:
    - Input layer with 8 features.
    - Two hidden layers with 25 and 30 neurons respectively.
    - Output layer with 1 feature for regression output.
  - Activation function: ReLU.

- **Training**:
  - Optimizer: Adam with a learning rate of 0.01.
  - Loss Function: Mean Squared Error (MSE).
  - Trains for 100 epochs while tracking the loss.

- **Evaluation**:
  - Generates predictions on the test set.
  - Calculates Mean Squared Error (MSE) for evaluation.

- **Visualization**:
  - Includes a plot of the training loss curve across epochs.

## Requirements
- Python 3.7 or higher
- PyTorch
- NumPy
- scikit-learn
- Matplotlib
- pandas

You can clone this repository:
   ```bash
   https://github.com/DawnJo123/House-Price-Prediction-using-Neural-Network.git
   cd california-housing-prediction
   ```

## Usage

1. **Data Preprocessing**:
   - The data is scaled using `StandardScaler` to normalize features.
   - The dataset is divided into training and testing sets.

2. **Training**:
   - A neural network is trained on the scaled features.
   - Loss is logged and plotted after training.

3. **Evaluation**:
   - The trained model is used to make predictions on the test data.
   - The Mean Squared Error (MSE) is calculated to evaluate performance.


## Results

- The model achieved a Mean Squared Error (MSE) of **1.316** on the test data.
- The training loss curve is shown below.

![housePriceNNloss](https://github.com/user-attachments/assets/f404bbf7-be7a-44fb-af5b-266532d72e38)


