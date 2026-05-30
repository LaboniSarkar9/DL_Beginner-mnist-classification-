# DL_Beginner-mnist-classification-
# Objective To develop and train a deep learning model capable of accurately recognizing handwritten digits from image data.


# MNIST Handwritten Digit Classification

## Overview
This project implements a neural network for classifying handwritten digits from the MNIST dataset.

## Dataset
- 70,000 grayscale images
- Image size: 28×28 pixels
- Classes: Digits 0–9

## Technologies Used
- Python
- TensorFlow/Keras
- NumPy
- Matplotlib

## Workflow

### 1. Import Libraries
Load all required packages.

### 2. Load Dataset
Download and load the MNIST dataset from Keras.

### 3. Data Preprocessing
- Normalize pixel values
- Reshape images
- Convert labels if required

### 4. Build Neural Network
- Input Layer
- Hidden Layer(s)
- Output Layer with Softmax

### 5. Compile Model
- Optimizer: Adam
- Loss: Sparse Categorical Crossentropy
- Metric: Accuracy

### 6. Train Model
Train for specified epochs and batch size.

### 7. Evaluate Performance
Measure test accuracy and loss.

### 8. Make Predictions
Predict digits on unseen images.

## Results
| Metric | Value |
|----------|----------|
| Training Accuracy | XX% |
| Test Accuracy | XX% |

## How to Run

```bash
git clone <repository-url>
cd mnist-classification
pip install -r requirements.txt
jupyter notebook mnist-classification.ipynb
