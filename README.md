# Mushroom


For prediction of Mushroom We are going to use Deep Neural Network.
Library Used - Tensorflow
The model of neural network is as following:
  1.Layer 1 = (INPUT*Weight) + Biases
  2.Then applying RELU activation Function
  3.NOW using dropout with keep_prob = 0.75
  4.THEN hidden layer = Dropout(Relu(Layer1))*Hidden weights + Hidden Biases 
The hidden layer will have 150 hidden neurons and the output will be a 2*1 Matrix having probablities of edible or poisnous
