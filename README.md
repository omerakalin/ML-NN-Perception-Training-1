# ML-NN-Perception-Training-1
Machine Learning and Neural Network with Synthetic Datasets


The challenge provides two synthetic datasets, class2_tr and class2_test, containing 220 and 80 samples respectively, each with 2 features and 1 label bit from two classes. The task requires creating a perceptron structure with a single unit, followed by training it with delta rule using gradient descent and stochastic gradient descent, and testing it with the test data. The solution also requires generating figures to display data distribution, classification for training and test data, and training error vs iterations. The solution should include source code for training the perceptron with delta rule using both gradient descent and stochastic gradient descent.


The main approach is to work with Delta rule using gradient descent and Delta rule using stochastic gradient descent.

Delta rule using gradient descent:
This code trains a perceptron using the delta rule with gradient descent. It takes the training dataset and the learning rate as input and updates the weights of the perceptron for each epoch using the gradient of the error with respect to the weights. It then tests the perceptron on the test dataset and calculates the accuracy. The code also generates figures to display the data distribution, classification for training and test data, and training error vs iterations. The figures are saved in separate files for further analysis.

Delta rule using stochastic gradient descent:
This code trains a perceptron using the delta rule with stochastic gradient descent. It takes the training dataset, learning rate, and batch size as input and updates the weights of the perceptron for each batch using the gradient of the error with respect to the weights. It then tests the perceptron on the test dataset and calculates the accuracy. The code also generates figures to display the data distribution, classification for training and test data, and training error vs iterations. The figures are saved in separate files for further analysis.

Both codes implement the delta rule, which is a simple learning rule that updates the weights of a perceptron based on the error between the predicted and actual outputs. Gradient descent is used to update the weights for the entire training dataset, whereas stochastic gradient descent updates the weights for a small batch of data at a time. The batch size is a hyperparameter that can affect the convergence and accuracy of the model. The codes also generate figures to visualize the data distribution and the performance of the model during training and testing. These figures can help to understand how the model is learning and identify any potential issues such as overfitting or underfitting.
