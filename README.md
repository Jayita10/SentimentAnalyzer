# SentimentAnalyzer

## Problem Statement : Sentiment Analysis on IMDB movie review
Sentiment Analysis is a forthcoming exploration progressing field that is becoming important because of utilization of different applications.

 - The aim of this project is to build a Machine Learning model to analyze sentiments from textual data.
 - Here I design neural network of reviews, from the IMDB movie reviews dataset, to determine whether the reviews are positive or negative.
## The IMDB Dataset
 - The IMDB dataset is a set of 50,000 highly polarized reviews from the Internet Movie Database. They are split into 25000 reviews each for training and testing. Each set contains an equal number (50%) of positive and negative reviews.
 - The IMDB dataset comes packaged with Keras. It consists of reviews and their corresponding labels (0 for negative and 1 for positive review). The reviews are a sequence of words. They come preprocessed as a sequence of integers, where each integer stands for a specific word in the dictionary.

## The Neural Network
  Model Architecture-
<b>We are using keras to build our neural network.</b>

<b>Input Layer</b>: 
- This is where the training observations are fed. The number of predictor variables is also specified here through the neurons.

- Our input data is vectors that need to be mapped to scaler labels (0s and 1s). This is one of the easiest setups, and a simple stack of fully-connected, Dense layers with relu activation perform quite well.

<b>Hidden Layers</b>: 
- These are the intermediate layers between the input and output layers. The deep neural network learns about the relationships involved in data in this component.

- Each hidden Layer will have 16 nodes.

  Dense layer implements:

              `output = activation(dot(input, W) + bias)`

  Here W is the weight matrix. W initialization defines the way to set the initial random weights of Keras layers.

<b>Output Layer</b>: 
- This is the layer where the final output is extracted from what’s happening in the previous two layers.


### <b><em>At the end of the training, this Machine Learning Model attained a training accuracy of 88.99% and validation accuracy of 86.66%.</b>
