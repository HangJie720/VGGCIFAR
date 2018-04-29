# VGGCIFAR
Classification of Cifar-10 dataset using VGG-like Convolutional Neural Network

# Model
Define VGG-like CNN model based on [the original paper](https://arxiv.org/pdf/1409.1556/).  
  
A little changes are made compared to the original model.
  
  
  
![model_without_shape](https://user-images.githubusercontent.com/20081122/39403379-8866d15e-4bb5-11e8-8adf-28910cb35c38.png)

# Result
Accuracy and loss are plotted as below.  
  
![graph](https://user-images.githubusercontent.com/20081122/39403363-349c808c-4bb5-11e8-82c8-ab55b70ffe0e.PNG)  
  
In my attempt, "BN before Relu" makes less overfitting than "BN after Relu".  
Having not tried it, **learning rate decay** may be valid to this optimization. 

# Environment
Windows 10 64-bit  
GeForce GTX 1060  
CUDA 9.0  
CuDNN v7.1.3 for CUDA 9.0  
Python 3.6.5 
