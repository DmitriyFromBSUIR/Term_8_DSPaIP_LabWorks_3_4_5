# Term_8_DSPaIP_LabWorks_3_4_5
Complex Projetc that included LabWork 3 (MultiLayer Perceptron), LabWork 4 (RBF), LabWork 5 (Competitive Neural Networks)

A multilayer perceptron (MLP) is a feedforward artificial neural network model that maps sets of input data onto a set of 
appropriate outputs. An MLP consists of multiple layers of nodes in a directed graph, with each layer fully connected to the next 
one. Except for the input nodes, each node is a neuron (or processing element) with a nonlinear activation function. MLP utilizes 
a supervised learning technique called backpropagation for training the network.[1][2] MLP is a modification of the standard 
linear perceptron and can distinguish data that are not linearly separable.

Activation function

If a multilayer perceptron has a linear activation function in all neurons, that is, a linear function that maps the weighted 
inputs to the output of each neuron, then it is easily proved with linear algebra that any number of layers can be reduced to the 
standard two-layer input-output model (see perceptron). What makes a multilayer perceptron different is that some neurons use a 
nonlinear activation function which was developed to model the frequency of action potentials, or firing, of biological neurons 
in the brain. This function is modeled in several ways.

Layers

The multilayer perceptron consists of three or more layers (an input and an output layer with one or more hidden layers) of 
nonlinearly-activating nodes and is thus considered a deep neural network. Since an MLP is a Fully Connected Network, each node 
in one layer connects with a certain weight w_{ij} to every node in the following layer. Some people do not include the input 
layer when counting the number of layers and there is disagreement about whether w_{ij} should be interpreted as the weight 
from i to j or the other way around.

Learning through backpropagation

Learning occurs in the perceptron by changing connection weights after each piece of data is processed, based on the amount of 
error in the output compared to the expected result. This is an example of supervised learning, and is carried out through 
backpropagation, a generalization of the least mean squares algorithm in the linear perceptron.

We represent the error in output node j in the nth data point (training example) by e_j(n)=d_j(n)-y_j(n), where d is the target 
value and y is the value produced by the perceptron.

... etc
