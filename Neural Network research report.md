# Neural Network research report

Artificial Neural Networks are computational models that are modeled after the human brain. As humans, we all have the ability to think; however computers do not have this ability. To try replicate thinking as good as we can, we can create neural networks to output results. 

The basic architecture of neural networks consist of 3 main components:

### Neurons

Much like a human brain, neural networks use neurons, or “nodes” to perform tasks. These neurons receive data, process it, and transmit the output onto further neurons. Every neuron has a weight and bias that determine it’s importance in the network.

### Layers

Neural networks are made of 3 types of layers:

**Input Layer**: This layer receives the input data

**Hidden Layers**: These layers process the data. They are called “Hidden Layers” because their outputs are not seen by the end user.

**Output Layer**: Once the hidden layer is finished processing the data, it outputs it’s data to the end user through the output layer.

### Activation Functions

After processing the inputs, neurons apply an activation function to the weighted sum of inputs to introduce non-linearity into the model. This non-linearity allows neural networks to learn from complex data. Common activation functions include

**Sigmoid**: Maps input to a value between 0 and 1. This is heavily used in binary classification.

**Tanh**: Maps a value between -1 and 1. This is usually used in cases where the output needs to be centered around zero. 

**ReLU**: Outputs the input if it’s positive. Otherwise it outputs 0. This is widely used due to it’s simplicity and effectiveness

### Types of neural Networks

There are many types of neural networks for different tasks. 

**Feedforward Neural Networks**: These are the simplest type of neural network. Information flows from input to output in one direction. They are commonly used for classification, regression analysis, and pattern recognition.

**Convolutional Neural Networks**:  These are used for processing data in grid-like structures (Usually images.) CNNs use convolutional layers to learn features from the input data. These filters detect features like edges, textures, and patterns.

**Recurrent Neural Networks:** RNNs are designed to work with sequential data by maintaining an internal “memory.” These are commonly used for natural language processing, and speech recognition.

### Training neural networks

Training neural networks involves adjusting their weights and biases between notes, to increase the accuracy between predicted outputs, and actual outputs. The training process involves the following:

**Forwards Propagation**: Data from the input layer is moved through the network, and the output is calculated. This is done by calculating the weighted sum of the inputs and producing outputs at each layer. 

**Loss Function**: The function that calculates the difference between the predicted output and the actual output.

**Backpropagation:** Calculating the gradient of the difference between the predicted and actual output, which allows us to update the weights to reduce the loss.

**Optimization Techniques**: While not completely essential, optimization techniques are highly reccomended, and help you achieve good performance efficiently. There are many different ones such as Stochastic Gradient Descent (SDG), Adam, and L1 and L2 regularization.

Neural networks have revolutionised artificial intelligence, by allowing machines to learn from data and make decisions. Their complex nature makes them difficult to understand, but their vast use cases make them incredibly important to understand, and will undoubtedly become a major part of many peoples lives in the near future.

## Bibliography:

[Activation Functions in Neural Networks: With 15 examples](https://encord.com/blog/activation-functions-neural-networks/)

[What is a Neural Network? - Artificial Neural Network Explained - AWS](https://aws.amazon.com/what-is/neural-network/)

[What is a Neural Network? | IBM](https://www.ibm.com/topics/neural-networks)

[Backpropagation in Neural Network - GeeksforGeeks](https://www.geeksforgeeks.org/backpropagation-in-neural-network/)