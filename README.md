# Traffic Sign classifier using CNN and TensorFlow

The goal of this project was to implement a Convolutional Neural Network to detect German Traffic Sign using TensorFlow. The entire model
was trained a ubuntu instance on Google Cloud Platform (GCP) with a NVIDIA Tesla K80 GPU.

The data set used is the **German Traffic Sign** data set that can be dowloaded from [here](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset#Downloads). 
German Trafffic Sign Dataset is a set of **51,839** labeled images of **43** different German traffic signs. 
It comes in two separate sets. 
A set of **39,209** images for training and another set of **12,630** in order to test the accuracy of our trained network. 
A pickled version of the dataset can be downloaded from [here](https://d17h27t6h515a5.cloudfront.net/topher/2016/November/581faac4_traffic-signs-data/traffic-signs-data.zip).

The CNN architecture used was LeNet architecture with 2 CONV layers and 3 fully connected layers. Activation function was ReLU.
Training was done for 30 epochs with a batch size of 128 using Adam Optimizer.
I was able to obtain a validation accuracy of **96.4%** and test accuracy of **91.8%**

