# Yoga Pose Classification using Convolutional Neural Networks (CNN)

This repository contains the code for training a Convolutional Neural Network (CNN) to classify yoga poses from images. The dataset consists of images belonging to 5 different yoga poses.

## Dataset
The dataset used for this project is public dataset by UJJWAL CHOWDHURY. And can be found on Kaggle: [Yoga Pose Classification Dataset](https://www.kaggle.com/datasets/ujjwalchowdhury/yoga-pose-classification/data)

## Model Architecture
The CNN model used for classification consists of the following layers:

1. **Convolutional Layers**: Two convolutional layers with 32 and 64 filters respectively, each followed by a ReLU activation function and max pooling layer to extract features from the input images.
2. **Flatten Layer**: Flattens the output of the convolutional layers into a vector.
3. **Dense Layers**: Two fully connected dense layers with 128 units each, followed by ReLU activation and a dropout layer to prevent overfitting.
4. **Output Layer**: A dense output layer with 5 units (one for each class) and softmax activation to output class probabilities.
