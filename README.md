# Orbital Position Polynomial Regression Using Neural Networks

This project aims to analyze the relationship between orbital positions and time using polynomial regression implemented with a neural network. The dataset contains time steps and corresponding positions, and the objective is to create a neural network that accurately models this relationship, while preventing overfitting.

## Project Overview

- **Input:** Time steps (as features)
- **Output:** Orbital positions (target)
- **Objective:** Use polynomial regression implemented via a neural network to predict orbital positions from time steps.
- **Requirements:**
  - Neural Network with multiple layers and dropout to avoid overfitting.
  - Early stopping during training to avoid overfitting.
  - Metrics: Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared.
  - Visualization: Plot of actual vs predicted positions.

## Dataset

The dataset used contains two columns:
- `time_steps`: The time steps of the orbit.
- `y`: The corresponding positions at each time step.

## Requirements

Ensure you have Python installed and then install the required packages listed in `requirements.txt` using:

```bash
pip install -r
