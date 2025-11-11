# Exploring-Neural-Networks
In this notebook I complete mathematical derivations for cross entropy loss using the chain rule and I create a neural network from scratch using PyTorch

In this notebook, I really explored the architecture of a simple neural network/Multi-Layer Perceptron (MLP). While experimenting with the network's architecture, I:
- Implemented dropout layers and analyzing how they impacted the model's performance and how effective they were at preventing overfitting
- Implemented k-Fold cross validation to train the model in a robust manner and allow the model to generalize across new data points better
- Conducted hyperparameter tuning to find the ideal learning rate, number of hidden dimensions, and dropout probability for the model on the MNIST dataset

I used the CrossEntropy loss and the Stochastic Gradient Descent (SGD) optimizer, training my model over 10 epochs because I did not have enough compute to run it for a larger number. 
