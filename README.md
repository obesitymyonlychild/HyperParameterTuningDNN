# HyperparameterTuningDNN

## Purpose
To better understand how changes in hyperparameters can effect optimizing non-convex cost functions, we analyze hyperparameters in Adam optimization method on two convolutional networks -- ResNet and VGG. 

## Method&Experiment Setup
We implement two CNNS VGG and ResNet on the CIFAR-10 image dataset with the setting in ResNet paper. We test on four different Adam hyperparameters and test the sensitivity of these parameters on loss of training data.  

## Key Results
The default values of the Adam hyperparameters does not drastically change by our manual pick of deviation of the parameters. We observe the stability of these hyperparameters overall. The default values indeed work well in VGG and ResNet architectures of DNNs.  
