# Handwritten Character Recognition

## CodeAlpha Machine Learning Internship

### Project Overview

This project implements a Convolutional Neural Network (CNN) to recognize handwritten digits using the MNIST dataset.

The model is trained to classify handwritten images into one of 10 digit classes, from 0 to 9.

## Objective

The objective of this project is to build and evaluate a deep learning model capable of recognizing handwritten digits accurately.

## Dataset

The project uses the MNIST handwritten digit dataset.

- Training images: 60,000
- Testing images: 10,000
- Image size: 28 × 28 pixels
- Number of classes: 10
- Classes: 0 to 9

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Model Architecture

The CNN consists of:

- Convolutional layer with 32 filters
- Max Pooling layer
- Convolutional layer with 64 filters
- Max Pooling layer
- Flatten layer
- Dense layer with 128 neurons
- Output layer with 10 neurons using Softmax activation

## Data Preprocessing

The pixel values were normalized from the range 0–255 to 0–1.

The images were also reshaped to include the grayscale channel required by the CNN.

## Training

The model was trained using:

- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy
- Epochs: 5
- Batch Size: 64
- Validation Split: 10%

## Results

The trained CNN achieved:

**Test Accuracy: 99.17%**

**Test Loss: 0.0291**

The model was also evaluated using a confusion matrix and classification report containing precision, recall, and F1-score for each digit.

## Files

- `CodeAlpha_HandwrittenCharacterRecognition.ipynb` — Complete Google Colab notebook
- `handwritten_character_recognition.keras` — Trained CNN model

## Conclusion

The CNN successfully recognizes handwritten digits from the MNIST dataset with high accuracy. The trained model can be saved and reused for future handwritten digit prediction tasks.

## Internship Task

This project was completed as part of the **CodeAlpha Machine Learning Internship**.
