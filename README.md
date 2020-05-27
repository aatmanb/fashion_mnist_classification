# fashion_mnist_classification

## Required Libraries
1. numpy
2. tensorflow
3. tensorflow_datasets (required only if you want to use the dataset from tensorflow)
4. math
5. matplotlib (to visualize the dataset)

## Fashion MNIST Dataset
split: 60000 train and 10000 test

Number of classes = 10

## Files
The repository contains two jupyter notebooks which build two different kinds of neural networks

1. simple_nn.ipynb contains code for a simple dense layer neural network with the following architecture

![download (1)](https://user-images.githubusercontent.com/44796478/83008038-2ce16780-a032-11ea-8e08-ee4e959fa9ca.png)

2. cnn_fashion_mnist.ipynb contains code for a Convolutional Neural Network with the following architecture

![download](https://user-images.githubusercontent.com/44796478/83008073-3bc81a00-a032-11ea-94ca-3ef1c4548bf8.png)

## Results
Simple Neural Network achieves train set accuracy of 0.9091 and test set accuracy of 0.8722

Convolutional Neural Network achieves train set accuracy of 0.9760 and test set accuracy of 0.9214
