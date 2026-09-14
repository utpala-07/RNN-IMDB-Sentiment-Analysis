# RNN IMDB Sentiment Analysis
An RNN-based sentiment analysis project that classifies IMDB movie reviews as positive or negative using PyTorch.

## Overview

This project uses a Recurrent Neural Network (RNN) to analyze the sentiment of movie reviews from the IMDB dataset.
The reviews are preprocessed and converted into numerical representations before being passed to the RNN model. The model learns patterns in the text and predicts whether a review is **Positive** or **Negative**.

## Dataset

The project uses the **IMDB Movie Reviews Dataset**, which contains movie reviews labeled with their corresponding sentiment.

- Positive
- Negative

The dataset contains approximately **50,000 reviews**.

##  Workflow

IMDB Movie Reviews
        ↓
Text Preprocessing
        ↓
Feature Extraction
        ↓
RNN Model
        ↓
Hidden State
        ↓
Fully Connected Layer
        ↓
Sentiment Prediction

## RNN Model

The project uses a basic Recurrent Neural Network (RNN) implemented using PyTorch.

The RNN processes the input sequence step by step and maintains a hidden state that represents information from the sequence processed so far.

The final hidden state is passed to a fully connected layer to generate the sentiment prediction.

## Technologies Used
Python
PyTorch
NumPy
Pandas
Scikit-learn
Jupyter Notebook

## Objective

The main objective of this project is to understand how Recurrent Neural Networks can be used for Natural Language Processing (NLP) and text classification.

## Future Improvements
Experiment with different RNN architectures
Improve text preprocessing and feature representation
Tune model hyperparameters
Compare RNN with other deep learning architectures
Deploy the model as a web application

## Author 
P.Utpala
