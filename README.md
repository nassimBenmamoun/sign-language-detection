# sign-language-detection
This project aims to create a program capable of recognizing and interpreting American Sign Language (ASL) gestures from still images. The main objective is to accurately classify sign language images in order to create a useful tool for deaf or hard-of-hearing individuals who wish to communicate with those who do not understand ASL, as well as for educational or training contexts.

## Dataset
We have collected a dataset of American Sign Language (ASL) sign images from this source:
[Dataset](https://www.kaggle.com/datasets/datamunge/sign-language-mnist?select=sign_mnist_test)

## Data preprocessing
We cleaned and prepared the data by resizing the images to a uniform size, normalizing the pixels, and splitting them into training, validation, and test sets for training and evaluating our model.

## Classification model
We used a Convolutional Neural Network (CNN) to create our image classification model. We trained the model on the training data and used the validation data to optimize the model's parameters and prevent overfitting. Finally, we evaluated the model's performance on the test dataset.

## Contributor
- [Chentoui Abdelali](https://github.com/AbdelaliChe)
