# Pedestrian_Detection_Using_HOGS

This project implements a classical computer vision technique to detect pedestrians in images using the Histogram of Oriented Gradients (HOG) feature descriptor in combination with a pre-trained Support Vector Machine (SVM) classifier.

The goal is to accurately identify and localize pedestrians in a static image by leveraging traditional feature extraction and machine learning methods. This method serves as a lightweight and interpretable alternative to deep learning-based detectors, making it suitable for resource-constrained environments or educational use.

# Key Features
Image-based pedestrian detection

HOG descriptor for feature extraction

SVM classifier for person recognition

Non-Maximum Suppression (NMS) to remove overlapping bounding boxes

Visual comparison of detections before and after suppression

Easily extendable to video streams or real-time applications

# Technologies Used
Python

OpenCV

NumPy

imutils

# Project Highlights
Detected multiple pedestrians in a single frame using HOG + SVM.

Applied Non-Maximum Suppression to reduce redundancy and improve precision.

Compared and visualized results for better interpretability.

Lightweight and efficient implementation without deep learning dependencies.

