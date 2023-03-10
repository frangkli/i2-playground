# Week 3
## Synthesis Questions
### Neural Network
- What is a neuron (in terms of Neural Networks) and what does its “activation” represent?
	- Neuron in NN is just a number or a function that takes an input and provides an output
	- Activation is an artificial process of simulating biological neuron activation which is achieved by having activation functions based on the value of the function.
	- Bonus: Research and consider the correlation between a biological neuron and an artificial neuron. How are they similar/different?
- What is a network layer? How is it connected to other network layers?
- How is a picture of a digit decomposed into a network layer?
- What does the final layer of a neural network represent?
- What are weights? What are biases? Can you describe in English how information is passed from one layer to the next?
- A neural network **IS**/~~IS NOT~~ just a very highly parameterized function (Choose one)
- What is the purpose of the sigmoid function?

### Gradient Descent
- Why is there a need for a train/test split for a neural network? Why is it important for a NN to be able to generalize to examples it has not seen?
- Describe the Mean Squared Error (MSE) cost function. What does a higher value mean? What does a lower value mean? (For one training example)
	- Bonus: Assume you have a binary classifier neural network that outputs the vector [0.25, 0.75] and you are using the MSE Loss function to train the Network. The data label indicates that the output for this training example should have been [0, 1]. What is the MSE Loss for this training example?
- What is the gradient of a function? What is gradient descent?
- What does minimizing the loss function do to the network’s performance over time?
- Do the hidden layers of a basic NN encode any useful information assuming you use the MSE Loss function? Why or why not?

### Backpropagation
- Describe Gradient Descent, and how it works in principle with a Deep Neural Network.
