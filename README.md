# bigram
Executable implementation of a baseline language model M1
Here are the general steps to implement a bigram model M1 on a PTB and WIKI dataset:
Load the dataset
Preprocess the data (tokenize, clean, etc.)
Create a vocabulary of all unique words in the dataset
Generate bigrams (pair of adjacent words) from the dataset
Compute the frequency of each bigram
Compute the probability of each bigram
Implement the bigram model M1 (with and without backoff) using the probabilities computed in the previous step
Evaluate the model using perplexity metrics.
