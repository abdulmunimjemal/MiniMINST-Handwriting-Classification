# MiniMINST: Hadnwritten Number Recognition

## Introduction

MiniMINST will be used to write a neural network model from scratch using numpy. The model will be trained on the MNIST dataset and will be able to recognize handwritten digits. The model will be trained using the stochastic gradient descent algorithm.

## Data

The MNIST dataset is a large database of handwritten digits that is commonly used for training various image processing systems. The dataset contains 60,000 training images and 10,000 testing images. The images are grayscale and 28x28 pixels in size. The dataset is available at http://yann.lecun.com/exdb/mnist/.

Since our main concern is the writing of the neural network model, we will use a clean mini version of the MNIST dataset. The mini version contains 1000 training images and 100 testing images. The dataset is available in data/ folder.

## Model

The model will be a simple feedforward neural network with one hidden layer. The input layer will have 784 neurons, the hidden layer will have 30 neurons, and the output layer will have 10 neurons. The model will use the relu activation function for the hidden layer and the softmax activation function for the output layer. The model will be trained using the stochastic gradient descent algorithm.

## Training

The model will be trained using the mini version of the MNIST dataset. The training process will be done in batches of 10 images. The model will be trained for 30 epochs with a learning rate of 0.01.

## Evaluation

The model will be evaluated using the mini version of the MNIST dataset. The evaluation process will be done using the testing images. The accuracy of the model will be calculated and printed to the console.

## Conclusion

The model will be able to recognize handwritten digits with a high accuracy. The model will be able to generalize well to unseen data and will be able to recognize digits with high accuracy.

## References

- https://en.wikipedia.org/wiki/MNIST_database
- https://www.tensorflow.org/datasets/catalog/mnist

## Author

- [Abdulmunim Jundurahman](https://www.linkedin.com/in/abdulmunim-jemal/)
