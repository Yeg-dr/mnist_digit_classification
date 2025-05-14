# Handwritten Digit Classification with CNN on MNIST Dataset

## Overview
This project implements a Convolutional Neural Network (CNN) to classify handwritten digits (0-9) from the MNIST dataset using PyTorch. As my first serious project in deep learning, it demonstrates my ability to build, train, and evaluate a neural network for image classification, achieving ~98-99% accuracy on the test set. I used an AI assistant for guidance on project structure and debugging to streamline the development process.

## Features
- Loads and preprocesses the MNIST dataset with PyTorch.
- Implements a CNN with two convolutional layers, max-pooling, and fully connected layers.
- Visualizes training/test loss and accuracy over epochs.
- Displays sample predictions with true and predicted labels.

## Technologies Used
- Python
- PyTorch
- NumPy, Matplotlib, OpenCV

## Installation
To run this project, install the required libraries:
```bash
pip install -r requirements.txt
```
## Usage
1. Clone the repository
```bash
git clone https://github.com/yeg-dr/mnist-digit-classification
```
2. Open main.py inJupyter Notebook or run main.py in your python environment.
3. Execute all cells/scripts to train the model and view result.
4. Check the result/ folder for visualizations (sample digits, loss/accuracy plots, and predictions.

# Project Structure
mnist_digit_classification/
├── main.ipynb              # Main code (Jupyter Notebook)
├── mnist_cnn.pth          # Trained model weights (optional)
├── requirements.txt        # Dependencies
├── results/               # Visualizations
│   ├── sample_digits.png  # Sample MNIST digits
│   ├── loss_plot.png      # Loss over epochs
│   ├── accuracy_plot.png  # Accuracy over epochs
│   ├── predictions.png    # Predicted vs true labels
│   ├── incorrect_predictions.png  # Misclassified digits
├── README.md              # Documentation
