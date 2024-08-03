# Image Caption Generator Using Flickr Dataset

Dataset Link - https://www.kaggle.com/datasets/aladdinpersson/flickr8kimagescaptions

## Project Overview
The objective of the project is to predict the caption for the input image.The dataset consist of 8k images and have 5 captions for each image.The features of images are extracted through vgg16 model using transfer learning method and the text caption are given as input to LSTM model for learning.The image features and text caption feature vector are concatenated to predict the next word of the caption.<br>
BLEU Score is used as a metric to evaluate the performance of the trained model.<br>
Function model is build for prediction.

## Libraries Used
1) numpy
2) tensorflow
3) os
4) re
5) nltk
6) opencv-python
7) matplotlib
8) pickle

## Important Point - 
1) VGG16 Network is used to extract image feature vector
2) CNN-LSTM Network for generating predictions

