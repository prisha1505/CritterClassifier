# CritterClassifier: Animal Detection

This project is a deep learning-based Animal Detection System that classifies images into 100 different animal species. The system uses a Convolutional Neural Network (CNN), a type of neural network designed specifically for image classification tasks. The model is trained using TensorFlow and Keras, and the application is deployed as a web interface using Streamlit, allowing users to easily upload images and get real-time predictions.

## Features
### Image Classification:

Classifies uploaded images into one of 100 animal species.
### Real-time Predictions: 
Provides predictions with confidence scores instantly upon image upload.

### User-Friendly Interface: 
Simple web app built using Streamlit for easy image uploads and viewing results.

## Tech Stack
### 1. TensorFlow & Keras
- These are widely-used open-source libraries for building and training deep learning models.
- TensorFlow provides the low-level operations, and Keras simplifies the building and training of the Convolutional Neural Network (CNN).

### 2. Convolutional Neural Network (CNN)
- A CNN is a type of neural network that excels in image classification tasks. It automatically learns important features and patterns from images, which is perfect for recognizing animals in photos.
- The CNN in this project is trained to classify images into 100 different animal species.
- 
### 3. Streamlit
- Streamlit is a framework for building interactive web applications for machine learning projects.
- It’s used here to create a simple web interface that allows users to upload animal images and receive predictions from the trained CNN model.
- 
### 4. NumPy
- NumPy is a library for handling arrays and numerical operations efficiently.
- It is used for manipulating image data and performing necessary calculations before feeding images into the model for classification.

### 5. Pillow (PIL)
- Pillow is the Python Imaging Library used to open, manipulate, and save various image formats.
- In this project, Pillow is used to load and preprocess the uploaded animal images, resizing them and converting them into a format that the model can work with.
  
### 6. H5 (Model Saving Format)
- The trained CNN model is saved in the H5 format, which is commonly used for saving and sharing deep learning models.
- This allows the model to be reused later for predictions without retraining.

# User Flow

![user_flow png](https://github.com/user-attachments/assets/954d49d2-090a-465b-acd1-b491207a7f0b)

# Data Flow

![dataflow png](https://github.com/user-attachments/assets/bd25940d-8419-4271-87a0-da3a0afeaf44)

# Architecture


![architecture png](https://github.com/user-attachments/assets/5877f991-1e9e-47dc-9010-04a02ae33c35)
