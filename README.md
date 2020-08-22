# MNIST_drilldown
Step by step breakdown of how acheive high accuracy with less parameters for MNIST dataset
##Aim
Acheive atleeast 99.4% acuuracy without using more than 10,000 parameters in less than 15 epochs

This has been done in 4steps
1) Setup the basic structure of the code like implement basic transforms and setup the train and testing loops
2) optimise the model architecture .This architecture has been  used in the future steps as well
3) Implement Regularization
4) Implement various augmentations,LR Scheduler and experiment with ADAM optimizer to finally yield an accuracy of 99.45%
