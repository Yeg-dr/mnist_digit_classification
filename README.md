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

## Project Structure
```bash
mnist_digit_classification/
├── main.ipynb              # Main code (Jupyter Notebook)
├── mnist_cnn.pth          # Trained model weights (optional)
├── requirements.txt        # Dependencies
├── results/               # Visualizations
│   ├── sample_digits.png  # Sample MNIST digits
│   ├── loss_and_accuracy_plot.png  # Loss and Accuracy over epochs
│   ├── predictions.png    # Predicted vs true labels
│   ├── incorrect_predictions.png  # Misclassified digits
├── README.md              # Documentation
```

# Results

## Sample Digits:
![sample_digits](https://github.com/user-attachments/assets/53616189-6a7c-4609-b720-4f6d85771d27)

## Loss and Accuracy:
![loss_and_accuracy_plot](https://github.com/user-attachments/assets/a914e225-bed2-4457-bded-9056c2258357)

## Sample Predictions:
![predictions](https://github.com/user-attachments/assets/d4a29ace-1af2-4014-97f6-4bebd8589823)

## Challenges Faced
#Learning Rate Tuning:
Experimented with learning rates to achieve faster convergence.
#Overfitting: 
Added dropout (0.2) to improve model generalization.
#Debugging: 
Fixed tensor shape issues in the CNN by adjusting layer dimensions.

## What I Learned
1. Building and training CNNs for image classification with PyTorch.
2. Preprocessing image datasets and using DataLoader.
3. Visualizing model performance through loss and accuracy plots.
4. Analyzing model errors to identify improvement opportunities.

## Future Improvements
1. Create a web interface with Streamlit for interactive digit classification.
2. Experiment with deeper CNN architectures or data augmentation.
3. Test the model on real-world handwritten digits (e.g., scanned images).

## Acknowledgments
This project marks my first deep dive into deep learning. I learned from various resources, including PyTorch documentation, online tutorials, and an AI assistant that helped streamline development.
