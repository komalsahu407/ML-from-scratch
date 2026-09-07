# SVM-Based Bus vs Car Image Classification

## Overview

This project uses **Support Vector Machine (SVM)** to classify images into **Bus** and **Car** categories.

## Technologies Used

* Python
* OpenCV
* NumPy
* Matplotlib
* Scikit-learn
* SVM (SVC)

## Workflow

1. Load and preprocess images
2. Resize images to **150×150**
3. Flatten image data
4. Split data into training and testing sets
5. Train SVM model
6. Predict image classes
7. Evaluate model performance

## Model

* Algorithm: **SVM**
* Kernel: **Linear**
* C: **1.0**

## Results

* **Accuracy: 75%**
* Confusion Matrix: `[[16, 4], [6, 14]]`

## Future Improvements

* Use more training images
* Try different SVM kernels
* Apply data augmentation
* Improve classification accuracy

