# Artificial_Intelligence_II
This repository consists of some tasks that have as their main goal to create a classifier that classifies movies based on their positive or negative reviews for a dataset containing movies and their reviews.
The movies classifier is created with the following ways:

[**Logistic Regression**](https://github.com/DimOriCoding/Artificial-Intelligence-II/blob/main/Logistic_Regression_Movies_Classifier.ipynb)

Logistic Regression is a supervised machine learning algorithm used for classification problems. It predicts the probability that an input belongs to a specific class. It is used for binary classification where the output can be one of two possible categories such as for this task there are movies with positive sentiment and movies with negative sentiment.

[**Feed Forward Neural Network (FNN)**](https://github.com/DimOriCoding/Artificial-Intelligence-II/blob/main/FNN_Movies_Classifier.ipynb)

An Feed Forward Neural Network (FNN) consists a neural network that processes data in such a way that it flows in one direction, from input to output. There is no looping back, no recursion, and no cycles.

[**RNN, LSTM, GRU**](https://github.com/DimOriCoding/Artificial-Intelligence-II/blob/main/RNN_Movies_Classifier.ipynb)

Recurrent Neural Networks (RNNs) are neural networks that in contrast to standard neural networks thatpass information in one direction i.e from input to output, they feed information back into the network at each step.
Long Short-Term Memory LSTMs are neural networks that capture long-term dependencies in sequential data making them ideal for tasks like language translation etc. Also LSTM introduce a memory cell that holds information over extended periods addressing the challenge of learning long-term dependencies.
Gated Recurrent Units (GRUs) are a type of RNN introduced by Cho et al. in 2014. The core idea behind GRUs is to use gating mechanisms to selectively update the hidden state at each time step allowing them to remember important information while discarding irrelevant details. GRUs aim to simplify the LSTM architecture by merging some of its components and focusing on just two main gates: the update gate which decides how much information from previous hidden state should be retained for the next time step and reset Gate which determines how much of the past hidden state should be forgotten. Additionally GRUs aim to replace LSTM due to its higher computational cost.



[**RNN with skip connections**](https://github.com/DimOriCoding/Artificial-Intelligence-II/blob/main/RNN_Movies_Classifier_with_skip_connections.ipynb)

The classifier consists not only from RNN/LSTM/GRU cells, but also from skip connections method, where some layer in the neural network are skipped and the output of one layer is fed as the input to the next layers (instead of only the next one).

[**RNN with skip connections and self-attention**](https://github.com/DimOriCoding/Artificial-Intelligence-II/blob/main/RNN_Movies_Classifier_with_skip_connections_and_self_attention.ipynb)

The classifier consists from RNN/LSTM/GRU cells, skip connections method is used as well as self-attention mechanism is used. This is a mechanism captures long range dependencies by calculating attention between all words in the sequence (sentence) and helping the model to find which words are most relevant to each other.
