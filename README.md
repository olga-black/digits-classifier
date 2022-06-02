a# About the project

This project was created as a take-home task for a job application process at Alvaria.

## Data

Custom dataset of handwritten digit images from MNIST.
Each data point consists of a sequence of images of a variable size.
Sequence sizes in the dataset are normally distributed.

Training set: 50,000 original images
Validation set: 10,000 original images
Testing set: 10,000 original images

## Model

The model performs a binary classification:
Does the given sequence of images contain a 4?
No: negative class
Yes: positive class

The model is convolutional neural network.
Three 2-D convolutional layers, mean, dropout, two linear layers.
Output is a probabilistic prediction between 0 and 1.

## Installation

Jupyter Notebook is required to run the script.
Get Jupyter Notebook here: [https://jupyter.org/install](https://jupyter.org/install)

### Install the dependencies

`python3 -m pip install -r requirements.txt`


