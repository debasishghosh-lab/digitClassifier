# Handwritten Digit Recognition using MobileNetV2 Transfer Learning

## Project Overview

This project implements a handwritten digit recognition system using Transfer Learning with MobileNetV2. The model classifies images of digits (0–9) and demonstrates how pre-trained computer vision models can be adapted for custom image classification tasks.

## Key Features

* Transfer Learning with MobileNetV2
* Automatic train-validation split
* Data preprocessing using MobileNetV2 preprocessing pipeline
* Real-time prediction on uploaded images
* Model persistence using TensorFlow/Keras
* Training and validation performance visualization

## Tech Stack

* Python
* TensorFlow
* Keras
* MobileNetV2
* NumPy
* Matplotlib
* Google Colab

## Model Architecture

Input Image (224×224×3)

↓

MobileNetV2 (ImageNet Pretrained)

↓

Global Average Pooling

↓

Dense Layer (128 Units)

↓

Dropout (0.3)

↓

Softmax Layer (10 Classes)

## Results

* Training Accuracy: 92%
* Validation Accuracy: 85%
* Number of Classes: 10
* Transfer Learning Strategy: Feature Extraction

## Example Prediction

Input Image: Handwritten Digit

Predicted Class: 8

Confidence: 34.75%

## How to Run
1. Upload Dataset.zip
2. Run notebook
3. Upload test image
4. Get prediction

## Future Improvements

* Fine-tuning MobileNetV2 layers
* Data augmentation
* Streamlit deployment
* Model quantization for edge devices
* Support for real-time webcam prediction
