# Tensorflow Image Classifier: Globular vs Open Star Cluster

This is the repository developed for demonstrating _Transfer Learning_ with Convolutional Neural Networks like MobileNet and Inception.

Astronomers can use this classifier to automatically label whether an image taken by telescope is of a Globular Star Cluster or an Open Star Cluster.

![diff](screenshots/diffclusters.JPG)

## Requirements

- [Python v3.6](https://www.python.org/)
- [Tensorflow v1.8](https://www.tensorflow.org/)

## Usage 

1. Change directory structure for classification directories.

2. Retrain the model using _retrain.py_ and modifying the hyperparameters.

2. Run the _label_image.py_ to label the image. `python label_image.py <path_to_image>`

## Training

![training](screenshots/training.jpg)

## Tensorboard Training Summaries

![s1](screenshots/tensorboard1.jpg)
![s2](screenshots/tensorboard2.jpg)

## Results
Model can successfully differentiate between image of a globular cluster and an open cluster. 

### Accuracy
![accuracy](screenshots/fin.jpg)

### Test on Globular Star Cluster Image
![result1](screenshots/result1.png)

### Test on Open Star Cluster Image
![result2](screenshots/result2.png)
