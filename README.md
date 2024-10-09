# CIFAR-10 Image Classification

This project is an image classification system built using the CIFAR-10 dataset. It demonstrates the process of loading and preprocessing the data, building a Convolutional Neural Network (CNN) model, training, evaluating the model, and visualizing the results.

## Overview

A classification model to identify images from 10 different classes: airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships, and trucks. The goal is to achieve high accuracy using a CNN built with TensorFlow and Keras.

## Dataset

The [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. There are 50,000 training images and 10,000 test images.

## Model Architecture

The CNN model consists of:

- **3 Convolutional Layers** with ReLU activation.
- **MaxPooling** layers for downsampling.
- A **Fully Connected Layer** with 128 neurons.
- A **Dropout Layer** to prevent overfitting.
- An output layer with **softmax** activation for classification.

## Results

After training the model for 10 epochs, we achieve a test accuracy of approximately **70.34%**.
