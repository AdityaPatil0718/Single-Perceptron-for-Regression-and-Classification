# Single-Perceptron-for-Regression-and-Classification


**Aim:** 
Implement a basic single perceptron for regression and classification on XOR and XNOR truth table


**Theory :**
A single layer perceptron (SLP) is a feed-forward network based on a threshold transfer function. SLP is the simplest type of artificial neural networks and can only classify linearly separable cases with a binary target (1 , 0). The single layer perceptron does not have a priori knowledge, so the initial weights are assigned randomly. SLP sums all the weighted inputs and if the sum is above the threshold (some predetermined value), SLP is said to be activated (output=1).

![image](https://github.com/AdityaPatil0718/Single-Perceptron-for-Regression-and-Classification/assets/128233555/4e88ea36-71ef-4bde-85af-dcd70ffce0cd)
![image](https://github.com/AdityaPatil0718/Single-Perceptron-for-Regression-and-Classification/assets/128233555/63526060-37d3-4434-8410-cabef54906f5)

 
 

The input values are presented to the perceptron, and if the predicted output is the same as the desired output, then the performance is considered satisfactory and no changes to the weights are made. However, if the output does not match the desired output, then the weights need to be changed to reduce the error.

The most famous example of the inability of perceptron to solve problems with linearly non-separable cases is the XOR problem. However, a multi-layer perceptron using the backpropagation algorithm can successfully classify the XOR data. A multi-layer perceptron (MLP) has the same structure of a single layer perceptron with one or more hidden layers.

![image](https://github.com/AdityaPatil0718/Single-Perceptron-for-Regression-and-Classification/assets/128233555/b9d07276-f5f8-4750-ab2b-ec2426b8d539)

 
The backpropagation algorithm consists of two phases: 
a) the forward phase where the activations are propagated from the input to the output layer, and b) the backward phase, where the error between the observed actual and the requested nominal value in the output layer is propagated backwards in order to modify the weights and bias values.



**Conclusion:**
A single perceptron can capture simple linear relationships, it struggles to accurately model complex non-linear relationships such as those found in XOR and XNOR gates.
