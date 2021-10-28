# CTScans

## Description

The goal of this project is to train a model for CT scan classification. This is a multi-way classification task in which an image must be classified into one of the three classes (native, arterial, venous). 

The training data is composed of 15,000 image files, the validation set is composed of 4,500 image files and the test data is composed of 3,900 image files. 

The model used contains 2 convolutional layers, 2 pooling layers and 2 linear layers and it was originally based on the LeNet model. The ReLu activation function was used for the convolutional layers and for the linear layers as well. To prevent overfitting, we also used a dropout layer.
