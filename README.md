# Multi-layer Neural Network
Implementing multi-layer neural network WITHOUT using external deep learning libraries such as Keras, Caffe, Theano, TensorFlow, PyTorch...

- Considering a neural network as shown in Figure 1
  - The width of the layer 1 is 2, and the width of the layer 2 is 1.
  - The activation functions of the layer 1 are the hyperbolic tangent.
  - The activation function of the layer 2 is the sigmoid.
  - The loss function is the binary cross entropy.
 
 - Calculating ![image](https://user-images.githubusercontent.com/104048277/216734595-9ba6ff4a-3dd0-458b-89b5-542dc17a7491.png)

- Implementing the model without using any deep learning libraries. 
- Using numpy
  - X = np.array([[0,0],[0,1],[1,0],[1,1]])
  - y = np.array([0,1,1,0])
- Optimized using gradient descent method

![image](https://user-images.githubusercontent.com/104048277/216734698-42837ae9-407a-4a49-8170-ab5063c6744e.png)


