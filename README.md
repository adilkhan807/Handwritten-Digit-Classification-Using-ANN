# Handwritten Digit Classification Using Artificial Neural Networks (ANN)

## Overview

This project implements a Handwritten Digit Classification system using an Artificial Neural Network (ANN) built with TensorFlow and Keras. The model is trained on the MNIST dataset to recognize handwritten digits from 0 to 9.

## Features

* Uses the MNIST handwritten digit dataset
* Data preprocessing and normalization
* ANN model built using TensorFlow/Keras
* Training and validation performance monitoring
* Accuracy evaluation on test data
* Prediction of handwritten digits

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Scikit-learn

## Dataset

The project uses the MNIST dataset, which contains:

* 60,000 training images
* 10,000 testing images
* 28×28 grayscale handwritten digit images
* 10 output classes (0–9)

## Model Architecture

* Flatten Layer (28×28 input)
* Dense Layer (128 neurons, ReLU)
* Dense Layer (32 neurons, ReLU)
* Output Layer (10 neurons, Softmax)

## Project Workflow

1. Load MNIST dataset
2. Normalize image pixel values
3. Build ANN model
4. Train the model
5. Evaluate performance
6. Generate predictions
7. Visualize training results

## Results

The model achieves high classification accuracy on the MNIST test dataset and demonstrates the effectiveness of Artificial Neural Networks for image classification tasks.

## Installation

```bash
git clone https://github.com/your-username/handwritten-digit-classification.git
cd handwritten-digit-classification
pip install -r requirements.txt
```

## Run the Project

```bash
jupyter notebook Handwritten_digit_classification.ipynb
```

## Repository Structure

```text
Handwritten-Digit-Classification/
│
├── README.md
├── requirements.txt
├── .gitignore
├── Handwritten_digit_classification.ipynb
├── screenshots/
│   ├── training_accuracy.png
│   ├── training_loss.png
│   └── prediction_sample.png
└── LICENSE
```

## Author

Developed as a Deep Learning project for handwritten digit recognition using Artificial Neural Networks.
