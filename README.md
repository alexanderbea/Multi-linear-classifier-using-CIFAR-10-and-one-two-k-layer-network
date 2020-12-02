# Training multi-linear classifier with a one layer network

<p align="justify">Herein I have trained and tested a one layer network with multiple outputs to classify images from the CIFAR-10 dataset. I have trained the network using mini-batch gradient descent applied to a cost function that computes the cross-entropy loss of the classifier applied to the labelled training data and an L2 regularization term on the weight matrix.</p>

![](https://github.com/alexanderbea/Multi-linear-classifier-using-CIFAR-10-and-one-two-k-layer-network/blob/main/Images/Figure%201.PNG)

# Training multi-linear classifier with a two layer network

<p align="justify">Next, I trained and tested a two layer network with multiple outputs to classify images from the CIFAR-10 dataset. I trained the network using mini-batch gradient descent applied to a cost function that computes the cross-entropy loss of the classifier applied to the labelled training data and an L2 regularization term on the weight matrix. The overall structure of my code for this notebook mimics that from the notebook of the one layer network. I used more parameters than before and have changed the functions that 1) evaluate the network (the forward pass) and 2) compute the gradients (the backward pass). I also payed more attention to how to search for good parameter settings for the network's regularization term and the learning rate.</p>

![](https://github.com/alexanderbea/Multi-linear-classifier-using-CIFAR-10-and-one-two-k-layer-network/blob/main/Images/Figure%202.PNG)

# Training multi-linear classifier with k-layer networks

<p align="justify">In this assignment I trained and tested k-layer networks with multiple outputs to classify images (once again) from the CIFAR-10 dataset. I upgraded my code from the notebook with two layer network in two significant ways:
1. Generalized my code so that I can train and test k-layer networks
2. Incorporated batch normalization into the k-layer network both for training and testing
  
The overall structure of my code for this notebook mimics that from the one with two layers. I mainly just had to modify the functions that implements the forward and backward passes. As in the nb with two layers I trained my network with mini-batch gradient descent and cyclical learning rates. As in the previous assignment I trained my networks by minimizing a cost function, a weighted sum of the cross-entropy loss on the labelled training data and an L2 regularization of the weight matrices for the general form, using mini-batch gradient descent.</p>

# See reports that discuss/describe all solutions and analysis in detail as well
