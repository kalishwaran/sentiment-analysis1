##Sentiment Analysis Project
This is a sentiment analysis project that aims to classify tweets as either positive (label 0) or negative (label 1). The project involves data preprocessing, text cleaning, model building, and hyperparameter tuning.

About dataset
id: The unique identifier for each tweet.
label: The sentiment label (0 for positive, 1 for negative).
tweet: The text of the tweet.
The dataset contains a total of 7920 entries with no missing values.

Class Distribution
Positive tweets (label 0): 5894
Negative tweets (label 1): 2026
Data Preprocessing
URLs, punctuation, and special characters were removed from the tweets.
Contractions were expanded (e.g., "won't" becomes "will not").
Words were lemmatized to their base forms.
Stopwords were removed from the cleaned tweets.
Data Visualization
A bar chart was created to visualize the top 30 most common words in the cleaned tweets without stopwords.

Model Building
Tokenization and padding of sequences were performed.
A LSTM-based neural network model was built.
Hyperparameter tuning was conducted using Keras Tuner with the following hyperparameters:
Embedding output dimension
LSTM units
Optimizer (Adam, RMSprop, or SGD)
Learning rate
The best model was selected based on validation accuracy.

Model Evaluation
The best model achieved an accuracy of approximately 86.99% on the testing dataset.

Author
Author: kaleeshwaram