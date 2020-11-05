# Backpropagation_By_Hand

In this , we implement the backpropagation algorithm and train the first multi-layer perceptron
to distinguid between 4 classes. We implement everything on your own without using existing libraries
like Tensorflow, Keras, or PyTorch.
We are provided with two files “train data.csv“ and “train labels.csv“ The dataset contains 24754 samples, each
with 784 features divided into 4 classes (0,1,2,3). Divide this into training, and validation sets (a
validation set is used to make sure your network did not overfit). 
Use one input layer, one hidden layer, and one output layer in your implementation. The labels are one-hot
encoded. For example, class 0 has a label of [1, 0, 0, 0] and class 2 has a label of [0,0,1,0]. Make sure use the
appropriate activation function in the output layer. Use any number of nodes in the hidden layer.
Provide one single function that allows us to use the network to predict the test set. This function
should output the labels one-hot encoded in a numpy array.
