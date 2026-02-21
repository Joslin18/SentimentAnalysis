# SentimentAnalysis

Overview
The goal of this project is to classify movie reviews as either positive or negative. The process involves:

Loading and preprocessing the IMDB dataset.
Building an LSTM model.
Training the model.
Evaluating the model's performance.
Providing an interactive way to predict the sentiment of new movie reviews.
Dataset
The IMDB Movie Review Dataset is used for training and evaluation. It consists of 50,000 highly polarized reviews (25,000 for training, 25,000 for testing), with each review labeled as positive (1) or negative (0).

Model Architecture
The model is a sequential Keras model consisting of the following layers:

Embedding Layer: Converts positive integer inputs (word indices) into dense vectors of fixed size.
LSTM Layer: A recurrent layer that processes sequences and captures long-range dependencies in the text.
Dense Layer: A fully connected output layer with a sigmoid activation function for binary classification.
