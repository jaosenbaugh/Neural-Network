# Neural-Network
Javascript implementation for an artificial neural network. This will be for personal use.
My goals are to have this library accept an array to initialize the network.
So if the input is [6, 10, 8, 2] the network would have 6 input nodes, 10 nodes in the first hidden layer, 8 nodes in the second hidden layer, and 2 output nodes.
The network should also have a public train function and a public ?guess? function. These should both put inputs through the network but train will also accept the 'correct' answer allowing for supervised learning. I also plan to allow this neural network to clone and mutate itse$
For the matrix math, I'll use the math.js library and the calculus for the back propigation and calculation of gradient descent I'll do the math directly in the library.
