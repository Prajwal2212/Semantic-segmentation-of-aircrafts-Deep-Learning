# Identification and Semantic Segmentation of Aircraft

This project aims to accurately identify and perform semantic segmentation of aircraft in images. Using a dataset of labeled aircraft images and segmentation masks, we develop and train machine learning models to detect aircraft and differentiate them from other objects in a given scene.

## Project Overview
Aircraft identification and segmentation is essential in various fields, including defense, aviation management, and environmental monitoring. This project leverages deep learning techniques to build a model capable of identifying aircraft and performing pixel-wise classification to distinguish aircraft from backgrounds.

## Table of Contents
### Project Structure
### Dataset
### Requirements
### Usage
### Training the Model
### Evaluating the Model
### Results
### Acknowledgments

## Project Structure
train: Contains the training data and annotations.\
test: Contains the testing data and annotations.\
valid: Contains the validation data and annotations.

## Dataset
The dataset used for this project contains images and XML files that define segmentation labels.

Image data is acquired from SkyFusion dataset from Kaggle.
Corresponding segmentation annotations in XML format are prepared by me and my teammates.\
![002](https://github.com/user-attachments/assets/bf2c46de-13ac-4885-853e-4eec15d7db2b)


## Installation
Clone the repository using git:
```bash
git clone https://github.com/Prajwal2212/Semantic-segmentation-of-aircrafts-Deep-Learning.git
cd Semantic-segmentation-of-aircrafts-Deep-Learning
```

## Usage
### Preprocess the Dataset
Parse the XML files to identify polygon's coordinates to enable model training.

### Run the Training Script
Use the provided Jupyter notebook or script to train the model.

### Inference
Run inference on test images to evaluate model performance.

## Training the Model
In this project, we used a U-Net model, which is widely used for semantic segmentation tasks. The model architecture can be customized and trained on the provided dataset.

## Evaluating the Model
Evaluation metrics like IoU (Intersection over Union) and pixel accuracy are used to measure the model's performance.\
<img width="845" alt="image" src="https://github.com/user-attachments/assets/08f492b3-1ed7-4c41-ba4b-538173f28900">


## Results
Model Accuracy: 98.1%

## Acknowledgments
This project was developed as part of an academic course, and we are grateful for the guidance received from our instructors of IIITN.
