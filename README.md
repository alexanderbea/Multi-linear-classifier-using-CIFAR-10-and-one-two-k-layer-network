# Training multi-linear classifier with a one layer network

<p align="justify">Herein I have trained and tested a one layer network with multiple outputs to classify images from the CIFAR-10 dataset. I have trained the network using mini-batch gradient descent applied to a cost function that computes the cross-entropy loss of the classifier applied to the labelled training data and an L2 regularization term on the weight matrix.</p>

![](https://github.com/alexanderbea/Multi-linear-classifier-using-CIFAR-10-and-one-two-k-layer-network/blob/main/Images/Figure%201.PNG)

# Training multi-linear classifier with a two layer network

Next, I trained and tested a two layer network with multiple outputs to classify images from the CIFAR-10 dataset. I trained the network using mini-batch gradient descent applied to a cost function that computes the cross-entropy loss of the classifier applied to the labelled training data and an L2 regularization term on the weight matrix. The overall structure of my code for this notebook mimics that from the notebook of the one layer network. I used more parameters than before and have changed the functions that 1) evaluate the network (the forward pass) and 2) compute the gradients (the backward pass). I also payed more attention to how to search for good parameter settings for the network's regularization term and the learning rate.

![](https://github.com/alexanderbea/Multi-linear-classifier-using-CIFAR-10-and-one-two-k-layer-network/blob/main/Images/Figure%202.PNG)

