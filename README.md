[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

# Pytorch Implementation for book "Dive Into Deep Learning" and course Berkeley STAT 157
This repo reproduces codes in the course STAT 157 (UC Berkeley, Fall 2019, https://courses.d2l.ai/) using Pytorch. The textbook for this course is "Dive Into Deep Learning" (http://d2l.ai/). 

Notebooks in this repo are more or less a practice coding session during the self-learning of the book and the course. So, compared to the original MxNet implementation, notebooks in this repo may contain more code comments, lecture notes, some personal options, and it is implemented entirely based on pytorch packages. 

This repo also provides sample code to run some interesting algorithms that was mentioned but not implemented in the original book/course, using Pytorch pretrained models:
* AlexNet
* [VGG](https://github.com/JiahongChen/d2l-pytorch-implementation/blob/master/L12%20Basic%20Convolutional%20Networks/L12_6_VGG.ipynb)
* ResNet
* Faster RCNN
* Mask RCNN

This repo also compares some interesting differece between MxNet and PyTorch
* [Tranfer between tensors/ndarray and numpy array](https://github.com/JiahongChen/d2l-pytorch-implementation/blob/master/L01%20Introduction%20to%20Deep%20Learning/L2_1_torch_tensors_tutorial.ipynb).
* [Modify the number of class of output layer in pretrained model output](https://github.com/JiahongChen/d2l-pytorch-implementation/blob/master/L15%20Image%20Augmentation%2C%20Fine%20Turning%2C%20Neural%20Style/L15_3_Fine_Tuning.ipynb).


## Todo
* L15/5 Style Transfer
* L16/7 Single Shot Multibox Detection
* L19 RNN/GRU/LSTM
