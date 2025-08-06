Required packages:
scikit-learn, matplotlib

# What is a perceptron?
It is a binary classifier capable of deciding whether data belongs to one class or another. It works by adjusting its weighted inputs until it becomes better at predicting the right **class** for the data (aka, learning).

`Perceptron` - a basic computational model in ML that makes decisions by weighing data.
`Binary Cliassifier` - A type of system that categorizes data into one of two groups.
`Vector of Numbers` - A sequence of numbers in order which represent a single piece of data.
`Activation Function` - A mathematical equation that decides whether the percepterons calculated sum from its inputs is enough to trigger a negative or positive output. 

# Multi-Layer Perceptron
Makes decisions by mimicking the way the human brain's neurons work. Processes information through layers, passing each layer's result to the next, until the output is provided in the out put layer. Input Layer > 1+ Hidden Layers > Output Layer > Result
Number of neurons equal to the number of classes we have?

`Multi-Layer Perceptron (MLP)` - A type of artificial neural network that has multiple layers of nodes, each layer learning to recognize increasingly complex features of the input data.
`Input Layer` - The first layer in an MLP where the raw data is initially received.
`Output Layer` - The last layer in an MLP that produces the final result or prediction of the network.
`Hidden Layers` - Layers between the input and output that perform complex data transformations.

# Gradient Descent
 An optimization algorithm used to fine tune params in a deep learning models. Its purpose is to minimize the cost function. 
 In mathematics, gradient represents the direction of the steepest increase in a function. Descending the gradient means moving opposite this direction (move downhill).
 At each iteration, the algorithm adjusts the weights of the model by a defined amount (learning rate).

`Labeled Dataset` - This is a collection of data where each piece of information comes with a correct answer or label. It's like a quiz with the questions and answers already provided.
`Gradient Descent` - This method helps find the best settings for a neural network by slowly tweaking them to reduce errors, similar to finding the lowest point in a valley.
`Cost Function` - Imagine it as a score that tells you how wrong your network's predictions are. The goal is to make this score as low as possible.
`Learning Rate` - This hyperparameter specifies how big the steps are when adjusting the neural network's settings during training. Too big, and you might skip over the best setting; too small, and it'll take a very long time to get there.
`Backpropagation` - Short for backward propagation of errors. This is like a feedback system that tells each part of the neural network how much it contributed to any mistakes, so it can learn and do better next time.
