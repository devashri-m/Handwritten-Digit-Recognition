# Handwritten-Digit-Recognition
This introductory project focuses on building your skills with Python and some of the libraries and tools you will need to work with neural network models. <br>
**Dataset:** <Br>
The Optical recognition of handwritten digits dataset, included with the scikit-learn library, consists of 8✕8 grayscale images of hand-written digits sorted into classes 0-9. Once the dataset has been loaded, the feature vectors and labels are accessible as the data and targets attributes.<br>
**Tasks:**<br>
1.	Split the dataset into training and test sets, then train a fully-connected neural network to recognize the digits. You will need to determine the size and number of layers, activation functions, and other hyperparameters. You can see a similar example using Keras as Problem 21 in the Programming Exercises and Sample Code.
Note that while it is possible to achieve 100% accuracy on the training set, this may not generalize to the same accuracy on the test set. Try varying the architecture and parameters to see how they influence the test score.
2.	When you are satisfied with your model's performance, dump the trained weights and biases from the model as NumPy arrays for each layer. If you are using Keras, this is the get_weights method. For PyTorch, you will need the model’s state_dict and the numpy method.
Once you have the weights, implement forward propagation using NumPy. You can see relevant examples in Problems 1 through 6 and 8 in the Programming Exercises and Sample Code.
3.	Compute the training and test accuracies produced by your code in step (2) and compare it to those reported for the model in step (1). Verify your code’s predictions by plotting images for several results in each class.

**Libraries**:
You will need the following Python libraries:<br>
●	scikit-learn to obtain the dataset and split the data into training and test sets<br>
●	NumPy to perform matrix and vector operations<br>
●	Either Keras or PyTorch to construct and train a neural network<br>
●	Matplotlib to view images of the digits<br>
