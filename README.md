# Dog-Breed-Classifier
# Overview

This project is a deep learning-based dog breed classifier built using TensorFlow and TensorFlow Hub. The model leverages transfer learning with a pre-trained MobileNetV2 architecture to classify dog images into 120 different breeds.
 # Features

    Utilizes transfer learning with MobileNetV2 (130 depth, 224 input size)

    Handles image preprocessing and data augmentation

    Includes visualization tools for model predictions

    Implements early stopping and TensorBoard callbacks

    Provides prediction confidence visualization

# Model Architecture

    Input layer: (224, 224, 3) images

    MobileNetV2 feature extractor (from TF Hub)

    Dense output layer with softmax activation (120 units)

# Training

The model uses:

    Adam optimizer

    Categorical crossentropy loss

    Early stopping (patience=3)

    TensorBoard logging

# Visualization

The notebook includes functions to:

    Display sample images with labels

    Plot predictions vs actual labels

    Show top prediction confidences

    Generate side-by-side prediction comparisons

# Performance

Model performance can be monitored through:

    Training/validation accuracy

    TensorBoard logs

    Prediction visualization tools

# Saving Models

Use the provided save_model() function to save trained models for later use.
# Notes

    The code was originally developed in Google Colab

    Paths may need adjustment for local execution

    GPU is recommended for faster training
