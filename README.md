# Facial Recognition Project Report

## Introduction:

Facial recognition technology has become a focal point in recent years, finding applications in security systems, identity verification, and personalized user experiences. This report outlines the development and implementation of a facial recognition project using Convolutional Neural Networks (CNNs). The primary objective is to achieve accurate and real-time face detection and classification.

## Abstract:

This project utilizes CNNs, a powerful deep learning algorithm, for facial recognition. The process includes dataset creation, data preprocessing, model architecture design, model training, testing, and real-time face recognition. The goal is to develop an efficient system capable of recognizing and classifying individuals based on their facial features.

## Steps Followed:

### 1. Dataset Creation:

The project begins with the creation of a comprehensive facial image dataset, capturing variations in angles, lighting, and expressions to enhance model training.

### 2. Data Preprocessing:

Before training, the dataset undergoes preprocessing, including resizing, pixel value normalization, and augmentation to improve model generalization.

### 3. Model Architecture:

The CNN model architecture is designed with convolutional layers for feature extraction and fully connected layers for classification, incorporating components like pooling layers and dropout layers.

### 4. Model Training:

The dataset is split into training and validation sets for model training using backpropagation and gradient descent. Adjustments are made based on validation set performance.

### 5. Model Testing and Evaluation:

The trained model is tested on a separate dataset, and evaluation metrics like accuracy, precision, recall, and F1 score are employed to assess performance.

### 6. Real-Time Face Recognition:

The trained model is integrated into a real-time face recognition system. Live video or images from a webcam are used to detect and classify faces, enabling real-time identification.

## Features Included:

### 1. Development of Webpage using Flask:

- A webpage is developed using Flask, allowing image transfer in base64 string format. The deployed model calculates the probability score for the input image.

![image](https://github.com/Kaviyarasu-S007/Emotion-Detection/assets/151661034/a518427e-ab51-4dfd-a717-d513369b398d)
![image](https://github.com/Kaviyarasu-S007/Emotion-Detection/assets/151661034/dc7843b3-0462-457a-9f6e-89755605cba9)


### 2. Real-Time Facial Emotion Detection Implementation:

![image](https://github.com/Kaviyarasu-S007/Emotion-Detection/assets/151661034/0c462048-e279-45a1-bdaa-b1c403e5695b)

## Conclusion:

The facial recognition project successfully implements a CNN-based system for accurate face detection, classification, and real-time recognition. The system has broad applications in security, surveillance, and personalized user experiences. Future work may involve optimizing the model architecture, exploring additional data augmentation techniques, and expanding the dataset for improved performance and robustness.
