In this assignment, we build a complete neural network using Numpy. 
We will implement all the steps required to build a network - feedforward, loss computation, backpropagation, weight updates etc.

Here we use the MNIST dataset to train your model to classify handwritten digits between 0-9.

The project is divided into the following sections:

1. Data preparation
2. Feedforward
3. Loss computation
4. Backpropagation
5. Parameter updates
6. Model training and predictions

The dataset is 'mnist.pkl.gz'. 
There are 28x28 greyscale images in the MNIST dataset. Hence, each input image is a vector of length 784. 
The ground truth labels of a batch are stored in a matrix which is converted to a one-hot matrix. Also, the output of the model is a softmax output of length 10. 