This repo contains the deep learning model built during the Neural Network and Deep Learning module. The model attempts to classify the images from the CIFAR-10 dataset. The final model was able to achieve an 80% test accuracy.

The model consists of 4 blocks each with 
around 4-5 convolutional layers. As the network goes deeper the resolution of the images is 
decreased while the number of channels is increased. Finally, a classifier with 3 linear layers is 
used to perform the prediction. Tanh has been used as the activation function. The model was 
made to have as little parameters as possible. Thus, it only has 400k parameters.


Hyperparameters: 
            Learning Rate: 0.0005
            Weight Decay: 0.015
            Momentum : 0.7
            Epochs: 150
