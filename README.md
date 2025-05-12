# Orbital Altitude Prediction with PyTorch

This project demonstrates a simple neural network for predicting orbital altitude over time using PyTorch. The model is trained on a sequence of altitude data and learns to approximate the underlying trend for future or missing values.

## 🧠 Model Architecture

- **Input:** Time step (integer)
- **Hidden Layers:** 
  - Layer 1: Fully connected, 64 units, ReLU activation
  - Layer 2: Fully connected, 32 units, ReLU activation
- **Output:** Predicted altitude (float)

## 🚀 Features

- Implements a basic regression model using PyTorch
- Visualizes training loss over epochs
- Compares predicted vs actual altitude values
- Uses Adam optimizer and MSE loss for training

## 🛠 Requirements

- Python 3.x
- PyTorch
- NumPy
- Matplotlib

Install requirements (if needed):

```bash
pip install torch numpy matplotlib

