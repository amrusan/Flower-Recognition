# Flower-Recognition
Flower recognition project using Python and CNN models in order to predict the given image of a flower.

This project uses a Convolutional Neural Network (CNN) to predict flowers of 5 types using the flower recognition dataset on Kaggle.


There are 5 types of flowers that are predicted and trained on:

-Daisy
-Dandelion
-Rose
-Sunflower
-Tulip


There are 4242 images in the original dataset.

I use a simple CNN to do training and predictions. The CNN has 18 layers. Cross Entropy is used for loss and Adam is used as the optimizer. I use ReLu within my layers as the activation function. Within my CNN, I take advantage of maxpooling.

The images are first preprocessed by flipping them horizontally to add more data, resized to 32x32, center cropped to 32x32, changed to a pytorch tensor and fianlly normalized ((0.5,0.5,0.5),(0.5,0.5,0.5)).

I have managed a 71% accuracy during training.

Link to the data: https://www.kaggle.com/alxmamaev/flowers-recognition
