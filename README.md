# Deep-Learning
This repository provides insights about starter educational projects built for Deep Learning categorised in various areas like ANN, CNN, RNN  and so on.


ANN - Exit Prediction Model
This project is an starter/learner ANN project which encompasses different Neural network principles like forward and back propagation, Stochastic gradient descent. Additionally data pre-processing is done similar to ML  implementation.

1. Creation of a fully functional neural network is done using Keras module:Sequential class while  the creation of intrinsic hidden layers is done using Keras module:Dense Class.

2.  Forward propagation is performed by creating fully functional networks which has 2 hidden layers,1 i/p layer having i/p's like basic (dummy) customer details & 1 output layer since it has a binary output for a dependent output variable.

3. Activation functions like Rectifier functions are applied to hidden layers while sigmoid function applied to output layer to better predict values near 0 or 1

4. Once output is received for one forward propagation the output is matched with the actuarial value 'y' for the same row and cost/loss function is calculated. This cost function is usually 0.5*(y-y^)*(y-y^) where y^ is the value obtained after one feed forward propagation of one row input. 

5. After the cost function provides a difference value, the value is back-propagated in the network to adjust the weights 'W'. In mathematical terms gradient descent is used to minimise the cost function and adjust weights at every layer by using partial derivative of the activation function w.r.t X multiplying it with the learning rate.

Once the values of weights is adjusted. The process of forward and backward propagation is continued to find the local minima in case of gradient descent and global minima in case of stochastic gradient descent.

6. Similarly, this is done for other rows separately to achieve outputs respectively. This process is done for customised number of epochs. Epochs is one cycle of complete dataset processing. This is done to get the better optimisation results for all the variables.

7. Finally the model is trained and tested to achieve the best fit.







