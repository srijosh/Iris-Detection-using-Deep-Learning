# Iris Detection using Deep Learning

This repository contains a project for detecting irises in images of faces using a deep learning model. The project focuses on leveraging custom-captured images and annotations to train a model that accurately identifies iris locations.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model](#model)

## Introduction

Iris Detection is a critical task in biometric authentication and computer vision. This project aims to develop a deep learning model that can accurately detect the iris in human faces. The model is trained using custom-captured images and annotated keypoints for iris circles.

## Dataset

The dataset consists of images of the user's face, from which the irises are detected. The annotations for the iris keypoints were created using the LabelMe tool.

## Installation

To run this project, you need to have Python installed on your machine. You can install the required dependencies using pip.

## Installation

To run this project, you need to have Python installed on your machine. You can install the required dependencies using `pip`.

```
pip install tensorflow opencv-python labelme albumentations matplotlib

```

Requirements
Python 3.x
TensorFlow
OpenCV
LabelMe
Albumentations
Matplotlib

## Usage

1. Clone the repository to your local machine:

```
   git clone https://github.com/srijosh/Iris-Detection-using-Deep-Learning.git
```

2. Navigate to the project directory:
   cd Iris-Detection-using-Deep-Learning

3. Open and run the Jupyter Notebook:
   - jupyter notebook DataCollection.ipynb
   - jupyter notebook IrisDetection.ipynb

## Model

The model used in this project is based on a convolutional neural network architecture, leveraging the ResNet152V2 model for feature extraction.

### Data Preprocessing

- Image Capture: Captured images of the user's face using OpenCV.
- Annotation: Annotated the iris circles using LabelMe.

### Model Training

The model is trained to predict the locations of the iris based on the annotated images.

### Real-Time Detection

The model can perform real-time iris detection using a webcam feed captured via OpenCV.

### Evaluation

The model is evaluated based on its ability to accurately locate the iris in unseen images.
