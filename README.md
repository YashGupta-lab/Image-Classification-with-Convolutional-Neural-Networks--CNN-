# Image Classification with Convolutional Neural Networks (CNN)
 This project demonstrates the use of a Convolutional Neural Network (CNN) for image classification. The model is designed to classify images as either 'dog' or 'cat' based on a dataset provided.

# Overview
 
 In this project, a CNN model is trained using a dataset of images to classify them as either 'dog' or 'cat'. The model is designed using Keras and consists of convolutional, pooling, and dense layers to 
 effectively learn and classify the images.

# Dataset

 The dataset used for this project contains images and labels for training and testing. The images are provided in separate CSV files (input.csv, input_test.csv) and are labeled as 'dog' or 'cat' (labels.csv, 
 labels_test.csv).

# Model Architecture
 
 The CNN model consists of:

 1. Convolutional layers for feature extraction.

 2. Max pooling layers for dimensionality reduction.

 3. Dense layers for classification.
 
 4. Activation functions include ReLU and Sigmoid.
 
 The model is compiled with the binary cross-entropy loss function and the Adam optimizer.

# Requirements
 
 1. Python 3
 
 2. TensorFlow and Keras
 
 3. NumPy
 
 4. Matplotlib

To install the required libraries, use the following command:
 
 pip install tensorflow keras numpy matplotlib

# Result

The model's performance is evaluated using the accuracy metric. The model also predicts whether a random test image is a 'dog' or a 'cat'.
