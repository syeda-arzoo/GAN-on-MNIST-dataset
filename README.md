# GAN-on-MNIST-dataset

This file creates a Generative Adversarial Network on the MNIST data with the following specifications - 

1. Input is a randomly generated vector with dimension = 10.

2. Generator network consists of a 3 layer MLP with dimensions[784,784,784].
Activation function for the first two layers is LeakyReLU(0.2) and for the output layer is Tanh.

3. The input to the discriminator is a flattened image with size 784.

4. Generator network also consists of a 3 layer MLP with dimensions[784,784,784].
Activation function for the first 2layers is LeakyReLU(0.2).

5. The loss function is Binary Cross Entropyloss.

6. Adam Optimizer is used with learning rate 0.0005.
