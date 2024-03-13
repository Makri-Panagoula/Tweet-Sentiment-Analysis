# Tweet-Sentiment-Analysis
Our goal in this assignment is to perform sentiment analysis on tweets regarding Greek elections classifying them as positive or negative or neutral experimenting with different models.The datasets have the following columns ; 'New ID' for the record id, 'Text' for the tweet and 'Party' for the political party the tweet refers to and 'Sentiment' which is the label.


## Fine Tuning Greek BERT Models
- In this implementation, we load pretained Greek BERT models and experiment with the subsequent layers of the network, batch size , optimizers, activation functions,patience,learning rates and dropout rates.

## Bidirectional RNN 
- In this approach, we implement a  Bidirectional RNN experimenting on the number of stacked RNNs ,the number of hidden layers , type of cells (LSTM/ GRU) , skipping connections , gradient clipping , multihead attention and dropout probability.This time, we build a vocabulary out of the embeddiings and perform padding in the batches to ensure the sequential data processing needed in the model.

## FNN with Word Embeddings
- In this notebook, we utilize word2VEC embeddings and build a deep neural network experimenting on activation functions,optimizers,patience,learning rates, schedulers,early stopping and dropout rates using the optuna framework.
