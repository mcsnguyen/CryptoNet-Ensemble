# CryptoNet-Ensemble
Keras Version of the CryptoNet Structure Implemented as an Ensemble

This is specifically for CryptoNet's testing neural network with MNIST.

The training dataset is split into 3 component models each with a different distribution of the training images and labels. Each of these models and the whole dataset model are trained separately. The ensemble takes the outputs of the component models and computes the average or maximum to produce an ensemble output.

Sample accuracy outputs are provided as .PNG files.
