# Fashion_classification using CNN


## Project Overview
This project involves building a Convolutional Neural Network (CNN) to classify images from the Fashion-MNIST dataset into one of ten categories, including t-shirts, trousers, pullovers, dresses and more.

## Objective
The primary goal is to achieve high accuracy in classifying grayscale images (28x28 pixels) into their respective fashion categories using a CNN architecture.

## Dataset
The Fashion-MNIST dataset contains:
- **Training Set:** 60,000 images
- **Test Set:** 10,000 images
- **Classes:** 10 categories such as 'T-shirt/top', 'Trouser', 'Pullover', 'Dress', 'Coat', etc.

## Technologies Used
- **Python**: Programming Language
- **TensorFlow/Keras**: Deep Learning Framework
- **Matplotlib**: Data Visualization

## Model Architecture
- **Input Layer:** Accepts 28x28 grayscale images
- **Convolutional Layers:** Extracts features using 32 and 64 filters
- **MaxPooling Layers:** Reduces spatial dimensions
- **Flatten Layer:** Converts 2D matrices to 1D vectors
- **Dense Layers:** Provides the classification output through a softmax activation

## Model Performance
- **Training Accuracy:** 96.53%
- **Validation Accuracy:** 91.15%
- **Training Loss:** 0.0948
- **Validation Loss:** 0.2959

### Key Observations:
- Consistent increase in both training and validation accuracy over epochs.
- Minimal overfitting indicated by the small gap between training and validation accuracy.
- Visual predictions align well with actual labels with few misclassifications.

