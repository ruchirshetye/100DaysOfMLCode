# Neural Network : 

***We’re going to train the neuron to solve the problem below. The first four examples are called a training set. Can you work out the pattern? Should the ‘?’ be 0 or 1?***

![alt text](https://cdn-images-1.medium.com/max/1000/1*nEooKljI8XbKQh4cFbZu1Q.png)

So the Neural Network has to learn the pattern of the input column(Features). So that it can predict the output.

Neural Network(NN) Diagram:
The given data tells us that there are 3 inputs and 1 output. Hence our NN will look like the figure given below.
![alt text](https://cdn-images-1.medium.com/max/1000/1*HDWhvFz5t0KAjIAIzjKR1w.png)

We need to train the neural network. We will give each input a weight, which can be a positive or negative number.
Weights in NN are basically "How much each feature contributes to the price ?". If a particular feature contributes more towards the output. The weight will hold a higher value.

Before we start, we set each weight to a random number. Then we begin the training process:

1) Take the inputs from a training set example, adjust them by the weights, and pass them through a ***Special formula*** to calculate the neuron’s output.

2) ***Calculate the error***, which is the difference between the neuron’s output f and the desired output in the training set example.

3) Depending on the direction of the error, ***adjust the weights slightly***.

4) Repeat this process 10, 000 times.
